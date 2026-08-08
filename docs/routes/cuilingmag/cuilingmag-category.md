# 萃嶺网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `cuilingmag`
- Namespace Name: `萃嶺网`
- Route Path: `/cuilingmag/:category?`
- Route Name: `分类`
- Example: `/cuilingmag`
- URL: `cuilingmag.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [#哲学・文明](https://www.cuilingmag.com/category/philosophy_civilization)，网址为 `https://www.cuilingmag.com/category/philosophy_civilization`。截取 `https://www.cuilingmag.com/category` 到末尾的部分 `philosophy_civilization` 作为参数填入，此时路由为 [`/cuilingmag/philosophy_civilization`](https://rsshub.app/cuilingmag/philosophy_civilization)。
:::

| 分类                                                                      | ID                                                                                |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [哲学・文明](https://www.cuilingmag.com/category/philosophy_civilization) | [philosophy\_civilization](https://rsshub.app/cuilingmag/philosophy_civilization) |
| [艺术・科技](https://www.cuilingmag.com/category/art_science)             | [art\_science](https://rsshub.app/cuilingmag/art_science)                         |
| [未来・生命](https://www.cuilingmag.com/category/future_life)             | [future\_life](https://rsshub.app/cuilingmag/future_life)                         |
| [行星智慧](https://www.cuilingmag.com/category/planetary_wisdom)          | [planetary\_wisdom](https://rsshub.app/cuilingmag/planetary_wisdom)               |
| [数字治理](https://www.cuilingmag.com/category/digital_governance)        | [digital\_governance](https://rsshub.app/cuilingmag/digital_governance)           |
| [Noema 精选](https://www.cuilingmag.com/category/selected_noema)          | [selected\_noema](https://rsshub.app/cuilingmag/selected_noema)                   |

## Parameters
- `category`: 分类，默认为空，即全部，可在对应分类页 URL 中找到


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
  - `cuilingmag.com/category/:category`
### Rule 2
- `title`: `全部`
- `source`:
  - `cuilingmag.com`
- `target`: `/`
### Rule 3
- `title`: `哲学 · 文明`
- `source`:
  - `cuilingmag.com/category/philosophy_civilization`
- `target`: `/philosophy_civilization`
### Rule 4
- `title`: `艺术 · 科技`
- `source`:
  - `cuilingmag.com/category/art_science`
- `target`: `/art_science`
### Rule 5
- `title`: `未来 · 生命`
- `source`:
  - `cuilingmag.com/category/future_life`
- `target`: `/future_life`
### Rule 6
- `title`: `行星智慧`
- `source`:
  - `cuilingmag.com/category/planetary_wisdom`
- `target`: `/planetary_wisdom`
### Rule 7
- `title`: `数字治理`
- `source`:
  - `cuilingmag.com/category/digital_governance`
- `target`: `/digital_governance`
### Rule 8
- `title`: `Noema精选`
- `source`:
  - `cuilingmag.com/category/selected_noema`
- `target`: `/selected_noema`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [#哲学・文明](https://www.cuilingmag.com/category/philosophy_civilization)，网址为 `https://www.cuilingmag.com/category/philosophy_civilization`。截取 `https://www.cuilingmag.com/category` 到末尾的部分 `philosophy_civilization` 作为参数填入，此时路由为 [`/cuilingmag/philosophy_civilization`](https://rsshub.app/cuilingmag/philosophy_civilization)。\n:::\n\n| 分类                                                                      | ID                                                                                |\n| ------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |\n| [哲学・文明](https://www.cuilingmag.com/category/philosophy_civilization) | [philosophy\\_civilization](https://rsshub.app/cuilingmag/philosophy_civilization) |\n| [艺术・科技](https://www.cuilingmag.com/category/art_science)             | [art\\_science](https://rsshub.app/cuilingmag/art_science)                         |\n| [未来・生命](https://www.cuilingmag.com/category/future_life)             | [future\\_life](https://rsshub.app/cuilingmag/future_life)                         |\n| [行星智慧](https://www.cuilingmag.com/category/planetary_wisdom)          | [planetary\\_wisdom](https://rsshub.app/cuilingmag/planetary_wisdom)               |\n| [数字治理](https://www.cuilingmag.com/category/digital_governance)        | [digital\\_governance](https://rsshub.app/cuilingmag/digital_governance)           |\n| [Noema 精选](https://www.cuilingmag.com/category/selected_noema)          | [selected\\_noema](https://rsshub.app/cuilingmag/selected_noema)                   |",
  "example": "/cuilingmag",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 68,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，默认为空，即全部，可在对应分类页 URL 中找到"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "cuilingmag.com/category/:category"
      ]
    },
    {
      "source": [
        "cuilingmag.com"
      ],
      "target": "/",
      "title": "全部"
    },
    {
      "source": [
        "cuilingmag.com/category/philosophy_civilization"
      ],
      "target": "/philosophy_civilization",
      "title": "哲学 · 文明"
    },
    {
      "source": [
        "cuilingmag.com/category/art_science"
      ],
      "target": "/art_science",
      "title": "艺术 · 科技"
    },
    {
      "source": [
        "cuilingmag.com/category/future_life"
      ],
      "target": "/future_life",
      "title": "未来 · 生命"
    },
    {
      "source": [
        "cuilingmag.com/category/planetary_wisdom"
      ],
      "target": "/planetary_wisdom",
      "title": "行星智慧"
    },
    {
      "source": [
        "cuilingmag.com/category/digital_governance"
      ],
      "target": "/digital_governance",
      "title": "数字治理"
    },
    {
      "source": [
        "cuilingmag.com/category/selected_noema"
      ],
      "target": "/selected_noema",
      "title": "Noema精选"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "萃嶺网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72920871518882824",
      "image": "https://www.cuilingmag.com/cuiling/icon/latest-logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.cuilingmag.com/",
      "title": "萃嶺网",
      "type": "feed",
      "url": "rsshub://cuilingmag"
    },
    {
      "description": "哲学·文明-萃嶺网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84053236632059904",
      "image": "https://www.cuilingmag.com/cuiling/icon/latest-logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.cuilingmag.com/category/philosophy_civilization",
      "title": "哲学·文明-萃嶺网",
      "type": "feed",
      "url": "rsshub://cuilingmag/philosophy_civilization"
    }
  ],
  "url": "cuilingmag.com"
}
```
