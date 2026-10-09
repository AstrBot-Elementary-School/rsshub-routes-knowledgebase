# International Monetary Fund - Staff Country Reports

## Coverage
`index-only`

## Route
- Namespace: `imf`
- Namespace Name: `International Monetary Fund`
- Route Path: `/imf/country-reports/:country?`
- Route Name: `Staff Country Reports`
- Example: `/imf/country-reports/Germany`
- URL: `www.imf.org`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `country-reports.ts`
- Source Module: `_None_`

## Description
Latest Staff Country Reports, including Article IV consultations, Selected Issues, and financial sector assessments. Items contain the official report abstract and link to the publication page.

## Parameters
- `country`: {"description": "Official country name in the Country search filter. Omit to subscribe to all countries.", "options": [{"label": "Germany", "value": "Germany"}, {"label": "United Kingdom", "value": "United Kingdom"}, {"label": "China", "value": "China, People's Republic of"}, {"label": "France", "value": "France"}, {"label": "United States", "value": "United States"}, {"label": "Japan", "value": "Japan"}, {"label": "Hong Kong", "value": "Hong Kong Special Administrative Region, People's Republic of China"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.imf.org/en/publications/search`
- `target`: `/country-reports`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Latest Staff Country Reports, including Article IV consultations, Selected Issues, and financial sector assessments. Items contain the official report abstract and link to the publication page.",
  "example": "/imf/country-reports/Germany",
  "heat": 0,
  "location": "country-reports.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Staff Country Reports",
  "parameters": {
    "country": {
      "description": "Official country name in the Country search filter. Omit to subscribe to all countries.",
      "options": [
        {
          "label": "Germany",
          "value": "Germany"
        },
        {
          "label": "United Kingdom",
          "value": "United Kingdom"
        },
        {
          "label": "China",
          "value": "China, People's Republic of"
        },
        {
          "label": "France",
          "value": "France"
        },
        {
          "label": "United States",
          "value": "United States"
        },
        {
          "label": "Japan",
          "value": "Japan"
        },
        {
          "label": "Hong Kong",
          "value": "Hong Kong Special Administrative Region, People's Republic of China"
        }
      ]
    }
  },
  "path": "/country-reports/:country?",
  "radar": [
    {
      "source": [
        "www.imf.org/en/publications/search"
      ],
      "target": "/country-reports"
    }
  ],
  "topFeeds": []
}
```
