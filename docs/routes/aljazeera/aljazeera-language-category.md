# Aljazeera - News

## Coverage
`index-only`

## Route
- Namespace: `aljazeera`
- Namespace Name: `Aljazeera`
- Route Path: `/aljazeera/:language?/:category{.+}?`
- Route Name: `News`
- Example: `/aljazeera/english/news`
- URL: `aljazeera.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
Language

| Arabic | Chinese | English |
| ------ | ------- | ------- |
| arabic | chinese | english |

::: tip
If you subscribe to [Al Jazeera English - Economy](https://www.aljazeera.com/economy), whose language is `english` and whose path is `economy`, you can get the route as [`/aljazeera/english/economy`](https://rsshub.app/aljazeera/english/economy)

If you subscribe to [Al Jazeera Chinese - Political](https://chinese.aljazeera.net/news/political) with language `chinese` and path `news/political`, you can get the route as [`/aljazeera/chinese/news/political`](https://rsshub.app/aljazeera/chinese/news/political)
:::

## Parameters
- `language`: Language, see below, arabic by default, as Arabic
- `category`: Category, can be found in URL, homepage by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.aljazeera.com/:category`
  - `www.aljazeera.com/`
- `target`: `/english/:category`
### Rule 2
- `source`:
  - `www.aljazeera.net/:category`
  - `www.aljazeera.net/`
- `target`: `/arabic/:category`
### Rule 3
- `source`:
  - `chinese.aljazeera.net/:category`
  - `chinese.aljazeera.net/`
- `target`: `/chinese/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Language\n\n| Arabic | Chinese | English |\n| ------ | ------- | ------- |\n| arabic | chinese | english |\n\n::: tip\nIf you subscribe to [Al Jazeera English - Economy](https://www.aljazeera.com/economy), whose language is `english` and whose path is `economy`, you can get the route as [`/aljazeera/english/economy`](https://rsshub.app/aljazeera/english/economy)\n\nIf you subscribe to [Al Jazeera Chinese - Political](https://chinese.aljazeera.net/news/political) with language `chinese` and path `news/political`, you can get the route as [`/aljazeera/chinese/news/political`](https://rsshub.app/aljazeera/chinese/news/political)\n:::",
  "example": "/aljazeera/english/news",
  "heat": 180,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, can be found in URL, homepage by default",
    "language": "Language, see below, arabic by default, as Arabic"
  },
  "path": "/:language?/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.aljazeera.com/:category",
        "www.aljazeera.com/"
      ],
      "target": "/english/:category"
    },
    {
      "source": [
        "www.aljazeera.net/:category",
        "www.aljazeera.net/"
      ],
      "target": "/arabic/:category"
    },
    {
      "source": [
        "chinese.aljazeera.net/:category",
        "chinese.aljazeera.net/"
      ],
      "target": "/chinese/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新闻 | 半岛电视台今日最新资讯 - Powered by RSSHub",
      "errorAt": "2025-12-30T17:17:58.172Z",
      "errorMessage": "Cannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n",
      "id": "41572238273905695",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chinese.aljazeera.net/news",
      "title": "新闻 | 半岛电视台今日最新资讯",
      "type": "feed",
      "url": "rsshub://aljazeera/chinese/news"
    },
    {
      "description": "俄罗斯-乌克兰战争 | 半岛电视台今日最新资讯 - Powered by RSSHub",
      "errorAt": "2025-12-30T21:45:14.570Z",
      "errorMessage": "Cannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n",
      "id": "88577770971737095",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chinese.aljazeera.net/news/war-in-ukraine/",
      "title": "俄罗斯-乌克兰战争 | 半岛电视台今日最新资讯",
      "type": "feed",
      "url": "rsshub://aljazeera/chinese/news/war-in-ukraine/"
    }
  ]
}
```
