# 扣子 - 创作者上架内容

## Coverage
`index-only`

## Route
- Namespace: `coze`
- Namespace Name: `扣子`
- Route Path: `/coze/user/:id/:type?`
- Route Name: `创作者上架内容`
- Example: `/coze/user/4223666036440905/template`
- URL: `www.coze.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
订阅创作者公开上架内容的首屏更新，包括选定类型的智能体、项目或模板。商品版本变化时会生成新的 GUID。

## Parameters
- `id`: 创作者公开主页 /user/ 后的数字 ID。
- `type`: 内容类型：agent（智能体，默认）、project（项目）或 template（模板）。


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "订阅创作者公开上架内容的首屏更新，包括选定类型的智能体、项目或模板。商品版本变化时会生成新的 GUID。",
  "example": "/coze/user/4223666036440905/template",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "创作者上架内容",
  "parameters": {
    "id": "创作者公开主页 /user/ 后的数字 ID。",
    "type": "内容类型：agent（智能体，默认）、project（项目）或 template（模板）。"
  },
  "path": "/user/:id/:type?",
  "topFeeds": []
}
```
