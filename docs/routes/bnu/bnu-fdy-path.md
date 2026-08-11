# 北京师范大学 - 党委学生工作部辅导员发展中心

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/fdy/:path{.+}?`
- Route Name: `党委学生工作部辅导员发展中心`
- Example: `/bnu/fdy/tzgg/dwjs`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `fdy.ts`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://fdy.bnu.edu.cn/` 和 `/index.htm` 之间的字段。下面是一个例子。

若订阅 [通知公告 > 队伍建设](https://fdy.bnu.edu.cn/tzgg/dwjs/index.htm) 则将对应页面 URL <https://fdy.bnu.edu.cn/tzgg/dwjs/index.htm> 中 `https://fdy.bnu.edu.cn/` 和 `/index.htm` 之间的字段 `tzgg/dwjs` 作为路径填入。此时路由为 [`/bnu/fdy/tzgg/dwjs`](https://rsshub.app/bnu/fdy/tzgg/dwjs)

## Parameters
- `path`: 路径，默认为 `tzgg`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "路径处填写对应页面 URL 中 `https://fdy.bnu.edu.cn/` 和 `/index.htm` 之间的字段。下面是一个例子。\n\n若订阅 [通知公告 > 队伍建设](https://fdy.bnu.edu.cn/tzgg/dwjs/index.htm) 则将对应页面 URL <https://fdy.bnu.edu.cn/tzgg/dwjs/index.htm> 中 `https://fdy.bnu.edu.cn/` 和 `/index.htm` 之间的字段 `tzgg/dwjs` 作为路径填入。此时路由为 [`/bnu/fdy/tzgg/dwjs`](https://rsshub.app/bnu/fdy/tzgg/dwjs)",
  "example": "/bnu/fdy/tzgg/dwjs",
  "heat": 0,
  "location": "fdy.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "党委学生工作部辅导员发展中心",
  "parameters": {
    "path": "路径，默认为 `tzgg`"
  },
  "path": "/fdy/:path{.+}?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
