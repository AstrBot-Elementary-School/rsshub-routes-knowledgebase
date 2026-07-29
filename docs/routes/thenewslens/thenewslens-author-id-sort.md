# The News Lens 關鍵評論 - 作者

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/author/:id/:sort{.+}?`
- Route Name: `作者`
- Example: `/thenewslens/author/BBC`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在对应作者页 URL 中找到
- `sort`: 排序方式，同上表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/author/:id/:sort?`
  - `thenewslens.com/`
- `target`: `/author/:id/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/author/BBC",
  "heat": 0,
  "location": "author.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 id，可在对应作者页 URL 中找到",
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/author/:id/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/author/:id/:sort?",
        "thenewslens.com/"
      ],
      "target": "/author/:id/:sort?"
    }
  ],
  "topFeeds": []
}
```
