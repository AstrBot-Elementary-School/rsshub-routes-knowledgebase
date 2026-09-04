# 中国证券监督管理委员会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/csrc`
- Namespace Name: `中国证券监督管理委员会`
- Route Path: `/gov/csrc/news/:suffix{.+}?`
- Route Name: `通用`
- Example: `/gov/csrc/news/c101975/zfxxgk_zdgk.shtml`
- URL: `www.csrc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `chinobing, LogicJake`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
::: tip
路径处填写对应页面 URL 中 `http://www.csrc.gov.cn/csrc/` 后的字段。下面是一个例子。

若订阅 [证监会要闻](http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml) 则将对应页面 URL <http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml> 中 `http://www.csrc.gov.cn/csrc/` 后的字段 `c100028/common_xq_list.shtml` 作为路径填入。此时路由为 [`/gov/csrc/news/c100028/common_xq_list.shtml`](https://rsshub.app/gov/csrc/news/c100028/common_xq_list.shtml)
:::

## Parameters
- `suffix`: 路径，预设为 `c100028/common_xq_list.shtml`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.csrc.gov.cn/csrc/*suffix`
- `target`: `/news/:suffix`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `http://www.csrc.gov.cn/csrc/` 后的字段。下面是一个例子。\n\n若订阅 [证监会要闻](http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml) 则将对应页面 URL <http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml> 中 `http://www.csrc.gov.cn/csrc/` 后的字段 `c100028/common_xq_list.shtml` 作为路径填入。此时路由为 [`/gov/csrc/news/c100028/common_xq_list.shtml`](https://rsshub.app/gov/csrc/news/c100028/common_xq_list.shtml)\n:::",
  "example": "/gov/csrc/news/c101975/zfxxgk_zdgk.shtml",
  "heat": 1,
  "location": "news.tsx",
  "maintainers": [
    "chinobing",
    "LogicJake"
  ],
  "name": "通用",
  "parameters": {
    "suffix": "路径，预设为 `c100028/common_xq_list.shtml`"
  },
  "path": "/news/:suffix{.+}?",
  "radar": [
    {
      "source": [
        "www.csrc.gov.cn/csrc/*suffix"
      ],
      "target": "/news/:suffix"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中国证券监督管理委员会 - 证监会要闻 - Powered by RSSHub",
      "errorAt": "2026-09-03T09:06:51.257Z",
      "errorMessage": "[GET] \"http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 45.253.17.18:80, 45.253.17.14:80, 45.253.17.13:80, 45.253.17.15:80, 45.253.17.16:80, 45.253.17.19:80, 45.253.17.17:80, 45.253.17.20:80, timeout: 10000ms))\n",
      "id": "1220957427747127299",
      "image": "http://www.csrc.gov.cn/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "http://www.csrc.gov.cn/csrc/c100028/common_xq_list.shtml",
      "title": "中国证券监督管理委员会 - 证监会要闻",
      "type": "feed",
      "url": "rsshub://gov/csrc/news/c100028/common_xq_list.shtml"
    }
  ]
}
```
