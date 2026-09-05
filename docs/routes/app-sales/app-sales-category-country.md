# AppSales - Category

## Coverage
`index-only`

## Route
- Namespace: `app-sales`
- Namespace Name: `AppSales`
- Route Path: `/app-sales/:category?/:country?`
- Route Name: `Category`
- Example: `/app-sales/highlights`
- URL: `app-sales.net`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Highlights](https://www.app-sales.net/highlights/), where the source URL is `https://www.app-sales.net/highlights/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/app-sales/highlights`](https://rsshub.app/app-sales/highlights).
:::

| Highlights | Active Sales | Now Free |
| ---------- | ------------ | -------- |
| highlights | activesales  | nowfree  |

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
- `category`: {"description": "Category, `highlights` as Highlights by default", "options": [{"label": "Highlights", "value": "highlights"}, {"label": "Active Sales", "value": "activesales"}, {"label": "Now Free", "value": "nowfree"}]}
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
  - `app-sales.net/:category`
### Rule 2
- `title`: `Highlights`
- `source`:
  - `app-sales.net/highlights`
- `target`: `/highlights`
### Rule 3
- `title`: `Active Sales`
- `source`:
  - `app-sales.net/activesales`
- `target`: `/activesales`
### Rule 4
- `title`: `Now Free`
- `source`:
  - `app-sales.net/nowfree`
- `target`: `/nowfree`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Highlights](https://www.app-sales.net/highlights/), where the source URL is `https://www.app-sales.net/highlights/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/app-sales/highlights`](https://rsshub.app/app-sales/highlights).\n:::\n\n| Highlights | Active Sales | Now Free |\n| ---------- | ------------ | -------- |\n| highlights | activesales  | nowfree  |\n\n<details>\n  <summary>More countries</summary>\n\n| Currency | Country       | ID |\n| -------- | ------------- | -- |\n| USD      | United States | us |\n| EUR      | Austria       | at |\n| AUD      | Australia     | au |\n| BRL      | Brazil        | br |\n| CAD      | Canada        | ca |\n| EUR      | France        | fr |\n| EUR      | Germany       | de |\n| INR      | India         | in |\n| EUR      | Italy         | it |\n| EUR      | Netherlands   | nl |\n| PLN      | Poland        | pl |\n| RUB      | Russia        | ru |\n| EUR      | Spain         | es |\n| SEK      | Sweden        | se |\n| GBP      | Great Britain | gb |\n\n</details>",
  "example": "/app-sales/highlights",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 7,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": {
      "description": "Category, `highlights` as Highlights by default",
      "options": [
        {
          "label": "Highlights",
          "value": "highlights"
        },
        {
          "label": "Active Sales",
          "value": "activesales"
        },
        {
          "label": "Now Free",
          "value": "nowfree"
        }
      ]
    },
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
    }
  },
  "path": "/:category?/:country?",
  "radar": [
    {
      "source": [
        "app-sales.net/:category"
      ]
    },
    {
      "source": [
        "app-sales.net/highlights"
      ],
      "target": "/highlights",
      "title": "Highlights"
    },
    {
      "source": [
        "app-sales.net/activesales"
      ],
      "target": "/activesales",
      "title": "Active Sales"
    },
    {
      "source": [
        "app-sales.net/nowfree"
      ],
      "target": "/nowfree",
      "title": "Now Free"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Android apps and games that are free for a limited time on Google Play - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198041350264348672",
      "image": "https://www.app-sales.net/img/appsales_logo_claim.png",
      "ownerUserId": null,
      "siteUrl": "https://www.app-sales.net/nowfree/",
      "title": "Now Free | AppSales",
      "type": "feed",
      "url": "rsshub://app-sales/nowfree/us"
    },
    {
      "description": "Most recent discounted and temporarily free Android apps and games on Google Play - Powered by RSSHub",
      "errorAt": "2026-09-03T17:22:52.802Z",
      "errorMessage": "Failed to fetch\n",
      "id": "256563101508143104",
      "image": "https://www.app-sales.net/img/appsales_logo_claim.png",
      "ownerUserId": null,
      "siteUrl": "https://www.app-sales.net/activesales/",
      "title": "Active Sales | AppSales",
      "type": "feed",
      "url": "rsshub://app-sales/activesales/us"
    }
  ],
  "url": "app-sales.net",
  "view": 0
}
```
