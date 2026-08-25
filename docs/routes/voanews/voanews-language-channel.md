# Voice of America (VOA) - Voice of America (VOA)

## Coverage
`index-only`

## Route
- Namespace: `voanews`
- Namespace Name: `Voice of America (VOA)`
- Route Path: `/voanews/:language/:channel?`
- Route Name: `Voice of America (VOA)`
- Example: `/voanews/cantonese/zprtie-ttp`
- URL: `www.voachinese.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
透過提取全文，以獲得更好的閱讀體驗

`语言`

| 粵語      | 中文    | 藏語    |
| --------- | ------- | ------- |
| cantonese | chinese | tibetan |

`频道`

可於各語言官網聚合新聞處 (如 <https://www.voacantonese.com/rssfeeds>) 獲取

例如 `https://www.voacantonese.com/api/zyrtyequty` 將對應 `/voanews/cantonese/zyrtyequty`

## Parameters
- `language`: 語言
- `channel`: 頻道，可於官網獲取


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "透過提取全文，以獲得更好的閱讀體驗\n\n`语言`\n\n| 粵語      | 中文    | 藏語    |\n| --------- | ------- | ------- |\n| cantonese | chinese | tibetan |\n\n`频道`\n\n可於各語言官網聚合新聞處 (如 <https://www.voacantonese.com/rssfeeds>) 獲取\n\n例如 `https://www.voacantonese.com/api/zyrtyequty` 將對應 `/voanews/cantonese/zyrtyequty`",
  "example": "/voanews/cantonese/zprtie-ttp",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "Voice of America (VOA)",
  "parameters": {
    "channel": "頻道，可於官網獲取",
    "language": "語言"
  },
  "path": "/:language/:channel?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
