# GTM Analytics Dashboards

Public repository for hosting interactive dashboards and visualizations for the Business Analytics team.

## Available Dashboards

### Territory Mapping - 2026 Consolidation

Two complementary views of the territory consolidation:

#### 1. Territory Overview (Recommended for Confluence)
High-level view showing countries grouped by territory with property counts as color-coded pills.

**Live URL:** https://mews-business-analytics.github.io/gh-pages/territory-mapping/overview.html

**Best for:** Executive summaries, quick territory comparisons, visual presentation

#### 2. Territory Details
Detailed table showing all countries with old/new territory mappings and property counts. Includes sortable columns.

**Live URL:** https://mews-business-analytics.github.io/gh-pages/territory-mapping/details.html

**Best for:** Detailed analysis, country lookup, territory migration tracking

## Usage

These dashboards are designed to be embedded in Confluence pages via iframe.

### Confluence Embed Examples

**For Overview (Recommended):**
```html
<iframe
  src="https://mews-business-analytics.github.io/gh-pages/territory-mapping/overview.html"
  width="100%"
  height="800px"
  frameborder="0"
  style="border: none;">
</iframe>
```

**For Details:**
```html
<iframe
  src="https://mews-business-analytics.github.io/gh-pages/territory-mapping/details.html"
  width="100%"
  height="1200px"
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
