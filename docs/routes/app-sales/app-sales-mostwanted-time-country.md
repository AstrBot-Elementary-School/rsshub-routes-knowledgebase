# AppSales - Watchlist Charts

## Coverage
`index-only`

## Route
- Namespace: `app-sales`
- Namespace Name: `AppSales`
- Route Path: `/app-sales/mostwanted/:time?/:country?`
- Route Name: `Watchlist Charts`
- Example: `/app-sales/mostwanted`
- URL: `app-sales.net`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `mostwanted.ts`
- Source Module: `_None_`

## Description
| Last 24h | Last Week | All Time |
| -------- | --------- | -------- |
| 24h      | week      | alltime  |

<details>
  <summary>More countries</summary>

| Currency | Country       | ID |
| -------- | ------------- | -- |
| USD      | United States | us |
| EUR      | Austria       | at |
| AUD      | Australia     | au |
| BRL      | Brazil        | br |
| CAD      | Canada        | ca |
| EUR      | France        | fr |
| EUR      | Germany       | de |
| INR      | India         | in |
| EUR      | Italy         | it |
| EUR      | Netherlands   | nl |
| PLN      | Poland        | pl |
| RUB      | Russia        | ru |
| EUR      | Spain         | es |
| SEK      | Sweden        | se |
| GBP      | Great Britain | gb |

</details>

## Parameters
- `time`: {"description": "Time, `24h` as Last 24h by default", "options": [{"label": "Last 24h", "value": "24h"}, {"label": "Last Week", "value": "week"}, {"label": "All Time", "value": "alltime"}]}
- `country`: {"description": "Country ID, `us` as United States by default", "options": [{"label": "United States", "value": "us"}, {"label": "Austria", "value": "at"}, {"label": "Australia", "value": "au"}, {"label": "Brazil", "value": "br"}, {"label": "Canada", "value": "ca"}, {"label": "France", "value": "fr"}, {"label": "Germany", "value": "de"}, {"label": "India", "value": "in"}, {"label": "Italy", "value": "it"}, {"label": "Netherlands", "value": "nl"}, {"label": "Poland", "value": "pl"}, {"label": "Russia", "value": "ru"}, {"label": "Spain", "value": "es"}, {"label": "Sweden", "value": "se"}, {"label": "Great Britain", "value": "gb"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `app-sales.net/mostwanted`
- `target`: `/mostwanted`
### Rule 2
- `title`: `Watchlist Charts - Last 24h`
- `source`:
  - `app-sales.net/mostwanted`
- `target`: `/mostwanted/24h`
### Rule 3
- `title`: `Watchlist Charts - Last Week`
- `source`:
  - `app-sales.net/mostwanted`
- `target`: `/mostwanted/week`
### Rule 4
- `title`: `Watchlist Charts - All Time`
- `source`:
  - `app-sales.net/mostwanted`
- `target`: `/mostwanted/alltime`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Last 24h | Last Week | All Time |\n| -------- | --------- | -------- |\n| 24h      | week      | alltime  |\n\n<details>\n  <summary>More countries</summary>\n\n| Currency | Country       | ID |\n| -------- | ------------- | -- |\n| USD      | United States | us |\n| EUR      | Austria       | at |\n| AUD      | Australia     | au |\n| BRL      | Brazil        | br |\n| CAD      | Canada        | ca |\n| EUR      | France        | fr |\n| EUR      | Germany       | de |\n| INR      | India         | in |\n| EUR      | Italy         | it |\n| EUR      | Netherlands   | nl |\n| PLN      | Poland        | pl |\n| RUB      | Russia        | ru |\n| EUR      | Spain         | es |\n| SEK      | Sweden        | se |\n| GBP      | Great Britain | gb |\n\n</details>",
  "example": "/app-sales/mostwanted",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "mostwanted.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Watchlist Charts",
  "parameters": {
    "country": {
      "description": "Country ID, `us` as United States by default",
      "options": [
        {
          "label": "United States",
          "value": "us"
        },
        {
          "label": "Austria",
          "value": "at"
        },
        {
          "label": "Australia",
          "value": "au"
        },
        {
          "label": "Brazil",
          "value": "br"
        },
        {
          "label": "Canada",
          "value": "ca"
        },
        {
          "label": "France",
          "value": "fr"
        },
        {
          "label": "Germany",
          "value": "de"
        },
        {
          "label": "India",
          "value": "in"
        },
        {
          "label": "Italy",
          "value": "it"
        },
        {
          "label": "Netherlands",
          "value": "nl"
        },
        {
          "label": "Poland",
          "value": "pl"
        },
        {
          "label": "Russia",
          "value": "ru"
        },
        {
          "label": "Spain",
          "value": "es"
        },
        {
          "label": "Sweden",
          "value": "se"
        },
        {
          "label": "Great Britain",
          "value": "gb"
        }
      ]
    },
    "time": {
      "description": "Time, `24h` as Last 24h by default",
      "options": [
        {
          "label": "Last 24h",
          "value": "24h"
        },
        {
          "label": "Last Week",
          "value": "week"
        },
        {
          "label": "All Time",
          "value": "alltime"
        }
      ]
    }
  },
  "path": "/mostwanted/:time?/:country?",
  "radar": [
    {
      "source": [
        "app-sales.net/mostwanted"
      ],
      "target": "/mostwanted"
    },
    {
      "source": [
        "app-sales.net/mostwanted"
      ],
      "target": "/mostwanted/24h",
      "title": "Watchlist Charts - Last 24h"
    },
    {
      "source": [
        "app-sales.net/mostwanted"
      ],
      "target": "/mostwanted/week",
      "title": "Watchlist Charts - Last Week"
    },
    {
      "source": [
        "app-sales.net/mostwanted"
      ],
      "target": "/mostwanted/alltime",
      "title": "Watchlist Charts - All Time"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The hottest android apps from the last 24 hours, 7 days or all-time. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198041481153666048",
      "image": "https://www.app-sales.net/img/appsales_logo_claim.png",
      "ownerUserId": null,
      "siteUrl": "https://www.app-sales.net/mostwanted/",
      "title": "Watchlist Charts | AppSales - Last 24h",
      "type": "feed",
      "url": "rsshub://app-sales/mostwanted/24h/us"
    },
    {
      "description": "The hottest android apps from the last 24 hours, 7 days or all-time. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "272254035724080128",
      "image": "https://www.app-sales.net/img/appsales_logo_claim.png",
      "ownerUserId": null,
      "siteUrl": "https://www.app-sales.net/mostwanted/",
      "title": "Watchlist Charts | AppSales - Last Week",
      "type": "feed",
      "url": "rsshub://app-sales/mostwanted/week/us"
    }
  ],
  "url": "app-sales.net",
  "view": 0
}
```
