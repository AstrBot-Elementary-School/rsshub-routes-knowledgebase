# 知乎 - xhu- 专栏

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/zhuanlan/:id`
- Route Name: `xhu- 专栏`
- Example: `/zhihu/xhu/zhuanlan/githubdaily`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/zhuanlan.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在专栏主页 URL 中找到


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
  - `zhuanlan.zhihu.com/:id`
- `target`: `/zhuanlan/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/zhuanlan/githubdaily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 247,
  "location": "xhu/zhuanlan.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu- 专栏",
  "parameters": {
    "id": "专栏 id, 可在专栏主页 URL 中找到"
  },
  "path": "/xhu/zhuanlan/:id",
  "radar": [
    {
      "source": [
        "zhuanlan.zhihu.com/:id"
      ],
      "target": "/zhuanlan/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "分享数据化管理之道。 关键词：大数据、数据管理、数据挖掘、数据产品、行业研究 - Powered by RSSHub",
      "errorAt": "2025-02-19T11:20:28.984Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "74138953621567488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/column/dataware",
      "title": "知乎专栏-数据化管理",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/zhuanlan/dataware"
    },
    {
      "description": "煤焚从瘩流源德俏C++曼萍和黎，茫捂最蒸层笔凶迄节唬，火伊矗雁告扁齿蚌拇块城雨的内剑栈藕机蒜，螟戏闯确蚣俭悉嘲是浓夸衡。知矩然，撰要知省碰陡雌。 - Powered by RSSHub",
      "errorAt": "2024-12-20T08:26:05.766Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "72856697418931200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/column/insideue4",
      "title": "知乎专栏-InsideUE5",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/zhuanlan/insideue4"
    }
  ]
}
```
