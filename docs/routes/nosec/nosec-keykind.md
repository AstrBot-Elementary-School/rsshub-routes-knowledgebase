# NOSEC 安全讯息平台 - Posts

## Coverage
`index-only`

## Route
- Namespace: `nosec`
- Namespace Name: `NOSEC 安全讯息平台`
- Route Path: `/nosec/:keykind?`
- Route Name: `Posts`
- Example: `/nosec/hole`
- URL: `nosec.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `hellodword`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类     | 标识       |
| :------- | :--------- |
| 威胁情报 | `threaten` |
| 安全动态 | `security` |
| 漏洞预警 | `hole`     |
| 数据泄露 | `leakage`  |
| 专题报告 | `speech`   |
| 技术分析 | `skill`    |
| 安全工具 | `tool`     |

## Parameters
- `keykind`: 对应文章分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `nosec.org/home/index/:keykind`
  - `nosec.org/home/index`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 分类     | 标识       |\n| :------- | :--------- |\n| 威胁情报 | `threaten` |\n| 安全动态 | `security` |\n| 漏洞预警 | `hole`     |\n| 数据泄露 | `leakage`  |\n| 专题报告 | `speech`   |\n| 技术分析 | `skill`    |\n| 安全工具 | `tool`     |",
  "example": "/nosec/hole",
  "heat": 438,
  "location": "index.ts",
  "maintainers": [
    "hellodword"
  ],
  "name": "Posts",
  "parameters": {
    "keykind": "对应文章分类"
  },
  "path": "/:keykind?",
  "radar": [
    {
      "source": [
        "nosec.org/home/index/:keykind",
        "nosec.org/home/index"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NOSEC 安全讯息平台 - 漏洞预警 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53723310721844256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nosec.org/home/index/hole.html",
      "title": "NOSEC 安全讯息平台 - 漏洞预警",
      "type": "feed",
      "url": "rsshub://nosec/hole"
    },
    {
      "description": "NOSEC 安全讯息平台 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71620232578810880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nosec.org/home/index",
      "title": "NOSEC 安全讯息平台",
      "type": "feed",
      "url": "rsshub://nosec"
    }
  ]
}
```
