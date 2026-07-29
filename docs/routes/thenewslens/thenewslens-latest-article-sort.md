# The News Lens 關鍵評論 - 最新

## Coverage
`index-only`

## Route
- Namespace: `thenewslens`
- Namespace Name: `The News Lens 關鍵評論`
- Route Path: `/thenewslens/latest-article/:sort{.+}?`
- Route Name: `最新`
- Example: `/thenewslens/latest-article`
- URL: `thenewslens.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新文章 | 最多觀看 | 最多分享 | 本日      | 本週     | 本月      | 今年     | 去年         | 有史以來    |
| -------- | -------- | -------- | --------- | -------- | --------- | -------- | ------------ | ----------- |
|          | hot      | social   | hot/today | hot/week | hot/month | hot/year | hot/lastYear | hot/history |

## Parameters
- `sort`: 排序方式，见下表，可在对应排序页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thenewslens.com/latest-article/:sort?`
  - `thenewslens.com/`
- `target`: `/latest-article/:sort?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新文章 | 最多觀看 | 最多分享 | 本日      | 本週     | 本月      | 今年     | 去年         | 有史以來    |\n| -------- | -------- | -------- | --------- | -------- | --------- | -------- | ------------ | ----------- |\n|          | hot      | social   | hot/today | hot/week | hot/month | hot/year | hot/lastYear | hot/history |",
  "example": "/thenewslens/latest-article",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "最新",
  "parameters": {
    "sort": "排序方式，见下表，可在对应排序页 URL 中找到"
  },
  "path": "/latest-article/:sort{.+}?",
  "radar": [
    {
      "source": [
        "thenewslens.com/latest-article/:sort?",
        "thenewslens.com/"
      ],
      "target": "/latest-article/:sort?"
    }
  ],
  "topFeeds": []
}
```
