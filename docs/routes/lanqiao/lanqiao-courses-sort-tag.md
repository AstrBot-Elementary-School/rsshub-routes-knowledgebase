# 蓝桥云课 - 全站发布的课程

## Coverage
`index-only`

## Route
- Namespace: `lanqiao`
- Namespace Name: `蓝桥云课`
- Route Path: `/lanqiao/courses/:sort/:tag`
- Route Name: `全站发布的课程`
- Example: `/lanqiao/courses/latest/all`
- URL: `lanqiao.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `huhuhang`
- Source Location: `courses.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sort`: 排序规则 sort, 默认(`default`)、最新(`latest`)、最热(`hotest`)
- `tag`: 课程标签 `tag`，可在该页面找到：https://www.lanqiao.cn/courses/


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/lanqiao/courses/latest/all",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "courses.ts",
  "maintainers": [
    "huhuhang"
  ],
  "name": "全站发布的课程",
  "parameters": {
    "sort": "排序规则 sort, 默认(`default`)、最新(`latest`)、最热(`hotest`)",
    "tag": "课程标签 `tag`，可在该页面找到：https://www.lanqiao.cn/courses/"
  },
  "path": "/courses/:sort/:tag",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "蓝桥云课【all】标签下最新课程列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "89306487292702720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lanqiao.cn/courses/?sort=latest&tag=all",
      "title": "蓝桥云课最新课程列表【all】",
      "type": "feed",
      "url": "rsshub://lanqiao/courses/latest/all"
    },
    {
      "description": "蓝桥云课【all】标签下最热课程列表 - Powered by RSSHub",
      "errorAt": "2025-11-11T11:39:55.246Z",
      "errorMessage": "Failed to fetch\n",
      "id": "182313167167346688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lanqiao.cn/courses/?sort=hotest&tag=all",
      "title": "蓝桥云课最热课程列表【all】",
      "type": "feed",
      "url": "rsshub://lanqiao/courses/hotest/all"
    }
  ]
}
```
