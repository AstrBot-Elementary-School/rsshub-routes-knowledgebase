# 豆瓣 - 豆瓣榜单与集合

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/list/:type?/:routeParams?`
- Route Name: `豆瓣榜单与集合`
- Example: `/douban/list/subject_real_time_hotest`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `5upernova-heng, honue`
- Source Location: `other/list.ts`
- Source Module: `_None_`

## Description
| 榜单 / 集合        | 路由                          |
| ------------------ | ----------------------------- |
| 实时热门书影音     | subject\_real\_time\_hotest   |
| 影院热映           | movie\_showing                |
| 实时热门电影       | movie\_real\_time\_hotest     |
| 实时热门电视       | tv\_real\_time\_hotest        |
| 一周口碑电影榜     | movie\_weekly\_best           |
| 华语口碑剧集榜     | tv\_chinese\_best\_weekly     |
| 全球口碑剧集榜     | tv\_global\_best\_weekly      |
| 国内口碑综艺榜     | show\_chinese\_best\_weekly   |
| 国外口碑综艺榜     | show\_global\_best\_weekly    |
| 热播新剧国产剧     | tv\_domestic                  |
| 热播新剧欧美剧     | tv\_american                  |
| 热播新剧日剧       | tv\_japanese                  |
| 热播新剧韩剧       | tv\_korean                    |
| 热播新剧动画       | tv\_animation                 |
| 虚构类小说热门榜   | book\_fiction\_hot\_weekly    |
| 非虚构类小说热门榜 | book\_nonfiction\_hot\_weekly |
| 热门单曲榜         | music\_single                 |
| 华语新碟榜         | music\_chinese                |
| ...                | ...                           |

| 额外参数 | 含义                   | 接受的值 | 默认值 |
| -------- | ---------------------- | -------- | ------ |
| playable | 仅看有可播放片源的影片 | 0/1      | 0      |
| score    | 筛选评分               | 0.0-10.0 | 0      |

用例：`/douban/list/tv_korean/playable=1&score=8`

> 上面的榜单 / 集合并没有列举完整。
>
> 如何找到榜单对应的路由参数：
> 在豆瓣手机 APP 中，对应地榜单页面右上角，点击分享链接。链接路径 `subject_collection` 后的路径就是路由参数 `type`。
> 如：小说热门榜的分享链接为：`https://m.douban.com/subject_collection/ECDIHUN4A`，其对应本 RSS 路由的 `type` 为 `ECDIHUN4A`，对应的订阅链接路由：[`/douban/list/ECDIHUN4A`](https://rsshub.app/douban/list/ECDIHUN4A)

## Parameters
- `type`: 榜单类型，见下表。默认为实时热门书影音
- `routeParams`: 额外参数；请参阅以下说明和表格


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
  - `www.douban.com/subject_collection/:type`
- `target`: `/list/:type`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "| 榜单 / 集合        | 路由                          |\n| ------------------ | ----------------------------- |\n| 实时热门书影音     | subject\\_real\\_time\\_hotest   |\n| 影院热映           | movie\\_showing                |\n| 实时热门电影       | movie\\_real\\_time\\_hotest     |\n| 实时热门电视       | tv\\_real\\_time\\_hotest        |\n| 一周口碑电影榜     | movie\\_weekly\\_best           |\n| 华语口碑剧集榜     | tv\\_chinese\\_best\\_weekly     |\n| 全球口碑剧集榜     | tv\\_global\\_best\\_weekly      |\n| 国内口碑综艺榜     | show\\_chinese\\_best\\_weekly   |\n| 国外口碑综艺榜     | show\\_global\\_best\\_weekly    |\n| 热播新剧国产剧     | tv\\_domestic                  |\n| 热播新剧欧美剧     | tv\\_american                  |\n| 热播新剧日剧       | tv\\_japanese                  |\n| 热播新剧韩剧       | tv\\_korean                    |\n| 热播新剧动画       | tv\\_animation                 |\n| 虚构类小说热门榜   | book\\_fiction\\_hot\\_weekly    |\n| 非虚构类小说热门榜 | book\\_nonfiction\\_hot\\_weekly |\n| 热门单曲榜         | music\\_single                 |\n| 华语新碟榜         | music\\_chinese                |\n| ...                | ...                           |\n\n| 额外参数 | 含义                   | 接受的值 | 默认值 |\n| -------- | ---------------------- | -------- | ------ |\n| playable | 仅看有可播放片源的影片 | 0/1      | 0      |\n| score    | 筛选评分               | 0.0-10.0 | 0      |\n\n用例：`/douban/list/tv_korean/playable=1&score=8`\n\n> 上面的榜单 / 集合并没有列举完整。\n>\n> 如何找到榜单对应的路由参数：\n> 在豆瓣手机 APP 中，对应地榜单页面右上角，点击分享链接。链接路径 `subject_collection` 后的路径就是路由参数 `type`。\n> 如：小说热门榜的分享链接为：`https://m.douban.com/subject_collection/ECDIHUN4A`，其对应本 RSS 路由的 `type` 为 `ECDIHUN4A`，对应的订阅链接路由：[`/douban/list/ECDIHUN4A`](https://rsshub.app/douban/list/ECDIHUN4A)",
  "example": "/douban/list/subject_real_time_hotest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1693,
  "location": "other/list.ts",
  "maintainers": [
    "5upernova-heng",
    "honue"
  ],
  "name": "豆瓣榜单与集合",
  "parameters": {
    "routeParams": "额外参数；请参阅以下说明和表格",
    "type": "榜单类型，见下表。默认为实时热门书影音"
  },
  "path": "/list/:type?/:routeParams?",
  "radar": [
    {
      "source": [
        "www.douban.com/subject_collection/:type"
      ],
      "target": "/list/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣热门电影作品，根据电影实时热度与关注度得出的综合排名，每小时更新。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55539094681492480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/movie_real_time_hotest",
      "title": "豆瓣 - 实时热门电影",
      "type": "feed",
      "url": "rsshub://douban/list/movie_real_time_hotest"
    },
    {
      "description": "每周一更新；关注榜单，第一时间了解最新好书 - Powered by RSSHub",
      "errorAt": "2025-03-04T07:16:45.428Z",
      "errorMessage": "[GET] \"https://m.douban.com/rexxar/api/v2/subject_collection/EC645NBAI/items?playable=0&start=0&count=50\": 404 Not Found\n[GET] \"https://m.douban.com/rexxar/api/v2/subject_collection/EC645NBAI/items?playable=0&start=0&count=50\": 404 Not Found\n[GET] \"https://m.douban.com/rexxar/api/v2/subject_collection/EC645NBAI/items?playable=0&start=0&count=50\": 404 Not Found\n502 \n[GET] \"https://m.douban.com/rexxar/api/v2/subject_collection/EC645NBAI/items?playable=0&start=0&count=50\": 404 Not Found\n",
      "id": "55621048231294976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/EC645NBAI",
      "title": "豆瓣 - 一周热门图书榜",
      "type": "feed",
      "url": "rsshub://douban/list/EC645NBAI"
    }
  ]
}
```
