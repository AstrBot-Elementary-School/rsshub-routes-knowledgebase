# 上海市人民政府 - 药品监督管理局

## Coverage
`index-only`

## Route
- Namespace: `gov/sh`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/sh/yjj/:path{.+}?`
- Route Name: `药品监督管理局`
- Example: `/gov/sh/yjj/zh`
- URL: `sh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `yjj/index.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `https://yjj.sh.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。

若订阅 [最新信息公开 > 综合](https://yjj.sh.gov.cn/zh/index.html) 则将对应页面 URL <https://yjj.sh.gov.cn/zh/index.html> 中 `https://yjj.sh.gov.cn/` 和 `/index.html` 之间的字段 `zh` 作为路径填入。此时路由为 [`/gov/sh/yjj/zh`](https://rsshub.app/gov/sh/yjj/zh)

:::

## Parameters
- `path`: 路径参数


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `yjj.sh.gov.cn/*path/index.html`
  - `yjj.sh.gov.cn/*path`
- `target`: `/yjj/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `https://yjj.sh.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。\n\n若订阅 [最新信息公开 > 综合](https://yjj.sh.gov.cn/zh/index.html) 则将对应页面 URL <https://yjj.sh.gov.cn/zh/index.html> 中 `https://yjj.sh.gov.cn/` 和 `/index.html` 之间的字段 `zh` 作为路径填入。此时路由为 [`/gov/sh/yjj/zh`](https://rsshub.app/gov/sh/yjj/zh)\n\n:::",
  "example": "/gov/sh/yjj/zh",
  "heat": 1,
  "location": "yjj/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "药品监督管理局",
  "parameters": {
    "path": "路径参数"
  },
  "path": "/yjj/:path{.+}?",
  "radar": [
    {
      "source": [
        "yjj.sh.gov.cn/*path/index.html",
        "yjj.sh.gov.cn/*path"
      ],
      "target": "/yjj/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
