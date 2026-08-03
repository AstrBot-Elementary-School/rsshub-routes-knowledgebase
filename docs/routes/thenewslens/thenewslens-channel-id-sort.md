# The News Lens 關鍵評論 - 频道

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/channel/:id/:sort{.+}?`
- Route Name: `频道`
- Example: `/thenewslens/channel/hk`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `channel.ts`
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
  - `thenewslens.com/channel/:id/:sort?`
  - `thenewslens.com/`
- `target`: `/channel/:id/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/channel/hk",
  "heat": 0,
  "location": "channel.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "频道",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到",
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/channel/:id/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/channel/:id/:sort?",
        "thenewslens.com/"
      ],
      "target": "/channel/:id/:sort?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
