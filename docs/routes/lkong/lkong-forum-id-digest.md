# 龙空 - 分区

## Coverage
`index-only`

## Route
- Namespace: `lkong`
- Namespace Name: `龙空`
- Route Path: `/lkong/forum/:id?/:digest?`
- Route Name: `分区`
- Example: `/lkong/forum/60`
- URL: `lkong.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, ma6254`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分区 id, 可在分区的URL里找到
- `digest`: 默认获取全部主题，任意值则只获取精华主题


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lkong.com/forum/:id`
  - `lkong.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/lkong/forum/60",
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "nczitzk",
    "ma6254"
  ],
  "name": "分区",
  "parameters": {
    "digest": "默认获取全部主题，任意值则只获取精华主题",
    "id": "分区 id, 可在分区的URL里找到"
  },
  "path": "/forum/:id?/:digest?",
  "radar": [
    {
      "source": [
        "lkong.com/forum/:id",
        "lkong.com/"
      ]
    }
  ],
  "topFeeds": []
}
```
