# Expats.cz - Czech News

## Coverage
`index-only`

## Route
- Namespace: `expats`
- Namespace Name: `Expats.cz`
- Route Path: `/expats/czech-news/:category?`
- Route Name: `Czech News`
- Example: `/expats/czech-news/daily-news`
- URL: `www.expats.cz`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `czech-news.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Daily News](https://www.expats.cz/czech-news/daily-news), where the source URL is `https://www.expats.cz/czech-news/daily-news`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/expats/czech-news/daily-news`](https://rsshub.app/expats/czech-news/daily-news).
:::

<details>
  <summary>More categories</summary>

| Category                                                      | ID                                                                    |
| ------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Daily News](https://www.expats.cz/czech-news/daily-news)     | [daily-news](https://rsshub.app/expats/czech-news/daily-news)         |
| [Prague Guide](https://www.expats.cz/czech-news/prague-guide) | [prague-guide](https://rsshub.app/expats/czech-news/prague-guide)     |
| [Culture](https://www.expats.cz/czech-news/culture-events)    | [culture-events](https://rsshub.app/expats/czech-news/culture-events) |
| [Food & Drink](https://www.expats.cz/czech-news/food-drink)   | [food-drink](https://rsshub.app/expats/czech-news/food)               |
| [Expat Life](https://www.expats.cz/czech-news/expat-life)     | [expat-life](https://rsshub.app/expats/czech-news/expat-life)         |
| [Housing](https://www.expats.cz/czech-news/housing)           | [housing](https://rsshub.app/expats/czech-news/housing)               |
| [Education](https://www.expats.cz/czech-news/education)       | [education](https://rsshub.app/expats/czech-news/education)           |
| [Health](https://www.expats.cz/czech-news/health)             | [health](https://rsshub.app/expats/czech-news/health)                 |
| [Work](https://www.expats.cz/czech-news/work)                 | [work](https://rsshub.app/expats/czech-news/work)                     |
| [Travel](https://www.expats.cz/czech-news/travel)             | [travel](https://rsshub.app/expats/czech-news/travel)                 |
| [Economy](https://www.expats.cz/czech-news/economy)           | [economy](https://rsshub.app/expats/czech-news/economy)               |
| [Language](https://www.expats.cz/czech-news/language)         | [language](https://rsshub.app/expats/czech-news/language)             |

</details>

## Parameters
- `category`: {"description": "Category, `daily-news` by default", "options": [{"label": "Daily News", "value": "daily-news"}, {"label": "Prague Guide", "value": "prague-guide"}, {"label": "Culture & Events", "value": "culture-events"}, {"label": "Food & Drink", "value": "food-drink"}, {"label": "Expat Life", "value": "expat-life"}, {"label": "Housing", "value": "housing"}, {"label": "Education", "value": "education"}, {"label": "Health", "value": "health"}, {"label": "Work", "value": "work"}, {"label": "Travel", "value": "travel"}, {"label": "Economy", "value": "economy"}, {"label": "Language", "value": "language"}]}


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
  - `www.expats.cz/czech-news/:category`
### Rule 2
- `title`: `Daily News`
- `source`:
  - `www.expats.cz/czech-news/daily-news`
- `target`: `/expats/czech-news/daily-news`
### Rule 3
- `title`: `Prague Guide`
- `source`:
  - `www.expats.cz/czech-news/prague-guide`
- `target`: `/expats/czech-news/prague-guide`
### Rule 4
- `title`: `Culture & Events`
- `source`:
  - `www.expats.cz/czech-news/culture-events`
- `target`: `/expats/czech-news/culture-events`
### Rule 5
- `title`: `Food & Drink`
- `source`:
  - `www.expats.cz/czech-news/food-drink`
- `target`: `/expats/czech-news/food-drink`
### Rule 6
- `title`: `Expat Life`
- `source`:
  - `www.expats.cz/czech-news/expat-life`
- `target`: `/expats/czech-news/expat-life`
### Rule 7
- `title`: `Housing`
- `source`:
  - `www.expats.cz/czech-news/housing`
- `target`: `/expats/czech-news/housing`
### Rule 8
- `title`: `Education`
- `source`:
  - `www.expats.cz/czech-news/education`
- `target`: `/expats/czech-news/education`
### Rule 9
- `title`: `Health`
- `source`:
  - `www.expats.cz/czech-news/health`
- `target`: `/expats/czech-news/health`
### Rule 10
- `title`: `Work`
- `source`:
  - `www.expats.cz/czech-news/work`
- `target`: `/expats/czech-news/work`
### Rule 11
- `title`: `Travel`
- `source`:
  - `www.expats.cz/czech-news/travel`
- `target`: `/expats/czech-news/travel`
### Rule 12
- `title`: `Economy`
- `source`:
  - `www.expats.cz/czech-news/economy`
- `target`: `/expats/czech-news/economy`
### Rule 13
- `title`: `Language`
- `source`:
  - `www.expats.cz/czech-news/language`
- `target`: `/expats/czech-news/language`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Daily News](https://www.expats.cz/czech-news/daily-news), where the source URL is `https://www.expats.cz/czech-news/daily-news`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/expats/czech-news/daily-news`](https://rsshub.app/expats/czech-news/daily-news).\n:::\n\n<details>\n  <summary>More categories</summary>\n\n| Category                                                      | ID                                                                    |\n| ------------------------------------------------------------- | --------------------------------------------------------------------- |\n| [Daily News](https://www.expats.cz/czech-news/daily-news)     | [daily-news](https://rsshub.app/expats/czech-news/daily-news)         |\n| [Prague Guide](https://www.expats.cz/czech-news/prague-guide) | [prague-guide](https://rsshub.app/expats/czech-news/prague-guide)     |\n| [Culture](https://www.expats.cz/czech-news/culture-events)    | [culture-events](https://rsshub.app/expats/czech-news/culture-events) |\n| [Food & Drink](https://www.expats.cz/czech-news/food-drink)   | [food-drink](https://rsshub.app/expats/czech-news/food)               |\n| [Expat Life](https://www.expats.cz/czech-news/expat-life)     | [expat-life](https://rsshub.app/expats/czech-news/expat-life)         |\n| [Housing](https://www.expats.cz/czech-news/housing)           | [housing](https://rsshub.app/expats/czech-news/housing)               |\n| [Education](https://www.expats.cz/czech-news/education)       | [education](https://rsshub.app/expats/czech-news/education)           |\n| [Health](https://www.expats.cz/czech-news/health)             | [health](https://rsshub.app/expats/czech-news/health)                 |\n| [Work](https://www.expats.cz/czech-news/work)                 | [work](https://rsshub.app/expats/czech-news/work)                     |\n| [Travel](https://www.expats.cz/czech-news/travel)             | [travel](https://rsshub.app/expats/czech-news/travel)                 |\n| [Economy](https://www.expats.cz/czech-news/economy)           | [economy](https://rsshub.app/expats/czech-news/economy)               |\n| [Language](https://www.expats.cz/czech-news/language)         | [language](https://rsshub.app/expats/czech-news/language)             |\n\n</details>",
  "example": "/expats/czech-news/daily-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "czech-news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Czech News",
  "parameters": {
    "category": {
      "description": "Category, `daily-news` by default",
      "options": [
        {
          "label": "Daily News",
          "value": "daily-news"
        },
        {
          "label": "Prague Guide",
          "value": "prague-guide"
        },
        {
          "label": "Culture & Events",
          "value": "culture-events"
        },
        {
          "label": "Food & Drink",
          "value": "food-drink"
        },
        {
          "label": "Expat Life",
          "value": "expat-life"
        },
        {
          "label": "Housing",
          "value": "housing"
        },
        {
          "label": "Education",
          "value": "education"
        },
        {
          "label": "Health",
          "value": "health"
        },
        {
          "label": "Work",
          "value": "work"
        },
        {
          "label": "Travel",
          "value": "travel"
        },
        {
          "label": "Economy",
          "value": "economy"
        },
        {
          "label": "Language",
          "value": "language"
        }
      ]
    }
  },
  "path": "/czech-news/:category?",
  "radar": [
    {
      "source": [
        "www.expats.cz/czech-news/:category"
      ]
    },
    {
      "source": [
        "www.expats.cz/czech-news/daily-news"
      ],
      "target": "/expats/czech-news/daily-news",
      "title": "Daily News"
    },
    {
      "source": [
        "www.expats.cz/czech-news/prague-guide"
      ],
      "target": "/expats/czech-news/prague-guide",
      "title": "Prague Guide"
    },
    {
      "source": [
        "www.expats.cz/czech-news/culture-events"
      ],
      "target": "/expats/czech-news/culture-events",
      "title": "Culture & Events"
    },
    {
      "source": [
        "www.expats.cz/czech-news/food-drink"
      ],
      "target": "/expats/czech-news/food-drink",
      "title": "Food & Drink"
    },
    {
      "source": [
        "www.expats.cz/czech-news/expat-life"
      ],
      "target": "/expats/czech-news/expat-life",
      "title": "Expat Life"
    },
    {
      "source": [
        "www.expats.cz/czech-news/housing"
      ],
      "target": "/expats/czech-news/housing",
      "title": "Housing"
    },
    {
      "source": [
        "www.expats.cz/czech-news/education"
      ],
      "target": "/expats/czech-news/education",
      "title": "Education"
    },
    {
      "source": [
        "www.expats.cz/czech-news/health"
      ],
      "target": "/expats/czech-news/health",
      "title": "Health"
    },
    {
      "source": [
        "www.expats.cz/czech-news/work"
      ],
      "target": "/expats/czech-news/work",
      "title": "Work"
    },
    {
      "source": [
        "www.expats.cz/czech-news/travel"
      ],
      "target": "/expats/czech-news/travel",
      "title": "Travel"
    },
    {
      "source": [
        "www.expats.cz/czech-news/economy"
      ],
      "target": "/expats/czech-news/economy",
      "title": "Economy"
    },
    {
      "source": [
        "www.expats.cz/czech-news/language"
      ],
      "target": "/expats/czech-news/language",
      "title": "Language"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(4) ] to not include 'https://www.expats.cz/czech-news/arti…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.expats.cz",
  "view": 0
}
```
