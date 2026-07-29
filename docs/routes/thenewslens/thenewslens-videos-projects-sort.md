# The News Lens 關鍵評論 - 影音

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/videos/Projects/:sort{.+}?`
- Route Name: `影音`
- Example: `/thenewslens/videos/Projects`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `videos.ts`
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
  - `thenewslens.com/videos/Projects/:sort?`
- `target`: `/videos/Projects/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thenewslens/videos/Projects",
  "heat": 0,
  "location": "videos.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "影音",
  "parameters": {
    "sort": "排序方式，同上表，可在对应排序页 URL 中找到"
  },
  "path": "/videos/Projects/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/videos/Projects/:sort?"
      ],
      "target": "/videos/Projects/:sort?"
    }
  ],
  "topFeeds": []
}
```
