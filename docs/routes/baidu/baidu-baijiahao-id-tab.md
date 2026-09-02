# 百度 - 百家号

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/baijiahao/:id/:tab?`
- Route Name: `百家号`
- Example: `/baidu/baijiahao/3617`
- URL: `baijiahao.baidu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `baijiahao.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Account id, the `app_id` in the URL of the author page
- `tab`: {"default": "main", "description": "Content type", "options": [{"label": "全部", "value": "main"}, {"label": "文章", "value": "article"}, {"label": "动态", "value": "dynamic"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/baidu/baijiahao/3617",
  "heat": 0,
  "location": "baijiahao.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "百家号",
  "parameters": {
    "id": "Account id, the `app_id` in the URL of the author page",
    "tab": {
      "default": "main",
      "description": "Content type",
      "options": [
        {
          "label": "全部",
          "value": "main"
        },
        {
          "label": "文章",
          "value": "article"
        },
        {
          "label": "动态",
          "value": "dynamic"
        }
      ]
    }
  },
  "path": "/baijiahao/:id/:tab?",
  "topFeeds": [],
  "url": "baijiahao.baidu.com"
}
```
