# HelloGitHub - 文章

## Coverage
`index-only`

## Route
- Namespace: `hellogithub`
- Namespace Name: `HelloGitHub`
- Route Path: `/hellogithub/article/:sort?`
- Route Name: `文章`
- Example: `/hellogithub/article`
- URL: `hellogithub.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `moke8, nczitzk, CaoMeiYouRen`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 热门 | 最近 |
| ---- | ---- |
| hot  | last |

## Parameters
- `sort`: 排序方式，见下表，默认为 `last`，即最近


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
    "programming"
  ],
  "description": "| 热门 | 最近 |\n| ---- | ---- |\n| hot  | last |",
  "example": "/hellogithub/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 195,
  "location": "article.ts",
  "maintainers": [
    "moke8",
    "nczitzk",
    "CaoMeiYouRen"
  ],
  "name": "文章",
  "parameters": {
    "sort": "排序方式，见下表，默认为 `last`，即最近"
  },
  "path": "/article/:sort?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "HelloGithub - 最近文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86943157703859200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hellogithub.com/article/?sort_by=last",
      "title": "HelloGithub - 最近文章",
      "type": "feed",
      "url": "rsshub://hellogithub/article"
    },
    {
      "description": "HelloGithub - 最近文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86856661627058176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hellogithub.com/article/?sort_by=last",
      "title": "HelloGithub - 最近文章",
      "type": "feed",
      "url": "rsshub://hellogithub/article/last"
    }
  ]
}
```
