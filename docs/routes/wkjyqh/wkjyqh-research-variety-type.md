# 五矿期货 - 研究报告

## Coverage
`index-only`

## Route
- Namespace: `wkjyqh`
- Namespace Name: `五矿期货`
- Route Path: `/wkjyqh/research/:variety?/:type?`
- Route Name: `研究报告`
- Example: `/wkjyqh/research`
- URL: `www.wkjyqh.com/main/research_center/yjbg/index.shtml`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
例如农产品周报使用 `/wkjyqh/research/5/2`，全部品种周报使用 `/wkjyqh/research/0/2`。参数对应官网原生研究报告栏目，不请求后续页面。

## Parameters
- `variety`: 官网交易品种编码，0 或省略为全部；宏观金融为 1、农产品为 5、贵金属为 7。
- `type`: 官网报告类型编码，0 或省略为全部，2 为周报。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wkjyqh.com/main/research_center/yjbg/index.shtml`
  - `www.wkjyqh.com/main/research_center/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "例如农产品周报使用 `/wkjyqh/research/5/2`，全部品种周报使用 `/wkjyqh/research/0/2`。参数对应官网原生研究报告栏目，不请求后续页面。",
  "example": "/wkjyqh/research",
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "研究报告",
  "parameters": {
    "type": "官网报告类型编码，0 或省略为全部，2 为周报。",
    "variety": "官网交易品种编码，0 或省略为全部；宏观金融为 1、农产品为 5、贵金属为 7。"
  },
  "path": "/research/:variety?/:type?",
  "radar": [
    {
      "source": [
        "www.wkjyqh.com/main/research_center/yjbg/index.shtml",
        "www.wkjyqh.com/main/research_center/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.wkjyqh.com/main/research_center/yjbg/index.shtml"
}
```
