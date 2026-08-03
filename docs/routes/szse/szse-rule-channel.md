# 深圳证券交易所 - 本所业务规则

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/szse/rule/:channel{.+}?`
- Route Name: `本所业务规则`
- Example: `/szse/rule/allrules/bussiness`
- URL: `www.szse.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `rule.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [综合类](https://www.szse.cn/www/lawrules/rule/all/index.html)，网址为 `https://www.szse.cn/www/lawrules/rule/all/index.html`。截取 `https://www.szse.cn/www/lawrules/rule/` 到末尾 `/index.html` 的部分 `all` 作为参数填入，此时路由为 [`/szse/rule/all`](https://rsshub.app/szse/rule/all)。
:::

| 频道                                                                        | ID                                                    |
| --------------------------------------------------------------------------- | ----------------------------------------------------- |
| [综合类](https://www.szse.cn/www/lawrules/rule/all/index.html)              | [all](https://rsshub.app/szes/rule/all)               |
| [基础设施 REITs 类](https://www.szse.cn/www/lawrules/rule/reits/index.html) | [reits](https://rsshub.app/szes/rule/reits)           |
| [衍生品类](https://www.szse.cn/www/lawrules/rule/derivative/index.html)     | [derivative](https://rsshub.app/szes/rule/derivative) |
| [会员管理类](https://www.szse.cn/www/lawrules/rule/memberty/index.html)     | [memberty](https://rsshub.app/szes/rule/memberty)     |
| [纪律处分与内部救济类](https://www.szse.cn/www/lawrules/rule/pr/index.html) | [pr](https://rsshub.app/szes/rule/pr)                 |

#### 股票类

| 频道                                                                                     | ID                                                                                    |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [发行上市审核](https://www.szse.cn/www/lawrules/rule/stock/audit/index.html)             | [stock/audit](https://rsshub.app/szes/rule/stock/audit)                               |
| [发行承销](https://www.szse.cn/www/lawrules/rule/stock/issue/index.html)                 | [stock/issue](https://rsshub.app/szes/rule/stock/issue)                               |
| [通用](https://www.szse.cn/www/lawrules/rule/stock/supervision/currency/index.html)      | [stock/supervision/currency](https://rsshub.app/szes/rule/stock/supervision/currency) |
| [主板专用](https://www.szse.cn/www/lawrules/rule/stock/supervision/mb/index.html)        | [stock/supervision/mb](https://rsshub.app/szes/rule/stock/supervision/mb)             |
| [创业板专用](https://www.szse.cn/www/lawrules/rule/stock/supervision/chinext/index.html) | [stock/supervision/chinext](https://rsshub.app/szes/rule/stock/supervision/chinext)   |
| [交易](https://www.szse.cn/www/lawrules/rule/stock/trade/index.html)                     | [stock/trade](https://rsshub.app/szes/rule/stock/trade)                               |

#### 固收类

| 频道                                                                                 | ID                                                                            |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
| [发行上市（挂牌）](https://www.szse.cn/www/lawrules/rule/bond/bonds/list/index.html) | [bond/bonds/list](https://rsshub.app/szes/rule/bond/bonds/list)               |
| [持续监管](https://www.szse.cn/www/lawrules/rule/bond/bonds/supervision/index.html)  | [bond/bonds/supervision](https://rsshub.app/szes/rule/bond/bonds/supervision) |
| [交易](https://www.szse.cn/www/lawrules/rule/bond/bonds/trade/index.html)            | [bond/bonds/trade](https://rsshub.app/szes/rule/bond/bonds/trade)             |
| [资产支持证券](https://www.szse.cn/www/lawrules/rule/bond/abs/index.html)            | [bond/abs](https://rsshub.app/szes/rule/bond/abs)                             |

#### 基金类

| 频道                                                                | ID                                                    |
| ------------------------------------------------------------------- | ----------------------------------------------------- |
| [上市](https://www.szse.cn/www/lawrules/rule/fund/list/index.html)  | [fund/list](https://rsshub.app/szes/rule/fund/list)   |
| [交易](https://www.szse.cn/www/lawrules/rule/fund/trade/index.html) | [fund/trade](https://rsshub.app/szes/rule/fund/trade) |

#### 交易类

| 频道                                                                                     | ID                                                                                    |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [通用](https://www.szse.cn/www/lawrules/rule/trade/current/index.html)                   | [trade/current](https://rsshub.app/szes/rule/trade/current)                           |
| [融资融券](https://www.szse.cn/www/lawrules/rule/trade/business/margin/index.html)       | [trade/business/margin](https://rsshub.app/szes/rule/trade/business/margin)           |
| [转融通](https://www.szse.cn/www/lawrules/rule/trade/business/refinancing/index.html)    | [trade/business/refinancing](https://rsshub.app/szes/rule/trade/business/refinancing) |
| [股票质押式回购](https://www.szse.cn/www/lawrules/rule/trade/business/pledge/index.html) | [trade/business/pledge](https://rsshub.app/szes/rule/trade/business/pledge)           |
| [质押式报价回购](https://www.szse.cn/www/lawrules/rule/trade/business/price/index.html)  | [trade/business/price](https://rsshub.app/szes/rule/trade/business/price)             |
| [约定购回](https://www.szse.cn/www/lawrules/rule/trade/business/promise/index.html)      | [trade/business/promise](https://rsshub.app/szes/rule/trade/business/promise)         |
| [协议转让](https://www.szse.cn/www/lawrules/rule/trade/business/transfer/index.html)     | [trade/business/transfer](https://rsshub.app/szes/rule/trade/business/transfer)       |
| [其他](https://www.szse.cn/www/lawrules/rule/trade/business/oth/index.html)              | [trade/business/oth](https://rsshub.app/szes/rule/trade/business/oth)                 |

#### 跨境创新类

| 频道                                                                          | ID                                                    |
| ----------------------------------------------------------------------------- | ----------------------------------------------------- |
| [深港通](https://www.szse.cn/www/lawrules/rule/inno/szhk/index.html)          | [inno/szhk](https://rsshub.app/szes/rule/inno/szhk)   |
| [试点创新企业](https://www.szse.cn/www/lawrules/rule/inno/pilot/index.html)   | [inno/pilot](https://rsshub.app/szes/rule/inno/pilot) |
| [H 股全流通](https://www.szse.cn/www/lawrules/rule/inno/hc/index.html)        | [inno/hc](https://rsshub.app/szes/rule/inno/hc)       |
| [互联互通存托凭证](https://www.szse.cn/www/lawrules/rule/inno/gdr/index.html) | [inno/gdr](https://rsshub.app/szes/rule/inno/gdr)     |

#### 全部规则

| 频道                                                                                | ID                                                                    |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [全部业务规则](https://www.szse.cn/www/lawrules/rule/allrules/bussiness/index.html) | [allrules/bussiness](https://rsshub.app/szes/rule/allrules/bussiness) |
| [规则汇编下载](https://www.szse.cn/www/lawrules/rule/allrules/rulejoin/index.html)  | [allrules/rulejoin](https://rsshub.app/szes/rule/allrules/rulejoin)   |

#### 已废止规则

| 频道                                                                                 | ID                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| [规则废止公告](https://www.szse.cn/www/lawrules/rule/repeal/announcement/index.html) | [repeal/announcement](https://rsshub.app/szes/rule/repeal/announcement) |
| [已废止规则文本](https://www.szse.cn/www/lawrules/rule/repeal/rules/index.html)      | [repeal/rules](https://rsshub.app/szes/rule/repeal/rules)               |

## Parameters
- `channel`: 频道，默认为 `allrules/bussiness`，即全部业务规则，可在对应频道页 URL 中找到


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
  - `www.szse.cn/www/lawrules/rule/:category`
### Rule 2
- `title`: `综合类`
- `source`:
  - `www.szse.cn/www/lawrules/rule/all/index.html`
- `target`: `/rule/all`
### Rule 3
- `title`: `基础设施REITs类`
- `source`:
  - `www.szse.cn/www/lawrules/rule/reits/index.html`
- `target`: `/rule/reits`
### Rule 4
- `title`: `衍生品类`
- `source`:
  - `www.szse.cn/www/lawrules/rule/derivative/index.html`
- `target`: `/rule/derivative`
### Rule 5
- `title`: `会员管理类`
- `source`:
  - `www.szse.cn/www/lawrules/rule/memberty/index.html`
- `target`: `/rule/memberty`
### Rule 6
- `title`: `纪律处分与内部救济类`
- `source`:
  - `www.szse.cn/www/lawrules/rule/pr/index.html`
- `target`: `/rule/pr`
### Rule 7
- `title`: `股票类 - 发行上市审核`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/audit/index.html`
- `target`: `/rule/stock/audit`
### Rule 8
- `title`: `股票类 - 发行承销`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/issue/index.html`
- `target`: `/rule/stock/issue`
### Rule 9
- `title`: `股票类 - 通用`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/supervision/currency/index.html`
- `target`: `/rule/stock/supervision/currency`
### Rule 10
- `title`: `股票类 - 主板专用`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/supervision/mb/index.html`
- `target`: `/rule/stock/supervision/mb`
### Rule 11
- `title`: `股票类 - 创业板专用`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/supervision/chinext/index.html`
- `target`: `/rule/stock/supervision/chinext`
### Rule 12
- `title`: `股票类 - 交易`
- `source`:
  - `www.szse.cn/www/lawrules/rule/stock/trade/index.html`
- `target`: `/rule/stock/trade`
### Rule 13
- `title`: `固收类 - 发行上市（挂牌）`
- `source`:
  - `www.szse.cn/www/lawrules/rule/bond/bonds/list/index.html`
- `target`: `/rule/bond/bonds/list`
### Rule 14
- `title`: `固收类 - 持续监管`
- `source`:
  - `www.szse.cn/www/lawrules/rule/bond/bonds/supervision/index.html`
- `target`: `/rule/bond/bonds/supervision`
### Rule 15
- `title`: `固收类 - 交易`
- `source`:
  - `www.szse.cn/www/lawrules/rule/bond/bonds/trade/index.html`
- `target`: `/rule/bond/bonds/trade`
### Rule 16
- `title`: `固收类 - 资产支持证券`
- `source`:
  - `www.szse.cn/www/lawrules/rule/bond/abs/index.html`
- `target`: `/rule/bond/abs`
### Rule 17
- `title`: `基金类 - 上市`
- `source`:
  - `www.szse.cn/www/lawrules/rule/fund/list/index.html`
- `target`: `/rule/fund/list`
### Rule 18
- `title`: `基金类 - 交易`
- `source`:
  - `www.szse.cn/www/lawrules/rule/fund/trade/index.html`
- `target`: `/rule/fund/trade`
### Rule 19
- `title`: `交易类 - 通用`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/current/index.html`
- `target`: `/rule/trade/current`
### Rule 20
- `title`: `交易类 - 融资融券`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/margin/index.html`
- `target`: `/rule/trade/business/margin`
### Rule 21
- `title`: `交易类 - 转融通`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/refinancing/index.html`
- `target`: `/rule/trade/business/refinancing`
### Rule 22
- `title`: `交易类 - 股票质押式回购`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/pledge/index.html`
- `target`: `/rule/trade/business/pledge`
### Rule 23
- `title`: `交易类 - 质押式报价回购`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/price/index.html`
- `target`: `/rule/trade/business/price`
### Rule 24
- `title`: `交易类 - 约定购回`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/promise/index.html`
- `target`: `/rule/trade/business/promise`
### Rule 25
- `title`: `交易类 - 协议转让`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/transfer/index.html`
- `target`: `/rule/trade/business/transfer`
### Rule 26
- `title`: `交易类 - 其他`
- `source`:
  - `www.szse.cn/www/lawrules/rule/trade/business/oth/index.html`
- `target`: `/rule/trade/business/oth`
### Rule 27
- `title`: `跨境创新类 - 深港通`
- `source`:
  - `www.szse.cn/www/lawrules/rule/inno/szhk/index.html`
- `target`: `/rule/inno/szhk`
### Rule 28
- `title`: `跨境创新类 - 试点创新企业`
- `source`:
  - `www.szse.cn/www/lawrules/rule/inno/pilot/index.html`
- `target`: `/rule/inno/pilot`
### Rule 29
- `title`: `跨境创新类 - H股全流通`
- `source`:
  - `www.szse.cn/www/lawrules/rule/inno/hc/index.html`
- `target`: `/rule/inno/hc`
### Rule 30
- `title`: `跨境创新类 - 互联互通存托凭证`
- `source`:
  - `www.szse.cn/www/lawrules/rule/inno/gdr/index.html`
- `target`: `/rule/inno/gdr`
### Rule 31
- `title`: `全部规则 - 全部业务规则`
- `source`:
  - `www.szse.cn/www/lawrules/rule/allrules/bussiness/index.html`
- `target`: `/rule/allrules/bussiness`
### Rule 32
- `title`: `全部规则 - 规则汇编下载`
- `source`:
  - `www.szse.cn/www/lawrules/rule/allrules/rulejoin/index.html`
- `target`: `/rule/allrules/rulejoin`
### Rule 33
- `title`: `已废止规则 - 规则废止公告`
- `source`:
  - `www.szse.cn/www/lawrules/rule/repeal/announcement/index.html`
- `target`: `/rule/repeal/announcement`
### Rule 34
- `title`: `已废止规则 - 已废止规则文本`
- `source`:
  - `www.szse.cn/www/lawrules/rule/repeal/rules/index.html`
- `target`: `/rule/repeal/rules`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [综合类](https://www.szse.cn/www/lawrules/rule/all/index.html)，网址为 `https://www.szse.cn/www/lawrules/rule/all/index.html`。截取 `https://www.szse.cn/www/lawrules/rule/` 到末尾 `/index.html` 的部分 `all` 作为参数填入，此时路由为 [`/szse/rule/all`](https://rsshub.app/szse/rule/all)。\n:::\n\n| 频道                                                                        | ID                                                    |\n| --------------------------------------------------------------------------- | ----------------------------------------------------- |\n| [综合类](https://www.szse.cn/www/lawrules/rule/all/index.html)              | [all](https://rsshub.app/szes/rule/all)               |\n| [基础设施 REITs 类](https://www.szse.cn/www/lawrules/rule/reits/index.html) | [reits](https://rsshub.app/szes/rule/reits)           |\n| [衍生品类](https://www.szse.cn/www/lawrules/rule/derivative/index.html)     | [derivative](https://rsshub.app/szes/rule/derivative) |\n| [会员管理类](https://www.szse.cn/www/lawrules/rule/memberty/index.html)     | [memberty](https://rsshub.app/szes/rule/memberty)     |\n| [纪律处分与内部救济类](https://www.szse.cn/www/lawrules/rule/pr/index.html) | [pr](https://rsshub.app/szes/rule/pr)                 |\n\n#### 股票类\n\n| 频道                                                                                     | ID                                                                                    |\n| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |\n| [发行上市审核](https://www.szse.cn/www/lawrules/rule/stock/audit/index.html)             | [stock/audit](https://rsshub.app/szes/rule/stock/audit)                               |\n| [发行承销](https://www.szse.cn/www/lawrules/rule/stock/issue/index.html)                 | [stock/issue](https://rsshub.app/szes/rule/stock/issue)                               |\n| [通用](https://www.szse.cn/www/lawrules/rule/stock/supervision/currency/index.html)      | [stock/supervision/currency](https://rsshub.app/szes/rule/stock/supervision/currency) |\n| [主板专用](https://www.szse.cn/www/lawrules/rule/stock/supervision/mb/index.html)        | [stock/supervision/mb](https://rsshub.app/szes/rule/stock/supervision/mb)             |\n| [创业板专用](https://www.szse.cn/www/lawrules/rule/stock/supervision/chinext/index.html) | [stock/supervision/chinext](https://rsshub.app/szes/rule/stock/supervision/chinext)   |\n| [交易](https://www.szse.cn/www/lawrules/rule/stock/trade/index.html)                     | [stock/trade](https://rsshub.app/szes/rule/stock/trade)                               |\n\n#### 固收类\n\n| 频道                                                                                 | ID                                                                            |\n| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |\n| [发行上市（挂牌）](https://www.szse.cn/www/lawrules/rule/bond/bonds/list/index.html) | [bond/bonds/list](https://rsshub.app/szes/rule/bond/bonds/list)               |\n| [持续监管](https://www.szse.cn/www/lawrules/rule/bond/bonds/supervision/index.html)  | [bond/bonds/supervision](https://rsshub.app/szes/rule/bond/bonds/supervision) |\n| [交易](https://www.szse.cn/www/lawrules/rule/bond/bonds/trade/index.html)            | [bond/bonds/trade](https://rsshub.app/szes/rule/bond/bonds/trade)             |\n| [资产支持证券](https://www.szse.cn/www/lawrules/rule/bond/abs/index.html)            | [bond/abs](https://rsshub.app/szes/rule/bond/abs)                             |\n\n#### 基金类\n\n| 频道                                                                | ID                                                    |\n| ------------------------------------------------------------------- | ----------------------------------------------------- |\n| [上市](https://www.szse.cn/www/lawrules/rule/fund/list/index.html)  | [fund/list](https://rsshub.app/szes/rule/fund/list)   |\n| [交易](https://www.szse.cn/www/lawrules/rule/fund/trade/index.html) | [fund/trade](https://rsshub.app/szes/rule/fund/trade) |\n\n#### 交易类\n\n| 频道                                                                                     | ID                                                                                    |\n| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |\n| [通用](https://www.szse.cn/www/lawrules/rule/trade/current/index.html)                   | [trade/current](https://rsshub.app/szes/rule/trade/current)                           |\n| [融资融券](https://www.szse.cn/www/lawrules/rule/trade/business/margin/index.html)       | [trade/business/margin](https://rsshub.app/szes/rule/trade/business/margin)           |\n| [转融通](https://www.szse.cn/www/lawrules/rule/trade/business/refinancing/index.html)    | [trade/business/refinancing](https://rsshub.app/szes/rule/trade/business/refinancing) |\n| [股票质押式回购](https://www.szse.cn/www/lawrules/rule/trade/business/pledge/index.html) | [trade/business/pledge](https://rsshub.app/szes/rule/trade/business/pledge)           |\n| [质押式报价回购](https://www.szse.cn/www/lawrules/rule/trade/business/price/index.html)  | [trade/business/price](https://rsshub.app/szes/rule/trade/business/price)             |\n| [约定购回](https://www.szse.cn/www/lawrules/rule/trade/business/promise/index.html)      | [trade/business/promise](https://rsshub.app/szes/rule/trade/business/promise)         |\n| [协议转让](https://www.szse.cn/www/lawrules/rule/trade/business/transfer/index.html)     | [trade/business/transfer](https://rsshub.app/szes/rule/trade/business/transfer)       |\n| [其他](https://www.szse.cn/www/lawrules/rule/trade/business/oth/index.html)              | [trade/business/oth](https://rsshub.app/szes/rule/trade/business/oth)                 |\n\n#### 跨境创新类\n\n| 频道                                                                          | ID                                                    |\n| ----------------------------------------------------------------------------- | ----------------------------------------------------- |\n| [深港通](https://www.szse.cn/www/lawrules/rule/inno/szhk/index.html)          | [inno/szhk](https://rsshub.app/szes/rule/inno/szhk)   |\n| [试点创新企业](https://www.szse.cn/www/lawrules/rule/inno/pilot/index.html)   | [inno/pilot](https://rsshub.app/szes/rule/inno/pilot) |\n| [H 股全流通](https://www.szse.cn/www/lawrules/rule/inno/hc/index.html)        | [inno/hc](https://rsshub.app/szes/rule/inno/hc)       |\n| [互联互通存托凭证](https://www.szse.cn/www/lawrules/rule/inno/gdr/index.html) | [inno/gdr](https://rsshub.app/szes/rule/inno/gdr)     |\n\n#### 全部规则\n\n| 频道                                                                                | ID                                                                    |\n| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------- |\n| [全部业务规则](https://www.szse.cn/www/lawrules/rule/allrules/bussiness/index.html) | [allrules/bussiness](https://rsshub.app/szes/rule/allrules/bussiness) |\n| [规则汇编下载](https://www.szse.cn/www/lawrules/rule/allrules/rulejoin/index.html)  | [allrules/rulejoin](https://rsshub.app/szes/rule/allrules/rulejoin)   |\n\n#### 已废止规则\n\n| 频道                                                                                 | ID                                                                      |\n| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- |\n| [规则废止公告](https://www.szse.cn/www/lawrules/rule/repeal/announcement/index.html) | [repeal/announcement](https://rsshub.app/szes/rule/repeal/announcement) |\n| [已废止规则文本](https://www.szse.cn/www/lawrules/rule/repeal/rules/index.html)      | [repeal/rules](https://rsshub.app/szes/rule/repeal/rules)               |",
  "example": "/szse/rule/allrules/bussiness",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 31,
  "location": "rule.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "本所业务规则",
  "parameters": {
    "channel": "频道，默认为 `allrules/bussiness`，即全部业务规则，可在对应频道页 URL 中找到"
  },
  "path": "/rule/:channel{.+}?",
  "radar": [
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/:category"
      ]
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/all/index.html"
      ],
      "target": "/rule/all",
      "title": "综合类"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/reits/index.html"
      ],
      "target": "/rule/reits",
      "title": "基础设施REITs类"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/derivative/index.html"
      ],
      "target": "/rule/derivative",
      "title": "衍生品类"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/memberty/index.html"
      ],
      "target": "/rule/memberty",
      "title": "会员管理类"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/pr/index.html"
      ],
      "target": "/rule/pr",
      "title": "纪律处分与内部救济类"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/audit/index.html"
      ],
      "target": "/rule/stock/audit",
      "title": "股票类 - 发行上市审核"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/issue/index.html"
      ],
      "target": "/rule/stock/issue",
      "title": "股票类 - 发行承销"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/supervision/currency/index.html"
      ],
      "target": "/rule/stock/supervision/currency",
      "title": "股票类 - 通用"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/supervision/mb/index.html"
      ],
      "target": "/rule/stock/supervision/mb",
      "title": "股票类 - 主板专用"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/supervision/chinext/index.html"
      ],
      "target": "/rule/stock/supervision/chinext",
      "title": "股票类 - 创业板专用"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/stock/trade/index.html"
      ],
      "target": "/rule/stock/trade",
      "title": "股票类 - 交易"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/bond/bonds/list/index.html"
      ],
      "target": "/rule/bond/bonds/list",
      "title": "固收类 - 发行上市（挂牌）"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/bond/bonds/supervision/index.html"
      ],
      "target": "/rule/bond/bonds/supervision",
      "title": "固收类 - 持续监管"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/bond/bonds/trade/index.html"
      ],
      "target": "/rule/bond/bonds/trade",
      "title": "固收类 - 交易"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/bond/abs/index.html"
      ],
      "target": "/rule/bond/abs",
      "title": "固收类 - 资产支持证券"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/fund/list/index.html"
      ],
      "target": "/rule/fund/list",
      "title": "基金类 - 上市"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/fund/trade/index.html"
      ],
      "target": "/rule/fund/trade",
      "title": "基金类 - 交易"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/current/index.html"
      ],
      "target": "/rule/trade/current",
      "title": "交易类 - 通用"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/margin/index.html"
      ],
      "target": "/rule/trade/business/margin",
      "title": "交易类 - 融资融券"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/refinancing/index.html"
      ],
      "target": "/rule/trade/business/refinancing",
      "title": "交易类 - 转融通"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/pledge/index.html"
      ],
      "target": "/rule/trade/business/pledge",
      "title": "交易类 - 股票质押式回购"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/price/index.html"
      ],
      "target": "/rule/trade/business/price",
      "title": "交易类 - 质押式报价回购"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/promise/index.html"
      ],
      "target": "/rule/trade/business/promise",
      "title": "交易类 - 约定购回"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/transfer/index.html"
      ],
      "target": "/rule/trade/business/transfer",
      "title": "交易类 - 协议转让"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/trade/business/oth/index.html"
      ],
      "target": "/rule/trade/business/oth",
      "title": "交易类 - 其他"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/inno/szhk/index.html"
      ],
      "target": "/rule/inno/szhk",
      "title": "跨境创新类 - 深港通"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/inno/pilot/index.html"
      ],
      "target": "/rule/inno/pilot",
      "title": "跨境创新类 - 试点创新企业"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/inno/hc/index.html"
      ],
      "target": "/rule/inno/hc",
      "title": "跨境创新类 - H股全流通"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/inno/gdr/index.html"
      ],
      "target": "/rule/inno/gdr",
      "title": "跨境创新类 - 互联互通存托凭证"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/allrules/bussiness/index.html"
      ],
      "target": "/rule/allrules/bussiness",
      "title": "全部规则 - 全部业务规则"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/allrules/rulejoin/index.html"
      ],
      "target": "/rule/allrules/rulejoin",
      "title": "全部规则 - 规则汇编下载"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/repeal/announcement/index.html"
      ],
      "target": "/rule/repeal/announcement",
      "title": "已废止规则 - 规则废止公告"
    },
    {
      "source": [
        "www.szse.cn/www/lawrules/rule/repeal/rules/index.html"
      ],
      "target": "/rule/repeal/rules",
      "title": "已废止规则 - 已废止规则文本"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "深交所官网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60583368044158976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/www/lawrules/rule/allrules/bussiness/",
      "title": "深圳证券交易所 - 全部业务规则",
      "type": "feed",
      "url": "rsshub://szse/rule/allrules/bussiness"
    },
    {
      "description": "深交所官网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121206842536209408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/www/lawrules/rule/allrules/bussiness/",
      "title": "深圳证券交易所 - 全部业务规则",
      "type": "feed",
      "url": "rsshub://szse/rule"
    }
  ],
  "url": "www.szse.cn"
}
```
