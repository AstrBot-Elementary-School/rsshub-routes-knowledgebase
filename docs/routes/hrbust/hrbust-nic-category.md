# 哈尔滨理工大学 - 网络信息中心

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/nic/:category?`
- Route Name: `网络信息中心`
- Example: `/hrbust/nic`
- URL: `nic.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `nic.ts`
- Source Module: `_None_`

## Description
| 服务指南 | 常见问题 | 新闻动态 | 通知公告 | 国家政策法规 | 学校规章制度 | 部门规章制度 | 宣传教育 | 安全法规 |
| -------- | -------- | -------- | -------- | ------------ | ------------ | ------------ | -------- | -------- |
| 3982     | 3983     | 3988     | 3989     | 3990         | 3991         | 3992         | 3993     | 3994     |

## Parameters
- `category`: 栏目标识，默认为 3988（新闻动态）


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
  - `nic.hrbust.edu.cn/:category/list.htm`
- `target`: `/nic/:category`
### Rule 2
- `source`:
  - `nic.hrbust.edu.cn/`
- `target`: `/nic/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 服务指南 | 常见问题 | 新闻动态 | 通知公告 | 国家政策法规 | 学校规章制度 | 部门规章制度 | 宣传教育 | 安全法规 |\n| -------- | -------- | -------- | -------- | ------------ | ------------ | ------------ | -------- | -------- |\n| 3982     | 3983     | 3988     | 3989     | 3990         | 3991         | 3992         | 3993     | 3994     |",
  "example": "/hrbust/nic",
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
  "location": "nic.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "网络信息中心",
  "parameters": {
    "category": "栏目标识，默认为 3988（新闻动态）"
  },
  "path": "/nic/:category?",
  "radar": [
    {
      "source": [
        "nic.hrbust.edu.cn/:category/list.htm"
      ],
      "target": "/nic/:category"
    },
    {
      "source": [
        "nic.hrbust.edu.cn/"
      ],
      "target": "/nic/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "nic.hrbust.edu.cn",
  "view": 5
}
```
