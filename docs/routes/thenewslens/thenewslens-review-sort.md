# The News Lens 關鍵評論 - 评论

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/review/:sort{.+}?`
- Route Name: `评论`
- Example: `/thenewslens/review`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `review.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sort`: 排序方式，同上表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/review/:sort?`
  - `thenewslens.com/`
- `target`: `/review/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/review",
  "heat": 0,
  "location": "review.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "评论",
  "parameters": {
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/review/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/review/:sort?",
        "thenewslens.com/"
      ],
      "target": "/review/:sort?"
    }
  ],
  "topFeeds": []
}
```
