# 4399 - 论坛

## Coverage
`index-only`

## Route
- Namespace: `4399`
- Namespace Name: `4399`
- Route Path: `/4399/forums/:mtag`
- Route Name: `论坛`
- Example: `/4399/forums/mtag-83932`
- URL: `www.4399.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `lwgpshit`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mtag`: 论坛网址最后的 mtag 字段


## Features
- `requireConfig`: [{"description": "对应登录后的 cookie 值，获取方式：1. 在 4399 首页登录. 2. 打开开发者工具，切换到 Network 面板. 3. 刷新 4. 查找`www.4399.com`的访问请求，点击请求，在右侧 Headers 中找到 Cookie.", "name": "GAME_4399"}]

## Radar
### Rule 1
- `source`:
  - `my.4399.com/forums/:mtag`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4399/forums/mtag-83932",
  "features": {
    "requireConfig": [
      {
        "description": "对应登录后的 cookie 值，获取方式：1. 在 4399 首页登录. 2. 打开开发者工具，切换到 Network 面板. 3. 刷新 4. 查找`www.4399.com`的访问请求，点击请求，在右侧 Headers 中找到 Cookie.",
        "name": "GAME_4399"
      }
    ]
  },
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "lwgpshit"
  ],
  "name": "论坛",
  "parameters": {
    "mtag": "论坛网址最后的 mtag 字段"
  },
  "path": "/forums/:mtag",
  "radar": [
    {
      "source": [
        "my.4399.com/forums/:mtag"
      ]
    }
  ],
  "topFeeds": []
}
```
