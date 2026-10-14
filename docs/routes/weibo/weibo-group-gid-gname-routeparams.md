# 微博 - 自定义分组

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/group/:gid/:gname?/:routeParams?`
- Route Name: `自定义分组`
- Example: `/weibo/group/4541216424989965`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `monologconnor, Rongronggg9`
- Source Location: `group.ts`
- Source Module: `_None_`

## Description
::: warning
由于微博官方未提供自定义分组相关 api, 此方案必须使用用户`Cookie`进行抓取

因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知

微博用户 Cookie 的配置可参照部署文档
:::

## Parameters
- `gid`: 分组id, 在网页版分组地址栏末尾`?gid=`处获取
- `gname`: 分组显示名称; 默认为: `微博分组`
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES"}]
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
  "description": "::: warning\n由于微博官方未提供自定义分组相关 api, 此方案必须使用用户`Cookie`进行抓取\n\n因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知\n\n微博用户 Cookie 的配置可参照部署文档\n:::",
  "example": "/weibo/group/4541216424989965",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "group.ts",
  "maintainers": [
    "monologconnor",
    "Rongronggg9"
  ],
  "name": "自定义分组",
  "parameters": {
    "gid": "分组id, 在网页版分组地址栏末尾`?gid=`处获取",
    "gname": "分组显示名称; 默认为: `微博分组`",
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/group/:gid/:gname?/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
