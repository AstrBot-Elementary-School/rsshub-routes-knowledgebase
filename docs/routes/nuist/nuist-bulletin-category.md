# 南京信息工程大学 - 南信大信息公告栏

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/bulletin/:category?`
- Route Name: `南信大信息公告栏`
- Example: `/nuist/bulletin/wjgg`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian, QianYu-u`
- Source Location: `bulletin.ts`
- Source Module: `_None_`

## Description
| 参数    | 含义                         |
| :------ | :--------------------------- |
| default | 全部                         |
| wjgg    | 文件公告                     |
| kyxx    | 科研信息                     |
| zbxx    | 招标信息                     |
| jxks    | 教学考试                     |
| dzsw    | 党政事务                     |
| ...     | (支持官网对应栏目的拼音简写) |

::: warning
全文内容需使用 校园网或[VPN](http://vpn.nuist.edu.cn) 获取
:::

## Parameters
- `category`: 分类名，默认为 `default` (全部)，支持 wjgg, kyxx 等拼音缩写


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bulletin.nuist.edu.cn/:filename`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 参数    | 含义                         |\n| :------ | :--------------------------- |\n| default | 全部                         |\n| wjgg    | 文件公告                     |\n| kyxx    | 科研信息                     |\n| zbxx    | 招标信息                     |\n| jxks    | 教学考试                     |\n| dzsw    | 党政事务                     |\n| ...     | (支持官网对应栏目的拼音简写) |\n\n::: warning\n全文内容需使用 校园网或[VPN](http://vpn.nuist.edu.cn) 获取\n:::",
  "example": "/nuist/bulletin/wjgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "bulletin.ts",
  "maintainers": [
    "gylidian",
    "QianYu-u"
  ],
  "name": "南信大信息公告栏",
  "parameters": {
    "category": "分类名，默认为 `default` (全部)，支持 wjgg, kyxx 等拼音缩写"
  },
  "path": "/bulletin/:category?",
  "radar": [
    {
      "source": [
        "bulletin.nuist.edu.cn/:filename"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南信大信息公告栏 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72519156724598784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bulletin.nuist.edu.cn/index.htm",
      "title": "南信大信息公告栏 - 全部",
      "type": "feed",
      "url": "rsshub://nuist/bulletin/791"
    },
    {
      "description": "南信大信息公告栏 - Powered by RSSHub",
      "errorAt": "2025-05-09T09:24:48.000Z",
      "errorMessage": "[GET] \"https://bulletin.nuist.edu.cn/791/list.htm\": <no response> fetch failed\n",
      "id": "84855950375476224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bulletin.nuist.edu.cn/791/list.htm",
      "title": "南信大信息公告栏",
      "type": "feed",
      "url": "rsshub://nuist/bulletin/:category"
    }
  ]
}
```
