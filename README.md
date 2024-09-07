# sidequery

[sidequery.ai](https://sidequery.ai): Query & visualize remote & local CSV and Parquet with DuckDB in your browser. 

This is the public issue tracker. Issue reports for bugs or features requests are much appreciated! 😎

## Getting Started
Check out [sidequery.ai](https://sidequery.ai) to get started— no login required. 

## Privacy
All your tabs and queries are stored locally in your browser, and any uploaded data never leaves your device. We use Posthog and Cloudflare for analytics and instrument page view activities and metadata around query execution, discarding specific query content and results.

## Changelog

- `2024-09-07`
  - Faster file "uploads"
    - Sidequery currently runs 100% locally, so no data goes anywhere but your browser
  - Query is autorun on file upload
    - With a 1 million row limit; feels reasonable right now?
  - Explore view is the default

- `2024-09-06`
  - Public launch of sidequery.ai
