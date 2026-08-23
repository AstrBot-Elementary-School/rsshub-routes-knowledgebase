# 中国农工民主党 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `ngd`
- Namespace Name: `中国农工民主党`
- Route Path: `/ngd/:slug?`
- Route Name: `新闻中心`
- Example: `/ngd`
- URL: `www.ngd.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
将目标栏目的网址拆解为 `http://www.ngd.org.cn/` 和后面的字段，去掉 `.htm` 后，把后面的字段中的 `/` 替换为 `-`，即为该路由的 slug

如：（要闻动态）`http://www.ngd.org.cn/xwzx/ywdt/index.htm` 的网址在 `http://www.ngd.org.cn/` 后的字段是 `xwzx/ywdt/index.htm`，则对应的 slug 为 `xwzx-ywdt-index`，对应的路由即为 `/ngd/xwzx-ywdt-index`

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
  "description": "将目标栏目的网址拆解为 `http://www.ngd.org.cn/` 和后面的字段，去掉 `.htm` 后，把后面的字段中的 `/` 替换为 `-`，即为该路由的 slug\n\n如：（要闻动态）`http://www.ngd.org.cn/xwzx/ywdt/index.htm` 的网址在 `http://www.ngd.org.cn/` 后的字段是 `xwzx/ywdt/index.htm`，则对应的 slug 为 `xwzx-ywdt-index`，对应的路由即为 `/ngd/xwzx-ywdt-index`",
  "example": "/ngd",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻中心",
  "parameters": {
    "slug": "见下文"
  },
  "path": "/:slug?",
  "topFeeds": []
}
```
