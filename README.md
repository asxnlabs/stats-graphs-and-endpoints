# Morpheus AI Metrics Dashboard V2

## Overview

The Morpheus AI Metrics Dashboard is a comprehensive tool designed to provide detailed insights into the Supply, Staking, Capital and Code Metrics for the MorpheusAI Community and its native token $MOR. This dashboard serves as a central hub for community members, stakers and developers to access critical data and analytics.

## Useful Links:
1) [Morpheus AI Metrics Dashboard](https://mor-explorer-frontend.pages.dev/supply)
2) [Gitbook Catalog](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard)
2) [API Reference](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/api-reference/introduction)
3) [Frontend Examples & Reference](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/frontend/markdown)
4) [Backend Examples & Reference](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/backend/api-helpers)
5) [Frontend Repository](https://github.com/NirmaanAI/stats-graphs-and-endpoints/tree/v2/morpheus-metrics-dashboard-frontend)
6) [Backend Repository](https://github.com/NirmaanAI/stats-graphs-and-endpoints/tree/v2/morpheus-metrics-dashboard)
7) [API Code](https://github.com/NirmaanAI/stats-graphs-and-endpoints/blob/v2/morpheus-metrics-dashboard/main.py)
8) [Codepen](https://codepen.io/collection/VYopJj)

## Features

- Comprehensive capital and code metrics added for $MOR token
- Detailed staking and supply analytics
- Interactive data visualizations
- Added API integrations for extended functionality
- Interactive dashboard layouts
- Historical data trends and projections

## Deployment

The current version of the dashboard is live and accessible at:
[Morpheus AI Metrics Dashboard](https://mor-explorer-frontend.pages.dev/supply)

This deployment is hosted on MOR.Software's cloud infrastructure, ensuring high availability and performance.

## Documentation

### GitBook Catalog

We have compiled a comprehensive GitBook catalog to serve as a reference guide for contributors and developers. This catalog provides in-depth information about the project's architecture, implementation details, and usage guidelines.

- [Morpheus Metrics Dashboard GitBook](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard)

The catalog includes:
- Step-by-step walkthroughs
- Code examples for both frontend and backend
- Detailed API integration guides

### API Reference

For developers looking to integrate or extend the dashboard's functionality, we have created a detailed API reference:

- [API Reference Guide](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/api-reference/introduction)

This guide outlines:
- Available endpoints
- Data Structures
- Sample requests and responses

## Development Resources

### Frontend

- [Frontend Examples & Reference](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/frontend/markdown)
- [Frontend Repository](https://github.com/NirmaanAI/stats-graphs-and-endpoints/tree/v2/morpheus-metrics-dashboard-frontend)

#### Frontend Integration Points

1. **Defined Components**: Utilizes custom React components for consistent UI elements.
2. **Comprehensive Toggling**: Uses a host of toggles across the dashboard for ease of use and enhanced optionality for the user.
3. **Charting**: Integrates with Recharts and Charts.js for advanced data visualizations and interactive charts.

### Backend

- [Backend Examples & Reference](https://nirmaans-organization.gitbook.io/morpheus-metrics-dashboard/backend/api-helpers)
- [Backend Repository](https://github.com/NirmaanAI/stats-graphs-and-endpoints/tree/v2/morpheus-metrics-dashboard)
- [API Implementation](https://github.com/NirmaanAI/stats-graphs-and-endpoints/blob/v2/morpheus-metrics-dashboard/main.py)

#### Backend Integration Points

1. **Data Sources**: Connects to multiple blockchain nodes and indexers for accurate data using `web3.py`.
2. **Caching Layer**: Implements an elaborate caching mechanism which integrates with FastAPI schedulers and decorators to provide high-performance caching of all endpoints.
3. **Asynchronous Code**: Relies heavily of async and non-blocking code to ensure that the data is fetched in the most optimized manner while maintaining accuracy and consistency.

### CodePen Collection

- [CodePen Collection](https://codepen.io/collection/VYopJj): A curated set of CodePen examples demonstrating various components and visualizations used in the dashboard. This can be referred to, in order to get an idea on how to integrate visualizations in accordance with the official Morpheus design scheme.

## Getting Started

To begin working with the Morpheus AI Metrics Dashboard:

1. Clone the frontend and backend repositories
2. Review the `README.md` documentation in each of the respective sub-directories for setup instructions
3. Explore the API reference to understand data flow
4. Check out the CodePen examples for frontend component insights
5. Set up your local development environment following the README in each repository

## Support

If you encounter any issues or have questions, please open an issue in the appropriate GitHub repository or reach out to our development team through the official MorpheusAI community channels.

---

This doc serves as a comprehensive reference for developers looking to understand the Morpheus AI Metrics Dashboard. We encourage all community members to review this documentation and provide feedback to ensure its accuracy and usefulness.
