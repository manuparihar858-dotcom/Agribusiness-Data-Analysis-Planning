# Public Data Sources for Agribusiness Analysis

This list is a discovery register, not a guarantee that every portal currently exposes all listed fields. At collection time, record the exact dataset title, publisher, URL, access date, time range, units, licence/terms, and any API requirements.

| Source | URL | Potential use | Validation checks |
|---|---|---|---|
| AGMARKNET, Directorate of Marketing & Inspection | https://agmarknet.gov.in/ | Wholesale prices and arrivals by commodity and market, where available | Price field definition, unit, market identifier, missing dates, duplicate records |
| e-NAM, National Agriculture Market | https://www.enam.gov.in/ | Supplementary market/platform context | Coverage and field definitions may differ from AGMARKNET |
| Department of Agriculture & Farmers Welfare | https://agriwelfare.gov.in/ | Official agriculture reports and statistics | Publication date, provisional/final status, crop-year definition |
| Directorate of Economics & Statistics | https://desagri.gov.in/ | Area, production, and yield statistics | Units, revisions, geographic coverage, year alignment |
| Open Government Data Platform India | https://www.data.gov.in/ | Discovery of public datasets from government publishers | Dataset publisher, update date, schema, reuse terms, API key requirements |
| India Meteorological Department | https://mausam.imd.gov.in/ | Rainfall/weather context | Station coverage, spatial resolution, aggregation method, missingness |
| FAOSTAT | https://www.fao.org/faostat/en/#data | Internationally comparable production, yield, land, and input indicators | Reporting period, revisions, comparability, and national vs. subnational coverage |

## Collection checklist
- [ ] Confirm the dataset directly answers a stated research question.
- [ ] Capture the exact dataset name and direct download/API link.
- [ ] Record access date and source metadata.
- [ ] Check licence and terms of reuse.
- [ ] Inspect units, date formats, geography, and field definitions.
- [ ] Preserve the original file unchanged.
- [ ] Record data quality issues and any transformations.
- [ ] Do not combine datasets until identifiers and definitions are aligned.
