# Cache Analyzer

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/amithcabraal/cache-analyser)

A powerful web application for analyzing HTTP cache performance and network traffic patterns. This tool helps developers and performance engineers understand and optimize their website's caching behavior.

## Features

- **Data Import**: Import network traffic data from HAR files or JSON sources
- **Interactive Dashboard**: Visualize cache performance with dynamic, resizable charts
- **Advanced Filtering**: Filter requests by:
  - HTTP Method
  - URL Pattern
  - Cache Control Headers
  - CloudFront POP Location
  - Cache Status
  - File Types
  - Domains

## Charts and Analytics

- **Cache Performance**:
  - Size distribution by cache status
  - Request count by cache status
  - Domain-specific cache analysis
  - File type cache patterns

- **Geographic Analysis**:
  - Traffic distribution by CloudFront POPs
  - Regional cache performance

- **Resource Analysis**:
  - File type distribution
  - Domain-level statistics
  - Cache effectiveness by content type

## Data Grid Features

- **Detailed Request Analysis**:
  - Full URL inspection
  - Cache control headers
  - Response sizes
  - Status codes
  - Cache rankings
  - Time metrics

- **Grid Capabilities**:
  - Sorting and filtering
  - Column customization
  - Data export
  - Quick search

## Sharing and Collaboration

- Share analysis via URL
- Persistent layout customization
- Export data as JSON
- Save and reload previous analyses

## Cache Ranking System

Requests are categorized into different cache effectiveness levels:
- Optimal (Memory Cache)
- Excellent (Disk Cache, Service Worker)
- Browser Cache
- CDN Hit
- CDN Miss
- Uncached
- Error