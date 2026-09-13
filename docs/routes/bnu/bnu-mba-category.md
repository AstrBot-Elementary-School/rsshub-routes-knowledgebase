# 北京师范大学 - 经济与工商管理学院MBA

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/mba/:category{.+}?`
- Route Name: `经济与工商管理学院MBA`
- Example: `/bnu/mba/xwdt`
- URL: `mba.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `mba.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [新闻聚焦](https://mba.bnu.edu.cn/xwdt/index.html)，网址为 `https://mba.bnu.edu.cn/xwdt/index.html`。截取 `https://mba.bnu.edu.cn/` 到末尾 `/index.html` 的部分 `xwdt` 作为参数填入，此时路由为 [`/bnu/mba/xwdt`](https://rsshub.app/bnu/mba/xwdt)。
:::

#### [主页](https://mba.bnu.edu.cn)

| [新闻聚焦](https://mba.bnu.edu.cn/xwdt/index.html) | [通知公告](https://mba.bnu.edu.cn/tzgg/index.html) | [MBA 系列讲座](https://mba.bnu.edu.cn/mbaxljz/index.html) |
| -------------------------------------------------- | -------------------------------------------------- | --------------------------------------------------------- |
| [xwdt](https://rsshub.app/bnu/mba/xwdt)            | [tzgg](https://rsshub.app/bnu/mba/tzgg)            | [mbaxljz](https://rsshub.app/bnu/mba/mbaxljz)             |

#### [招生动态](https://mba.bnu.edu.cn/zsdt/zsjz/index.html)

| [下载专区](https://mba.bnu.edu.cn/zsdt/cjwt/index.html) |
| ------------------------------------------------------- |
| [zsdt/cjwt](https://rsshub.app/bnu/mba/zsdt/cjwt)       |

#### [国际视野](https://mba.bnu.edu.cn/gjhz/hwjd/index.html)

| [海外基地](https://mba.bnu.edu.cn/gjhz/hwjd/index.html) | [学位合作](https://mba.bnu.edu.cn/gjhz/xwhz/index.html) | [长期交换](https://mba.bnu.edu.cn/gjhz/zqjh/index.html) | [短期项目](https://mba.bnu.edu.cn/gjhz/dqxm/index.html) |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| [gjhz/hwjd](https://rsshub.app/bnu/mba/gjhz/hwjd)       | [gjhz/xwhz](https://rsshub.app/bnu/mba/gjhz/xwhz)       | [gjhz/zqjh](https://rsshub.app/bnu/mba/gjhz/zqjh)       | [gjhz/dqxm](https://rsshub.app/bnu/mba/gjhz/dqxm)       |

#### [校园生活](https://mba.bnu.edu.cn/xysh/xszz/index.html)

| [学生组织](https://mba.bnu.edu.cn/xysh/xszz/index.html) |
| ------------------------------------------------------- |
| [xysh/xszz](https://rsshub.app/bnu/mba/xysh/xszz)       |

#### [职业发展](https://mba.bnu.edu.cn/zyfz/xwds/index.html)

| [校外导师](https://mba.bnu.edu.cn/zyfz/xwds/index.html) | [企业实践](https://mba.bnu.edu.cn/zyfz/zycp/index.html) | [就业创业](https://mba.bnu.edu.cn/zyfz/jycy/index.html) |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| [zyfz/xwds](https://rsshub.app/bnu/mba/zyfz/xwds)       | [zyfz/zycp](https://rsshub.app/bnu/mba/zyfz/zycp)       | [zyfz/jycy](https://rsshub.app/bnu/mba/zyfz/jycy)       |

## Parameters
- `category`: 分类，默认为 xwdt，即新闻聚焦


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
  - `mba.bnu.edu.cn/:category?`
### Rule 2
- `title`: `新闻聚焦`
- `source`:
  - `mba.bnu.edu.cn/xwdt/index.html`
- `target`: `/mba/xwdt`
### Rule 3
- `title`: `通知公告`
- `source`:
  - `mba.bnu.edu.cn/tzgg/index.html`
- `target`: `/mba/tzgg`
### Rule 4
- `title`: `MBA系列讲座`
- `source`:
  - `mba.bnu.edu.cn/mbaxljz/index.html`
- `target`: `/mba/mbaxljz`
### Rule 5
- `title`: `招生动态 - 下载专区`
- `source`:
  - `mba.bnu.edu.cn/zsdt/cjwt/index.html`
- `target`: `/mba/zsdt/cjwt`
### Rule 6
- `title`: `国际视野 - 海外基地`
- `source`:
  - `mba.bnu.edu.cn/gjhz/hwjd/index.html`
- `target`: `/mba/gjhz/hwjd`
### Rule 7
- `title`: `国际视野 - 学位合作`
- `source`:
  - `mba.bnu.edu.cn/gjhz/xwhz/index.html`
- `target`: `/mba/gjhz/xwhz`
### Rule 8
- `title`: `国际视野 - 长期交换`
- `source`:
  - `mba.bnu.edu.cn/gjhz/zqjh/index.html`
- `target`: `/mba/gjhz/zqjh`
### Rule 9
- `title`: `国际视野 - 短期项目`
- `source`:
  - `mba.bnu.edu.cn/gjhz/dqxm/index.html`
- `target`: `/mba/gjhz/dqxm`
### Rule 10
- `title`: `校园生活 - 学生组织`
- `source`:
  - `mba.bnu.edu.cn/xysh/xszz/index.html`
- `target`: `/mba/xysh/xszz`
### Rule 11
- `title`: `职业发展 - 校外导师`
- `source`:
  - `mba.bnu.edu.cn/zyfz/xwds/index.html`
- `target`: `/mba/zyfz/xwds`
### Rule 12
- `title`: `职业发展 - 企业实践`
- `source`:
  - `mba.bnu.edu.cn/zyfz/zycp/index.html`
- `target`: `/mba/zyfz/zycp`
### Rule 13
- `title`: `职业发展 - 就业创业`
- `source`:
  - `mba.bnu.edu.cn/zyfz/jycy/index.html`
- `target`: `/mba/zyfz/jycy`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [新闻聚焦](https://mba.bnu.edu.cn/xwdt/index.html)，网址为 `https://mba.bnu.edu.cn/xwdt/index.html`。截取 `https://mba.bnu.edu.cn/` 到末尾 `/index.html` 的部分 `xwdt` 作为参数填入，此时路由为 [`/bnu/mba/xwdt`](https://rsshub.app/bnu/mba/xwdt)。\n:::\n\n#### [主页](https://mba.bnu.edu.cn)\n\n| [新闻聚焦](https://mba.bnu.edu.cn/xwdt/index.html) | [通知公告](https://mba.bnu.edu.cn/tzgg/index.html) | [MBA 系列讲座](https://mba.bnu.edu.cn/mbaxljz/index.html) |\n| -------------------------------------------------- | -------------------------------------------------- | --------------------------------------------------------- |\n| [xwdt](https://rsshub.app/bnu/mba/xwdt)            | [tzgg](https://rsshub.app/bnu/mba/tzgg)            | [mbaxljz](https://rsshub.app/bnu/mba/mbaxljz)             |\n\n#### [招生动态](https://mba.bnu.edu.cn/zsdt/zsjz/index.html)\n\n| [下载专区](https://mba.bnu.edu.cn/zsdt/cjwt/index.html) |\n| ------------------------------------------------------- |\n| [zsdt/cjwt](https://rsshub.app/bnu/mba/zsdt/cjwt)       |\n\n#### [国际视野](https://mba.bnu.edu.cn/gjhz/hwjd/index.html)\n\n| [海外基地](https://mba.bnu.edu.cn/gjhz/hwjd/index.html) | [学位合作](https://mba.bnu.edu.cn/gjhz/xwhz/index.html) | [长期交换](https://mba.bnu.edu.cn/gjhz/zqjh/index.html) | [短期项目](https://mba.bnu.edu.cn/gjhz/dqxm/index.html) |\n| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |\n| [gjhz/hwjd](https://rsshub.app/bnu/mba/gjhz/hwjd)       | [gjhz/xwhz](https://rsshub.app/bnu/mba/gjhz/xwhz)       | [gjhz/zqjh](https://rsshub.app/bnu/mba/gjhz/zqjh)       | [gjhz/dqxm](https://rsshub.app/bnu/mba/gjhz/dqxm)       |\n\n#### [校园生活](https://mba.bnu.edu.cn/xysh/xszz/index.html)\n\n| [学生组织](https://mba.bnu.edu.cn/xysh/xszz/index.html) |\n| ------------------------------------------------------- |\n| [xysh/xszz](https://rsshub.app/bnu/mba/xysh/xszz)       |\n\n#### [职业发展](https://mba.bnu.edu.cn/zyfz/xwds/index.html)\n\n| [校外导师](https://mba.bnu.edu.cn/zyfz/xwds/index.html) | [企业实践](https://mba.bnu.edu.cn/zyfz/zycp/index.html) | [就业创业](https://mba.bnu.edu.cn/zyfz/jycy/index.html) |\n| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |\n| [zyfz/xwds](https://rsshub.app/bnu/mba/zyfz/xwds)       | [zyfz/zycp](https://rsshub.app/bnu/mba/zyfz/zycp)       | [zyfz/jycy](https://rsshub.app/bnu/mba/zyfz/jycy)       |",
  "example": "/bnu/mba/xwdt",
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
  "location": "mba.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "经济与工商管理学院MBA",
  "parameters": {
    "category": "分类，默认为 xwdt，即新闻聚焦"
  },
  "path": "/mba/:category{.+}?",
  "radar": [
    {
      "source": [
        "mba.bnu.edu.cn/:category?"
      ]
    },
    {
      "source": [
        "mba.bnu.edu.cn/xwdt/index.html"
      ],
      "target": "/mba/xwdt",
      "title": "新闻聚焦"
    },
    {
      "source": [
        "mba.bnu.edu.cn/tzgg/index.html"
      ],
      "target": "/mba/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "mba.bnu.edu.cn/mbaxljz/index.html"
      ],
      "target": "/mba/mbaxljz",
      "title": "MBA系列讲座"
    },
    {
      "source": [
        "mba.bnu.edu.cn/zsdt/cjwt/index.html"
      ],
      "target": "/mba/zsdt/cjwt",
      "title": "招生动态 - 下载专区"
    },
    {
      "source": [
        "mba.bnu.edu.cn/gjhz/hwjd/index.html"
      ],
      "target": "/mba/gjhz/hwjd",
      "title": "国际视野 - 海外基地"
    },
    {
      "source": [
        "mba.bnu.edu.cn/gjhz/xwhz/index.html"
      ],
      "target": "/mba/gjhz/xwhz",
      "title": "国际视野 - 学位合作"
    },
    {
      "source": [
        "mba.bnu.edu.cn/gjhz/zqjh/index.html"
      ],
      "target": "/mba/gjhz/zqjh",
      "title": "国际视野 - 长期交换"
    },
    {
      "source": [
        "mba.bnu.edu.cn/gjhz/dqxm/index.html"
      ],
      "target": "/mba/gjhz/dqxm",
      "title": "国际视野 - 短期项目"
    },
    {
      "source": [
        "mba.bnu.edu.cn/xysh/xszz/index.html"
      ],
      "target": "/mba/xysh/xszz",
      "title": "校园生活 - 学生组织"
    },
    {
      "source": [
        "mba.bnu.edu.cn/zyfz/xwds/index.html"
      ],
      "target": "/mba/zyfz/xwds",
      "title": "职业发展 - 校外导师"
    },
    {
      "source": [
        "mba.bnu.edu.cn/zyfz/zycp/index.html"
      ],
      "target": "/mba/zyfz/zycp",
      "title": "职业发展 - 企业实践"
    },
    {
      "source": [
        "mba.bnu.edu.cn/zyfz/jycy/index.html"
      ],
      "target": "/mba/zyfz/jycy",
      "title": "职业发展 - 就业创业"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "mba.bnu.edu.cn"
}
```
