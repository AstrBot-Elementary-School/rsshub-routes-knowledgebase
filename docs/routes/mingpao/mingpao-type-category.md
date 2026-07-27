# 明報 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `mingpao`
- Namespace Name: `明報`
- Route Path: `/mingpao/:type?/:category?`
- Route Name: `新聞`
- Example: `/mingpao/ins/all`
- URL: `mingpao.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| category | 即時新聞頻道 |
| -------- | ------------ |
| all      | 總目錄       |
| s00001   | 港聞         |
| s00002   | 經濟         |
| s00003   | 地產         |
| s00004   | 兩岸         |
| s00005   | 國際         |
| s00006   | 體育         |
| s00007   | 娛樂         |
| s00022   | 文摘         |
| s00024   | 熱點         |

| category | 每日明報頻道 |
| -------- | ------------ |
| s00001   | 要聞         |
| s00002   | 港聞         |
| s00003   | 社評         |
| s00004   | 經濟         |
| s00005   | 副刊         |
| s00011   | 教育         |
| s00012   | 觀點         |
| s00013   | 中國         |
| s00014   | 國際         |
| s00015   | 體育         |
| s00016   | 娛樂         |
| s00017   | English      |
| s00018   | 作家專欄     |

## Parameters
- `type`: {"default": "ins", "description": "新聞類型", "options": [{"label": "即時新聞", "value": "ins"}, {"label": "每日明報", "value": "pns"}]}
- `category`: 頻道，見下表


## Features
_None_

## Radar
### Rule 1
- `title`: `即時新聞`
- `source`:
  - `news.mingpao.com/ins/:categoryName/section/:date/:category`
- `target`: `/mingpao/ins/:category`
### Rule 2
- `title`: `每日明報`
- `source`:
  - `news.mingpao.com/pns/:categoryName/section/:date/:category`
- `target`: `/mingpao/pns/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| category | 即時新聞頻道 |\n| -------- | ------------ |\n| all      | 總目錄       |\n| s00001   | 港聞         |\n| s00002   | 經濟         |\n| s00003   | 地產         |\n| s00004   | 兩岸         |\n| s00005   | 國際         |\n| s00006   | 體育         |\n| s00007   | 娛樂         |\n| s00022   | 文摘         |\n| s00024   | 熱點         |\n\n| category | 每日明報頻道 |\n| -------- | ------------ |\n| s00001   | 要聞         |\n| s00002   | 港聞         |\n| s00003   | 社評         |\n| s00004   | 經濟         |\n| s00005   | 副刊         |\n| s00011   | 教育         |\n| s00012   | 觀點         |\n| s00013   | 中國         |\n| s00014   | 國際         |\n| s00015   | 體育         |\n| s00016   | 娛樂         |\n| s00017   | English      |\n| s00018   | 作家專欄     |",
  "example": "/mingpao/ins/all",
  "heat": 27,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞",
  "parameters": {
    "category": "頻道，見下表",
    "type": {
      "default": "ins",
      "description": "新聞類型",
      "options": [
        {
          "label": "即時新聞",
          "value": "ins"
        },
        {
          "label": "每日明報",
          "value": "pns"
        }
      ]
    }
  },
  "path": "/:type?/:category?",
  "radar": [
    {
      "source": [
        "news.mingpao.com/ins/:categoryName/section/:date/:category"
      ],
      "target": "/mingpao/ins/:category",
      "title": "即時新聞"
    },
    {
      "source": [
        "news.mingpao.com/pns/:categoryName/section/:date/:category"
      ],
      "target": "/mingpao/pns/:category",
      "title": "每日明報"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "明報新聞網-即時新聞 RSS - Powered by RSSHub",
      "errorAt": "2025-11-13T23:43:50.376Z",
      "errorMessage": "[GET] \"https://news.mingpao.com/ins/%e6%b8%af%e8%81%9e/article/20260726/s00001/1785027404602/%e7%b4%85%e9%9c%9e-%e6%b8%af%e9%90%b5-%e9%83%a8%e5%88%86%e9%9c%b2%e5%a4%a9%e6%ae%b5%e5%88%97%e8%bb%8a%e6%9c%8d%e5%8b%99%e9%9c%80%e8%bc%83%e9%95%b7%e6%99%82%e9%96%93%e6%81%a2%e5%be%a9\": 403 Forbidden\nStatus code 403\n",
      "id": "67446046265380864",
      "image": "https://news.mingpao.com/image/mingpaonews_logo2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.mingpao.com/",
      "title": "明報新聞網-即時新聞 RSS 總目錄",
      "type": "feed",
      "url": "rsshub://mingpao/ins/all"
    },
    {
      "description": "明報新聞網-每日明報 RSS - Powered by RSSHub",
      "errorAt": "2026-02-04T20:51:42.711Z",
      "errorMessage": "[GET] \"https://news.mingpao.com/pns/%e8%a6%81%e8%81%9e/article/20260724/s00001/1784829689539/%e4%b8%ad%e5%9c%8b%e7%b1%8d%e6%95%b8%e5%ad%b8%e5%ae%b6%e3%80%8c%e9%9b%99%e9%9f%bf%e3%80%8d%e9%a6%96%e7%8d%b2%e8%8f%b2%e7%88%be%e8%8c%b2%e7%8d%8e-%e7%8e%8b%e8%99%b9%e7%a0%b4%e8%a7%a3%e3%80%8c%e4%b8%89%e7%b6%ad%e6%8e%9b%e8%b0%b7%e7%8c%9c%e6%83%b3%e3%80%8d-%e9%84%a7%e7%85%9c%e6%94%bb%e5%85%8b%e3%80%8c%e5%b8%8c%e7%88%be%e4%bc%af%e7%89%b9%e7%ac%ac%e5%85%ad%e5%95%8f%e9%a1%8c%e3%80%8d\": 403 Forbidden\n",
      "id": "79131389613658112",
      "image": "https://news.mingpao.com/image/mingpaonews_logo2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.mingpao.com/",
      "title": "明報新聞網-每日明報 RSS 要聞",
      "type": "feed",
      "url": "rsshub://mingpao/pns"
    }
  ]
}
```
