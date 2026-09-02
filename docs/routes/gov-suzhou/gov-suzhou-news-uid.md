# 苏州市人民政府 - 政府新闻

## Coverage
`index-only`

## Route
- Namespace: `gov/suzhou`
- Namespace Name: `苏州市人民政府`
- Route Path: `/gov/suzhou/news/:uid`
- Route Name: `政府新闻`
- Example: `/gov/suzhou/news/news`
- URL: `www.suzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `EsuRt, luyuhuang`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 新闻栏目名 |       :uid       |
| :--------: | :--------------: |
|  苏州要闻  |   news 或 szyw   |
|  区县快讯  | district 或 qxkx |
|  部门动态  |       bmdt       |
|  新闻视频  |       xwsp       |
|  政务公告  |       zwgg       |
|  便民公告  |       mszx       |
|  民生资讯  |       bmzx       |

| 热点专题栏目名 |  :uid  |
| :------------: | :----: |
|    热点专题    |  rdzt  |
|   市本级专题   |  sbjzt |
|  最新热点专题  | zxrdzt |
|    往期专题    |  wqzt  |
|    区县专题    |  qxzt  |

::: tip
**热点专题**栏目包含**市本级专题**和**区县专题**

**市本级专题**栏目包含**最新热点专题**和**往期专题**

如需订阅完整的热点专题，仅需订阅 **热点专题**`rdzt` 一项即可。
:::

## Parameters
- `uid`: 栏目名


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
  - `www.suzhou.gov.cn/szsrmzf/:uid/nav_list.shtml`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻栏目名 |       :uid       |\n| :--------: | :--------------: |\n|  苏州要闻  |   news 或 szyw   |\n|  区县快讯  | district 或 qxkx |\n|  部门动态  |       bmdt       |\n|  新闻视频  |       xwsp       |\n|  政务公告  |       zwgg       |\n|  便民公告  |       mszx       |\n|  民生资讯  |       bmzx       |\n\n| 热点专题栏目名 |  :uid  |\n| :------------: | :----: |\n|    热点专题    |  rdzt  |\n|   市本级专题   |  sbjzt |\n|  最新热点专题  | zxrdzt |\n|    往期专题    |  wqzt  |\n|    区县专题    |  qxzt  |\n\n::: tip\n**热点专题**栏目包含**市本级专题**和**区县专题**\n\n**市本级专题**栏目包含**最新热点专题**和**往期专题**\n\n如需订阅完整的热点专题，仅需订阅 **热点专题**`rdzt` 一项即可。\n:::",
  "example": "/gov/suzhou/news/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "news.ts",
  "maintainers": [
    "EsuRt",
    "luyuhuang"
  ],
  "name": "政府新闻",
  "parameters": {
    "uid": "栏目名"
  },
  "path": "/news/:uid",
  "radar": [
    {
      "source": [
        "www.suzhou.gov.cn/szsrmzf/:uid/nav_list.shtml"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "苏州市政府 - 苏州要闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "105467750186756096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.suzhou.gov.cn/szsrmzf/szyw/nav_list.shtml",
      "title": "苏州市政府 - 苏州要闻",
      "type": "feed",
      "url": "rsshub://gov/suzhou/news/news"
    },
    {
      "description": "苏州市政府 - 政务公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73328043907264512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.suzhou.gov.cn/szsrmzf/zwgg/nav_list.shtml",
      "title": "苏州市政府 - 政务公告",
      "type": "feed",
      "url": "rsshub://gov/suzhou/news/zwgg"
    }
  ]
}
```
