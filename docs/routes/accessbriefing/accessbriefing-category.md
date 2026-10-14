# Access Briefing - Articles

## Coverage
`index-only`

## Route
- Namespace: `accessbriefing`
- Namespace Name: `Access Briefing`
- Route Path: `/accessbriefing/:category{.+}?`
- Route Name: `Articles`
- Example: `/accessbriefing/latest/news`
- URL: `accessbriefing.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [Latest News](https://www.accessbriefing.com/latest/news)，where the URL is `https://www.accessbriefing.com/latest/news`, extract the part `https://www.accessbriefing.com/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/accessbriefing/latest/news`](https://rsshub.app/accessbriefing/latest/news).
:::

#### Latest

| Category                                                                               | ID                                                                                                 |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [News](https://www.accessbriefing.com/latest/news)                                     | [latest/news](https://rsshub.app/accessbriefing/latest/news)                                       |
| [Products & Technology](https://www.accessbriefing.com/latest/products-and-technology) | [latest/products-and-technology](https://rsshub.app/accessbriefing/latest/products-and-technology) |
| [Rental News](https://www.accessbriefing.com/latest/rental-news)                       | [latest/rental-news](https://rsshub.app/accessbriefing/latest/rental-news)                         |
| [People](https://www.accessbriefing.com/latest/people)                                 | [latest/people](https://rsshub.app/accessbriefing/latest/people)                                   |
| [Regualtions & Safety](https://www.accessbriefing.com/latest/regualtions-safety)       | [latest/regualtions-safety](https://rsshub.app/accessbriefing/latest/regualtions-safety)           |
| [Finance](https://www.accessbriefing.com/latest/finance)                               | [latest/finance](https://rsshub.app/accessbriefing/latest/finance)                                 |
| [Sustainability](https://www.accessbriefing.com/latest/sustainability)                 | [latest/sustainability](https://rsshub.app/accessbriefing/latest/sustainability)                   |

#### Insight

| Category                                                                          | ID                                                                                           |
| --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| [Interviews](https://www.accessbriefing.com/insight/interviews)                   | [insight/interviews](https://rsshub.app/accessbriefing/insight/interviews)                   |
| [Longer reads](https://www.accessbriefing.com/insight/longer-reads)               | [insight/longer-reads](https://rsshub.app/accessbriefing/insight/longer-reads)               |
| [Videos and podcasts](https://www.accessbriefing.com/insight/videos-and-podcasts) | [insight/videos-and-podcasts](https://rsshub.app/accessbriefing/insight/videos-and-podcasts) |

## Parameters
- `category`: Category, Latest News by default


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
  - `accessbriefing.com/:category*`
- `target`: `/:category`
### Rule 2
- `title`: `Latest - News`
- `source`:
  - `accessbriefing.com/latest/news`
- `target`: `/latest/news`
### Rule 3
- `title`: `Latest - Products & Technology`
- `source`:
  - `accessbriefing.com/latest/products-and-technology`
- `target`: `/latest/products-and-technology`
### Rule 4
- `title`: `Latest - Rental News`
- `source`:
  - `accessbriefing.com/latest/rental-news`
- `target`: `/latest/rental-news`
### Rule 5
- `title`: `Latest - People`
- `source`:
  - `accessbriefing.com/latest/people`
- `target`: `/latest/people`
### Rule 6
- `title`: `Latest - Regualtions & Safety`
- `source`:
  - `accessbriefing.com/latest/regualtions-safety`
- `target`: `/latest/regualtions-safety`
### Rule 7
- `title`: `Latest - Finance`
- `source`:
  - `accessbriefing.com/latest/finance`
- `target`: `/latest/finance`
### Rule 8
- `title`: `Latest - Sustainability`
- `source`:
  - `accessbriefing.com/latest/sustainability`
- `target`: `/latest/sustainability`
### Rule 9
- `title`: `Insight - Interviews`
- `source`:
  - `accessbriefing.com/insight/interviews`
- `target`: `/insight/interviews`
### Rule 10
- `title`: `Insight - Longer reads`
- `source`:
  - `accessbriefing.com/insight/longer-reads`
- `target`: `/insight/longer-reads`
### Rule 11
- `title`: `Insight - Videos and podcasts`
- `source`:
  - `accessbriefing.com/insight/videos-and-podcasts`
- `target`: `/insight/videos-and-podcasts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [Latest News](https://www.accessbriefing.com/latest/news)，where the URL is `https://www.accessbriefing.com/latest/news`, extract the part `https://www.accessbriefing.com/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/accessbriefing/latest/news`](https://rsshub.app/accessbriefing/latest/news).\n:::\n\n#### Latest\n\n| Category                                                                               | ID                                                                                                 |\n| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |\n| [News](https://www.accessbriefing.com/latest/news)                                     | [latest/news](https://rsshub.app/accessbriefing/latest/news)                                       |\n| [Products & Technology](https://www.accessbriefing.com/latest/products-and-technology) | [latest/products-and-technology](https://rsshub.app/accessbriefing/latest/products-and-technology) |\n| [Rental News](https://www.accessbriefing.com/latest/rental-news)                       | [latest/rental-news](https://rsshub.app/accessbriefing/latest/rental-news)                         |\n| [People](https://www.accessbriefing.com/latest/people)                                 | [latest/people](https://rsshub.app/accessbriefing/latest/people)                                   |\n| [Regualtions & Safety](https://www.accessbriefing.com/latest/regualtions-safety)       | [latest/regualtions-safety](https://rsshub.app/accessbriefing/latest/regualtions-safety)           |\n| [Finance](https://www.accessbriefing.com/latest/finance)                               | [latest/finance](https://rsshub.app/accessbriefing/latest/finance)                                 |\n| [Sustainability](https://www.accessbriefing.com/latest/sustainability)                 | [latest/sustainability](https://rsshub.app/accessbriefing/latest/sustainability)                   |\n\n#### Insight\n\n| Category                                                                          | ID                                                                                           |\n| --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |\n| [Interviews](https://www.accessbriefing.com/insight/interviews)                   | [insight/interviews](https://rsshub.app/accessbriefing/insight/interviews)                   |\n| [Longer reads](https://www.accessbriefing.com/insight/longer-reads)               | [insight/longer-reads](https://rsshub.app/accessbriefing/insight/longer-reads)               |\n| [Videos and podcasts](https://www.accessbriefing.com/insight/videos-and-podcasts) | [insight/videos-and-podcasts](https://rsshub.app/accessbriefing/insight/videos-and-podcasts) |",
  "example": "/accessbriefing/latest/news",
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
  "name": "Articles",
  "parameters": {
    "category": "Category, Latest News by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "accessbriefing.com/:category*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "accessbriefing.com/latest/news"
      ],
      "target": "/latest/news",
      "title": "Latest - News"
    },
    {
      "source": [
        "accessbriefing.com/latest/products-and-technology"
      ],
      "target": "/latest/products-and-technology",
      "title": "Latest - Products & Technology"
    },
    {
      "source": [
        "accessbriefing.com/latest/rental-news"
      ],
      "target": "/latest/rental-news",
      "title": "Latest - Rental News"
    },
    {
      "source": [
        "accessbriefing.com/latest/people"
      ],
      "target": "/latest/people",
      "title": "Latest - People"
    },
    {
      "source": [
        "accessbriefing.com/latest/regualtions-safety"
      ],
      "target": "/latest/regualtions-safety",
      "title": "Latest - Regualtions & Safety"
    },
    {
      "source": [
        "accessbriefing.com/latest/finance"
      ],
      "target": "/latest/finance",
      "title": "Latest - Finance"
    },
    {
      "source": [
        "accessbriefing.com/latest/sustainability"
      ],
      "target": "/latest/sustainability",
      "title": "Latest - Sustainability"
    },
    {
      "source": [
        "accessbriefing.com/insight/interviews"
      ],
      "target": "/insight/interviews",
      "title": "Insight - Interviews"
    },
    {
      "source": [
        "accessbriefing.com/insight/longer-reads"
      ],
      "target": "/insight/longer-reads",
      "title": "Insight - Longer reads"
    },
    {
      "source": [
        "accessbriefing.com/insight/videos-and-podcasts"
      ],
      "target": "/insight/videos-and-podcasts",
      "title": "Insight - Videos and podcasts"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Dive into the pulse of the access industry on our News Page. From breaking news to in-depth analyses, stay connected with the latest trends in access solutions. - Powered by RSSHub",
      "errorAt": "2025-11-06T10:59:28.495Z",
      "errorMessage": "[GET] \"https://www.accessbriefing.com/Ajax/GetPagedArticles?navcontentid=9282&brandid=32&page=0&lastpage=0&pagesize=30\": 404 Not Found\n",
      "id": "61651923101048832",
      "image": "https://www.accessbriefing.com/images/anyx34/20240429-122716-KHLFINALlogoWHITE.png",
      "ownerUserId": null,
      "siteUrl": "https://www.accessbriefing.com/latest/news",
      "title": "Latest News - Access Briefing",
      "type": "feed",
      "url": "rsshub://accessbriefing/latest/news"
    }
  ],
  "url": "accessbriefing.com"
}
```
