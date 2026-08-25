# 中国政协网 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `gov/cppcc`
- Namespace Name: `中国政协网`
- Route Path: `/gov/cppcc/:slug?`
- Route Name: `栏目`
- Example: `/gov/cppcc`
- URL: `www.cppcc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
将目标栏目的网址拆解为 `http://www.cppcc.gov.cn/` 和后面的字段，去掉末尾的 `/` 后，把字段中的 `/` 替换为 `-`，即为该路由的 slug

如：（要闻）`http://www.cppcc.gov.cn/zxxw/yw/` 的网址在 `http://www.cppcc.gov.cn/` 后的字段是 `zxxw/yw/`，则对应的 slug 为 `zxxw-yw`，对应的路由即为 `/gov/cppcc/zxxw-yw`

## Parameters
- `slug`: 见下文


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
  "description": "将目标栏目的网址拆解为 `http://www.cppcc.gov.cn/` 和后面的字段，去掉末尾的 `/` 后，把字段中的 `/` 替换为 `-`，即为该路由的 slug\n\n如：（要闻）`http://www.cppcc.gov.cn/zxxw/yw/` 的网址在 `http://www.cppcc.gov.cn/` 后的字段是 `zxxw/yw/`，则对应的 slug 为 `zxxw-yw`，对应的路由即为 `/gov/cppcc/zxxw-yw`",
  "example": "/gov/cppcc",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "slug": "见下文"
  },
  "path": "/:slug?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
