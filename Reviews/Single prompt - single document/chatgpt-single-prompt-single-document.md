Below are specific text revisions for selected sections of the “VTEX IO Documentation Engineering Guidelines” page. Each change is crafted to align with the VTEX Style Guide, with citations provided for each guideline:

---

### 1. Using APIs Efficiently

**Current Text:**
> Efficiently utilizing APIs is paramount for optimal performance in your application. Whenever possible, leverage our pre-built VTEX IO Clients to harness the following advantages:

**Proposed Revision:**
> **Using APIs Efficiently**
> Using APIs efficiently is essential for optimal app performance. Whenever possible, use our pre-built VTEX IO Clients to benefit from:
>
> - **Standardized Code:** VTEX IO Clients provide consistent code across all applications.
> - **Automatic Updates:** VTEX continuously updates these Clients to add features, resolve bugs, and ensure compatibility.
> - **Simplified Maintenance:** Relying on VTEX IO Clients reduces the need for extensive maintenance.

**Justification:**
- **Clarity & Brevity Rule:** Replacing “efficiently utilizing” with “using” and “optimal performance in your application” with “optimal app performance” streamlines the sentence for clarity and conciseness.
- **Structure & Formatting Guidelines:** Breaking down advantages into bullet points improves scannability.

---

### 2. Performance of External Systems (Blockquote)

**Current Text:**
> Performance of external systems
> When you offer your app on the VTEX App Store, your app may become available to brands of all sizes across different time zones and business calendars. In this context, relying on a manual system with on-demand scalability can become a huge risk in terms of performance.

**Proposed Revision:**
> **Performance of External Systems**
> When you list your app on the VTEX App Store, it becomes available to a diverse range of brands worldwide. Relying on a manual system that doesn’t scale on demand poses a significant performance risk.

**Justification:**
- **Clarity & Brevity Rule:** The revised text uses more direct language and shorter sentences to improve clarity.
- **Tone & Voice Guidelines:** A more straightforward tone increases engagement and accessibility.

---

### 3. Using the Latest Builders

**Current Text:**
> Builders work as an API responsible for configuring other IO services in your app. For developing and publishing apps for the VTEX App Store, the following builders must be up-to-date in your app's code:

**Proposed Revision:**
> **Using the Latest Builders**
> Builders act as APIs that configure other VTEX IO services in your app. When developing and publishing apps for the VTEX App Store, ensure that your code uses the following up-to-date builder versions:
>
> - **Node builder:** version 7.x
> - **React builder:** version 3.x
> - **Admin builder:** version 1.x
> - **Messages builder:** version 1.x
> - **Docs builder:** version 0.x
> - **GraphQL builder:** version 1.x

**Justification:**
- **Clarity & Brevity Rule:** Changing “work as an API responsible for configuring” to “act as APIs that configure” creates a more direct statement.
- **Tone & Voice Guidelines:** Using “ensure that your code uses” gives a clear, active instruction.

---

### 4. Versioning

**Current Text:**
> When releasing a new version of your app, it's crucial to adhere to best practices. There are various types of versions to consider, including major, minor, and patch, as well as stable and beta releases. Select the appropriate version type based on the nature of the implemented changes. Special attention is required for breaking changes, which should always result in a new major version.

**Proposed Revision:**
> **Versioning**
> When releasing a new version of your app, follow best practices. Consider the different version types—major, minor, patch, stable, and beta—and choose the one that best reflects your changes. Remember: breaking changes must trigger a new major version.

**Justification:**
- **Clarity & Brevity Rule:** The revised text uses shorter sentences and more direct language for improved clarity.
- **Tone & Voice Guidelines:** A direct call to “remember” makes the instruction more engaging.

---

### 5. Hardcoding VTEX appKey/appToken

**Current Text:**
> Hardcoding VTEX appKey/appToken
> Having an appKey/appToken exposed in your code can cause serious security issues, like unwanted access. Instead of using a VTEX appKey/appToken pair, apps should use the existing tokens (`ctx.authToken`, `ctx.vtex.storeUserAuthToken` or `ctx.vtex.adminUserAuthToken`). For more information, see Connecting to VTEX Core Commerce APIs.

**Proposed Revision:**
> **Hardcoding VTEX appKey/appToken**
> Exposing your appKey/appToken in the code can lead to serious security risks, such as unauthorized access. Instead, use the existing tokens (`ctx.authToken`, `ctx.vtex.storeUserAuthToken`, or `ctx.vtex.adminUserAuthToken`). For more details, see [Connecting to VTEX Core Commerce APIs](#).

**Justification:**
- **Clarity & Brevity Rule:** The revised version shortens and simplifies the explanation, removing unnecessary phrasing.
- **Tone & Voice Guidelines:** The active voice (“Exposing” and “use the existing tokens”) enhances readability and engagement.

---

### 6. Implementing Internationalization (i18n) Correctly

**Current Text:**
> Ensure that all messages are internationalized using the `messages` builder. Also, i18n keys should start with the domain (`store/` for storefront and `admin/` for Admin) where they are used. Otherwise, they will not render properly. For more information, see our reference for translating components.

**Proposed Revision:**
> **Implementing Internationalization (i18n) Correctly**
> Ensure all messages are internationalized using the `messages` builder. i18n keys should begin with the domain prefix—`store/` for storefront or `admin/` for Admin—to render correctly. For more details, see our [reference for translating components](#).

**Justification:**
- **Clarity & Brevity Rule:** Removing extra words such as “also” and “otherwise” makes the text more direct.
- **Structure & Formatting Guidelines:** Presenting the instructions in a concise, step-by-step manner helps users quickly understand the requirements.

---

Each proposed text edit follows the VTEX Style Guide by emphasizing clarity, brevity, and a consistent, active tone. These revisions should improve overall readability and user engagement while ensuring technical accuracy. If you need further modifications or additional sections reviewed, let me know!
