# 东北大学 - 医学与生物信息工程学院

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/neu/bmie/:type`
- Route Name: `医学与生物信息工程学院`
- Example: `/neu/bmie/news`
- URL: `neunews.neu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `tennousuathena`
- Source Location: `bmie.ts`
- Source Module: `_None_`

## Description
| Id                      | 名称       |
| ----------------------- | ---------- |
| news                    | 学院新闻   |
| academic                | 学术科研   |
| talent\_development     | 人才培养   |
| international\_exchange | 国际交流   |
| announcement            | 通知公告   |
| undergraduate\_dev      | 本科生培养 |
| postgraduate\_dev       | 研究生培养 |
| undergraduate\_recruit  | 本科生招募 |
| postgraduate\_recruit   | 研究生招募 |
| CPC\_build              | 党的建设   |
| CPC\_work               | 党委工作   |
| union\_work             | 工会工作   |
| CYL\_work               | 共青团工作 |
| security\_management    | 安全管理   |
| alumni\_style           | 校友风采   |

## Parameters
- `type`: 分类 id 见下表


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
  "description": "| Id                      | 名称       |\n| ----------------------- | ---------- |\n| news                    | 学院新闻   |\n| academic                | 学术科研   |\n| talent\\_development     | 人才培养   |\n| international\\_exchange | 国际交流   |\n| announcement            | 通知公告   |\n| undergraduate\\_dev      | 本科生培养 |\n| postgraduate\\_dev       | 研究生培养 |\n| undergraduate\\_recruit  | 本科生招募 |\n| postgraduate\\_recruit   | 研究生招募 |\n| CPC\\_build              | 党的建设   |\n| CPC\\_work               | 党委工作   |\n| union\\_work             | 工会工作   |\n| CYL\\_work               | 共青团工作 |\n| security\\_management    | 安全管理   |\n| alumni\\_style           | 校友风采   |",
  "example": "/neu/bmie/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "bmie.ts",
  "maintainers": [
    "tennousuathena"
  ],
  "name": "医学与生物信息工程学院",
  "parameters": {
    "type": "分类 id 见下表"
  },
  "path": "/bmie/:type",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
