# Benchmark planning

## 1. Review format

### Platform

1. Chat website
2. JupyterHub
3. API
4. IDE Chat

### Models to test

1. ChatGPT o3-mini
2. DeepSeek-R1
3. Claude Sonnet 3.7
4. Gemini Flash 2.0

### Prompt sequence

1. Single prompt - General review.
2. Multiple prompts separating by guideline set.
3. Multiple prompts separating by document segment.
4. Multiple prompts separating in two levels, one for guideline set and other by document segment.

## 2. Attachments

### Style Guide

1. Exported zip folder from Notion containing Markdown files and images.
2. Single file aggregating all the exported Markdown content.

### Review object

#### Document amount and type

1. Single document (tutorial)
   1. [Engineering best practices](https://developers.vtex.com/docs/guides/vtex-io-documentation-engineering-guidelines)
2. Multiple documents - at least one per documentation type (tutorial, API, announcement, etc.)
   1. [Set up catalog (Tutorial - Dev Portal)](https://developers.vtex.com/docs/guides/erp-integration-set-up-catalog)
   2. [FastStore: Performance improvements for mobile devices (Announcement - Dev Portal)](https://developers.vtex.com/updates/release-notes/2024-12-23-faststore-improvements)
   3. [POST Send anti-fraud pre-analysis data (optional) (API Reference - Dev Portal)](https://developers.vtex.com/docs/api-reference/antifraud-provider-protocol#post-/pre-analysis)
   4. [I am getting errors with my service configuration app (Troubleshooting - Dev Portal)](https://developers.vtex.com/docs/troubleshooting/i-am-getting-errors-with-my-service-configuration-app)
   5. [Backend integrations (Conceptual - Help Center)](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/7euXDZR5CCnVFSrXyczIhu)
   6. [Authentication (Conceptual - Help Center)](https://help.vtex.com/en/tutorial/authentication--21CkKHLKP1o41lUpGhuRUs)
   7. [Subscriptions: FAQ (FAQ - Help Center)](https://help.vtex.com/en/faq/subscriptions-faq--3g0blKxyWjsmPMTFvr8sLq)
   8. [How to add products (Practical guide - Help Center)](https://help.vtex.com/en/tutorial/adding-products--tutorials_2567)

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
