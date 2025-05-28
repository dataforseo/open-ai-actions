# open-ai-actions

This repository provides OpenAPI specifications for integrating [api.dataforseo.com](https://api.dataforseo.com) with ChatGPT Actions. The OpenAPI files describe endpoints for various DataForSEO APIs, enabling seamless access to SEO research and analysis tools via ChatGPT or other OpenAPI-compatible clients.

## Overview

The repository includes OpenAPI 3.1.0 specifications for the following DataForSEO API modules:

- **Backlinks API** (`dataforseo_backlinks_openapi.json`): Access backlink data, referring domains, anchors, competitors, and more.
- **Business Data API** (`dataforseo_business_data_openapi.json`): Retrieve business listings and related information from Google Maps.
- **DataForSEO Labs API** (`dataforseo_dataforseo_labs_openapi.json`): Advanced keyword, domain, and SERP analytics.
- **Domain Analytics API** (`dataforseo_domain_analytics_openapi.json`): WHOIS, technology stack, and domain analytics.
- **Keywords Data API** (`dataforseo_keywords_data_openapi.json`): Google Ads keyword search volume and related metrics.
- **On Page API** (`dataforseo_on_page_openapi.json`): On-page SEO analysis and content parsing.
- **SERP API** (`dataforseo_serp_api_openapi.json`): Real-time SERP data from Google, Bing, and Yahoo.
- **Researcher Toolkit API** (`dataforseo_researcher_toolkit.json`): Unified endpoints for common SEO research tasks, designed for seamless use with the ChatGPT Researcher Toolkit.

## Researcher Toolkit

The `dataforseo_researcher_toolkit.json` file provides a streamlined OpenAPI specification. This toolkit enables researchers, analysts, and SEO professionals to:

- Run advanced SEO research and analysis directly within ChatGPT.
- Automate workflows for keyword research, competitor analysis, SERP tracking, backlink audits, and content analysis.
- Use a simplified set of endpoints covering the most common DataForSEO use cases, making it easy to get started with minimal setup.

**Key endpoints in the Researcher Toolkit spec include:**
- SERP analysis for Google, Bing, and Yahoo.
- Google Ads keyword search volume.
- On-page content parsing and instant page analysis.
- Domain and keyword analytics, including competitor and intersection analysis.
- Backlink and referring domain data.

## Usage

1. **Import OpenAPI Specs:**  
   Use the provided `.json` files to import DataForSEO APIs into ChatGPT Actions, Postman, or any OpenAPI-compatible tool.

2. **Authentication:**  
   All endpoints require authentication with your DataForSEO API credentials. Refer to the [DataForSEO documentation](https://docs.dataforseo.com/) for details.

3. **Endpoint Structure:**  
   Each OpenAPI file documents available endpoints, request schemas, and usage examples which can be used with ChatGPT Actions.

## Example

To get Google Ads search volume for keywords using the Researcher Toolkit:

```json
POST /v3/keywords_data/google_ads/search_volume/live.ai
{
  "location_name": "United States",
  "language_code": "en",
  "keywords": ["seo", "backlinks"]
}
```

## Files

- `dataforseo_backlinks_openapi.json`
- `dataforseo_business_data_openapi.json`
- `dataforseo_dataforseo_labs_openapi.json`
- `dataforseo_domain_analytics_openapi.json`
- `dataforseo_keywords_data_openapi.json`
- `dataforseo_on_page_openapi.json`
- `dataforseo_serp_api_openapi.json`
- `dataforseo_researcher_toolkit.json` ← **Recommended for ChatGPT Researcher Toolkit**

## License

This project is licensed under the [Apache 2.0 License](LICENSE).

## References

- [DataForSEO Documentation](https://docs.dataforseo.com/)
- [OpenAPI Specification](https://swagger.io/specification/)
- [ChatGPT Researcher Toolkit](https://platform.openai.com/docs/assistants/overview)