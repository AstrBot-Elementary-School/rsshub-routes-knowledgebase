# Topbook - 文章

## Coverage
`index-only`

## Route
- Namespace: `topbook`
- Namespace Name: `Topbook`
- Route Path: `/topbook/:id?`
- Route Name: `文章`
- Example: `/topbook`
- URL: `topbook.cc`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `content.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分类 id，可在对应分类页 URL 中找到，默认为最新文章


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `topbook.cc/content`
  - `topbook.cc/`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/topbook",
  "heat": 1,
  "location": "content.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "id": "分类 id，可在对应分类页 URL 中找到，默认为最新文章"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "topbook.cc/content",
        "topbook.cc/"
      ],
      "target": "/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-07T13:19:57.538Z",
      "errorMessage": "[GET] \"https://topbook.cc/webapi/content/article/today/page?start=0&limit=24\": 404 Not Found\n",
      "id": "142843186232416258",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://topbook/today"
    }
  ]
}
```
