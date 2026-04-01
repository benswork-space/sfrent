# The Rent Is Too Damn High

An interactive infographic visualizing how lack of new housing construction in San Francisco has contributed to skyrocketing rents, compared to other US cities that built more.

## What it shows

- **San Francisco**: Rent vs. net new housing units completed (2004-2026), animated left-to-right
- **Comparison cities**: Austin, Nashville, Seattle, Denver, and Charlotte — cities that built significantly more housing and saw slower rent growth
- SF's rent line overlaid as a dashed ghost on comparison charts for contrast

## Data sources

- **Rent**: [Zillow Observed Rent Index (ZORI)](https://www.zillow.com/research/data/) — city-level, 2015-2025. Pre-2015 values scaled from Census ACS trends.
- **SF housing units**: [SF Planning Dept. Housing Inventory](https://sfplanning.org/project/housing-inventory) — net new units completed, city of San Francisco only.
- **Other cities' housing units**: [U.S. Census Bureau ACS Table B25001](https://data.census.gov/) — year-over-year change in total housing units at city level.

## Run locally

Open `index.html` in a browser, or:

```
python3 -m http.server 3000
```

Then visit http://localhost:3000

## Deploy

This is a single static HTML file — works on GitHub Pages, Netlify, Vercel, or any static host.
