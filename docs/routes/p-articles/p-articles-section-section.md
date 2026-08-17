# 虚词 - 版块

## Coverage
`index-only`

## Route
- Namespace: `p-articles`
- Namespace Name: `虚词`
- Route Path: `/p-articles/section/:section`
- Route Name: `版块`
- Example: `/p-articles/section/critics`
- URL: `p-articles.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `Insomnia1437`
- Source Location: `section.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: 版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `p-articles.com/:section/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/p-articles/section/critics",
  "heat": 38,
  "location": "section.ts",
  "maintainers": [
    "Insomnia1437"
  ],
  "name": "版块",
  "parameters": {
    "section": "版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接"
  },
  "path": "/section/:section",
  "radar": [
    {
      "source": [
        "p-articles.com/:section/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "虚词 p-articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53733146806773766",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://p-articles.com/works/",
      "title": "虚词 p-articles",
      "type": "feed",
      "url": "rsshub://p-articles/section/works"
    },
    {
      "description": "虚词 p-articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98011535417850904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://p-articles.com/critics/",
      "title": "虚词 p-articles",
      "type": "feed",
      "url": "rsshub://p-articles/section/critics"
    }
  ]
}
```
