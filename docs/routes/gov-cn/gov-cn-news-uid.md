# 中国政府网 - 政府新闻

## Coverage
`index-only`

## Route
- Namespace: `gov/cn`
- Namespace Name: `中国政府网`
- Route Path: `/gov/cn/news/:uid`
- Route Name: `政府新闻`
- Example: `/gov/cn/news/bm`
- URL: `www.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `EsuRt, howfool`
- Source Location: `news/index.ts`
- Source Module: `_None_`

## Description
| 政务部门 | 滚动新闻 | 新闻要闻 | 国务院新闻 | 国务院工作会议 | 政策文件 |
| :------: | :------: | :------: | :--------: | :------------: | :------: |
|    bm    |    gd    |    yw    |     gwy    |     gwyzzjg    |  zhengce |

## Parameters
- `uid`: 分类名


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
    "government"
  ],
  "description": "| 政务部门 | 滚动新闻 | 新闻要闻 | 国务院新闻 | 国务院工作会议 | 政策文件 |\n| :------: | :------: | :------: | :--------: | :------------: | :------: |\n|    bm    |    gd    |    yw    |     gwy    |     gwyzzjg    |  zhengce |",
  "example": "/gov/cn/news/bm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 147,
  "location": "news/index.ts",
  "maintainers": [
    "EsuRt",
    "howfool"
  ],
  "name": "政府新闻",
  "parameters": {
    "uid": "分类名"
  },
  "path": "/news/:uid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中国政府网 - 国务院信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88599589260275712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gov.cn/pushinfo/v150203/",
      "title": "中国政府网 - 国务院信息",
      "type": "feed",
      "url": "rsshub://gov/cn/news/gwy"
    },
    {
      "description": "中国政府网 - 部门政务 - Powered by RSSHub",
      "errorAt": "2025-12-15T18:35:42.946Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "67174356112248832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gov.cn/lianbo/bumen/index.htm",
      "title": "中国政府网 - 部门政务",
      "type": "feed",
      "url": "rsshub://gov/cn/news/bm"
    }
  ]
}
```
