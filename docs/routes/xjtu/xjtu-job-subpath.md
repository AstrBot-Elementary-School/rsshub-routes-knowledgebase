# 西安交通大学 - 就业创业中心

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/job/:subpath?`
- Route Name: `就业创业中心`
- Example: `/xjtu/job/zxgg`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `DylanXie123`
- Source Location: `job.tsx`
- Source Module: `_None_`

## Description
栏目类型

| 中心公告 | 选调生 | 重点单位 | 国际组织 | 创新创业 | 就业实习 |
| -------- | ------ | -------- | -------- | -------- | -------- |
| zxgg     | xds    | zddw     | gjzz     | cxcy     | jysx     |

## Parameters
- `subpath`: 栏目类型，默认请求`zxgg`，详见下方表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目类型\n\n| 中心公告 | 选调生 | 重点单位 | 国际组织 | 创新创业 | 就业实习 |\n| -------- | ------ | -------- | -------- | -------- | -------- |\n| zxgg     | xds    | zddw     | gjzz     | cxcy     | jysx     |",
  "example": "/xjtu/job/zxgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "job.tsx",
  "maintainers": [
    "DylanXie123"
  ],
  "name": "就业创业中心",
  "parameters": {
    "subpath": "栏目类型，默认请求`zxgg`，详见下方表格"
  },
  "path": "/job/:subpath?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "西安交通大学学生就业创业信息网 - 中心公告 - Powered by RSSHub",
      "errorAt": "2026-01-30T20:26:36.967Z",
      "errorMessage": "[POST] \"https://job.xjtu.edu.cn/xsfw/sys/jyxtgktapp/modules/jywzManage/getTzgg.do\": 404 \n",
      "id": "80889819752657920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://job.xjtu.edu.cn/",
      "title": "西安交通大学学生就业创业信息网 - 中心公告",
      "type": "feed",
      "url": "rsshub://xjtu/job/zxgg"
    },
    {
      "description": "西安交通大学学生就业创业信息网 - 选调生 - Powered by RSSHub",
      "errorAt": "2026-01-30T15:42:32.693Z",
      "errorMessage": "[POST] \"https://job.xjtu.edu.cn/xsfw/sys/jyxtgktapp/modules/jywzManage/getTzgg.do\": 404 \n",
      "id": "76603138476628992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://job.xjtu.edu.cn/",
      "title": "西安交通大学学生就业创业信息网 - 选调生",
      "type": "feed",
      "url": "rsshub://xjtu/job/xds"
    }
  ]
}
```
