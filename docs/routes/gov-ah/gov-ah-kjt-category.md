# 安徽省人民政府 - 科学技术厅

## Coverage
`index-only`

## Route
- Namespace: `gov/ah`
- Namespace Name: `安徽省人民政府`
- Route Path: `/gov/ah/kjt/:category{.+}?`
- Route Name: `科学技术厅`
- Example: `/gov/ah/kjt`
- URL: `kjt.ah.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `kjt.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://kjt.ah.gov.cn/kjzx/tzgg/)，网址为 `https://kjt.ah.gov.cn/kjzx/tzgg/`。将路径部分 `kjzx/tzgg` 作为分类参数填入，此时路由为 [`/gov/ah/kjt/kjzx/tzgg`](https://rsshub.app/gov/ah/kjt/kjzx/tzgg)。
:::

#### [科技资讯](https://kjt.ah.gov.cn/kjzx/index.html)

| [通知公告](https://kjt.ah.gov.cn/kjzx/tzgg/index.html) | [工作动态](https://kjt.ah.gov.cn/kjzx/gzdt/index.html) | [基层科技](https://kjt.ah.gov.cn/kjzx/jckj/index.html) | [媒体聚焦](https://kjt.ah.gov.cn/kjzx/mtjj/index.html) |
| ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ |
| [kjzx/tzgg](https://rsshub.app/gov/ah/kjt/kjzx/tzgg)   | [kjzx/gzdt](https://rsshub.app/gov/ah/kjt/kjzx/gzdt)   | [kjzx/jckj](https://rsshub.app/gov/ah/kjt/kjzx/jckj)   | [kjzx/mtjj](https://rsshub.app/gov/ah/kjt/kjzx/mtjj)   |

| [重要转载](https://kjt.ah.gov.cn/kjzx/zyzz/index.html) | [图片视频](https://kjt.ah.gov.cn/kjzx/tpsp/index.html) |
| ------------------------------------------------------ | ------------------------------------------------------ |
| [kjzx/zyzz](https://rsshub.app/gov/ah/kjt/kjzx/zyzz)   | [kjzx/tpsp](https://rsshub.app/gov/ah/kjt/kjzx/tpsp)   |

#### [科技统计](https://kjt.ah.gov.cn/kjzy/kjtj/index.html)

| [技术市场交易](https://kjt.ah.gov.cn/kjzy/kjtj/jsscjy/index.html)  | [科技成果公报](https://kjt.ah.gov.cn/kjzy/kjtj/kjcggb/index.html)  | [孵化载体发展](https://kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/index.html)  |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| [kjzy/kjtj/jsscjy](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/jsscjy) | [kjzy/kjtj/kjcggb](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/kjcggb) | [kjzy/kjtj/cyfhfz](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/cyfhfz) |

#### [科技数据](https://kjt.ah.gov.cn/kjzy/kjsj/index.html)

| [创新企业](https://kjt.ah.gov.cn/kjzy/kjsj/cxqy/index.html)    | [创新项目](https://kjt.ah.gov.cn/kjzy/kjsj/cxxm/index.html)    | [创新成果](https://kjt.ah.gov.cn/kjzy/kjsj/cxcg/index.html)    | [转化基金入库项目](https://kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/index.html) |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [kjzy/kjsj/cxqy](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxqy) | [kjzy/kjsj/cxxm](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxxm) | [kjzy/kjsj/cxcg](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxcg) | [kjzy/kjsj/zhjjrkxm](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/zhjjrkxm)  |

| [创新平台](https://kjt.ah.gov.cn/kjzy/kjsj/cxpt/index.html)    | [创新园区](https://kjt.ah.gov.cn/kjzy/kjsj/cxyq/index.html)    | [创新许可](https://kjt.ah.gov.cn/kjzy/kjsj/cxxk/index.html)    |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| [kjzy/kjsj/cxpt](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxpt) | [kjzy/kjsj/cxyq](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxyq) | [kjzy/kjsj/cxxk](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxxk) |

## Parameters
- `category`: 分类，默认为 `kjzx/tzgg`，即通知公告，可在对应分类页 URL 中找到


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
  - `kjt.ah.gov.cn/`
- `target`: `/kjt`
### Rule 2
- `title`: `科技资讯 - 通知公告`
- `source`:
  - `kjt.ah.gov.cn/kjzx/tzgg/index.html`
  - `kjt.ah.gov.cn/kjzx/tzgg/`
- `target`: `/kjt/kjzx/tzgg`
### Rule 3
- `title`: `科技资讯 - 工作动态`
- `source`:
  - `kjt.ah.gov.cn/kjzx/gzdt/index.html`
  - `kjt.ah.gov.cn/kjzx/gzdt/`
- `target`: `/kjt/kjzx/gzdt`
### Rule 4
- `title`: `科技资讯 - 基层科技`
- `source`:
  - `kjt.ah.gov.cn/kjzx/jckj/index.html`
  - `kjt.ah.gov.cn/kjzx/jckj/`
- `target`: `/kjt/kjzx/jckj`
### Rule 5
- `title`: `科技资讯 - 媒体聚焦`
- `source`:
  - `kjt.ah.gov.cn/kjzx/mtjj/index.html`
  - `kjt.ah.gov.cn/kjzx/mtjj/`
- `target`: `/kjt/kjzx/mtjj`
### Rule 6
- `title`: `科技资讯 - 重要转载`
- `source`:
  - `kjt.ah.gov.cn/kjzx/zyzz/index.html`
  - `kjt.ah.gov.cn/kjzx/zyzz/`
- `target`: `/kjt/kjzx/zyzz`
### Rule 7
- `title`: `科技资讯 - 图片视频`
- `source`:
  - `kjt.ah.gov.cn/kjzx/tpsp/index.html`
  - `kjt.ah.gov.cn/kjzx/tpsp/`
- `target`: `/kjt/kjzx/tpsp`
### Rule 8
- `title`: `科技统计 - 技术市场交易`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjtj/jsscjy/index.html`
  - `kjt.ah.gov.cn/kjzy/kjtj/jsscjy/`
- `target`: `/kjt/kjzy/kjtj/jsscjy`
### Rule 9
- `title`: `科技统计 - 科技成果公报`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjtj/kjcggb/index.html`
  - `kjt.ah.gov.cn/kjzy/kjtj/kjcggb/`
- `target`: `/kjt/kjzy/kjtj/kjcggb`
### Rule 10
- `title`: `科技统计 - 孵化载体发展`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/index.html`
  - `kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/`
- `target`: `/kjt/kjzy/kjtj/cyfhfz`
### Rule 11
- `title`: `科技数据 - 创新企业`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxqy/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxqy/`
- `target`: `/kjt/kjzy/kjsj/cxqy`
### Rule 12
- `title`: `科技数据 - 创新项目`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxxm/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxxm/`
- `target`: `/kjt/kjzy/kjsj/cxxm`
### Rule 13
- `title`: `科技数据 - 创新成果`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxcg/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxcg/`
- `target`: `/kjt/kjzy/kjsj/cxcg`
### Rule 14
- `title`: `科技数据 - 转化基金入库项目`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/`
- `target`: `/kjt/kjzy/kjsj/zhjjrkxm`
### Rule 15
- `title`: `科技数据 - 创新平台`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxpt/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxpt/`
- `target`: `/kjt/kjzy/kjsj/cxpt`
### Rule 16
- `title`: `科技数据 - 创新园区`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxyq/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxyq/`
- `target`: `/kjt/kjzy/kjsj/cxyq`
### Rule 17
- `title`: `科技数据 - 创新许可`
- `source`:
  - `kjt.ah.gov.cn/kjzy/kjsj/cxxk/index.html`
  - `kjt.ah.gov.cn/kjzy/kjsj/cxxk/`
- `target`: `/kjt/kjzy/kjsj/cxxk`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [通知公告](https://kjt.ah.gov.cn/kjzx/tzgg/)，网址为 `https://kjt.ah.gov.cn/kjzx/tzgg/`。将路径部分 `kjzx/tzgg` 作为分类参数填入，此时路由为 [`/gov/ah/kjt/kjzx/tzgg`](https://rsshub.app/gov/ah/kjt/kjzx/tzgg)。\n:::\n\n#### [科技资讯](https://kjt.ah.gov.cn/kjzx/index.html)\n\n| [通知公告](https://kjt.ah.gov.cn/kjzx/tzgg/index.html) | [工作动态](https://kjt.ah.gov.cn/kjzx/gzdt/index.html) | [基层科技](https://kjt.ah.gov.cn/kjzx/jckj/index.html) | [媒体聚焦](https://kjt.ah.gov.cn/kjzx/mtjj/index.html) |\n| ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ |\n| [kjzx/tzgg](https://rsshub.app/gov/ah/kjt/kjzx/tzgg)   | [kjzx/gzdt](https://rsshub.app/gov/ah/kjt/kjzx/gzdt)   | [kjzx/jckj](https://rsshub.app/gov/ah/kjt/kjzx/jckj)   | [kjzx/mtjj](https://rsshub.app/gov/ah/kjt/kjzx/mtjj)   |\n\n| [重要转载](https://kjt.ah.gov.cn/kjzx/zyzz/index.html) | [图片视频](https://kjt.ah.gov.cn/kjzx/tpsp/index.html) |\n| ------------------------------------------------------ | ------------------------------------------------------ |\n| [kjzx/zyzz](https://rsshub.app/gov/ah/kjt/kjzx/zyzz)   | [kjzx/tpsp](https://rsshub.app/gov/ah/kjt/kjzx/tpsp)   |\n\n#### [科技统计](https://kjt.ah.gov.cn/kjzy/kjtj/index.html)\n\n| [技术市场交易](https://kjt.ah.gov.cn/kjzy/kjtj/jsscjy/index.html)  | [科技成果公报](https://kjt.ah.gov.cn/kjzy/kjtj/kjcggb/index.html)  | [孵化载体发展](https://kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/index.html)  |\n| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |\n| [kjzy/kjtj/jsscjy](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/jsscjy) | [kjzy/kjtj/kjcggb](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/kjcggb) | [kjzy/kjtj/cyfhfz](https://rsshub.app/gov/ah/kjt/kjzy/kjtj/cyfhfz) |\n\n#### [科技数据](https://kjt.ah.gov.cn/kjzy/kjsj/index.html)\n\n| [创新企业](https://kjt.ah.gov.cn/kjzy/kjsj/cxqy/index.html)    | [创新项目](https://kjt.ah.gov.cn/kjzy/kjsj/cxxm/index.html)    | [创新成果](https://kjt.ah.gov.cn/kjzy/kjsj/cxcg/index.html)    | [转化基金入库项目](https://kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/index.html) |\n| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------- |\n| [kjzy/kjsj/cxqy](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxqy) | [kjzy/kjsj/cxxm](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxxm) | [kjzy/kjsj/cxcg](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxcg) | [kjzy/kjsj/zhjjrkxm](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/zhjjrkxm)  |\n\n| [创新平台](https://kjt.ah.gov.cn/kjzy/kjsj/cxpt/index.html)    | [创新园区](https://kjt.ah.gov.cn/kjzy/kjsj/cxyq/index.html)    | [创新许可](https://kjt.ah.gov.cn/kjzy/kjsj/cxxk/index.html)    |\n| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |\n| [kjzy/kjsj/cxpt](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxpt) | [kjzy/kjsj/cxyq](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxyq) | [kjzy/kjsj/cxxk](https://rsshub.app/gov/ah/kjt/kjzy/kjsj/cxxk) |",
  "example": "/gov/ah/kjt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "kjt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "科学技术厅",
  "parameters": {
    "category": "分类，默认为 `kjzx/tzgg`，即通知公告，可在对应分类页 URL 中找到"
  },
  "path": "/kjt/:category{.+}?",
  "radar": [
    {
      "source": [
        "kjt.ah.gov.cn/"
      ],
      "target": "/kjt"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/tzgg/index.html",
        "kjt.ah.gov.cn/kjzx/tzgg/"
      ],
      "target": "/kjt/kjzx/tzgg",
      "title": "科技资讯 - 通知公告"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/gzdt/index.html",
        "kjt.ah.gov.cn/kjzx/gzdt/"
      ],
      "target": "/kjt/kjzx/gzdt",
      "title": "科技资讯 - 工作动态"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/jckj/index.html",
        "kjt.ah.gov.cn/kjzx/jckj/"
      ],
      "target": "/kjt/kjzx/jckj",
      "title": "科技资讯 - 基层科技"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/mtjj/index.html",
        "kjt.ah.gov.cn/kjzx/mtjj/"
      ],
      "target": "/kjt/kjzx/mtjj",
      "title": "科技资讯 - 媒体聚焦"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/zyzz/index.html",
        "kjt.ah.gov.cn/kjzx/zyzz/"
      ],
      "target": "/kjt/kjzx/zyzz",
      "title": "科技资讯 - 重要转载"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzx/tpsp/index.html",
        "kjt.ah.gov.cn/kjzx/tpsp/"
      ],
      "target": "/kjt/kjzx/tpsp",
      "title": "科技资讯 - 图片视频"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjtj/jsscjy/index.html",
        "kjt.ah.gov.cn/kjzy/kjtj/jsscjy/"
      ],
      "target": "/kjt/kjzy/kjtj/jsscjy",
      "title": "科技统计 - 技术市场交易"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjtj/kjcggb/index.html",
        "kjt.ah.gov.cn/kjzy/kjtj/kjcggb/"
      ],
      "target": "/kjt/kjzy/kjtj/kjcggb",
      "title": "科技统计 - 科技成果公报"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/index.html",
        "kjt.ah.gov.cn/kjzy/kjtj/cyfhfz/"
      ],
      "target": "/kjt/kjzy/kjtj/cyfhfz",
      "title": "科技统计 - 孵化载体发展"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxqy/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxqy/"
      ],
      "target": "/kjt/kjzy/kjsj/cxqy",
      "title": "科技数据 - 创新企业"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxxm/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxxm/"
      ],
      "target": "/kjt/kjzy/kjsj/cxxm",
      "title": "科技数据 - 创新项目"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxcg/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxcg/"
      ],
      "target": "/kjt/kjzy/kjsj/cxcg",
      "title": "科技数据 - 创新成果"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/zhjjrkxm/"
      ],
      "target": "/kjt/kjzy/kjsj/zhjjrkxm",
      "title": "科技数据 - 转化基金入库项目"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxpt/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxpt/"
      ],
      "target": "/kjt/kjzy/kjsj/cxpt",
      "title": "科技数据 - 创新平台"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxyq/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxyq/"
      ],
      "target": "/kjt/kjzy/kjsj/cxyq",
      "title": "科技数据 - 创新园区"
    },
    {
      "source": [
        "kjt.ah.gov.cn/kjzy/kjsj/cxxk/index.html",
        "kjt.ah.gov.cn/kjzy/kjsj/cxxk/"
      ],
      "target": "/kjt/kjzy/kjsj/cxxk",
      "title": "科技数据 - 创新许可"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "kjt.ah.gov.cn"
}
```
