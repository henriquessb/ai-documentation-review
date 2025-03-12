# AI Documentation Review Benchmark

This repository aims to setup and store automatic benchmarks of AI models for technical documentation reviews.

## File structure

There are many files and folders in this repository to configure the AI-based automated reviews and comparisons and store the results. The structure in this repository is:

1. **Planning.md**: An overall planning of how to structure the aspects of the reviews (AI models, segmentation of prompts, file formats, etc.).
2. **E&D Style Guide.md**: The Style Guide used by VTEX Education team to write and review technical documentation.
3. **Input docs/**: Folder with the documentation files the AI models review.
4. **Prompts/**: Folder with the prompt files that have the instructions the AI models will follow for the reivews and comparisons. There are two subfolders, one for each case of execution: **Agent** and **Chat**.
5. **Reviews/**: Folder with the AI-generated reviews of the documentation files. Each subfolder has the review outputs of each AI model that executed the review. The review files include the individual review of each documentation file, and an aggregated report from the review of all documentation files.
6. **Comparison/**: Folder with the AI-generated comparisons of the AI-generated reviews. Each subfolder has the comparison results generated by each AI model. In each subfolder, there are files with a general analysis of the reviews for each AI model and a final comparison between all models.

## How to configure

### Review configuration

#### Agent review setup

- `Prompts/Agent/Review prompt.md`: Prompt with instructions to execute the reviews of each documentation file and the aggregated report, including the response templates.
- `Prompts/Agent/review-config.json`: JSON file with the paths that Agent mode will use to execute the reviews. It includes the Style Guide, the list of documentation files, the folder to store the reviews and the aggregated report.

#### Chat review setup

- `Prompts/Chat/Aggregated report.md`: Template of the aggregated report.
- `Prompts/Chat/General behavior.md`: Prompt with instructions to execute the reviews of each documentation file and the aggregated report.
- `Prompts/Chat/Individual review.md`: Prompt to execute the review of a single documentation file.
- `Prompts/Chat/Review template.md`: Template of the documentation file reviews.

### Comparison configuration

#### Agent comparison setup

- `Prompts/Agent/Compare prompt.md`:Prompt with instructions to execute the analysis of the AI-generated reviews and the comparison between them, including the response templates.
- `Prompts/Agent/comparison-config.json`: JSON file with the paths that Agent mode will use to execute the comparison. It includes the Style Guide, the list of aggregated reports, and the paths for the comparison outputs.

## How to execute

### Review execution

There are two ways to execute the automated reviews: **Agent** and **Chat**. With **Agent** you insert the prompt to execute along with the prompt file reference, and the files will be generated, since the input files are accessed directly from this repository. With **Chat** you have to insert prompts and files manually in the AI chat interface, then copy the results to new files in this repository.

#### Agent review

1. Open the AI sidebar of the desired IDE (Cursor, VS Code).
2. Choose the **Agent** option in the chat and the desired AI model (e.g., GPT-4o).
3. Add the prompt in the textbox: "Execute the comparison following the instructions in {Reference to Prompts/Agent/Compare prompt.md}", without quotes. Replace the reference to the `Compare prompt.md` file according to the IDE. Cursor uses `@` (@Compare prompt.md) to reference files. VS Code/GitHub Copilot uses `#` (#Compare prompt.md).
4. The AI model will execute the review and generate the files in the folder `Reviews/Single prompt - multiple documents/{Model name}`. E.g., if the model executing the reviews is GPT-4o, the files will be in the folder `Reviews/Single prompt - multiple documents/GPT-4o`.

#### Chat review

1. Create a new folder for the desired AI model in `Reviews/Single prompt - multiple documents`. For instance, if you want to execute the reviews with DeepSeek-R1, create the folder `Reviews/Single prompt - multiple documents/DeepSeek-R1`.
2. Open the AI chat interface of the desired AI model. For instance, if you want to execute the reviews with DeepSeek-R1, go to https://chat.deepseek.com and choose the option **DeepThink (R1)**.
3. Attach the `Prompts/Chat/Review template.md` and `E&D Style Guide.md` files to the chat.
4. Insert the content of `Prompts/Chat/General behavior.md` in the text box and run. The AI model will reply understanding the review task.
5. For each documentation file you want the review, follow these steps repeatedly:
   1. Attach the documentation file in the chat. In this repository, they are located at `Input docs`.
   2. Insert the content of `Prompts/Chat/Individual review.md` in the text box and run. The AI model will answer with the review of the documentation.
   3. Copy the review response from chat.
   4. Create a new file inside the folder you created for the reviews of this model (`Reviews/Single prompt - multiple documents/{Model name}/review_{documentation name}.md`). E.g., `Reviews/Single prompt - multiple documents/DeepSeek-R1/review_authentication.md`.
   5. Paste the review response in the file you just created.
6. After the reviews of all documentation files are done, you will execute the aggregated report. Insert the content of `Prompts/Chat/Aggregated report.md` in the text box and run.
7. Copy the aggregated report response from chat.
8. Create a new file inside the folder you created for the aggregated report of this model (`Reviews/Single prompt - multiple documents/{Model name}/{Model name}-aggregated-report.md`). E.g., `Reviews/Single prompt - multiple documents/DeepSeek-R1/DeepSeek-R1-aggregated-report.md`.
9. Paste the aggregated report response in the file you just created.

> ℹ️ For reviews with Gemini on Google AI Studio, you need to attach the files from Google Drive. The recommendation is to create a dedicated folder with the files, preferably in the **Google AI Studio** folder, and insert there all the files you will need to attach in the chat. Then, in the chat, you select the files from Google Drive.

### Comparison execution

Currently, comparison works only with **Agent** mode. You insert the prompt to execute along with the prompt file reference, and the files will be generated, since the input files are accessed directly from this repository.

#### Agent comparison

1. Open the AI sidebar of the desired IDE (Cursor, VS Code).
2. Choose the **Agent** option in the chat and the desired AI model (e.g., GPT-4o).
3. Add the prompt in the textbox: "Execute the comparison following the instructions in {Reference to Prompts/Agent/Compare prompt.md}", without quotes. Replace the reference to the `Compare prompt.md` file according to the IDE. Cursor uses `@` (@Compare prompt.md) to reference files. VS Code/GitHub Copilot uses `#` (#Compare prompt.md).
4. The AI model will execute the comparison and generate the files in the folder `Comparison/{Model name}`. E.g., if the model executing the comparison is GPT-4o, the files will be in the folder `Comparison/GPT-4o`.
