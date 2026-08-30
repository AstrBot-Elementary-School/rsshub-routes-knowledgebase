# 国务院政策文件库 - 政策

## Coverage
`index-only`

## Route
- Namespace: `gov/zhengce`
- Namespace Name: `国务院政策文件库`
- Route Path: `/gov/zhengce/:category{.+}?`
- Route Name: `政策`
- Example: `/gov/zhengce`
- URL: `www.gov.cn/zhengce/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新政策 | 政策解读 | 图解政策    |
| -------- | -------- | ----------- |
| zuixin   | jiedu    | jiedu/tujie |

## Parameters
- `category`: 分类，见下表，默认为最新


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
  - `www.gov.cn/zhengce/*category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 最新政策 | 政策解读 | 图解政策    |\n| -------- | -------- | ----------- |\n| zuixin   | jiedu    | jiedu/tujie |",
  "example": "/gov/zhengce",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 125,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "政策",
  "parameters": {
    "category": "分类，见下表，默认为最新"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.gov.cn/zhengce/*category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中国政府网政策与法主栏目下解读国务院法规,政策,部门规章等有关文件的栏目页 - Powered by RSSHub",
      "errorAt": "2026-01-26T16:57:03.541Z",
      "errorMessage": "Failed to fetch\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "85521092373168149",
      "image": "https://www.gov.cn/images/gtrs_logo_rt.png",
      "ownerUserId": null,
      "siteUrl": "https://www.gov.cn/zhengce/jiedu/",
      "title": "中国政府网 - 政策解读",
      "type": "feed",
      "url": "rsshub://gov/zhengce/jiedu"
    },
    {
      "description": "中共中央和国务院最近发布的政策 - Powered by RSSHub",
      "errorAt": "2026-02-04T15:59:01.539Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "63695474853662720",
      "image": "https://www.gov.cn/images/gtrs_logo_rt.png",
      "ownerUserId": null,
      "siteUrl": "https://www.gov.cn/zhengce/zuixin/",
      "title": "中国政府网 - 最新政策",
      "type": "feed",
      "url": "rsshub://gov/zhengce"
    }
  ],
  "url": "www.gov.cn/zhengce/"
}
```
