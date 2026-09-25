# Komica - 討論板

## Coverage
`index-only`

## Route
- Namespace: `komica`
- Namespace Name: `Komica`
- Route Path: `/komica/:host/:board/:category?`
- Route Name: `討論板`
- Example: `/komica/gita/00b/動畫`
- URL: `komica1.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
例如綜合避難所 <https://gita.komica1.org/00b/> 對應 `/komica/gita/00b`，其「動畫」列表對應 `/komica/gita/00b/動畫`。

## Parameters
- `host`: 子網域，即討論板網址中 `*.komica1.org` 的第一段，如 `gita`
- `board`: 討論板路徑，如 `00b`
- `category`: 類別（列表模式），如 `動畫`、`漫畫`、`掛圖`、`新番捏他`、`新番實況`、`模型`、`軍武`；留空為整個版面


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `komica1.org/:board/`
- `target`: `/:host/:board`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "例如綜合避難所 <https://gita.komica1.org/00b/> 對應 `/komica/gita/00b`，其「動畫」列表對應 `/komica/gita/00b/動畫`。",
  "example": "/komica/gita/00b/動畫",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "討論板",
  "parameters": {
    "board": "討論板路徑，如 `00b`",
    "category": "類別（列表模式），如 `動畫`、`漫畫`、`掛圖`、`新番捏他`、`新番實況`、`模型`、`軍武`；留空為整個版面",
    "host": "子網域，即討論板網址中 `*.komica1.org` 的第一段，如 `gita`"
  },
  "path": "/:host/:board/:category?",
  "radar": [
    {
      "source": [
        "komica1.org/:board/"
      ],
      "target": "/:host/:board"
    }
  ],
  "topFeeds": [],
  "url": "komica1.org"
}
```
