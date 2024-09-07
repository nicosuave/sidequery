# sidequery

[sidequery.ai](https://sidequery.ai): Query & visualize remote & local CSV and Parquet with DuckDB in your browser. 

This is the public issue tracker, changelog, and privacy policy, all in one. Issue reports for bugs or features requests are much appreciated! 😎

## Getting Started
Check out [sidequery.ai](https://sidequery.ai) to get started— no login required. 

## Changelog

- `2024-09-07`
  - Faster file "uploads"
    - Sidequery currently runs 100% locally, so no data goes anywhere but your browser
  - Query is autorun on file upload
    - With a 1 million row limit; feels reasonable right now?
  - Explore view is the default

- `2024-09-06`
  - Public launch of sidequery.ai

## Privacy

We value your privacy and strive to ensure that your data is handled securely and transparently. Below is a breakdown of how we collect, store, and process data:

1. **Local Storage**  
   All your tabs and queries are stored locally in your browser, meaning that none of your query content or results ever leave your device. Uploaded data also remains entirely on your device and is not transmitted to external servers.

2. **Query Metadata**  
   We collect metadata about your query activities to improve user experience and monitor usage patterns. Currently, this metadata includes whether or not a query ran successfully. In the future, we may also collect information such as:
   - Query runtime
   - Data source (remote or local)
   - File type (e.g., CSV, Parquet)
   - Query type (DDL vs. DML)

   No actual query content or results are ever stored or processed externally, only derived metadata.

3. **Analytics**  
   We use **Posthog** and **Cloudflare** for analytics purposes. Here’s how each service is involved:

   - **Posthog**:  
     Posthog is used to instrument page views, user interactions, and metadata around query execution. It does not capture or store query content, and all data collected is anonymized where possible (e.g., no personally identifiable information). Posthog may track:
     - Page views and navigational actions
     - Interaction metadata (e.g., whether a query was submitted)
     - Device and browser type
     - Session lengths and patterns  
     Posthog’s terms state that user data is stored securely and in compliance with GDPR and other relevant data privacy regulations. [More on Posthog’s privacy policy.](https://posthog.com/privacy)

   - **Cloudflare**:  
     Cloudflare helps provide secure content delivery and protects the platform from malicious activity. While Cloudflare collects certain data for these purposes, such as IP addresses and browser information, it does so to optimize network performance and maintain security. This data is typically anonymized or aggregated. Cloudflare’s terms of service ensure data privacy through encryption and adherence to GDPR guidelines. [More on Cloudflare’s privacy policy.](https://www.cloudflare.com/privacypolicy/)
