# The News Lens 關鍵評論 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/news/:sort{.+}?`
- Route Name: `新闻`
- Example: `/thenewslens/news`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 最新文章 | 最多觀看 | 最多分享 |
| -------- | -------- | -------- |
|          | hot      | social   |

## Parameters
- `sort`: 排序方式，见下表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/news/:sort?`
  - `thenewslens.com/`
- `target`: `/news/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新文章 | 最多觀看 | 最多分享 |\n| -------- | -------- | -------- |\n|          | hot      | social   |",
  "example": "/thenewslens/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "sort": "排序方式，见下表，可在对应排序页 URL 中找到"
  },
  "path": "/news/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/news/:sort?",
        "thenewslens.com/"
      ],
      "target": "/news/:sort?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
