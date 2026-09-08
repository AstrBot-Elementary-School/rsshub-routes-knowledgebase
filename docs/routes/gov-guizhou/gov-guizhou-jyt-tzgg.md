# 贵州省人民政府 - 教育厅 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `gov/guizhou`
- Namespace Name: `贵州省人民政府`
- Route Path: `/gov/guizhou/jyt/tzgg`
- Route Name: `教育厅 - 通知公告`
- Example: `/gov/guizhou/jyt/tzgg`
- URL: `jyt.guizhou.gov.cn/zwgk/tzgg/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `sheetung`
- Source Location: `jyt.ts`
- Source Module: `_None_`

## Description
贵州省教育厅官方网站通知公告 RSS 源

## Parameters
_None_


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
  - `jyt.guizhou.gov.cn/zwgk/tzgg/`
  - `jyt.guizhou.gov.cn/zwgk/tzgg/index.html`
- `target`: `/jyt/tzgg`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "贵州省教育厅官方网站通知公告 RSS 源",
  "example": "/gov/guizhou/jyt/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "jyt.ts",
  "maintainers": [
    "sheetung"
  ],
  "name": "教育厅 - 通知公告",
  "parameters": {},
  "path": "/jyt/tzgg",
  "radar": [
    {
      "source": [
        "jyt.guizhou.gov.cn/zwgk/tzgg/",
        "jyt.guizhou.gov.cn/zwgk/tzgg/index.html"
      ],
      "target": "/jyt/tzgg"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "贵州省教育厅门户网站通知公告 - Powered by RSSHub",
      "errorAt": "2026-09-07T01:46:55.639Z",
      "errorMessage": "[GET] \"https://jyt.guizhou.gov.cn/zwgk/tzgg/\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 117.187.129.203:443, 2409:8c6a:b011:410b:a411:b7f4:2af4:8699:443, timeout: 10000ms))\n",
      "id": "238150952866085888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jyt.guizhou.gov.cn/zwgk/tzgg/",
      "title": "贵州省教育厅 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/guizhou/jyt/tzgg"
    }
  ],
  "url": "jyt.guizhou.gov.cn/zwgk/tzgg/"
}
```
