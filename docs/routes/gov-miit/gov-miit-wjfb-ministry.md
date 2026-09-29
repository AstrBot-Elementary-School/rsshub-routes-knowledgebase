# 中华人民共和国工业和信息化部 - 文件发布

## Coverage
`index-only`

## Route
- Namespace: `gov/miit`
- Namespace Name: `中华人民共和国工业和信息化部`
- Route Path: `/gov/miit/wjfb/:ministry`
- Route Name: `文件发布`
- Example: `/gov/miit/wjfb/ghs`
- URL: `www.miit.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `wjfb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ministry`: 部门缩写，可以在对应 URL 中获取


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
  - `miit.gov.cn/jgsj/:ministry/wjfb/index.html`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/miit/wjfb/ghs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "wjfb.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "文件发布",
  "parameters": {
    "ministry": "部门缩写，可以在对应 URL 中获取"
  },
  "path": "/wjfb/:ministry",
  "radar": [
    {
      "source": [
        "miit.gov.cn/jgsj/:ministry/wjfb/index.html"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "工业和信息化部 - 规划司 文件发布 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177905314710033408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miit.gov.cn/jgsj/ghs/wjfb/index.html",
      "title": "工业和信息化部 - 规划司 文件发布",
      "type": "feed",
      "url": "rsshub://gov/miit/wjfb/ghs"
    }
  ]
}
```
