# 牛客网 - 牛客面试经验

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/nowcoder/interview/:jobId`
- Route Name: `牛客面试经验`
- Example: `/nowcoder/interview/11200`
- URL: `nowcoder.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `xia0ne`
- Source Location: `interview.ts`
- Source Module: `_None_`

## Description
牛客面试经验

## Parameters
- `jobId`: 岗位 ID，如 11200（全部）、11002（Java）


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
  - `www.nowcoder.com/interview/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "牛客面试经验",
  "example": "/nowcoder/interview/11200",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "interview.ts",
  "maintainers": [
    "xia0ne"
  ],
  "name": "牛客面试经验",
  "parameters": {
    "jobId": "岗位 ID，如 11200（全部）、11002（Java）"
  },
  "path": "/interview/:jobId",
  "radar": [
    {
      "source": [
        "www.nowcoder.com/interview/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "牛客网面试经验 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "241056303310466048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nowcoder.com/interview/",
      "title": "牛客网-面试经验",
      "type": "feed",
      "url": "rsshub://nowcoder/interview/11200"
    }
  ],
  "url": "nowcoder.com/"
}
```
