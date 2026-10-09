# 扣子 - 商店更新

## Coverage
`index-only`

## Route
- Namespace: `coze`
- Namespace Name: `扣子`
- Route Path: `/coze/store/:type?`
- Route Name: `商店更新`
- Example: `/coze/store/project`
- URL: `www.coze.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `store.ts`
- Source Module: `_None_`

## Description
订阅扣子中国站公开商店按上架时间排列的首屏内容。商品版本变化时会生成新的 GUID。模板包括智能体、工作流和项目模板。

## Parameters
- `type`: 内容类型：project（项目，默认）、agent（智能体）或 template（模板）。


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
  "description": "订阅扣子中国站公开商店按上架时间排列的首屏内容。商品版本变化时会生成新的 GUID。模板包括智能体、工作流和项目模板。",
  "example": "/coze/store/project",
  "heat": 0,
  "location": "store.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "商店更新",
  "parameters": {
    "type": "内容类型：project（项目，默认）、agent（智能体）或 template（模板）。"
  },
  "path": "/store/:type?",
  "topFeeds": []
}
```
