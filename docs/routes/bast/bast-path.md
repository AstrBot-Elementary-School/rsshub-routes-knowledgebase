# 北京市科学技术协会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `bast`
- Namespace Name: `北京市科学技术协会`
- Route Path: `/bast/:path{.+}?`
- Route Name: `通用`
- Example: `/bast/col/col31266`
- URL: `bast.net.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://www.bast.net.cn/` 后的字段。下面是两个例子。

若订阅 [通知公告](https://www.bast.net.cn/col/col31266) 则将对应页面 URL <https://www.bast.net.cn/col/col31266> 中 `https://www.bast.net.cn/` 后的字段 `col/col31266` 作为路径填入。此时路由为 [`/bast/col/col31266`](https://rsshub.app/bast/col/col31266)

若订阅 [学术动态](https://www.bast.net.cn/col/col31530) 则将对应页面 URL <https://www.bast.net.cn/col/col31530> 中 `https://www.bast.net.cn/` 后的字段 `col/col31530` 作为路径填入。此时路由为 [`/bast/col/col31530`](https://rsshub.app/bast/col/col31530)

如果路由符合 `/col/colXXXXX` 的格式，可以由 [`/bast/col/col31266`](https://rsshub.app/bast/col/col31266) 精简为 [`/bast/31266`](https://rsshub.app/bast/31266)

## Parameters
- `path`: 路径，默认为通知公告


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "路径处填写对应页面 URL 中 `https://www.bast.net.cn/` 后的字段。下面是两个例子。\n\n若订阅 [通知公告](https://www.bast.net.cn/col/col31266) 则将对应页面 URL <https://www.bast.net.cn/col/col31266> 中 `https://www.bast.net.cn/` 后的字段 `col/col31266` 作为路径填入。此时路由为 [`/bast/col/col31266`](https://rsshub.app/bast/col/col31266)\n\n若订阅 [学术动态](https://www.bast.net.cn/col/col31530) 则将对应页面 URL <https://www.bast.net.cn/col/col31530> 中 `https://www.bast.net.cn/` 后的字段 `col/col31530` 作为路径填入。此时路由为 [`/bast/col/col31530`](https://rsshub.app/bast/col/col31530)\n\n如果路由符合 `/col/colXXXXX` 的格式，可以由 [`/bast/col/col31266`](https://rsshub.app/bast/col/col31266) 精简为 [`/bast/31266`](https://rsshub.app/bast/31266)",
  "example": "/bast/col/col31266",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
