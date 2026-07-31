# 凤凰网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `ifeng`
- Namespace Name: `凤凰网`
- Route Path: `/ifeng/news/:path{.+}?`
- Route Name: `资讯`
- Example: `/ifeng/news`
- URL: `feng.ifeng.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
::: tip
路径处填写对应页面 URL 中 `https://news.ifeng.com/` 后的字段。下面是一个例子。

若订阅 [大湾区\_资讯\_凤凰网](https://news.ifeng.com/shanklist/3-305565-) 则将对应页面 URL `https://news.ifeng.com/shanklist/3-305565-` 中 `https://news.ifeng.com/` 后的字段 `shanklist/3-305565-` 作为路径填入。此时路由为 [`/ifeng/news/shanklist/3-305565-`](https://rsshub.app/ifeng/news/shanklist/3-305565-)
:::

## Parameters
- `path`: 路径，对应分类资讯页 URL 路径，默认为空


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `https://news.ifeng.com/` 后的字段。下面是一个例子。\n\n若订阅 [大湾区\\_资讯\\_凤凰网](https://news.ifeng.com/shanklist/3-305565-) 则将对应页面 URL `https://news.ifeng.com/shanklist/3-305565-` 中 `https://news.ifeng.com/` 后的字段 `shanklist/3-305565-` 作为路径填入。此时路由为 [`/ifeng/news/shanklist/3-305565-`](https://rsshub.app/ifeng/news/shanklist/3-305565-)\n:::",
  "example": "/ifeng/news",
  "heat": 328,
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "path": "路径，对应分类资讯页 URL 路径，默认为空"
  },
  "path": "/news/:path{.+}?",
  "topFeeds": [
    {
      "description": "资讯_凤凰网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58310184330535940",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ifeng.com/",
      "title": "资讯_凤凰网",
      "type": "feed",
      "url": "rsshub://ifeng/news"
    },
    {
      "description": "凤凰大参考_资讯_凤凰网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150755089712076813",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ifeng.com/shanklist/3-245389-",
      "title": "凤凰大参考_资讯_凤凰网",
      "type": "feed",
      "url": "rsshub://ifeng/news/shanklist/3-245389-"
    }
  ]
}
```
