# Benchmark planning

## 1. Review format

### Platform

1. Chat website
2. JupyterHub
3. API
4. IDE AI panel

### Models to test

1. [GPT-4o](https://openai.com/index/hello-gpt-4o/)
2. [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)
3. [Claude Sonnet 3.7](https://www.anthropic.com/news/claude-3-7-sonnet)
4. [Gemini 2.0 Flash](https://blog.google/technology/google-deepmind/google-gemini-ai-update-december-2024/#gemini-2-0-flash)
5. [GitHub Copilot (Claude Sonnet 3.5)](https://github.com/features/copilot)

### Prompt sequence

1. Single prompt - General review.
2. Multiple prompts separating by guideline set.
3. Multiple prompts separating by document segment.
4. Multiple prompts separating in two levels, one for guideline set and other by document segment.

## 2. Attachments

### Style Guide

1. Exported zip folder from Notion containing Markdown files and images.
2. Single text file aggregating all the exported Markdown content.

### Review object

#### Document amount and type

1. Single document (tutorial)
   1. [Engineering best practices](https://developers.vtex.com/docs/guides/vtex-io-documentation-engineering-guidelines)
2. Multiple documents - at least one per documentation type (tutorial, troubleshooting, announcement, etc.)
   1. [FastStore: Performance improvements for mobile devices (Announcement - Dev Portal)](https://developers.vtex.com/updates/release-notes/2024-12-23-faststore-improvements)
   2. [Authentication (Conceptual - Help Center)](https://help.vtex.com/en/tutorial/authentication--21CkKHLKP1o41lUpGhuRUs)
   3. [Backend integrations (Conceptual - Help Center)](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/7euXDZR5CCnVFSrXyczIhu)
   4. [Set up catalog (Tutorial - Dev Portal)](https://developers.vtex.com/docs/guides/erp-integration-set-up-catalog)
   5. [How to add products (Practical guide - Help Center)](https://help.vtex.com/en/tutorial/adding-products--tutorials_2567)
   6. [I am getting errors with my service configuration app (Troubleshooting - Dev Portal)](https://developers.vtex.com/docs/troubleshooting/i-am-getting-errors-with-my-service-configuration-app)
   7. [Subscriptions: FAQ (FAQ - Help Center)](https://help.vtex.com/en/faq/subscriptions-faq--3g0blKxyWjsmPMTFvr8sLq)
   8. [Engineering best practices (Tutorial - Dev Portal)](https://developers.vtex.com/docs/guides/vtex-io-documentation-engineering-guidelines)

#### Document format

1. Text file.
2. Link from GitHub.
3. Link from portal.

## 3. Review analysis

### Review export format

1. Text file (Markdown, TXT).
2. Structured (JSON).
3. Image (JPEG, PNG).
4. Shared link.

### Analysis method

1. Use LLM to compare exported reviews.
