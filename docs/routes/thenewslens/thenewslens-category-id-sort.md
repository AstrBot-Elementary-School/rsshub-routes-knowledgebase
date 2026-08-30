# The News Lens 關鍵評論 - 分类

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/category/:id/:sort{.+}?`
- Route Name: `分类`
- Example: `/thenewslens/category/politics`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分类 id，可在对应分类页 URL 中找到
- `sort`: 排序方式，同上表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/category/:id/:sort?`
  - `thenewslens.com/`
- `target`: `/category/:id/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/category/politics",
  "heat": 1,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id，可在对应分类页 URL 中找到",
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/category/:id/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/category/:id/:sort?",
        "thenewslens.com/"
      ],
      "target": "/category/:id/:sort?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-11T10:10:21.927Z",
      "errorMessage": "[GET] \"https://www.thenewslens.com/category/music\": 403 Forbidden\n",
      "id": "177651896292778021",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://thenewslens/category/music"
    }
  ]
}
```
