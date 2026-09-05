# 人民网 - 人民日报电子版

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/people/paper/:page?`
- Route Name: `人民日报电子版`
- Example: `/people/paper`
- URL: `paper.people.com.cn/rmrb/pc/layout/index.html`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `pseudoyu`
- Source Location: `paper.ts`
- Source Module: `_None_`

## Description
获取当日《人民日报》全部版面或指定版面的文章。

## Parameters
- `page`: 版面编号，如 `01`；使用 `all` 或留空获取全部版面


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `paper.people.com.cn/rmrb/pc/layout/index.html`
- `target`: `/paper`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "获取当日《人民日报》全部版面或指定版面的文章。",
  "example": "/people/paper",
  "heat": 4,
  "location": "paper.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "人民日报电子版",
  "parameters": {
    "page": "版面编号，如 `01`；使用 `all` 或留空获取全部版面"
  },
  "path": "/paper/:page?",
  "radar": [
    {
      "source": [
        "paper.people.com.cn/rmrb/pc/layout/index.html"
      ],
      "target": "/paper"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "人民日报电子版 - 2026年09月04日 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1231515877518475264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://paper.people.com.cn/rmrb/pc/layout/index.html",
      "title": "人民日报电子版 - 2026年09月04日",
      "type": "feed",
      "url": "rsshub://people/paper"
    }
  ],
  "url": "paper.people.com.cn/rmrb/pc/layout/index.html"
}
```
