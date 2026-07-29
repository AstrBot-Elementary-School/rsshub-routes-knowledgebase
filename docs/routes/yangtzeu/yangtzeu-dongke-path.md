# 长江大学 - 动物科学学院

## Coverage
`index-only`

## Route
- Namespace: `yangtzeu`
- Namespace Name: `长江大学`
- Route Path: `/yangtzeu/dongke/:path{.+}?`
- Route Name: `动物科学学院`
- Example: `/yangtzeu/dongke/yqzl/tzgg`
- URL: `yangtzeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `dongke.ts`
- Source Module: `_None_`

## Description
路径处填写网址中 `https://dongke.yangtzeu.edu.cn` 到末尾 `.htm` 之间的部分，默认为学院新闻。

如订阅 [院情总览 - 通知公告](https://dongke.yangtzeu.edu.cn/yqzl/tzgg.htm)，网址为 `https://dongke.yangtzeu.edu.cn/yqzl/tzgg.htm`，截取 `/yqzl/tzgg` 作为参数，此时路由为 [`/yangtzeu/dongke/yqzl/tzgg`](https://rsshub.app/yangtzeu/dongke/yqzl/tzgg)。

若订阅子分类 [学生工作](https://dongke.yangtzeu.edu.cn/xsgz.htm)，网址为 `https://dongke.yangtzeu.edu.cn/xsgz.htm`。截取 `https://dongke.yangtzeu.edu.cn` 到末尾 `.htm` 的部分 `/xsgz` 作为参数，此时路由为 [`/yangtzeu/dongke/xsgz`](https://rsshub.app/yangtzeu/dongke/xsgz)。

## Parameters
- `path`: 路径，默认为学院新闻


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
  "description": "路径处填写网址中 `https://dongke.yangtzeu.edu.cn` 到末尾 `.htm` 之间的部分，默认为学院新闻。\n\n如订阅 [院情总览 - 通知公告](https://dongke.yangtzeu.edu.cn/yqzl/tzgg.htm)，网址为 `https://dongke.yangtzeu.edu.cn/yqzl/tzgg.htm`，截取 `/yqzl/tzgg` 作为参数，此时路由为 [`/yangtzeu/dongke/yqzl/tzgg`](https://rsshub.app/yangtzeu/dongke/yqzl/tzgg)。\n\n若订阅子分类 [学生工作](https://dongke.yangtzeu.edu.cn/xsgz.htm)，网址为 `https://dongke.yangtzeu.edu.cn/xsgz.htm`。截取 `https://dongke.yangtzeu.edu.cn` 到末尾 `.htm` 的部分 `/xsgz` 作为参数，此时路由为 [`/yangtzeu/dongke/xsgz`](https://rsshub.app/yangtzeu/dongke/xsgz)。",
  "example": "/yangtzeu/dongke/yqzl/tzgg",
  "heat": 0,
  "location": "dongke.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "动物科学学院",
  "parameters": {
    "path": "路径，默认为学院新闻"
  },
  "path": "/dongke/:path{.+}?",
  "topFeeds": []
}
```
