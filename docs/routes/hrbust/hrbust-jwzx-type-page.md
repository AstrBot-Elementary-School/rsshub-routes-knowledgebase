# 哈尔滨理工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/jwzx/:type?/:page?`
- Route Name: `教务处`
- Example: `/hrbust/jwzx`
- URL: `jwzx.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LenaNouzen, cscnk52`
- Source Location: `jwzx.ts`
- Source Module: `_None_`

## Description
::: tip

- type 可以从 URL 中的 columnId 获取。
- 由于源站未提供精确时间，只能抓取日期粒度的时间。

:::

| 组织机构 | 工作职责 | 专业设置 | 教务信箱 | 名师风采 | 热点新闻 | 教务公告 | 教学新闻 | 教学管理 | 教务管理 | 学籍管理 | 实践教学 | 系统使用动画 | 教学管理 | 教务管理 | 学籍管理 | 实验教学 | 实践教学 | 教研论文教材认定 | 教学管理 | 学籍管理 | 实践教学 | 网络教学 | 多媒体教室管理 | 实验教学与实验室管理 | 教学成果 | 国创计划 | 学科竞赛 | 微专业 | 众创空间 | 示范基地 | 学生社团 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | -------- | -------- | -------- | -------- | -------- | ---------------- | -------- | -------- | -------- | -------- | -------------- | -------------------- | -------- | -------- | -------- | ------ | -------- | -------- | -------- |
| 339      | 340      | 342      | 346      | 351      | 353      | 354      | 355      | 442      | 443      | 444      | 445      | 2106         | 2332     | 2333     | 2334     | 2335     | 2336     | 2730             | 2855     | 2857     | 2859     | 3271     | 3508           | 3519                 | 3981     | 4057     | 4058     | 4059   | 4060     | 4061     | 4062     |

## Parameters
- `type`: 分类编号，默认为 354（教务公告），具体见下表
- `page`: 文章数，默认为 12


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
  - `jwzx.hrbust.edu.cn/homepage/index.do`
- `target`: `/jwzx`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n\n- type 可以从 URL 中的 columnId 获取。\n- 由于源站未提供精确时间，只能抓取日期粒度的时间。\n\n:::\n\n| 组织机构 | 工作职责 | 专业设置 | 教务信箱 | 名师风采 | 热点新闻 | 教务公告 | 教学新闻 | 教学管理 | 教务管理 | 学籍管理 | 实践教学 | 系统使用动画 | 教学管理 | 教务管理 | 学籍管理 | 实验教学 | 实践教学 | 教研论文教材认定 | 教学管理 | 学籍管理 | 实践教学 | 网络教学 | 多媒体教室管理 | 实验教学与实验室管理 | 教学成果 | 国创计划 | 学科竞赛 | 微专业 | 众创空间 | 示范基地 | 学生社团 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | -------- | -------- | -------- | -------- | -------- | ---------------- | -------- | -------- | -------- | -------- | -------------- | -------------------- | -------- | -------- | -------- | ------ | -------- | -------- | -------- |\n| 339      | 340      | 342      | 346      | 351      | 353      | 354      | 355      | 442      | 443      | 444      | 445      | 2106         | 2332     | 2333     | 2334     | 2335     | 2336     | 2730             | 2855     | 2857     | 2859     | 3271     | 3508           | 3519                 | 3981     | 4057     | 4058     | 4059   | 4060     | 4061     | 4062     |",
  "example": "/hrbust/jwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "jwzx.ts",
  "maintainers": [
    "LenaNouzen",
    "cscnk52"
  ],
  "name": "教务处",
  "parameters": {
    "page": "文章数，默认为 12",
    "type": "分类编号，默认为 354（教务公告），具体见下表"
  },
  "path": "/jwzx/:type?/:page?",
  "radar": [
    {
      "source": [
        "jwzx.hrbust.edu.cn/homepage/index.do"
      ],
      "target": "/jwzx"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "教务公告 - 哈尔滨理工大学教务处 - Powered by RSSHub",
      "errorAt": "2026-04-03T10:52:35.839Z",
      "errorMessage": "[GET] \"http://jwzx.hrbust.edu.cn/homepage/infoArticleList.do?columnId=354&pagingNumberPer=12\": <no response> fetch failed (Connect Timeout Error (attempted address: jwzx.hrbust.edu.cn:80, timeout: 10000ms))\n",
      "id": "71898308097212416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://jwzx.hrbust.edu.cn/homepage/infoArticleList.do?columnId=354&pagingNumberPer=12",
      "title": "教务公告 - 哈尔滨理工大学教务处",
      "type": "feed",
      "url": "rsshub://hrbust/jwzx"
    }
  ],
  "url": "jwzx.hrbust.edu.cn",
  "view": 5
}
```
