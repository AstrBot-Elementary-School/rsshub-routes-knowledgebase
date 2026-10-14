# 中国五矿化工进出口商会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `cccmc`
- Namespace Name: `中国五矿化工进出口商会`
- Route Path: `/cccmc/:category{.+}?`
- Route Name: `通用`
- Example: `/cccmc/ywgg/tzgg`
- URL: `www.cccmc.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [综合政策](https://www.cccmc.org.cn/zcfg/zhzc/)，网址为 `https://www.cccmc.org.cn/zcfg/zhzc/`，请截取 `https://www.cccmc.org.cn/` 到末尾的部分 `zcfg/zhzc` 作为 `category` 参数填入，此时目标路由为 [`/cccmc/zcfg/zhzc`](https://rsshub.app/cccmc/zcfg/zhzc)。
:::

<details>
<summary>更多分类</summary>

#### [会员之家](https://www.cccmc.org.cn/hyzj)

| [会员之声](https://www.cccmc.org.cn/hyzj/hyzs/) | [会员动态](https://www.cccmc.org.cn/hyzj/hydt/) | [会员推介](https://www.cccmc.org.cn/hyzj/hytj/) |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| [hyzj/hyzs](https://rsshub.app/cccmc/hyzj/hyzs) | [hyzj/hydt](https://rsshub.app/cccmc/hyzj/hydt) | [hyzj/hytj](https://rsshub.app/cccmc/hyzj/hytj) |

#### [政策法规](https://www.cccmc.org.cn/zcfg)

| [综合政策](https://www.cccmc.org.cn/zcfg/zhzc/) | [国内贸易](https://www.cccmc.org.cn/zcfg/gnmy/) | [对外贸易](https://www.cccmc.org.cn/zcfg/dwmy/) | [投资合作](https://www.cccmc.org.cn/zcfg/tzhz/) |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| [zcfg/zhzc](https://rsshub.app/cccmc/zcfg/zhzc) | [zcfg/gnmy](https://rsshub.app/cccmc/zcfg/gnmy) | [zcfg/dwmy](https://rsshub.app/cccmc/zcfg/dwmy) | [zcfg/tzhz](https://rsshub.app/cccmc/zcfg/tzhz) |

#### [行业资讯](https://www.cccmc.org.cn/hyzx)

| [统计分析](https://www.cccmc.org.cn/hyzx/tjfx/) | [石油化工](https://www.cccmc.org.cn/hyzx/syhg/) | [金属矿产](https://www.cccmc.org.cn/hyzx/jskc/) | [五金建材](https://www.cccmc.org.cn/hyzx/wjjc/) |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| [hyzx/tjfx](https://rsshub.app/cccmc/hyzx/tjfx) | [hyzx/syhg](https://rsshub.app/cccmc/hyzx/syhg) | [hyzx/jskc](https://rsshub.app/cccmc/hyzx/jskc) | [hyzx/wjjc](https://rsshub.app/cccmc/hyzx/wjjc) |

#### [商业机会](https://www.cccmc.org.cn/syjh/)+

| [供应信息](https://www.cccmc.org.cn/syjh/gyxx/) | [需求信息](https://www.cccmc.org.cn/syjh/xqxx/) | [合作信息](https://www.cccmc.org.cn/syjh/hzxx/) |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| [syjh/gyxx](https://rsshub.app/cccmc/syjh/gyxx) | [syjh/xqxx](https://rsshub.app/cccmc/syjh/xqxx) | [syjh/hzxx](https://rsshub.app/cccmc/syjh/hzxx) |

#### [商会党建](https://www.cccmc.org.cn/shdj)

| [党群动态](https://www.cccmc.org.cn/shdj/dqdt/) | [党内法规](https://www.cccmc.org.cn/shdj/dnfg/) | [青年工作](https://www.cccmc.org.cn/shdj/qngz/) |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| [shdj/dqdt](https://rsshub.app/cccmc/shdj/dqdt) | [shdj/dnfg](https://rsshub.app/cccmc/shdj/dnfg) | [shdj/qngz](https://rsshub.app/cccmc/shdj/qngz) |

</details>

## Parameters
- `category`: 分类，默认为 `ywgg/tzgg`，即通知公告，可在对应分类页 URL 中找到, Category, `ywgg/tzgg`，即通知公告  by default


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
  - `www.cccmc.org.cn/`
  - `www.cccmc.org.cn/ywgg/tzgg/`
- `target`: `/ywgg/tzgg`
### Rule 2
- `title`: `商业机会 - 供应信息`
- `source`:
  - `www.cccmc.org.cn/syjh/gyxx/`
- `target`: `/syjh/gyxx`
### Rule 3
- `title`: `商业机会 - 需求信息`
- `source`:
  - `www.cccmc.org.cn/syjh/xqxx/`
- `target`: `/syjh/xqxx`
### Rule 4
- `title`: `商业机会 - 合作信息`
- `source`:
  - `www.cccmc.org.cn/syjh/hzxx/`
- `target`: `/syjh/hzxx`
### Rule 5
- `title`: `商会党建 - 党群动态`
- `source`:
  - `www.cccmc.org.cn/shdj/dqdt/`
- `target`: `/shdj/dqdt`
### Rule 6
- `title`: `商会党建 - 党内法规`
- `source`:
  - `www.cccmc.org.cn/shdj/dnfg/`
- `target`: `/shdj/dnfg`
### Rule 7
- `title`: `商会党建 - 青年工作`
- `source`:
  - `www.cccmc.org.cn/shdj/qngz/`
- `target`: `/shdj/qngz`
### Rule 8
- `title`: `行业资讯 - 统计分析`
- `source`:
  - `www.cccmc.org.cn/hyzx/tjfx/`
- `target`: `/hyzx/tjfx`
### Rule 9
- `title`: `行业资讯 - 石油化工`
- `source`:
  - `www.cccmc.org.cn/hyzx/syhg/`
- `target`: `/hyzx/syhg`
### Rule 10
- `title`: `行业资讯 - 金属矿产`
- `source`:
  - `www.cccmc.org.cn/hyzx/jskc/`
- `target`: `/hyzx/jskc`
### Rule 11
- `title`: `行业资讯 - 五金建材`
- `source`:
  - `www.cccmc.org.cn/hyzx/wjjc/`
- `target`: `/hyzx/wjjc`
### Rule 12
- `title`: `会员之家 - 会员之声`
- `source`:
  - `www.cccmc.org.cn/hyzj/hyzs/`
- `target`: `/hyzj/hyzs`
### Rule 13
- `title`: `会员之家 - 会员动态`
- `source`:
  - `www.cccmc.org.cn/hyzj/hydt/`
- `target`: `/hyzj/hydt`
### Rule 14
- `title`: `会员之家 - 会员推介`
- `source`:
  - `www.cccmc.org.cn/hyzj/hytj/`
- `target`: `/hyzj/hytj`
### Rule 15
- `title`: `政策法规 - 综合政策`
- `source`:
  - `www.cccmc.org.cn/zcfg/zhzc/`
- `target`: `/zcfg/zhzc`
### Rule 16
- `title`: `政策法规 - 国内贸易`
- `source`:
  - `www.cccmc.org.cn/zcfg/gnmy/`
- `target`: `/zcfg/gnmy`
### Rule 17
- `title`: `政策法规 - 对外贸易`
- `source`:
  - `www.cccmc.org.cn/zcfg/dwmy/`
- `target`: `/zcfg/dwmy`
### Rule 18
- `title`: `政策法规 - 投资合作`
- `source`:
  - `www.cccmc.org.cn/zcfg/tzhz/`
- `target`: `/zcfg/tzhz`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [综合政策](https://www.cccmc.org.cn/zcfg/zhzc/)，网址为 `https://www.cccmc.org.cn/zcfg/zhzc/`，请截取 `https://www.cccmc.org.cn/` 到末尾的部分 `zcfg/zhzc` 作为 `category` 参数填入，此时目标路由为 [`/cccmc/zcfg/zhzc`](https://rsshub.app/cccmc/zcfg/zhzc)。\n:::\n\n<details>\n<summary>更多分类</summary>\n\n#### [会员之家](https://www.cccmc.org.cn/hyzj)\n\n| [会员之声](https://www.cccmc.org.cn/hyzj/hyzs/) | [会员动态](https://www.cccmc.org.cn/hyzj/hydt/) | [会员推介](https://www.cccmc.org.cn/hyzj/hytj/) |\n| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |\n| [hyzj/hyzs](https://rsshub.app/cccmc/hyzj/hyzs) | [hyzj/hydt](https://rsshub.app/cccmc/hyzj/hydt) | [hyzj/hytj](https://rsshub.app/cccmc/hyzj/hytj) |\n\n#### [政策法规](https://www.cccmc.org.cn/zcfg)\n\n| [综合政策](https://www.cccmc.org.cn/zcfg/zhzc/) | [国内贸易](https://www.cccmc.org.cn/zcfg/gnmy/) | [对外贸易](https://www.cccmc.org.cn/zcfg/dwmy/) | [投资合作](https://www.cccmc.org.cn/zcfg/tzhz/) |\n| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |\n| [zcfg/zhzc](https://rsshub.app/cccmc/zcfg/zhzc) | [zcfg/gnmy](https://rsshub.app/cccmc/zcfg/gnmy) | [zcfg/dwmy](https://rsshub.app/cccmc/zcfg/dwmy) | [zcfg/tzhz](https://rsshub.app/cccmc/zcfg/tzhz) |\n\n#### [行业资讯](https://www.cccmc.org.cn/hyzx)\n\n| [统计分析](https://www.cccmc.org.cn/hyzx/tjfx/) | [石油化工](https://www.cccmc.org.cn/hyzx/syhg/) | [金属矿产](https://www.cccmc.org.cn/hyzx/jskc/) | [五金建材](https://www.cccmc.org.cn/hyzx/wjjc/) |\n| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |\n| [hyzx/tjfx](https://rsshub.app/cccmc/hyzx/tjfx) | [hyzx/syhg](https://rsshub.app/cccmc/hyzx/syhg) | [hyzx/jskc](https://rsshub.app/cccmc/hyzx/jskc) | [hyzx/wjjc](https://rsshub.app/cccmc/hyzx/wjjc) |\n\n#### [商业机会](https://www.cccmc.org.cn/syjh/)+\n\n| [供应信息](https://www.cccmc.org.cn/syjh/gyxx/) | [需求信息](https://www.cccmc.org.cn/syjh/xqxx/) | [合作信息](https://www.cccmc.org.cn/syjh/hzxx/) |\n| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |\n| [syjh/gyxx](https://rsshub.app/cccmc/syjh/gyxx) | [syjh/xqxx](https://rsshub.app/cccmc/syjh/xqxx) | [syjh/hzxx](https://rsshub.app/cccmc/syjh/hzxx) |\n\n#### [商会党建](https://www.cccmc.org.cn/shdj)\n\n| [党群动态](https://www.cccmc.org.cn/shdj/dqdt/) | [党内法规](https://www.cccmc.org.cn/shdj/dnfg/) | [青年工作](https://www.cccmc.org.cn/shdj/qngz/) |\n| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |\n| [shdj/dqdt](https://rsshub.app/cccmc/shdj/dqdt) | [shdj/dnfg](https://rsshub.app/cccmc/shdj/dnfg) | [shdj/qngz](https://rsshub.app/cccmc/shdj/qngz) |\n\n</details>",
  "example": "/cccmc/ywgg/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "category": "分类，默认为 `ywgg/tzgg`，即通知公告，可在对应分类页 URL 中找到, Category, `ywgg/tzgg`，即通知公告  by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.cccmc.org.cn/",
        "www.cccmc.org.cn/ywgg/tzgg/"
      ],
      "target": "/ywgg/tzgg"
    },
    {
      "source": [
        "www.cccmc.org.cn/syjh/gyxx/"
      ],
      "target": "/syjh/gyxx",
      "title": "商业机会 - 供应信息"
    },
    {
      "source": [
        "www.cccmc.org.cn/syjh/xqxx/"
      ],
      "target": "/syjh/xqxx",
      "title": "商业机会 - 需求信息"
    },
    {
      "source": [
        "www.cccmc.org.cn/syjh/hzxx/"
      ],
      "target": "/syjh/hzxx",
      "title": "商业机会 - 合作信息"
    },
    {
      "source": [
        "www.cccmc.org.cn/shdj/dqdt/"
      ],
      "target": "/shdj/dqdt",
      "title": "商会党建 - 党群动态"
    },
    {
      "source": [
        "www.cccmc.org.cn/shdj/dnfg/"
      ],
      "target": "/shdj/dnfg",
      "title": "商会党建 - 党内法规"
    },
    {
      "source": [
        "www.cccmc.org.cn/shdj/qngz/"
      ],
      "target": "/shdj/qngz",
      "title": "商会党建 - 青年工作"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzx/tjfx/"
      ],
      "target": "/hyzx/tjfx",
      "title": "行业资讯 - 统计分析"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzx/syhg/"
      ],
      "target": "/hyzx/syhg",
      "title": "行业资讯 - 石油化工"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzx/jskc/"
      ],
      "target": "/hyzx/jskc",
      "title": "行业资讯 - 金属矿产"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzx/wjjc/"
      ],
      "target": "/hyzx/wjjc",
      "title": "行业资讯 - 五金建材"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzj/hyzs/"
      ],
      "target": "/hyzj/hyzs",
      "title": "会员之家 - 会员之声"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzj/hydt/"
      ],
      "target": "/hyzj/hydt",
      "title": "会员之家 - 会员动态"
    },
    {
      "source": [
        "www.cccmc.org.cn/hyzj/hytj/"
      ],
      "target": "/hyzj/hytj",
      "title": "会员之家 - 会员推介"
    },
    {
      "source": [
        "www.cccmc.org.cn/zcfg/zhzc/"
      ],
      "target": "/zcfg/zhzc",
      "title": "政策法规 - 综合政策"
    },
    {
      "source": [
        "www.cccmc.org.cn/zcfg/gnmy/"
      ],
      "target": "/zcfg/gnmy",
      "title": "政策法规 - 国内贸易"
    },
    {
      "source": [
        "www.cccmc.org.cn/zcfg/dwmy/"
      ],
      "target": "/zcfg/dwmy",
      "title": "政策法规 - 对外贸易"
    },
    {
      "source": [
        "www.cccmc.org.cn/zcfg/tzhz/"
      ],
      "target": "/zcfg/tzhz",
      "title": "政策法规 - 投资合作"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "200757829221265408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cccmc.org.cn/ywgg/tzgg/",
      "title": "通知公告 - 中国五矿化工进出口商会",
      "type": "feed",
      "url": "rsshub://cccmc"
    }
  ],
  "url": "www.cccmc.org.cn",
  "view": 0
}
```
