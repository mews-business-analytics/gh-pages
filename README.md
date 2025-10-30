# GTM Analytics Dashboards

Public repository for hosting interactive dashboards and visualizations for the Business Analytics team.

## Available Dashboards

### Territory Mapping
View the 2026 territory consolidation overview with countries grouped by new territories.

**Live URL:** https://mews-business-analytics.github.io/gh-pages/territory-mapping/territory-mapping.html

## Usage

These dashboards are designed to be embedded in Confluence pages via iframe.

### Confluence Embed Example

```html
<iframe
  src="https://mews-business-analytics.github.io/gh-pages/territory-mapping/territory-mapping.html"
  width="100%"
  height="1000px"
  frameborder="0"
  style="border: none;">
</iframe>
```

## Maintenance

This repository is maintained by the Business Analytics team.

To add new dashboards:
1. Create a new folder for the dashboard (e.g., `my-dashboard/`)
2. Add your HTML file (self-contained with all CSS/JS inline)
3. Update this README with the new dashboard link
4. Commit and push to main
5. GitHub Pages will automatically deploy within 2-3 minutes

## Source Repository

The source code and data transformations are maintained in the private [gtm_dbt](https://github.com/mews-business-analytics/gtm_dbt) repository.
