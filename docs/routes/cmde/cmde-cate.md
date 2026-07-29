# 国家药品监督管理局医疗器械技术审评中心 - 通用

## Coverage
`index-only`

## Route
- Namespace: `cmde`
- Namespace Name: `国家药品监督管理局医疗器械技术审评中心`
- Route Path: `/cmde/:cate{.+}?`
- Route Name: `通用`
- Example: `/cmde/xwdt/zxyw`
- URL: `www.cmde.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `run-ze`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://www.cmde.org.cn/` 与 `/index.html` 之间的字段，下面是一个例子。

若订阅 [最新要闻](https://www.cmde.org.cn/xwdt/zxyw/index.html) 则将对应页面 URL <https://www.cmde.org.cn/xwdt/zxyw/index.html> 中 `https://www.cmde.org.cn/` 和 `/index.html` 之间的字段 `xwdt/zxyw` 作为路径填入。此时路由为 [`/cmde/xwdt/zxyw`](https://rsshub.app/cmde/xwdt/zxyw)

## Parameters
- `cate`: 路径，默认为最新要闻


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "路径处填写对应页面 URL 中 `https://www.cmde.org.cn/` 与 `/index.html` 之间的字段，下面是一个例子。\n\n若订阅 [最新要闻](https://www.cmde.org.cn/xwdt/zxyw/index.html) 则将对应页面 URL <https://www.cmde.org.cn/xwdt/zxyw/index.html> 中 `https://www.cmde.org.cn/` 和 `/index.html` 之间的字段 `xwdt/zxyw` 作为路径填入。此时路由为 [`/cmde/xwdt/zxyw`](https://rsshub.app/cmde/xwdt/zxyw)",
  "example": "/cmde/xwdt/zxyw",
  "heat": 11,
  "location": "index.ts",
  "maintainers": [
    "run-ze"
  ],
  "name": "通用",
  "parameters": {
    "cate": "路径，默认为最新要闻"
  },
  "path": "/:cate{.+}?",
  "topFeeds": [
    {
      "description": "国家药品监督管理局医疗器械技术审评中心工作动态相关信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71471683425747968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cmde.org.cn/xwdt/zxyw/",
      "title": "国家药品监督管理局医疗器械技术审评中心----工作动态",
      "type": "feed",
      "url": "rsshub://cmde/xwdt/zxyw"
    }
  ]
}
```
