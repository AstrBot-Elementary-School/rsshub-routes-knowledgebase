# 中国科学院大学 - 招聘信息

## Coverage
`index-only`

## Route
- Namespace: `ucas`
- Namespace Name: `中国科学院大学`
- Route Path: `/ucas/job/:type?`
- Route Name: `招聘信息`
- Example: `/ucas/job`
- URL: `ai.ucas.ac.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 招聘类型 | 博士后 | 课题项目聘用 | 管理支撑人才 | 教学科研人才 |
| :------: | :----: | :----------: | :----------: | :----------: |
|   参数   |   bsh  |    ktxmpy    |    glzcrc    |    jxkyrc    |

## Parameters
- `type`: 招聘类型，默认为博士后


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
  - `zhaopin.ucas.ac.cn/gjob/login.do`
- `title`: `博士后`
- `target`: `/job/bsh`
### Rule 2
- `source`:
  - `zhaopin.ucas.ac.cn/gjob/login.do`
- `title`: `课题项目聘用`
- `target`: `/job/ktxmpy`
### Rule 3
- `source`:
  - `zhaopin.ucas.ac.cn/gjob/login.do`
- `title`: `管理支撑人才`
- `target`: `/job/glzcrc`
### Rule 4
- `source`:
  - `zhaopin.ucas.ac.cn/gjob/login.do`
- `title`: `教学科研人才`
- `target`: `/job/jxkyrc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 招聘类型 | 博士后 | 课题项目聘用 | 管理支撑人才 | 教学科研人才 |\n| :------: | :----: | :----------: | :----------: | :----------: |\n|   参数   |   bsh  |    ktxmpy    |    glzcrc    |    jxkyrc    |",
  "example": "/ucas/job",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "招聘信息",
  "parameters": {
    "type": "招聘类型，默认为博士后"
  },
  "path": "/job/:type?",
  "radar": [
    {
      "source": [
        "zhaopin.ucas.ac.cn/gjob/login.do"
      ],
      "target": "/job/bsh",
      "title": "博士后"
    },
    {
      "source": [
        "zhaopin.ucas.ac.cn/gjob/login.do"
      ],
      "target": "/job/ktxmpy",
      "title": "课题项目聘用"
    },
    {
      "source": [
        "zhaopin.ucas.ac.cn/gjob/login.do"
      ],
      "target": "/job/glzcrc",
      "title": "管理支撑人才"
    },
    {
      "source": [
        "zhaopin.ucas.ac.cn/gjob/login.do"
      ],
      "target": "/job/jxkyrc",
      "title": "教学科研人才"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
