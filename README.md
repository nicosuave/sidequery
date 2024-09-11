# sidequery

[sidequery.ai](https://sidequery.ai): Query & visualize remote & local CSV and Parquet with DuckDB in your browser. 

This is the changelog, privacy policy & public issue tracker, all in one. Bug reports or feature requests are much appreciated!

## Getting Started
Check out [sidequery.ai](https://sidequery.ai) to get started— no login required. 

## Changelog
- `2024-09-11`
  - Folder refresh
    - If you attached a folder of files, you can now add more files & refresh the tables (actually views)

- `2024-09-09`
  - CSV exports
  - Rearranged chart configuration

- `2024-09-08`
  - Column summaries
    - Hover over a column in the documentation sidebar and you'll get statistics for the column
  - Table peek
    - When you hover over a table name, you'll now see an eye icon. Clicking that will load 10,000 results into the results browser.
      - Look, ma— no SQL required
  - Sharing
    - Each time you run a query, the URL will be updated, encoding your query as part of the URL so you can share it
    - If you open a shared url, the shared query will open in a new editor tab
  - Bugfixes
    - Sort order is now properly reset when the results are updated

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
   All your data, including queries, results, and uploaded files, are stored 100% locally in your browser. This data never leaves your device and is not transmitted to our servers. Your information remains entirely under your control and is only accessible on your local machine.

2. **Analytics**
   We use Posthog and Cloudflare for analytics and security purposes. These services collect limited data to help us improve the platform and ensure its security. This includes:
   - Anonymous usage statistics (e.g., page views, feature usage)
   - Technical information (e.g., browser type, device type)

   No specific query content, results, or personal data are ever collected or stored by our analytics tools.
