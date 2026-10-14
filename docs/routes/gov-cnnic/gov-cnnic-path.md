# 中国互联网络信息中心 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `gov/cnnic`
- Namespace Name: `中国互联网络信息中心`
- Route Path: `/gov/cnnic/:path{.+}?`
- Route Name: `新闻中心`
- Example: `/gov/cnnic/11/39`
- URL: `www.cnnic.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `https://www.cnnic.net.cn/` 后的字段。下面是一个例子。

若订阅 [通知公告](https://www.cnnic.net.cn/11/39/index.html) 则将对应页面 URL <https://www.cnnic.net.cn/11/39/index.html> 中 `https://www.cnnic.net.cn/` 后的字段 `11/39` 作为路径填入。此时路由为 [`/gov/cnnic/11/39`](https://rsshub.app/gov/cnnic/11/39)

:::

## Parameters
- `path`: 路径，默认为通知公告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cnnic.net.cn/11/:id/index.html`
  - `www.cnnic.net.cn/11/:id`
- `target`: `/11/:id`
### Rule 2
- `source`:
  - `www.cnnic.net.cn/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `https://www.cnnic.net.cn/` 后的字段。下面是一个例子。\n\n若订阅 [通知公告](https://www.cnnic.net.cn/11/39/index.html) 则将对应页面 URL <https://www.cnnic.net.cn/11/39/index.html> 中 `https://www.cnnic.net.cn/` 后的字段 `11/39` 作为路径填入。此时路由为 [`/gov/cnnic/11/39`](https://rsshub.app/gov/cnnic/11/39)\n\n:::",
  "example": "/gov/cnnic/11/39",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻中心",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.cnnic.net.cn/11/:id/index.html",
        "www.cnnic.net.cn/11/:id"
      ],
      "target": "/11/:id"
    },
    {
      "source": [
        "www.cnnic.net.cn/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
