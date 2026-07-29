# 厦门网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `xmnn`
- Namespace Name: `厦门网`
- Route Path: `/xmnn/news/:category{.+}?`
- Route Name: `新闻`
- Example: `/xmnn/news/xmxw`
- URL: `epaper.xmnn.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 分类名       | 分类 id |
| ------------ | ------- |
| 厦门新闻发布 | xmxwfb  |
| 厦门新闻     | xmxw    |
| 本网快报     | bwkb    |
| 厦门网眼     | xmwy    |
| 福建新闻     | fjxw    |
| 国内新闻     | gnxw    |
| 国际新闻     | gjxw    |
| 台海新闻     | thxw    |
| 社会新闻     | shxw    |

## Parameters
- `category`: 分类 id，见下表，默认为厦门新闻


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
  - `news.xmnn.cn/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 分类名       | 分类 id |\n| ------------ | ------- |\n| 厦门新闻发布 | xmxwfb  |\n| 厦门新闻     | xmxw    |\n| 本网快报     | bwkb    |\n| 厦门网眼     | xmwy    |\n| 福建新闻     | fjxw    |\n| 国内新闻     | gnxw    |\n| 国际新闻     | gjxw    |\n| 台海新闻     | thxw    |\n| 社会新闻     | shxw    |",
  "example": "/xmnn/news/xmxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类 id，见下表，默认为厦门新闻"
  },
  "path": "/news/:category{.+}?",
  "radar": [
    {
      "source": [
        "news.xmnn.cn/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "topFeeds": []
}
```
