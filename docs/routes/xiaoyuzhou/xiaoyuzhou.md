# 小宇宙 - 发现

## Coverage
`index-only`

## Route
- Namespace: `xiaoyuzhou`
- Namespace Name: `小宇宙`
- Route Path: `/xiaoyuzhou/`
- Route Name: `发现`
- Example: `/xiaoyuzhou`
- URL: `xiaoyuzhoufm.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `prnake, Maecenas`
- Source Location: `pickup.ts`
- Source Module: `_None_`

## Description
::: warning
需要配置小宇宙账户的 `XIAOYUZHOU_TOKEN`（refresh token）。可选配置 `XIAOYUZHOU_ID`（设备 ID），具体见部署文档。
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "小宇宙账户的 refresh token，用于获取编辑精选。", "name": "XIAOYUZHOU_TOKEN"}, {"description": "小宇宙账户的设备 ID。", "name": "XIAOYUZHOU_ID", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `xiaoyuzhoufm.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: warning\n需要配置小宇宙账户的 `XIAOYUZHOU_TOKEN`（refresh token）。可选配置 `XIAOYUZHOU_ID`（设备 ID），具体见部署文档。\n:::",
  "example": "/xiaoyuzhou",
  "features": {
    "requireConfig": [
      {
        "description": "小宇宙账户的 refresh token，用于获取编辑精选。",
        "name": "XIAOYUZHOU_TOKEN"
      },
      {
        "description": "小宇宙账户的设备 ID。",
        "name": "XIAOYUZHOU_ID",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "pickup.ts",
  "maintainers": [
    "prnake",
    "Maecenas"
  ],
  "name": "发现",
  "path": "/",
  "radar": [
    {
      "source": [
        "xiaoyuzhoufm.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "xiaoyuzhoufm.com/"
}
```
