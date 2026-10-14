# 厦门网 - 数字媒体

## Coverage
`index-only`

## Route
- Namespace: `xmnn`
- Namespace Name: `厦门网`
- Route Path: `/xmnn/epaper/:id?`
- Route Name: `数字媒体`
- Example: `/xmnn/epaper/xmrb`
- URL: `epaper.xmnn.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `epaper.ts`
- Source Module: `_None_`

## Description
| 厦门日报 | 厦门晚报 | 海西晨报 | 城市捷报 |
| -------- | -------- | -------- | -------- |
| xmrb     | xmwb     | hxcb     | csjb     |

## Parameters
- `id`: 报纸 id，见下表，默认为 `xmrb`，即厦门日报


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
  - `epaper.xmnn.cn/:id`
- `target`: `/epaper/:id`
### Rule 2
- `source`:
  - `epaper.xmrb.com/xmrb/*path`
  - `epaper.xmrb.com/xmrb/`
- `target`: `/epaper/xmrb`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 厦门日报 | 厦门晚报 | 海西晨报 | 城市捷报 |\n| -------- | -------- | -------- | -------- |\n| xmrb     | xmwb     | hxcb     | csjb     |",
  "example": "/xmnn/epaper/xmrb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "epaper.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "数字媒体",
  "parameters": {
    "id": "报纸 id，见下表，默认为 `xmrb`，即厦门日报"
  },
  "path": "/epaper/:id?",
  "radar": [
    {
      "source": [
        "epaper.xmnn.cn/:id"
      ],
      "target": "/epaper/:id"
    },
    {
      "source": [
        "epaper.xmrb.com/xmrb/*path",
        "epaper.xmrb.com/xmrb/"
      ],
      "target": "/epaper/xmrb"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "厦门日报电子版_厦门网 - Powered by RSSHub",
      "errorAt": "2025-06-26T06:39:30.905Z",
      "errorMessage": "[GET] \"https://epaper.xmnn.cn/xmrb/\": 404 Not Found\n",
      "id": "149675643701493760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://epaper.xmnn.cn/xmrb/20231109/index_5811.htm",
      "title": "厦门日报电子版_厦门网",
      "type": "feed",
      "url": "rsshub://xmnn/epaper"
    }
  ]
}
```
