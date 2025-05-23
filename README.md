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

## Usage

1. **Import OpenAPI Specs:**  
   Use the provided `.json` files to import DataForSEO APIs into ChatGPT Actions, Postman, or any OpenAPI-compatible tool.

2. **Authentication:**  
   All endpoints require authentication with your DataForSEO API credentials. Refer to the [DataForSEO documentation](https://docs.dataforseo.com/) for details.

3. **Endpoint Structure:**  
   Each OpenAPI file documents available endpoints, request schemas, and usage examples which can be used with ChatGPT Actions.