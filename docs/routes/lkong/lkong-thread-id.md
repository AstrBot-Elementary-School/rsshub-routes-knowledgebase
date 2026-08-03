# 龙空 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `lkong`
- Namespace Name: `龙空`
- Route Path: `/lkong/thread/:id`
- Route Name: `帖子`
- Example: `/lkong/thread/3100275`
- URL: `lkong.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, ma6254`
- Source Location: `thread.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 id, 可在帖子的URL里找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lkong.com/thread/:id`
  - `lkong.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/lkong/thread/3100275",
  "heat": 0,
  "location": "thread.tsx",
  "maintainers": [
    "nczitzk",
    "ma6254"
  ],
  "name": "帖子",
  "parameters": {
    "id": "帖子 id, 可在帖子的URL里找到"
  },
  "path": "/thread/:id",
  "radar": [
    {
      "source": [
        "lkong.com/thread/:id",
        "lkong.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
