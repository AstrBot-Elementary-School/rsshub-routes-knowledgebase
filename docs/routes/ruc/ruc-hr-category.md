# Renmin University of China - 人事处

## Coverage
`index-only`

## Route
- Namespace: `ruc`
- Namespace Name: `Renmin University of China`
- Route Path: `/ruc/hr/:category?`
- Route Name: `人事处`
- Example: `/ruc/hr`
- URL: `hr.ruc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `hr.ts`
- Source Module: `_None_`

## Description
::: tip
分类字段处填写的是对应中国人民大学人事处分类页网址中介于 **`http://hr.ruc.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。

如 [中国人民大学人事处 - 办事机构 - 教师事务办公室 - 教师通知公告](http://hr.ruc.edu.cn/bsjg/bsjsswbgs/jstzgg/index.htm) 的网址为 `http://hr.ruc.edu.cn/bsjg/bsjsswbgs/jstzgg/index.htm` 其中介于 **`http://hr.ruc.edu.cn/`** 和 **/index.htm** 中间的一段为 `bsjg/bsjsswbgs/jstzgg`。随后，并将其中的 `/` 修改为 `-`，可以得到 `bsjg-bsjsswbgs-jstzgg`。所以最终我们的路由为 [`/ruc/hr/bsjg-bsjsswbgs-jstzgg`](https://rsshub.app/ruc/hr/bsjg-bsjsswbgs-jstzgg)
:::

## Parameters
- `category`: 分类，见下方说明，默认为首页通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hr.ruc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n分类字段处填写的是对应中国人民大学人事处分类页网址中介于 **`http://hr.ruc.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。\n\n如 [中国人民大学人事处 - 办事机构 - 教师事务办公室 - 教师通知公告](http://hr.ruc.edu.cn/bsjg/bsjsswbgs/jstzgg/index.htm) 的网址为 `http://hr.ruc.edu.cn/bsjg/bsjsswbgs/jstzgg/index.htm` 其中介于 **`http://hr.ruc.edu.cn/`** 和 **/index.htm** 中间的一段为 `bsjg/bsjsswbgs/jstzgg`。随后，并将其中的 `/` 修改为 `-`，可以得到 `bsjg-bsjsswbgs-jstzgg`。所以最终我们的路由为 [`/ruc/hr/bsjg-bsjsswbgs-jstzgg`](https://rsshub.app/ruc/hr/bsjg-bsjsswbgs-jstzgg)\n:::",
  "example": "/ruc/hr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hr.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "人事处",
  "parameters": {
    "category": "分类，见下方说明，默认为首页通知公告"
  },
  "path": "/hr/:category?",
  "radar": [
    {
      "source": [
        "hr.ruc.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "hr.ruc.edu.cn/"
}
```
