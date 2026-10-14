# 国务院国有资产监督管理委员会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/sasac`
- Namespace Name: `国务院国有资产监督管理委员会`
- Route Path: `/gov/sasac/:path{.+}`
- Route Name: `通用`
- Example: `/gov/sasac/n2588030/n16436141`
- URL: `www.sasac.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `generic.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `http://www.sasac.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。

若订阅 [其他](http://www.sasac.gov.cn/n2588030/n16436141/index.html) 则将对应页面 URL <http://www.sasac.gov.cn/n2588030/n16436141/index.html> 中 `http://www.sasac.gov.cn/` 和 `/index.html` 之间的字段 `n2588030/n16436141` 作为路径填入。此时路由为 [`/gov/sasac/n2588030/n16436141`](https://rsshub.app/gov/sasac/n2588030/n16436141)

:::

## Parameters
- `path`: 路径，可在 URL 找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sasac.gov.cn/*path/index.html`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `http://www.sasac.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。\n\n若订阅 [其他](http://www.sasac.gov.cn/n2588030/n16436141/index.html) 则将对应页面 URL <http://www.sasac.gov.cn/n2588030/n16436141/index.html> 中 `http://www.sasac.gov.cn/` 和 `/index.html` 之间的字段 `n2588030/n16436141` 作为路径填入。此时路由为 [`/gov/sasac/n2588030/n16436141`](https://rsshub.app/gov/sasac/n2588030/n16436141)\n\n:::",
  "example": "/gov/sasac/n2588030/n16436141",
  "heat": 0,
  "location": "generic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，可在 URL 找到"
  },
  "path": "/:path{.+}",
  "radar": [
    {
      "source": [
        "www.sasac.gov.cn/*path/index.html"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
