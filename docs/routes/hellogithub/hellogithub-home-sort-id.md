# HelloGitHub - 开源项目

## Coverage
`index-only`

## Route
- Namespace: `hellogithub`
- Namespace Name: `HelloGitHub`
- Route Path: `/hellogithub/home/:sort?/:id?`
- Route Name: `开源项目`
- Example: `/hellogithub/home`
- URL: `hellogithub.com`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `moke8, nczitzk, CaoMeiYouRen`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 精选     | 全部 |
| -------- | ---- |
| featured | all  |

## Parameters
- `sort`: 排序方式，见下表，默认为 `featured`，即精选
- `id`: 标签 id，可在对应标签页 URL 中找到，默认为全部标签


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "description": "| 精选     | 全部 |\n| -------- | ---- |\n| featured | all  |",
  "example": "/hellogithub/home",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7467,
  "location": "index.ts",
  "maintainers": [
    "moke8",
    "nczitzk",
    "CaoMeiYouRen"
  ],
  "name": "开源项目",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到，默认为全部标签",
    "sort": "排序方式，见下表，默认为 `featured`，即精选"
  },
  "path": "/home/:sort?/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "HelloGithub - 精选开源项目 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66526115085137920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hellogithub.com/?sort_by=featured",
      "title": "HelloGithub - 精选开源项目",
      "type": "feed",
      "url": "rsshub://hellogithub/home"
    },
    {
      "description": "HelloGithub - 全部开源项目 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80951006332301312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hellogithub.com/?sort_by=all",
      "title": "HelloGithub - 全部开源项目",
      "type": "feed",
      "url": "rsshub://hellogithub/home/all"
    }
  ]
}
```
