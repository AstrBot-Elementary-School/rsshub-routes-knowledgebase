# 哔哩哔哩 bilibili - 视频搜索

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/vsearch/:kw/:order?/:embed?/:tid?`
- Route Name: `视频搜索`
- Example: `/bilibili/vsearch/RSSHub`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `pcrtool, DIYgod`
- Source Location: `vsearch.ts`
- Source Module: `_None_`

## Description
分区 id 的取值请参考下表：

| 全部分区 | 动画 | 番剧 | 国创 | 音乐 | 舞蹈 | 游戏 | 知识 | 科技 | 运动 | 汽车 | 生活 | 美食 | 动物圈 | 鬼畜 | 时尚 | 资讯 | 娱乐 | 影视 | 纪录片 | 电影 | 电视剧 |
| -------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ------ |
| 0        | 1    | 13   | 167  | 3    | 129  | 4    | 36   | 188  | 234  | 223  | 160  | 211  | 217    | 119  | 155  | 202  | 5    | 181  | 177    | 23   | 11     |

## Parameters
- `kw`: 检索关键字
- `order`: 排序方式, 综合:totalrank 最多点击:click 最新发布:pubdate(缺省) 最多弹幕:dm 最多收藏:stow
- `embed`: 默认为开启内嵌视频, 任意值为关闭
- `tid`: 分区 id


## Features
- `requireConfig`: [{"description": "如果没有此配置，那么必须开启 Playwright 支持；BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n2.  打开控制台，切换到 Network 面板，刷新\n3.  点击 dynamic_new 请求，找到 Cookie\n4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie", "name": "BILIBILI_COOKIE_*", "optional": true}]
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
    "social-media"
  ],
  "description": "分区 id 的取值请参考下表：\n\n| 全部分区 | 动画 | 番剧 | 国创 | 音乐 | 舞蹈 | 游戏 | 知识 | 科技 | 运动 | 汽车 | 生活 | 美食 | 动物圈 | 鬼畜 | 时尚 | 资讯 | 娱乐 | 影视 | 纪录片 | 电影 | 电视剧 |\n| -------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ------ |\n| 0        | 1    | 13   | 167  | 3    | 129  | 4    | 36   | 188  | 234  | 223  | 160  | 211  | 217    | 119  | 155  | 202  | 5    | 181  | 177    | 23   | 11     |",
  "example": "/bilibili/vsearch/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "如果没有此配置，那么必须开启 Playwright 支持；BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n2.  打开控制台，切换到 Network 面板，刷新\n3.  点击 dynamic_new 请求，找到 Cookie\n4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie",
        "name": "BILIBILI_COOKIE_*",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 218,
  "location": "vsearch.ts",
  "maintainers": [
    "pcrtool",
    "DIYgod"
  ],
  "name": "视频搜索",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "kw": "检索关键字",
    "order": "排序方式, 综合:totalrank 最多点击:click 最新发布:pubdate(缺省) 最多弹幕:dm 最多收藏:stow",
    "tid": "分区 id"
  },
  "path": "/vsearch/:kw/:order?/:embed?/:tid?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Result from 思源笔记 bilibili search, ordered by pubdate. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66120396417817600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.bilibili.com/all?keyword=%E6%80%9D%E6%BA%90%E7%AC%94%E8%AE%B0&order=pubdate",
      "title": "思源笔记 - bilibili",
      "type": "feed",
      "url": "rsshub://bilibili/vsearch/%E6%80%9D%E6%BA%90%E7%AC%94%E8%AE%B0"
    },
    {
      "description": "Result from 沙雕动画 bilibili search, ordered by totalrank. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84117288401258496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.bilibili.com/all?keyword=%E6%B2%99%E9%9B%95%E5%8A%A8%E7%94%BB&order=totalrank",
      "title": "沙雕动画 - bilibili",
      "type": "feed",
      "url": "rsshub://bilibili/vsearch/%E6%B2%99%E9%9B%95%E5%8A%A8%E7%94%BB/totalrank"
    }
  ]
}
```
