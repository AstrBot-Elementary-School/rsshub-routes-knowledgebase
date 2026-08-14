# 浙江大学 - 控制学院通知

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/zju/cse/:category?`
- Route Name: `控制学院通知`
- Example: `/zju/cse/bksjy`
- URL: `physics.zju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Rabbits-sys`
- Source Location: `cse/index.ts`
- Source Module: `_None_`

## Description
栏目类型

| 简讯专栏 | 本科生教育 | 研究生教育 | 科研学术 | 人事工作 | 学生思政 | 对外交流 | 就业指导 |
| -------- | ---------- | ---------- | -------- | -------- | -------- | -------- | -------- |
| -        | bksjy      | yjsjy      | kyxs     | rsgz     | xssz     | dwjl     | jyzd     |

## Parameters
- `category`: 类别：`bksjy`，默认为简讯专栏，详情在描述中


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
  "description": "栏目类型\n\n| 简讯专栏 | 本科生教育 | 研究生教育 | 科研学术 | 人事工作 | 学生思政 | 对外交流 | 就业指导 |\n| -------- | ---------- | ---------- | -------- | -------- | -------- | -------- | -------- |\n| -        | bksjy      | yjsjy      | kyxs     | rsgz     | xssz     | dwjl     | jyzd     |",
  "example": "/zju/cse/bksjy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "cse/index.ts",
  "maintainers": [
    "Rabbits-sys"
  ],
  "name": "控制学院通知",
  "parameters": {
    "category": "类别：`bksjy`，默认为简讯专栏，详情在描述中"
  },
  "path": "/cse/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "浙江大学控制学院通知 - 对外交流 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "194422763742295040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cse.zju.edu.cn//39353/list.htm",
      "title": "浙江大学控制学院通知 - 对外交流",
      "type": "feed",
      "url": "rsshub://zju/cse/dwjl"
    },
    {
      "description": "浙江大学控制学院通知 - 简讯专栏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "194422241770488832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cse.zju.edu.cn//39283/list.htm",
      "title": "浙江大学控制学院通知 - 简讯专栏",
      "type": "feed",
      "url": "rsshub://zju/cse"
    }
  ]
}
```
