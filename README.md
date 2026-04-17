# European Real Estate Market Data

Open dataset of property prices across **6 European countries**, **35+ cities**, and **500,000+ active listings**. Updated weekly from major property portals.

Data powered by [**Realty Pulse**](https://realty-pulse.com) — European real estate market intelligence platform.

## What's Inside

| File | Description | Updated |
|------|-------------|---------|
| [`data/city_prices.csv`](data/city_prices.csv) | Median prices by city (price, price/m², avg size) | Weekly |
| [`data/country_summary.csv`](data/country_summary.csv) | Country-level aggregates | Weekly |

## Coverage

| Country | Cities | Active Listings | Source |
|---------|--------|----------------|--------|
| Spain | 10 | 390,000+ | Idealista, Fotocasa |
| France | 10 | 220,000+ | Bienici |
| Germany | 10 | 45,000+ | ImmoScout24, Immowelt |
| United Kingdom | 8 | 40,000+ | Rightmove |
| Portugal | 8 | 29,000+ | Imovirtual |
| Italy | 10 | 15,000+ | Casa.it |

## Sample Data

### Most Expensive Cities by Price per m² (2026)

| City | Country | Median Price/m² | Median Price | Listings |
|------|---------|----------------|--------------|----------|
| Paris | France | €11,000 | €160,000 | 47,720 |
| Munich | Germany | €9,096 | €709,000 | 335 |
| San Sebastian | Spain | €6,580 | €695,000 | 598 |
| Frankfurt | Germany | €6,172 | €505,000 | 96 |
| Hamburg | Germany | €5,554 | €672,040 | 353 |
| Palma | Spain | €5,280 | €750,000 | 8,593 |
| Düsseldorf | Germany | €5,161 | €640,900 | 87 |
| Stuttgart | Germany | €4,925 | €396,757 | 90 |
| Berlin | Germany | €4,800 | €449,500 | 690 |
| Cologne | Germany | €4,554 | €439,000 | 129 |

## Full Analysis

For interactive charts, district-level breakdowns, city comparisons, and transaction data from official government records:

**[realty-pulse.com](https://realty-pulse.com)**

- [City Pages](https://realty-pulse.com/en/city/madrid) — district prices, trends, ask vs sold gap
- [Country Pages](https://realty-pulse.com/en/country/es) — city rankings, market overview
- [City Comparisons](https://realty-pulse.com/en/compare/madrid-vs-barcelona) — side-by-side analysis
- [Blog](https://realty-pulse.com/en/blog) — weekly market insights

## Data Sources

Listing data is aggregated from public property portals. Transaction data comes from official government open data:
- France: DVF (Demandes de Valeurs Foncières)
- UK: HM Land Registry Price Paid Data
- Latvia: VZD (State Land Service)
- Estonia: Land Board transaction data
- Slovenia: GURS geodetic data

## License

Data is provided for research and educational purposes. Commercial use requires attribution to [Realty Pulse](https://realty-pulse.com).

## API Access

Looking for programmatic access? Visit [realty-pulse.com](https://realty-pulse.com) for API documentation.
