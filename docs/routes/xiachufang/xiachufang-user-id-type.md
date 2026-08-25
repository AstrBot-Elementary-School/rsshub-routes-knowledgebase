# 下厨房 - 用户菜谱/作品

## Coverage
`index-only`

## Route
- Namespace: `xiachufang`
- Namespace Name: `下厨房`
- Route Path: `/xiachufang/user/:id/:type?`
- Route Name: `用户菜谱/作品`
- Example: `/xiachufang/user/103309404`
- URL: `xiachufang.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `xyqfer`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到
- `type`: {"default": "created", "description": "类型", "options": [{"label": "菜谱", "value": "created"}, {"label": "作品", "value": "cooked"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/xiachufang/user/103309404",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "用户菜谱/作品",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到",
    "type": {
      "default": "created",
      "description": "类型",
      "options": [
        {
          "label": "菜谱",
          "value": "created"
        },
        {
          "label": "作品",
          "value": "cooked"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
