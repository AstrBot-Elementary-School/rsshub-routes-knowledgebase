# 盛趣游戏在线 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `sdo`
- Namespace Name: `盛趣游戏在线`
- Route Path: `/sdo/ff14risingstones/posts/:pid?/:type?`
- Route Name: `帖子`
- Example: `/sdo/ff14risingstones/posts/all/hot`
- URL: `sdo.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `ff14risingstones/posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pid`: {"default": "all", "description": "分区id，默认显示所有分区，可通过 `,` 拼接多个分区 id 进行筛选", "options": [{"label": "全部", "value": "all"}, {"label": "冒险者行会", "value": "34"}, {"label": "生活杂谈", "value": "52"}, {"label": "同人创作", "value": "38"}, {"label": "剧情讨论", "value": "36"}, {"label": "建议和BUG反馈", "value": "51"}, {"label": "游戏记录", "value": "37"}, {"label": "举手提问", "value": "35"}, {"label": "版务专区", "value": "74"}, {"label": "官方讯息", "value": "75"}]}
- `type`: {"description": "帖文类型，默认不做筛选", "options": [{"label": "置顶", "value": "top"}, {"label": "精华", "value": "refine"}, {"label": "周热门", "value": "hot"}]}


## Features
- `requireConfig`: [{"description": "值为 Cookie 头中 ff14risingstones 值", "name": "SDO_FF14RISINGSTONES"}, {"description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值", "name": "SDO_UA"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sdo/ff14risingstones/posts/all/hot",
  "features": {
    "requireConfig": [
      {
        "description": "值为 Cookie 头中 ff14risingstones 值",
        "name": "SDO_FF14RISINGSTONES"
      },
      {
        "description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值",
        "name": "SDO_UA"
      }
    ]
  },
  "heat": 3,
  "location": "ff14risingstones/posts.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "帖子",
  "parameters": {
    "pid": {
      "default": "all",
      "description": "分区id，默认显示所有分区，可通过 `,` 拼接多个分区 id 进行筛选",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "冒险者行会",
          "value": "34"
        },
        {
          "label": "生活杂谈",
          "value": "52"
        },
        {
          "label": "同人创作",
          "value": "38"
        },
        {
          "label": "剧情讨论",
          "value": "36"
        },
        {
          "label": "建议和BUG反馈",
          "value": "51"
        },
        {
          "label": "游戏记录",
          "value": "37"
        },
        {
          "label": "举手提问",
          "value": "35"
        },
        {
          "label": "版务专区",
          "value": "74"
        },
        {
          "label": "官方讯息",
          "value": "75"
        }
      ]
    },
    "type": {
      "description": "帖文类型，默认不做筛选",
      "options": [
        {
          "label": "置顶",
          "value": "top"
        },
        {
          "label": "精华",
          "value": "refine"
        },
        {
          "label": "周热门",
          "value": "hot"
        }
      ]
    }
  },
  "path": "/ff14risingstones/posts/:pid?/:type?",
  "topFeeds": [
    {
      "description": "石之家 - 帖文 - 官方讯息 - Powered by RSSHub",
      "errorAt": "2026-06-09T08:16:25.111Z",
      "errorMessage": "ff14risingstones RSS is disabled due to the lack of relevant config\nff14risingstones RSS is disabled due to the lack of relevant config\n",
      "id": "188045775088455680",
      "image": "https://ff14risingstones.web.sdo.com/pc/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://ff14risingstones.web.sdo.com/pc/index.html#/post",
      "title": "石之家 - 帖文 - 官方讯息",
      "type": "feed",
      "url": "rsshub://sdo/ff14risingstones/posts/75"
    }
  ]
}
```
