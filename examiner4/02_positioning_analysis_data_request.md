# Data request for Section 7.2.4: positioning China and Singapore against the Chapter 4 European sample

This session cannot reach the OECD and World Bank data servers (the network policy blocks them), so please download the values below and send them to me. I will compute the statistics, fill in Table [new-5], and write the interpretation.

## 1. Reference year
- Use **one reference year**, ideally the last year in the Chapter 4 data window that has complete data (for example 2019, to avoid COVID distortion, or 2021).
- If a value is missing for that year, use the nearest earlier year and note which year it is.

## 2. Indicators and where to download them

| # | Construct | Indicator | Source and series | Countries |
|---|---|---|---|---|
| 1 | Government incentives (GI) | GERD financed by government, as % of GDP | OECD Data Explorer → *Main Science and Technology Indicators (MSTI)* → "GERD financed by government as a percentage of GDP" | All 35 European sample countries + China + Singapore |
| 2 | Innovation input (II) | GERD as % of GDP | OECD MSTI → "Gross domestic expenditure on R&D as a percentage of GDP" | same |
| 3 | Innovation input (II) | Total researchers (FTE) per thousand total employment | OECD MSTI → "Total researchers per thousand total employment" | same |
| 4 | Technology capability (TC) | Number of triadic patent families (priority year) | OECD MSTI → "Number of triadic patent families" | same |
| 5 | Technology capability (TC) | High-technology exports (current US$) | World Bank WDI, code **TX.VAL.TECH.CD** | same |

- OECD Data Explorer: https://data-explorer.oecd.org (search "MSTI")
- World Bank WDI: https://data.worldbank.org/indicator/TX.VAL.TECH.CD

China and Singapore are both covered by MSTI as non-member economies. If one MSTI series has no data for Singapore or China, tell me which one, and I will propose an equivalent from UNESCO UIS or WIPO.

## 3. What to send me
- A simple Excel/CSV file with columns: `country, iso3, indicator, year, value`.
- The **list of the 35 European countries** in the Chapter 4 sample. This lets me check the wording "European countries" and identify which are EU and which are not.

## 4. What I will compute
- For each indicator: the European sample minimum, 25th percentile, median, 75th percentile and maximum.
- China's and Singapore's position for each indicator: below the range, within the inter-quartile range, within the range, or above the range.
- Optionally, a scale-free version (indicators per capita or as % of GDP), because China's absolute values will exceed those of every European country simply because of its size.
- A short interpretation paragraph for Section 7.2.4, and one sentence for the response letter.
