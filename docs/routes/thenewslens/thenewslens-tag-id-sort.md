# The News Lens 關鍵評論 - 标签

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/tag/:id/:sort{.+}?`
- Route Name: `标签`
- Example: `/thenewslens/tag/中國`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 标签 id，可在对应标签页 URL 中找到
- `sort`: 排序方式，同上表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/tag/:id/:sort?`
  - `thenewslens.com/`
- `target`: `/tag/:id/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/tag/中國",
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到",
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/tag/:id/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/tag/:id/:sort?",
        "thenewslens.com/"
      ],
      "target": "/tag/:id/:sort?"
    }
  ],
  "topFeeds": []
}
```
