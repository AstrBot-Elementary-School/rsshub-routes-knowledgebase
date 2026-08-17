# 哈尔滨理工大学 - 计算机学院

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/cs/:category?`
- Route Name: `计算机学院`
- Example: `/hrbust/cs`
- URL: `cs.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `cs.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学院要闻 | 常用下载 | 博士后流动站 | 学生指导 | 科研动态 | 科技成果 | 党建理论 | 党建学习 | 党建活动 | 党建风采 | 团学组织 | 学生党建 | 学生活动 | 心理健康 | 青春榜样 | 就业工作 | 校友风采 | 校庆专栏 | 专业介绍 | 本科生培养方案 | 硕士生培养方案 | 能力作风建设 | 博士生培养方案 | 省级实验教学示范中心 | 喜迎二十大系列活动 | 学习贯彻省十三次党代会精神 |
| -------- | -------- | -------- | ------------ | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------------- | -------------- | ------------ | -------------- | -------------------- | ------------------ | -------------------------- |
| 3708     | 3709     | 3710     | 3725         | 3729     | 3732     | 3733     | 3740     | 3741     | 3742     | 3743     | 3744     | 3745     | 3746     | 3747     | 3748     | 3751     | 3752     | 3753     | 3755     | 3756           | 3759           | nlzfjs       | pyfa           | sjsyjxsfzx           | srxxgcddesdjs      | xxgcssscddhjs              |

## Parameters
- `category`: 栏目标识，默认为 3709（学院要闻）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `cs.hrbust.edu.cn/:category/list.htm`
- `target`: `/cs/:category`
### Rule 2
- `source`:
  - `cs.hrbust.edu.cn`
- `target`: `/cs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学院要闻 | 常用下载 | 博士后流动站 | 学生指导 | 科研动态 | 科技成果 | 党建理论 | 党建学习 | 党建活动 | 党建风采 | 团学组织 | 学生党建 | 学生活动 | 心理健康 | 青春榜样 | 就业工作 | 校友风采 | 校庆专栏 | 专业介绍 | 本科生培养方案 | 硕士生培养方案 | 能力作风建设 | 博士生培养方案 | 省级实验教学示范中心 | 喜迎二十大系列活动 | 学习贯彻省十三次党代会精神 |\n| -------- | -------- | -------- | ------------ | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------------- | -------------- | ------------ | -------------- | -------------------- | ------------------ | -------------------------- |\n| 3708     | 3709     | 3710     | 3725         | 3729     | 3732     | 3733     | 3740     | 3741     | 3742     | 3743     | 3744     | 3745     | 3746     | 3747     | 3748     | 3751     | 3752     | 3753     | 3755     | 3756           | 3759           | nlzfjs       | pyfa           | sjsyjxsfzx           | srxxgcddesdjs      | xxgcssscddhjs              |",
  "example": "/hrbust/cs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cs.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "计算机学院",
  "parameters": {
    "category": "栏目标识，默认为 3709（学院要闻）"
  },
  "path": "/cs/:category?",
  "radar": [
    {
      "source": [
        "cs.hrbust.edu.cn/:category/list.htm"
      ],
      "target": "/cs/:category"
    },
    {
      "source": [
        "cs.hrbust.edu.cn"
      ],
      "target": "/cs"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "cs.hrbust.edu.cn",
  "view": 5
}
```
