# 哈尔滨理工大学 - 国有资产管理处

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/gzc/:category?`
- Route Name: `国有资产管理处`
- Example: `/hrbust/gzc`
- URL: `gzc.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `gzc.ts`
- Source Module: `_None_`

## Description
| 政策规章 | 资料下载 | 处务公开 | 招标信息 | 岗位职责 | 管理办法 | 物资处理 | 工作动态 | 热点新闻 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 1287     | 1288     | 1289     | 1291     | 1300     | 1301     | 1302     | 1304     | 1305     |

## Parameters
- `category`: 栏目标识，默认为 1305（热点新闻）


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
  - `gzc.hrbust.edu.cn/:category/list.htm`
- `target`: `/gzc/:category`
### Rule 2
- `source`:
  - `gzc.hrbust.edu.cn`
- `target`: `/gzc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 政策规章 | 资料下载 | 处务公开 | 招标信息 | 岗位职责 | 管理办法 | 物资处理 | 工作动态 | 热点新闻 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 1287     | 1288     | 1289     | 1291     | 1300     | 1301     | 1302     | 1304     | 1305     |",
  "example": "/hrbust/gzc",
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
  "location": "gzc.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "国有资产管理处",
  "parameters": {
    "category": "栏目标识，默认为 1305（热点新闻）"
  },
  "path": "/gzc/:category?",
  "radar": [
    {
      "source": [
        "gzc.hrbust.edu.cn/:category/list.htm"
      ],
      "target": "/gzc/:category"
    },
    {
      "source": [
        "gzc.hrbust.edu.cn"
      ],
      "target": "/gzc"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "gzc.hrbust.edu.cn",
  "view": 5
}
```
