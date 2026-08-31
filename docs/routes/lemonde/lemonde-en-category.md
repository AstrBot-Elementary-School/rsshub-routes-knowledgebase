# Le Monde - News (English)

## Coverage
`index-only`

## Route
- Namespace: `lemonde`
- Namespace Name: `Le Monde`
- Route Path: `/lemonde/en/:category?`
- Route Name: `News (English)`
- Example: `/lemonde/en`
- URL: `lemonde.fr`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `mlkgrnt`
- Source Location: `en.ts`
- Source Module: `_None_`

## Description
| Category                | Description               |
| ----------------------- | ------------------------- |
| (empty)                 | Homepage / Top stories    |
| international           | World – International     |
| americas                | World – Americas          |
| united-kingdom          | World – United Kingdom    |
| united-states           | World – United States     |
| africa                  | World – Africa            |
| asia-pacific            | World – Asia Pacific      |
| middle-east             | World – Middle East       |
| europe                  | Europe                    |
| politics                | France – French Politics  |
| police-and-justice      | France – French Justice   |
| education               | France – French Education |
| french-delights         | France – French Delights  |
| environment             | Environment               |
| economy                 | Economy                   |
| world-economy           | Economy – World Economy   |
| french-economy          | Economy – French Economy  |
| m-le-mag                | M Magazine                |
| lifestyle               | M Magazine – Lifestyle    |
| fashion                 | M Magazine – Fashion      |
| food                    | M Magazine – Food         |
| travel                  | M Magazine – Travel       |
| culture                 | Culture                   |
| arts                    | Culture – Art             |
| cinema                  | Culture – Cinema          |
| music                   | Culture – Music           |
| books                   | Culture – Books           |
| global-issues           | Global Issues             |
| pixels                  | Pixels                    |
| artificial-intelligence | Pixels – AI               |
| social-media            | Pixels – Social Media     |
| sports                  | Sports                    |
| football                | Sports – Football         |
| rugby                   | Sports – Rugby            |
| tennis                  | Sports – Tennis           |
| cycling                 | Sports – Cycling          |
| basketball              | Sports – Basketball       |
| science                 | Science                   |
| health                  | Health                    |
| intimacy                | Intimacy                  |
| les-decodeurs           | Les Décodeurs             |
| our-times               | Our Times                 |
| obituaries              | Obituaries                |
| religion                | Religion                  |
| opinion                 | Opinion                   |
| editorials              | Opinion – Editorials      |
| columns                 | Opinion – Columns         |
| op-eds                  | Opinion – Op-Eds          |

## Parameters
- `category`: {"default": "", "description": "Category slug, see table below. Defaults to homepage."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lemonde.fr/en/:category`
- `target`: `/en/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Category                | Description               |\n| ----------------------- | ------------------------- |\n| (empty)                 | Homepage / Top stories    |\n| international           | World – International     |\n| americas                | World – Americas          |\n| united-kingdom          | World – United Kingdom    |\n| united-states           | World – United States     |\n| africa                  | World – Africa            |\n| asia-pacific            | World – Asia Pacific      |\n| middle-east             | World – Middle East       |\n| europe                  | Europe                    |\n| politics                | France – French Politics  |\n| police-and-justice      | France – French Justice   |\n| education               | France – French Education |\n| french-delights         | France – French Delights  |\n| environment             | Environment               |\n| economy                 | Economy                   |\n| world-economy           | Economy – World Economy   |\n| french-economy          | Economy – French Economy  |\n| m-le-mag                | M Magazine                |\n| lifestyle               | M Magazine – Lifestyle    |\n| fashion                 | M Magazine – Fashion      |\n| food                    | M Magazine – Food         |\n| travel                  | M Magazine – Travel       |\n| culture                 | Culture                   |\n| arts                    | Culture – Art             |\n| cinema                  | Culture – Cinema          |\n| music                   | Culture – Music           |\n| books                   | Culture – Books           |\n| global-issues           | Global Issues             |\n| pixels                  | Pixels                    |\n| artificial-intelligence | Pixels – AI               |\n| social-media            | Pixels – Social Media     |\n| sports                  | Sports                    |\n| football                | Sports – Football         |\n| rugby                   | Sports – Rugby            |\n| tennis                  | Sports – Tennis           |\n| cycling                 | Sports – Cycling          |\n| basketball              | Sports – Basketball       |\n| science                 | Science                   |\n| health                  | Health                    |\n| intimacy                | Intimacy                  |\n| les-decodeurs           | Les Décodeurs             |\n| our-times               | Our Times                 |\n| obituaries              | Obituaries                |\n| religion                | Religion                  |\n| opinion                 | Opinion                   |\n| editorials              | Opinion – Editorials      |\n| columns                 | Opinion – Columns         |\n| op-eds                  | Opinion – Op-Eds          |",
  "example": "/lemonde/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "en.ts",
  "maintainers": [
    "mlkgrnt"
  ],
  "name": "News (English)",
  "parameters": {
    "category": {
      "default": "",
      "description": "Category slug, see table below. Defaults to homepage."
    }
  },
  "path": "/en/:category?",
  "radar": [
    {
      "source": [
        "lemonde.fr/en/:category"
      ],
      "target": "/en/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(7) ] to not include 'https://www.lemonde.fr/en/economy/art…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 0
}
```
