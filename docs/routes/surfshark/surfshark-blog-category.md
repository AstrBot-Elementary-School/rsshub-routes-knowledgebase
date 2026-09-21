# Surfshark - Blog

## Coverage
`index-only`

## Route
- Namespace: `surfshark`
- Namespace Name: `Surfshark`
- Route Path: `/surfshark/blog/:category{.+}?`
- Route Name: `Blog`
- Example: `/surfshark/blog`
- URL: `surfshark.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Cybersecurity](https://surfshark.com/blog/cybersecurity), where the source URL is `https://surfshark.com/blog/cybersecurity`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/surfshark/blog/cybersecurity`](https://rsshub.app/surfshark/blog/cybersecurity).
:::

<details>
  <summary>More categories</summary>

| Category                                                              | ID                                                                           |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| [All](https://surfshark.com/blog)                                     | (empty)                                                                      |
| [Cybersecurity](https://surfshark.com/blog/cybersecurity)             | [cybersecurity](https://rsshub.app/surfshark/blog/cybersecurity)             |
| [All things VPN](https://surfshark.com/blog/all-things-vpn)           | [all-things-vpn](https://rsshub.app/surfshark/blog/all-things-vpn)           |
| [Internet censorship](https://surfshark.com/blog/internet-censorship) | [internet-censorship](https://rsshub.app/surfshark/blog/internet-censorship) |
| [Entertainment](https://surfshark.com/blog/entertainment)             | [entertainment](https://rsshub.app/surfshark/blog/entertainment)             |
| [Expert Insights](https://surfshark.com/blog/expert-insights)         | [expert-insights](https://rsshub.app/surfshark/blog/expert-insights)         |
| [Video](https://surfshark.com/blog/video)                             | [video](https://rsshub.app/surfshark/blog/video)                             |
| [News](https://surfshark.com/blog/news)                               | [news](https://rsshub.app/surfshark/blog/news)                               |

</details>

## Parameters
- `category`: {"description": "Category, All by default", "options": [{"label": "All", "value": ""}, {"label": "Cybersecurity", "value": "cybersecurity"}, {"label": "All things VPN", "value": "all-things-vpn"}, {"label": "Internet censorship", "value": "internet-censorship"}, {"label": "Entertainment", "value": "entertainment"}, {"label": "Expert Insights", "value": "expert-insights"}, {"label": "Video", "value": "video"}, {"label": "News", "value": "news"}]}


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
  - `surfshark.com/blog/:category`
- `target`: `/blog/:category`
### Rule 2
- `title`: `All`
- `source`:
  - `surfshark.com/blog`
- `target`: `/blog`
### Rule 3
- `title`: `Cybersecurity`
- `source`:
  - `surfshark.com/blog/cybersecurity`
- `target`: `/blog/cybersecurity`
### Rule 4
- `title`: `All things VPN`
- `source`:
  - `surfshark.com/blog/all-things-vpn`
- `target`: `/blog/all-things-vpn`
### Rule 5
- `title`: `Internet censorship`
- `source`:
  - `surfshark.com/blog/internet-censorship`
- `target`: `/blog/internet-censorship`
### Rule 6
- `title`: `Entertainment`
- `source`:
  - `surfshark.com/blog/entertainment`
- `target`: `/blog/entertainment`
### Rule 7
- `title`: `Expert Insights`
- `source`:
  - `surfshark.com/blog/expert-insights`
- `target`: `/blog/expert-insights`
### Rule 8
- `title`: `Video`
- `source`:
  - `surfshark.com/blog/video`
- `target`: `/blog/video`
### Rule 9
- `title`: `News`
- `source`:
  - `surfshark.com/blog/news`
- `target`: `/blog/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Cybersecurity](https://surfshark.com/blog/cybersecurity), where the source URL is `https://surfshark.com/blog/cybersecurity`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/surfshark/blog/cybersecurity`](https://rsshub.app/surfshark/blog/cybersecurity).\n:::\n\n<details>\n  <summary>More categories</summary>\n\n| Category                                                              | ID                                                                           |\n| --------------------------------------------------------------------- | ---------------------------------------------------------------------------- |\n| [All](https://surfshark.com/blog)                                     | (empty)                                                                      |\n| [Cybersecurity](https://surfshark.com/blog/cybersecurity)             | [cybersecurity](https://rsshub.app/surfshark/blog/cybersecurity)             |\n| [All things VPN](https://surfshark.com/blog/all-things-vpn)           | [all-things-vpn](https://rsshub.app/surfshark/blog/all-things-vpn)           |\n| [Internet censorship](https://surfshark.com/blog/internet-censorship) | [internet-censorship](https://rsshub.app/surfshark/blog/internet-censorship) |\n| [Entertainment](https://surfshark.com/blog/entertainment)             | [entertainment](https://rsshub.app/surfshark/blog/entertainment)             |\n| [Expert Insights](https://surfshark.com/blog/expert-insights)         | [expert-insights](https://rsshub.app/surfshark/blog/expert-insights)         |\n| [Video](https://surfshark.com/blog/video)                             | [video](https://rsshub.app/surfshark/blog/video)                             |\n| [News](https://surfshark.com/blog/news)                               | [news](https://rsshub.app/surfshark/blog/news)                               |\n\n</details>",
  "example": "/surfshark/blog",
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
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Blog",
  "parameters": {
    "category": {
      "description": "Category, All by default",
      "options": [
        {
          "label": "All",
          "value": ""
        },
        {
          "label": "Cybersecurity",
          "value": "cybersecurity"
        },
        {
          "label": "All things VPN",
          "value": "all-things-vpn"
        },
        {
          "label": "Internet censorship",
          "value": "internet-censorship"
        },
        {
          "label": "Entertainment",
          "value": "entertainment"
        },
        {
          "label": "Expert Insights",
          "value": "expert-insights"
        },
        {
          "label": "Video",
          "value": "video"
        },
        {
          "label": "News",
          "value": "news"
        }
      ]
    }
  },
  "path": "/blog/:category{.+}?",
  "radar": [
    {
      "source": [
        "surfshark.com/blog/:category"
      ],
      "target": "/blog/:category"
    },
    {
      "source": [
        "surfshark.com/blog"
      ],
      "target": "/blog",
      "title": "All"
    },
    {
      "source": [
        "surfshark.com/blog/cybersecurity"
      ],
      "target": "/blog/cybersecurity",
      "title": "Cybersecurity"
    },
    {
      "source": [
        "surfshark.com/blog/all-things-vpn"
      ],
      "target": "/blog/all-things-vpn",
      "title": "All things VPN"
    },
    {
      "source": [
        "surfshark.com/blog/internet-censorship"
      ],
      "target": "/blog/internet-censorship",
      "title": "Internet censorship"
    },
    {
      "source": [
        "surfshark.com/blog/entertainment"
      ],
      "target": "/blog/entertainment",
      "title": "Entertainment"
    },
    {
      "source": [
        "surfshark.com/blog/expert-insights"
      ],
      "target": "/blog/expert-insights",
      "title": "Expert Insights"
    },
    {
      "source": [
        "surfshark.com/blog/video"
      ],
      "target": "/blog/video",
      "title": "Video"
    },
    {
      "source": [
        "surfshark.com/blog/news"
      ],
      "target": "/blog/news",
      "title": "News"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "surfshark.com",
  "view": 0
}
```
