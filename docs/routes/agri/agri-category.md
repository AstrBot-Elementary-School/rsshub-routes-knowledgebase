# 中国农业农村信息网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `agri`
- Namespace Name: `中国农业农村信息网`
- Route Path: `/agri/:category{.+}?`
- Route Name: `分类`
- Example: `/agri/zx/zxfb`
- URL: `www.agri.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [最新发布](http://www.agri.cn/zx/zxfb/)，网址为 `http://www.agri.cn/zx/zxfb/`。截取 `https://www.agri.cn/` 到末尾的部分 `zx/zxfb` 作为参数填入，此时路由为 [`/agri/zx/zxfb`](https://rsshub.app/agri/zx/zxfb)。
:::

#### [机构](http://www.agri.cn/jg/)

| 分类                                    | ID                                         |
| --------------------------------------- | ------------------------------------------ |
| [成果展示](http://www.agri.cn/jg/cgzs/) | [jg/cgzs](https://rsshub.app/agri/jg/cgzs) |

#### [资讯](http://www.agri.cn/zx/)

| 分类                                        | ID                                         |
| ------------------------------------------- | ------------------------------------------ |
| [最新发布](http://www.agri.cn/zx/zxfb/)     | [zx/zxfb](https://rsshub.app/agri/zx/zxfb) |
| [农业要闻](http://www.agri.cn/zx/nyyw/)     | [zx/nyyw](https://rsshub.app/agri/zx/nyyw) |
| [中心动态](http://www.agri.cn/zx/zxdt/)     | [zx/zxdt](https://rsshub.app/agri/zx/zxdt) |
| [通知公告](http://www.agri.cn/zx/hxgg/)     | [zx/hxgg](https://rsshub.app/agri/zx/hxgg) |
| [全国信息联播](http://www.agri.cn/zx/xxlb/) | [zx/xxlb](https://rsshub.app/agri/zx/xxlb) |

#### [生产](http://www.agri.cn/sc/)

| 分类                                    | ID                                         |
| --------------------------------------- | ------------------------------------------ |
| [生产动态](http://www.agri.cn/sc/scdt/) | [sc/scdt](https://rsshub.app/agri/sc/scdt) |
| [农业品种](http://www.agri.cn/sc/nypz/) | [sc/nypz](https://rsshub.app/agri/sc/nypz) |
| [农事指导](http://www.agri.cn/sc/nszd/) | [sc/nszd](https://rsshub.app/agri/sc/nszd) |
| [农业气象](http://www.agri.cn/sc/nyqx/) | [sc/nyqx](https://rsshub.app/agri/sc/nyqx) |
| [专项监测](http://www.agri.cn/sc/zxjc/) | [sc/zxjc](https://rsshub.app/agri/sc/zxjc) |

#### [数据](http://www.agri.cn/sj/)

| 分类                                    | ID                                         |
| --------------------------------------- | ------------------------------------------ |
| [市场动态](http://www.agri.cn/sj/scdt/) | [sj/scdt](https://rsshub.app/agri/sj/scdt) |
| [供需形势](http://www.agri.cn/sj/gxxs/) | [sj/gxxs](https://rsshub.app/agri/sj/gxxs) |
| [监测预警](http://www.agri.cn/sj/jcyj/) | [sj/jcyj](https://rsshub.app/agri/sj/jcyj) |

#### [信息化](http://www.agri.cn/xxh/)

| 分类                                           | ID                                               |
| ---------------------------------------------- | ------------------------------------------------ |
| [智慧农业](http://www.agri.cn/xxh/zhny/)       | [xxh/zhny](https://rsshub.app/agri/xxh/zhny)     |
| [信息化标准](http://www.agri.cn/xxh/xxhbz/)    | [xxh/xxhbz](https://rsshub.app/agri/xxh/xxhbz)   |
| [中国乡村资讯](http://www.agri.cn/xxh/zgxczx/) | [xxh/zgxczx](https://rsshub.app/agri/xxh/zgxczx) |

#### [视频](http://www.agri.cn/video/)

| 分类                                               | ID                                                               |
| -------------------------------------------------- | ---------------------------------------------------------------- |
| [新闻资讯](http://www.agri.cn/video/xwzx/nyxw/)    | [video/xwzx/nyxw](https://rsshub.app/agri/video/xwzx/nyxw)       |
| [致富天地](http://www.agri.cn/video/zftd/)         | [video/zftd](https://rsshub.app/agri/video/zftd)                 |
| [地方农业](http://www.agri.cn/video/dfny/beijing/) | [video/dfny/beijing](https://rsshub.app/agri/video/dfny/beijing) |
| [气象农业](http://www.agri.cn/video/qxny/)         | [video/qxny](https://rsshub.app/agri/video/qxny)                 |
| [讲座培训](http://www.agri.cn/video/jzpx/)         | [video/jzpx](https://rsshub.app/agri/video/jzpx)                 |
| [文化生活](http://www.agri.cn/video/whsh/)         | [video/whsh](https://rsshub.app/agri/video/whsh)                 |

## Parameters
- `category`: 分类，默认为 `zx/zxfb`，即最新发布，可在对应分类页 URL 中找到


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
  - `www.agri.cn/:category?`
### Rule 2
- `title`: `机构 - 成果展示`
- `source`:
  - `www.agri.cn/jg/cgzs/`
- `target`: `/jg/cgzs`
### Rule 3
- `title`: `资讯 - 最新发布`
- `source`:
  - `www.agri.cn/zx/zxfb/`
- `target`: `/zx/zxfb`
### Rule 4
- `title`: `资讯 - 农业要闻`
- `source`:
  - `www.agri.cn/zx/nyyw/`
- `target`: `/zx/nyyw`
### Rule 5
- `title`: `资讯 - 中心动态`
- `source`:
  - `www.agri.cn/zx/zxdt/`
- `target`: `/zx/zxdt`
### Rule 6
- `title`: `资讯 - 通知公告`
- `source`:
  - `www.agri.cn/zx/hxgg/`
- `target`: `/zx/hxgg`
### Rule 7
- `title`: `资讯 - 全国信息联播`
- `source`:
  - `www.agri.cn/zx/xxlb/`
- `target`: `/zx/xxlb`
### Rule 8
- `title`: `生产 - 生产动态`
- `source`:
  - `www.agri.cn/sc/scdt/`
- `target`: `/sc/scdt`
### Rule 9
- `title`: `生产 - 农业品种`
- `source`:
  - `www.agri.cn/sc/nypz/`
- `target`: `/sc/nypz`
### Rule 10
- `title`: `生产 - 农事指导`
- `source`:
  - `www.agri.cn/sc/nszd/`
- `target`: `/sc/nszd`
### Rule 11
- `title`: `生产 - 农业气象`
- `source`:
  - `www.agri.cn/sc/nyqx/`
- `target`: `/sc/nyqx`
### Rule 12
- `title`: `生产 - 专项监测`
- `source`:
  - `www.agri.cn/sc/zxjc/`
- `target`: `/sc/zxjc`
### Rule 13
- `title`: `数据 - 市场动态`
- `source`:
  - `www.agri.cn/sj/scdt/`
- `target`: `/sj/scdt`
### Rule 14
- `title`: `数据 - 供需形势`
- `source`:
  - `www.agri.cn/sj/gxxs/`
- `target`: `/sj/gxxs`
### Rule 15
- `title`: `数据 - 监测预警`
- `source`:
  - `www.agri.cn/sj/jcyj/`
- `target`: `/sj/jcyj`
### Rule 16
- `title`: `信息化 - 智慧农业`
- `source`:
  - `www.agri.cn/xxh/zhny/`
- `target`: `/xxh/zhny`
### Rule 17
- `title`: `信息化 - 信息化标准`
- `source`:
  - `www.agri.cn/xxh/xxhbz/`
- `target`: `/xxh/xxhbz`
### Rule 18
- `title`: `信息化 - 中国乡村资讯`
- `source`:
  - `www.agri.cn/xxh/zgxczx/`
- `target`: `/xxh/zgxczx`
### Rule 19
- `title`: `视频 - 新闻资讯`
- `source`:
  - `www.agri.cn/video/xwzx/nyxw/`
- `target`: `/video/xwzx/nyxw`
### Rule 20
- `title`: `视频 - 致富天地`
- `source`:
  - `www.agri.cn/video/zftd/`
- `target`: `/video/zftd`
### Rule 21
- `title`: `视频 - 地方农业`
- `source`:
  - `www.agri.cn/video/dfny/beijing/`
- `target`: `/video/dfny/beijing`
### Rule 22
- `title`: `视频 - 气象农业`
- `source`:
  - `www.agri.cn/video/qxny/`
- `target`: `/video/qxny`
### Rule 23
- `title`: `视频 - 讲座培训`
- `source`:
  - `www.agri.cn/video/jzpx/`
- `target`: `/video/jzpx`
### Rule 24
- `title`: `视频 - 文化生活`
- `source`:
  - `www.agri.cn/video/whsh/`
- `target`: `/video/whsh`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [最新发布](http://www.agri.cn/zx/zxfb/)，网址为 `http://www.agri.cn/zx/zxfb/`。截取 `https://www.agri.cn/` 到末尾的部分 `zx/zxfb` 作为参数填入，此时路由为 [`/agri/zx/zxfb`](https://rsshub.app/agri/zx/zxfb)。\n:::\n\n#### [机构](http://www.agri.cn/jg/)\n\n| 分类                                    | ID                                         |\n| --------------------------------------- | ------------------------------------------ |\n| [成果展示](http://www.agri.cn/jg/cgzs/) | [jg/cgzs](https://rsshub.app/agri/jg/cgzs) |\n\n#### [资讯](http://www.agri.cn/zx/)\n\n| 分类                                        | ID                                         |\n| ------------------------------------------- | ------------------------------------------ |\n| [最新发布](http://www.agri.cn/zx/zxfb/)     | [zx/zxfb](https://rsshub.app/agri/zx/zxfb) |\n| [农业要闻](http://www.agri.cn/zx/nyyw/)     | [zx/nyyw](https://rsshub.app/agri/zx/nyyw) |\n| [中心动态](http://www.agri.cn/zx/zxdt/)     | [zx/zxdt](https://rsshub.app/agri/zx/zxdt) |\n| [通知公告](http://www.agri.cn/zx/hxgg/)     | [zx/hxgg](https://rsshub.app/agri/zx/hxgg) |\n| [全国信息联播](http://www.agri.cn/zx/xxlb/) | [zx/xxlb](https://rsshub.app/agri/zx/xxlb) |\n\n#### [生产](http://www.agri.cn/sc/)\n\n| 分类                                    | ID                                         |\n| --------------------------------------- | ------------------------------------------ |\n| [生产动态](http://www.agri.cn/sc/scdt/) | [sc/scdt](https://rsshub.app/agri/sc/scdt) |\n| [农业品种](http://www.agri.cn/sc/nypz/) | [sc/nypz](https://rsshub.app/agri/sc/nypz) |\n| [农事指导](http://www.agri.cn/sc/nszd/) | [sc/nszd](https://rsshub.app/agri/sc/nszd) |\n| [农业气象](http://www.agri.cn/sc/nyqx/) | [sc/nyqx](https://rsshub.app/agri/sc/nyqx) |\n| [专项监测](http://www.agri.cn/sc/zxjc/) | [sc/zxjc](https://rsshub.app/agri/sc/zxjc) |\n\n#### [数据](http://www.agri.cn/sj/)\n\n| 分类                                    | ID                                         |\n| --------------------------------------- | ------------------------------------------ |\n| [市场动态](http://www.agri.cn/sj/scdt/) | [sj/scdt](https://rsshub.app/agri/sj/scdt) |\n| [供需形势](http://www.agri.cn/sj/gxxs/) | [sj/gxxs](https://rsshub.app/agri/sj/gxxs) |\n| [监测预警](http://www.agri.cn/sj/jcyj/) | [sj/jcyj](https://rsshub.app/agri/sj/jcyj) |\n\n#### [信息化](http://www.agri.cn/xxh/)\n\n| 分类                                           | ID                                               |\n| ---------------------------------------------- | ------------------------------------------------ |\n| [智慧农业](http://www.agri.cn/xxh/zhny/)       | [xxh/zhny](https://rsshub.app/agri/xxh/zhny)     |\n| [信息化标准](http://www.agri.cn/xxh/xxhbz/)    | [xxh/xxhbz](https://rsshub.app/agri/xxh/xxhbz)   |\n| [中国乡村资讯](http://www.agri.cn/xxh/zgxczx/) | [xxh/zgxczx](https://rsshub.app/agri/xxh/zgxczx) |\n\n#### [视频](http://www.agri.cn/video/)\n\n| 分类                                               | ID                                                               |\n| -------------------------------------------------- | ---------------------------------------------------------------- |\n| [新闻资讯](http://www.agri.cn/video/xwzx/nyxw/)    | [video/xwzx/nyxw](https://rsshub.app/agri/video/xwzx/nyxw)       |\n| [致富天地](http://www.agri.cn/video/zftd/)         | [video/zftd](https://rsshub.app/agri/video/zftd)                 |\n| [地方农业](http://www.agri.cn/video/dfny/beijing/) | [video/dfny/beijing](https://rsshub.app/agri/video/dfny/beijing) |\n| [气象农业](http://www.agri.cn/video/qxny/)         | [video/qxny](https://rsshub.app/agri/video/qxny)                 |\n| [讲座培训](http://www.agri.cn/video/jzpx/)         | [video/jzpx](https://rsshub.app/agri/video/jzpx)                 |\n| [文化生活](http://www.agri.cn/video/whsh/)         | [video/whsh](https://rsshub.app/agri/video/whsh)                 |",
  "example": "/agri/zx/zxfb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 21,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，默认为 `zx/zxfb`，即最新发布，可在对应分类页 URL 中找到"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.agri.cn/:category?"
      ]
    },
    {
      "source": [
        "www.agri.cn/jg/cgzs/"
      ],
      "target": "/jg/cgzs",
      "title": "机构 - 成果展示"
    },
    {
      "source": [
        "www.agri.cn/zx/zxfb/"
      ],
      "target": "/zx/zxfb",
      "title": "资讯 - 最新发布"
    },
    {
      "source": [
        "www.agri.cn/zx/nyyw/"
      ],
      "target": "/zx/nyyw",
      "title": "资讯 - 农业要闻"
    },
    {
      "source": [
        "www.agri.cn/zx/zxdt/"
      ],
      "target": "/zx/zxdt",
      "title": "资讯 - 中心动态"
    },
    {
      "source": [
        "www.agri.cn/zx/hxgg/"
      ],
      "target": "/zx/hxgg",
      "title": "资讯 - 通知公告"
    },
    {
      "source": [
        "www.agri.cn/zx/xxlb/"
      ],
      "target": "/zx/xxlb",
      "title": "资讯 - 全国信息联播"
    },
    {
      "source": [
        "www.agri.cn/sc/scdt/"
      ],
      "target": "/sc/scdt",
      "title": "生产 - 生产动态"
    },
    {
      "source": [
        "www.agri.cn/sc/nypz/"
      ],
      "target": "/sc/nypz",
      "title": "生产 - 农业品种"
    },
    {
      "source": [
        "www.agri.cn/sc/nszd/"
      ],
      "target": "/sc/nszd",
      "title": "生产 - 农事指导"
    },
    {
      "source": [
        "www.agri.cn/sc/nyqx/"
      ],
      "target": "/sc/nyqx",
      "title": "生产 - 农业气象"
    },
    {
      "source": [
        "www.agri.cn/sc/zxjc/"
      ],
      "target": "/sc/zxjc",
      "title": "生产 - 专项监测"
    },
    {
      "source": [
        "www.agri.cn/sj/scdt/"
      ],
      "target": "/sj/scdt",
      "title": "数据 - 市场动态"
    },
    {
      "source": [
        "www.agri.cn/sj/gxxs/"
      ],
      "target": "/sj/gxxs",
      "title": "数据 - 供需形势"
    },
    {
      "source": [
        "www.agri.cn/sj/jcyj/"
      ],
      "target": "/sj/jcyj",
      "title": "数据 - 监测预警"
    },
    {
      "source": [
        "www.agri.cn/xxh/zhny/"
      ],
      "target": "/xxh/zhny",
      "title": "信息化 - 智慧农业"
    },
    {
      "source": [
        "www.agri.cn/xxh/xxhbz/"
      ],
      "target": "/xxh/xxhbz",
      "title": "信息化 - 信息化标准"
    },
    {
      "source": [
        "www.agri.cn/xxh/zgxczx/"
      ],
      "target": "/xxh/zgxczx",
      "title": "信息化 - 中国乡村资讯"
    },
    {
      "source": [
        "www.agri.cn/video/xwzx/nyxw/"
      ],
      "target": "/video/xwzx/nyxw",
      "title": "视频 - 新闻资讯"
    },
    {
      "source": [
        "www.agri.cn/video/zftd/"
      ],
      "target": "/video/zftd",
      "title": "视频 - 致富天地"
    },
    {
      "source": [
        "www.agri.cn/video/dfny/beijing/"
      ],
      "target": "/video/dfny/beijing",
      "title": "视频 - 地方农业"
    },
    {
      "source": [
        "www.agri.cn/video/qxny/"
      ],
      "target": "/video/qxny",
      "title": "视频 - 气象农业"
    },
    {
      "source": [
        "www.agri.cn/video/jzpx/"
      ],
      "target": "/video/jzpx",
      "title": "视频 - 讲座培训"
    },
    {
      "source": [
        "www.agri.cn/video/whsh/"
      ],
      "target": "/video/whsh",
      "title": "视频 - 文化生活"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国农业农村信息网_最新发布 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70027894230618112",
      "image": "http://www.agri.cn/images/ny_logo.png",
      "ownerUserId": null,
      "siteUrl": "http://www.agri.cn/zx/zxfb/",
      "title": "中国农业农村信息网_最新发布",
      "type": "feed",
      "url": "rsshub://agri/zx/zxfb"
    },
    {
      "description": "中国农业农村信息网_农业要闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77696987597589504",
      "image": "http://www.agri.cn/images/ny_logo.png",
      "ownerUserId": null,
      "siteUrl": "http://www.agri.cn/zx/nyyw/",
      "title": "中国农业农村信息网_农业要闻",
      "type": "feed",
      "url": "rsshub://agri/zx/nyyw"
    }
  ],
  "url": "www.agri.cn"
}
```
