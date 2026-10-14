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
  - `bulletin.nuist.edu.cn/index.htm`
- `target`: `/bulletin`
### Rule 2
- `source`:
  - `bulletin.nuist.edu.cn/wjgg.htm`
- `target`: `/bulletin/wjgg`
### Rule 3
- `source`:
  - `bulletin.nuist.edu.cn/zbxx.htm`
- `target`: `/bulletin/zbxx`
### Rule 4
- `source`:
  - `bulletin.nuist.edu.cn/xsbg.htm`
- `target`: `/bulletin/xsbg`
### Rule 5
- `source`:
  - `bulletin.nuist.edu.cn/dzsw.htm`
- `target`: `/bulletin/dzsw`
### Rule 6
- `source`:
  - `bulletin.nuist.edu.cn/jxks.htm`
- `target`: `/bulletin/jxks`
### Rule 7
- `source`:
  - `bulletin.nuist.edu.cn/hytz.htm`
- `target`: `/bulletin/hytz`
### Rule 8
- `source`:
  - `bulletin.nuist.edu.cn/zzrs.htm`
- `target`: `/bulletin/zzrs`
### Rule 9
- `source`:
  - `bulletin.nuist.edu.cn/kyxx.htm`
- `target`: `/bulletin/kyxx`
### Rule 10
- `source`:
  - `bulletin.nuist.edu.cn/zsjy.htm`
- `target`: `/bulletin/zsjy`
### Rule 11
- `source`:
  - `bulletin.nuist.edu.cn/cxcy.htm`
- `target`: `/bulletin/cxcy`
### Rule 12
- `source`:
  - `bulletin.nuist.edu.cn/xyhd.htm`
- `target`: `/bulletin/xyhd`
### Rule 13
- `source`:
  - `bulletin.nuist.edu.cn/xydt.htm`
- `target`: `/bulletin/xydt`
### Rule 14
- `source`:
  - `bulletin.nuist.edu.cn/ztjz.htm`
- `target`: `/bulletin/ztjz`

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
        "bulletin.nuist.edu.cn/index.htm"
      ],
      "target": "/bulletin"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/wjgg.htm"
      ],
      "target": "/bulletin/wjgg"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/zbxx.htm"
      ],
      "target": "/bulletin/zbxx"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/xsbg.htm"
      ],
      "target": "/bulletin/xsbg"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/dzsw.htm"
      ],
      "target": "/bulletin/dzsw"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/jxks.htm"
      ],
      "target": "/bulletin/jxks"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/hytz.htm"
      ],
      "target": "/bulletin/hytz"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/zzrs.htm"
      ],
      "target": "/bulletin/zzrs"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/kyxx.htm"
      ],
      "target": "/bulletin/kyxx"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/zsjy.htm"
      ],
      "target": "/bulletin/zsjy"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/cxcy.htm"
      ],
      "target": "/bulletin/cxcy"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/xyhd.htm"
      ],
      "target": "/bulletin/xyhd"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/xydt.htm"
      ],
      "target": "/bulletin/xydt"
    },
    {
      "source": [
        "bulletin.nuist.edu.cn/ztjz.htm"
      ],
      "target": "/bulletin/ztjz"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
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
    },
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
    }
  ]
}
```
