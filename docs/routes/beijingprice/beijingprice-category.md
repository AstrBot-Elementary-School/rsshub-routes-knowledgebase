# 北京价格 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `beijingprice`
- Namespace Name: `北京价格`
- Route Path: `/beijingprice/:category{.+}?`
- Route Name: `资讯`
- Example: `/beijingprice/jgzx/xwzx`
- URL: `beijingprice.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [新闻资讯](https://www.beijingprice.cn/jgzx/xwzx/)，网址为 `https://www.beijingprice.cn/jgzx/xwzx/`。截取 `https://beijingprice.cn/` 到末尾 `/` 的部分 `jgzx/xwzx` 作为参数填入，此时路由为 [`/beijingprice/jgzx/xwzx`](https://rsshub.app/beijingprice/jgzx/xwzx)。
:::

#### [价格资讯](https://www.beijingprice.cn/jgzx/xwzx/)

| [新闻资讯](https://www.beijingprice.cn/jgzx/xwzx/)     | [工作动态](https://www.beijingprice.cn/jgzx/gzdt/)     | [各区动态](https://www.beijingprice.cn/jgzx/gqdt/)     | [通知公告](https://www.beijingprice.cn/jgzx/tzgg/)     | [价格早报](https://www.beijingprice.cn/jgzx/jgzb/)     |
| ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ |
| [jgzx/xwzx](https://rsshub.app/beijingprice/jgzx/xwzx) | [jgzx/gzdt](https://rsshub.app/beijingprice/jgzx/gzdt) | [jgzx/gqdt](https://rsshub.app/beijingprice/jgzx/gqdt) | [jgzx/tzgg](https://rsshub.app/beijingprice/jgzx/tzgg) | [jgzx/jgzb](https://rsshub.app/beijingprice/jgzx/jgzb) |

#### [综合信息](https://www.beijingprice.cn/zhxx/cbjs/)

| [价格听证](https://www.beijingprice.cn/zhxx/jgtz/)     | [价格监测定点单位名单](https://www.beijingprice.cn/zhxx/jgjcdddwmd/) | [部门预算决算](https://www.beijingprice.cn/bmys/) |
| ------------------------------------------------------ | -------------------------------------------------------------------- | ------------------------------------------------- |
| [zhxx/jgtz](https://rsshub.app/beijingprice/zhxx/jgtz) | [zhxx/jgjcdddwmd](https://rsshub.app/beijingprice/zhxx/jgjcdddwmd)   | [bmys](https://rsshub.app/beijingprice/bmys)      |

## Parameters
- `category`: 分类，默认为 `jgzx/xwzx` 即新闻资讯，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `beijingprice.cn/:category?`
### Rule 2
- `title`: `价格资讯 - 新闻资讯`
- `source`:
  - `beijingprice.cn/jgzx/xwzx/`
- `target`: `/jgzx/xwzx`
### Rule 3
- `title`: `价格资讯 - 工作动态`
- `source`:
  - `beijingprice.cn/jgzx/gzdt/`
- `target`: `/jgzx/gzdt`
### Rule 4
- `title`: `价格资讯 - 各区动态`
- `source`:
  - `beijingprice.cn/jgzx/gqdt/`
- `target`: `/jgzx/gqdt`
### Rule 5
- `title`: `价格资讯 - 通知公告`
- `source`:
  - `beijingprice.cn/jgzx/tzgg/`
- `target`: `/jgzx/tzgg`
### Rule 6
- `title`: `价格资讯 - 价格早报`
- `source`:
  - `beijingprice.cn/jgzx/jgzb/`
- `target`: `/jgzx/jgzb`
### Rule 7
- `title`: `综合信息 - 价格听证`
- `source`:
  - `beijingprice.cn/zhxx/jgtz/`
- `target`: `/zhxx/jgtz`
### Rule 8
- `title`: `综合信息 - 价格监测定点单位名单`
- `source`:
  - `beijingprice.cn/zhxx/jgjcdddwmd/`
- `target`: `/zhxx/jgjcdddwmd`
### Rule 9
- `title`: `综合信息 - 部门预算决算`
- `source`:
  - `beijingprice.cn/bmys/`
- `target`: `/bmys`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [新闻资讯](https://www.beijingprice.cn/jgzx/xwzx/)，网址为 `https://www.beijingprice.cn/jgzx/xwzx/`。截取 `https://beijingprice.cn/` 到末尾 `/` 的部分 `jgzx/xwzx` 作为参数填入，此时路由为 [`/beijingprice/jgzx/xwzx`](https://rsshub.app/beijingprice/jgzx/xwzx)。\n:::\n\n#### [价格资讯](https://www.beijingprice.cn/jgzx/xwzx/)\n\n| [新闻资讯](https://www.beijingprice.cn/jgzx/xwzx/)     | [工作动态](https://www.beijingprice.cn/jgzx/gzdt/)     | [各区动态](https://www.beijingprice.cn/jgzx/gqdt/)     | [通知公告](https://www.beijingprice.cn/jgzx/tzgg/)     | [价格早报](https://www.beijingprice.cn/jgzx/jgzb/)     |\n| ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ |\n| [jgzx/xwzx](https://rsshub.app/beijingprice/jgzx/xwzx) | [jgzx/gzdt](https://rsshub.app/beijingprice/jgzx/gzdt) | [jgzx/gqdt](https://rsshub.app/beijingprice/jgzx/gqdt) | [jgzx/tzgg](https://rsshub.app/beijingprice/jgzx/tzgg) | [jgzx/jgzb](https://rsshub.app/beijingprice/jgzx/jgzb) |\n\n#### [综合信息](https://www.beijingprice.cn/zhxx/cbjs/)\n\n| [价格听证](https://www.beijingprice.cn/zhxx/jgtz/)     | [价格监测定点单位名单](https://www.beijingprice.cn/zhxx/jgjcdddwmd/) | [部门预算决算](https://www.beijingprice.cn/bmys/) |\n| ------------------------------------------------------ | -------------------------------------------------------------------- | ------------------------------------------------- |\n| [zhxx/jgtz](https://rsshub.app/beijingprice/zhxx/jgtz) | [zhxx/jgjcdddwmd](https://rsshub.app/beijingprice/zhxx/jgjcdddwmd)   | [bmys](https://rsshub.app/beijingprice/bmys)      |",
  "example": "/beijingprice/jgzx/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 41,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": "分类，默认为 `jgzx/xwzx` 即新闻资讯，可在对应分类页 URL 中找到"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "beijingprice.cn/:category?"
      ]
    },
    {
      "source": [
        "beijingprice.cn/jgzx/xwzx/"
      ],
      "target": "/jgzx/xwzx",
      "title": "价格资讯 - 新闻资讯"
    },
    {
      "source": [
        "beijingprice.cn/jgzx/gzdt/"
      ],
      "target": "/jgzx/gzdt",
      "title": "价格资讯 - 工作动态"
    },
    {
      "source": [
        "beijingprice.cn/jgzx/gqdt/"
      ],
      "target": "/jgzx/gqdt",
      "title": "价格资讯 - 各区动态"
    },
    {
      "source": [
        "beijingprice.cn/jgzx/tzgg/"
      ],
      "target": "/jgzx/tzgg",
      "title": "价格资讯 - 通知公告"
    },
    {
      "source": [
        "beijingprice.cn/jgzx/jgzb/"
      ],
      "target": "/jgzx/jgzb",
      "title": "价格资讯 - 价格早报"
    },
    {
      "source": [
        "beijingprice.cn/zhxx/jgtz/"
      ],
      "target": "/zhxx/jgtz",
      "title": "综合信息 - 价格听证"
    },
    {
      "source": [
        "beijingprice.cn/zhxx/jgjcdddwmd/"
      ],
      "target": "/zhxx/jgjcdddwmd",
      "title": "综合信息 - 价格监测定点单位名单"
    },
    {
      "source": [
        "beijingprice.cn/bmys/"
      ],
      "target": "/bmys",
      "title": "综合信息 - 部门预算决算"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "北京价格网是北京市价格监测中心门户网站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65788338627183616",
      "image": "https://www.beijingprice.cn/images/common/common-header-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.beijingprice.cn/jgzx/xwzx/",
      "title": "新闻资讯-北京价格",
      "type": "feed",
      "url": "rsshub://beijingprice/jgzx/xwzx"
    }
  ],
  "url": "beijingprice.cn"
}
```
