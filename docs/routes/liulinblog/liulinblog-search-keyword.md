# 木木博客 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `liulinblog`
- Namespace Name: `木木博客`
- Route Path: `/liulinblog/search/:keyword`
- Route Name: `搜索`
- Example: `/liulinblog/search/单机游戏`
- URL: `liulinblog.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键字


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `liulinblog.com/search/:keyword`
  - `liulinblog.com/`
- `target`: `/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/liulinblog/search/单机游戏",
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键字"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "liulinblog.com/search/:keyword",
        "liulinblog.com/"
      ],
      "target": "/search/:keyword"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
