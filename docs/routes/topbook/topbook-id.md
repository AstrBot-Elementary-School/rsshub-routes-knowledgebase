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
  "heat": 0,
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
  "topFeeds": []
}
```
