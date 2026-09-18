# 西安交通大学 - 电气学院通知

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/ee/jzxx/:category?`
- Route Name: `电气学院通知`
- Example: `/xjtu/ee/jzxx/bks`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `riverflows2333`
- Source Location: `ee-jzxx.ts`
- Source Module: `_None_`

## Description
栏目类型

| 主页 | 本科生 | 研究生 | 科研学术 | 采购招标 | 招聘就业 | 行政办公 |
| ---- | ------ | ------ | -------- | -------- | -------- | -------- |
| -    | bks    | yjs    | kyxs     | cgzb     | zpjy     | xzbg     |

## Parameters
- `category`: 类别：`bks`，默认为首页，详情在描述中


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
  - `ee.xjtu.edu.cn/jzxx/:category?.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目类型\n\n| 主页 | 本科生 | 研究生 | 科研学术 | 采购招标 | 招聘就业 | 行政办公 |\n| ---- | ------ | ------ | -------- | -------- | -------- | -------- |\n| -    | bks    | yjs    | kyxs     | cgzb     | zpjy     | xzbg     |",
  "example": "/xjtu/ee/jzxx/bks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "ee-jzxx.ts",
  "maintainers": [
    "riverflows2333"
  ],
  "name": "电气学院通知",
  "parameters": {
    "category": "类别：`bks`，默认为首页，详情在描述中"
  },
  "path": "/ee/jzxx/:category?",
  "radar": [
    {
      "source": [
        "ee.xjtu.edu.cn/jzxx/:category?.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "西安交通大学电气学院通知 - 研究生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149109316436120576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ee.xjtu.edu.cn/jzxx/yjs.htm",
      "title": "西安交通大学电气学院通知 - 研究生",
      "type": "feed",
      "url": "rsshub://xjtu/ee/jzxx/yjs"
    }
  ]
}
```
