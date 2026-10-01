# 汽油价格网 - 今日油价查询

## Coverage
`index-only`

## Route
- Namespace: `qiyoujiage`
- Namespace Name: `汽油价格网`
- Route Path: `/qiyoujiage/:path{.+}`
- Route Name: `今日油价查询`
- Example: `/qiyoujiage/shanghai`
- URL: `qiyoujiage.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `price.ts`
- Source Module: `_None_`

## Description
::: tip
路径处填写对应页面 URL 中 `http://www.qiyoujiage.com/` 和 `.shtml` 之间的字段。下面是一个例子。

若订阅 [福建漳州龙海今日油价](http://www.qiyoujiage.com/fujian/zhangzhou/longhai.shtml) 则将对应页面 URL <http://www.qiyoujiage.com/fujian/zhangzhou/longhai.shtml> 中 `http://www.qiyoujiage.com/` 和 `.shtml` 之间的字段 `fujian/zhangzhou/longhai` 作为路径填入。此时路由为 [`/qiyoujiage/fujian/zhangzhou/longhai`](https://rsshub.app/qiyoujiage/fujian/zhangzhou/longhai)
:::

## Parameters
- `path`: 路径


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `http://www.qiyoujiage.com/` 和 `.shtml` 之间的字段。下面是一个例子。\n\n若订阅 [福建漳州龙海今日油价](http://www.qiyoujiage.com/fujian/zhangzhou/longhai.shtml) 则将对应页面 URL <http://www.qiyoujiage.com/fujian/zhangzhou/longhai.shtml> 中 `http://www.qiyoujiage.com/` 和 `.shtml` 之间的字段 `fujian/zhangzhou/longhai` 作为路径填入。此时路由为 [`/qiyoujiage/fujian/zhangzhou/longhai`](https://rsshub.app/qiyoujiage/fujian/zhangzhou/longhai)\n:::",
  "example": "/qiyoujiage/shanghai",
  "heat": 13,
  "location": "price.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "今日油价查询",
  "parameters": {
    "path": "路径"
  },
  "path": "/:path{.+}",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "提供最新广东汽油价格,广东92号汽油价格,广东90号汽油价格,广东95号汽油价格,广东0号柴油价格等今日最新油价查询 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74118757831855104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qiyoujiage.com/guangdong.shtml",
      "title": "广东油价_广东90_92_95汽油价格_广东今日油价查询_汽油价格网",
      "type": "feed",
      "url": "rsshub://qiyoujiage/guangdong"
    },
    {
      "description": "提供最新江苏汽油价格,江苏92号汽油价格,江苏90号汽油价格,江苏95号汽油价格,江苏0号柴油价格等今日最新油价查询 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74327510262388736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qiyoujiage.com/jiangsu.shtml",
      "title": "江苏油价_江苏90_92_95汽油价格_江苏今日油价查询_汽油价格网",
      "type": "feed",
      "url": "rsshub://qiyoujiage/jiangsu"
    }
  ]
}
```
