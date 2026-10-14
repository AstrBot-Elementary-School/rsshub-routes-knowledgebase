# 对外经济贸易大学 - 人力资源处

## Coverage
`index-only`

## Route
- Namespace: `uibe`
- Namespace Name: `对外经济贸易大学`
- Route Path: `/uibe/hr/:category?/:type?`
- Route Name: `人力资源处`
- Example: `/uibe/hr`
- URL: `hr.uibe.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `hr.ts`
- Source Module: `_None_`

## Description
::: tip
如 [通知公告](http://hr.uibe.edu.cn/tzgg) 的 URL 为 `http://hr.uibe.edu.cn/tzgg`，其路由为 [`/uibe/hr/tzgg`](https://rsshub.app/uibe/hr/tzgg)

如 [教师招聘](http://hr.uibe.edu.cn/jszp) 中的 [招聘信息](http://hr.uibe.edu.cn/jszp/zpxx) 的 URL 为 `http://hr.uibe.edu.cn/jszp/zpxx`，其路由为 [`/uibe/hr/jszp/zpxx`](https://rsshub.app/uibe/hr/jszp/zpxx)
:::

## Parameters
- `category`: 分类，可在对应页 URL 中找到，默认为通知公告
- `type`: 类型，可在对应页 URL 中找到，默认为空


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hr.uibe.edu.cn/:category/:type`
  - `hr.uibe.edu.cn/:category`
  - `hr.uibe.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n如 [通知公告](http://hr.uibe.edu.cn/tzgg) 的 URL 为 `http://hr.uibe.edu.cn/tzgg`，其路由为 [`/uibe/hr/tzgg`](https://rsshub.app/uibe/hr/tzgg)\n\n如 [教师招聘](http://hr.uibe.edu.cn/jszp) 中的 [招聘信息](http://hr.uibe.edu.cn/jszp/zpxx) 的 URL 为 `http://hr.uibe.edu.cn/jszp/zpxx`，其路由为 [`/uibe/hr/jszp/zpxx`](https://rsshub.app/uibe/hr/jszp/zpxx)\n:::",
  "example": "/uibe/hr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hr.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "人力资源处",
  "parameters": {
    "category": "分类，可在对应页 URL 中找到，默认为通知公告",
    "type": "类型，可在对应页 URL 中找到，默认为空"
  },
  "path": "/hr/:category?/:type?",
  "radar": [
    {
      "source": [
        "hr.uibe.edu.cn/:category/:type",
        "hr.uibe.edu.cn/:category",
        "hr.uibe.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
