# cpcaauto.com - 文章

## Coverage
`index-only`

## Route
- Namespace: `cpcaauto`
- Namespace Name: `cpcaauto.com`
- Route Path: `/cpcaauto/news/:type?/:id?`
- Route Name: `文章`
- Example: `/cpcaauto/news/news`
- URL: `cpcaauto.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [行业新闻 > 国内乘用车](http://cpcaauto.com/news.php?types=news\&anid=10)，网址为 `http://cpcaauto.com/news.php?types=news&anid=10`。截取 `types` 和 `anid` 的部分 \`\` 作为参数填入，此时路由为 [`/cpcaauto/news/news/10`](https://rsshub.app/cpcaauto/news/news/10)。
:::

#### [行业新闻](http://cpcaauto.com/news.php?types=news)

| [国内乘用车](http://cpcaauto.com/news.php?types=news\&anid=10) | [进口及国外乘用车](http://cpcaauto.com/news.php?types=news\&anid=64) | [后市场](http://cpcaauto.com/news.php?types=news\&anid=44) | [商用车](http://cpcaauto.com/news.php?types=news\&anid=62) |
| -------------------------------------------------------------- | -------------------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- |
| [news/10](https://rsshub.app/cpcaauto/news/news/10)            | [news/64](https://rsshub.app/cpcaauto/news/news/64)                  | [news/44](https://rsshub.app/cpcaauto/news/news/44)        | [news/62](https://rsshub.app/cpcaauto/news/news/62)        |

#### [车市解读](http://cpcaauto.com/news.php?types=csjd)

| [周度](http://cpcaauto.com/news.php?types=csjd\&anid=128) | [月度](http://cpcaauto.com/news.php?types=csjd\&anid=129) | [指数](http://cpcaauto.com/news.php?types=csjd\&anid=130) | [预测](http://cpcaauto.com/news.php?types=csjd\&anid=131) |
| --------------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------- |
| [csjd/128](https://rsshub.app/cpcaauto/news/csjd/128)     | [csjd/129](https://rsshub.app/cpcaauto/news/csjd/129)     | [csjd/130](https://rsshub.app/cpcaauto/news/csjd/130)     | [csjd/131](https://rsshub.app/cpcaauto/news/csjd/131)     |

#### [发布会报告](http://cpcaauto.com/news.php?types=bgzl)

| [上海市场上牌数](http://cpcaauto.com/news.php?types=bgzl\&anid=119) | [京城车市](http://cpcaauto.com/news.php?types=bgzl\&anid=122) | [进口车市场分析](http://cpcaauto.com/news.php?types=bgzl\&anid=120) | [二手车市场分析](http://cpcaauto.com/news.php?types=bgzl\&anid=121) | [价格指数](http://cpcaauto.com/news.php?types=bgzl\&anid=124) |
| ------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------- |
| [bgzl/119](https://rsshub.app/cpcaauto/news/bgzl/119)               | [bgzl/122](https://rsshub.app/cpcaauto/news/bgzl/122)         | [bgzl/120](https://rsshub.app/cpcaauto/news/bgzl/120)               | [bgzl/121](https://rsshub.app/cpcaauto/news/bgzl/121)               | [bgzl/124](https://rsshub.app/cpcaauto/news/bgzl/124)         |

| [热点评述](http://cpcaauto.com/news.php?types=bgzl\&anid=125) | [新能源月报](http://cpcaauto.com/news.php?types=bgzl\&anid=126) | [商用车月报](http://cpcaauto.com/news.php?types=bgzl\&anid=127) | [政策分析](http://cpcaauto.com/news.php?types=bgzl\&anid=123) |
| ------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------- |
| [bgzl/125](https://rsshub.app/cpcaauto/news/bgzl/125)         | [bgzl/126](https://rsshub.app/cpcaauto/news/bgzl/126)           | [bgzl/127](https://rsshub.app/cpcaauto/news/bgzl/127)           | [bgzl/123](https://rsshub.app/cpcaauto/news/bgzl/123)         |

#### [经济与政策](http://cpcaauto.com/news.php?types=meeting)

| [一周经济](http://cpcaauto.com/news.php?types=meeting\&anid=46) | [一周政策](http://cpcaauto.com/news.php?types=meeting\&anid=47) |
| --------------------------------------------------------------- | --------------------------------------------------------------- |
| [meeting/46](https://rsshub.app/cpcaauto/news/meeting/46)       | [meeting/47](https://rsshub.app/cpcaauto/news/meeting/47)       |

#### [乘联会论坛](http://cpcaauto.com/news.php?types=yjsy)

| [论坛文章](http://cpcaauto.com/news.php?types=yjsy\&anid=49) | [两会](http://cpcaauto.com/news.php?types=yjsy\&anid=111) | [车展看点](http://cpcaauto.com/news.php?types=yjsy\&anid=113) |
| ------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------- |
| [yjsy/49](https://rsshub.app/cpcaauto/news/yjsy/49)          | [yjsy/111](https://rsshub.app/cpcaauto/news/yjsy/111)     | [yjsy/113](https://rsshub.app/cpcaauto/news/yjsy/113)         |

## Parameters
- `type`: 分类，默认为 news，可在对应分类页 URL 中找到
- `id`: id，默认为 news，可在对应分类页 URL 中找到


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
  - `cpcaauto.com/news.php`
### Rule 2
- `title`: `行业新闻 - 国内乘用车`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/news/10`
### Rule 3
- `title`: `行业新闻 - 进口及国外乘用车`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/news/64`
### Rule 4
- `title`: `行业新闻 - 后市场`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/news/44`
### Rule 5
- `title`: `行业新闻 - 商用车`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/news/62`
### Rule 6
- `title`: `车市解读 - 周度`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/csjd/128`
### Rule 7
- `title`: `车市解读 - 月度`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/csjd/129`
### Rule 8
- `title`: `车市解读 - 指数`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/csjd/130`
### Rule 9
- `title`: `车市解读 - 预测`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/csjd/131`
### Rule 10
- `title`: `发布会报告 - 上海市场上牌数`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/119`
### Rule 11
- `title`: `发布会报告 - 京城车市`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/122`
### Rule 12
- `title`: `发布会报告 - 进口车市场分析`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/120`
### Rule 13
- `title`: `发布会报告 - 二手车市场分析`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/121`
### Rule 14
- `title`: `发布会报告 - 价格指数`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/124`
### Rule 15
- `title`: `发布会报告 - 热点评述`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/125`
### Rule 16
- `title`: `发布会报告 - 新能源月报`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/126`
### Rule 17
- `title`: `发布会报告 - 商用车月报`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/127`
### Rule 18
- `title`: `发布会报告 - 政策分析`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/bgzl/123`
### Rule 19
- `title`: `经济与政策 - 一周经济`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/meeting/46`
### Rule 20
- `title`: `经济与政策 - 一周政策`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/meeting/47`
### Rule 21
- `title`: `乘联会论坛 - 论坛文章`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/yjsy/49`
### Rule 22
- `title`: `乘联会论坛 - 两会`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/yjsy/111`
### Rule 23
- `title`: `乘联会论坛 - 车展看点`
- `source`:
  - `cpcaauto.com/news.php`
- `target`: `/news/yjsy/113`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [行业新闻 > 国内乘用车](http://cpcaauto.com/news.php?types=news\\&anid=10)，网址为 `http://cpcaauto.com/news.php?types=news&anid=10`。截取 `types` 和 `anid` 的部分 \\`\\` 作为参数填入，此时路由为 [`/cpcaauto/news/news/10`](https://rsshub.app/cpcaauto/news/news/10)。\n:::\n\n#### [行业新闻](http://cpcaauto.com/news.php?types=news)\n\n| [国内乘用车](http://cpcaauto.com/news.php?types=news\\&anid=10) | [进口及国外乘用车](http://cpcaauto.com/news.php?types=news\\&anid=64) | [后市场](http://cpcaauto.com/news.php?types=news\\&anid=44) | [商用车](http://cpcaauto.com/news.php?types=news\\&anid=62) |\n| -------------------------------------------------------------- | -------------------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- |\n| [news/10](https://rsshub.app/cpcaauto/news/news/10)            | [news/64](https://rsshub.app/cpcaauto/news/news/64)                  | [news/44](https://rsshub.app/cpcaauto/news/news/44)        | [news/62](https://rsshub.app/cpcaauto/news/news/62)        |\n\n#### [车市解读](http://cpcaauto.com/news.php?types=csjd)\n\n| [周度](http://cpcaauto.com/news.php?types=csjd\\&anid=128) | [月度](http://cpcaauto.com/news.php?types=csjd\\&anid=129) | [指数](http://cpcaauto.com/news.php?types=csjd\\&anid=130) | [预测](http://cpcaauto.com/news.php?types=csjd\\&anid=131) |\n| --------------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------- |\n| [csjd/128](https://rsshub.app/cpcaauto/news/csjd/128)     | [csjd/129](https://rsshub.app/cpcaauto/news/csjd/129)     | [csjd/130](https://rsshub.app/cpcaauto/news/csjd/130)     | [csjd/131](https://rsshub.app/cpcaauto/news/csjd/131)     |\n\n#### [发布会报告](http://cpcaauto.com/news.php?types=bgzl)\n\n| [上海市场上牌数](http://cpcaauto.com/news.php?types=bgzl\\&anid=119) | [京城车市](http://cpcaauto.com/news.php?types=bgzl\\&anid=122) | [进口车市场分析](http://cpcaauto.com/news.php?types=bgzl\\&anid=120) | [二手车市场分析](http://cpcaauto.com/news.php?types=bgzl\\&anid=121) | [价格指数](http://cpcaauto.com/news.php?types=bgzl\\&anid=124) |\n| ------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------- |\n| [bgzl/119](https://rsshub.app/cpcaauto/news/bgzl/119)               | [bgzl/122](https://rsshub.app/cpcaauto/news/bgzl/122)         | [bgzl/120](https://rsshub.app/cpcaauto/news/bgzl/120)               | [bgzl/121](https://rsshub.app/cpcaauto/news/bgzl/121)               | [bgzl/124](https://rsshub.app/cpcaauto/news/bgzl/124)         |\n\n| [热点评述](http://cpcaauto.com/news.php?types=bgzl\\&anid=125) | [新能源月报](http://cpcaauto.com/news.php?types=bgzl\\&anid=126) | [商用车月报](http://cpcaauto.com/news.php?types=bgzl\\&anid=127) | [政策分析](http://cpcaauto.com/news.php?types=bgzl\\&anid=123) |\n| ------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------- |\n| [bgzl/125](https://rsshub.app/cpcaauto/news/bgzl/125)         | [bgzl/126](https://rsshub.app/cpcaauto/news/bgzl/126)           | [bgzl/127](https://rsshub.app/cpcaauto/news/bgzl/127)           | [bgzl/123](https://rsshub.app/cpcaauto/news/bgzl/123)         |\n\n#### [经济与政策](http://cpcaauto.com/news.php?types=meeting)\n\n| [一周经济](http://cpcaauto.com/news.php?types=meeting\\&anid=46) | [一周政策](http://cpcaauto.com/news.php?types=meeting\\&anid=47) |\n| --------------------------------------------------------------- | --------------------------------------------------------------- |\n| [meeting/46](https://rsshub.app/cpcaauto/news/meeting/46)       | [meeting/47](https://rsshub.app/cpcaauto/news/meeting/47)       |\n\n#### [乘联会论坛](http://cpcaauto.com/news.php?types=yjsy)\n\n| [论坛文章](http://cpcaauto.com/news.php?types=yjsy\\&anid=49) | [两会](http://cpcaauto.com/news.php?types=yjsy\\&anid=111) | [车展看点](http://cpcaauto.com/news.php?types=yjsy\\&anid=113) |\n| ------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------- |\n| [yjsy/49](https://rsshub.app/cpcaauto/news/yjsy/49)          | [yjsy/111](https://rsshub.app/cpcaauto/news/yjsy/111)     | [yjsy/113](https://rsshub.app/cpcaauto/news/yjsy/113)         |",
  "example": "/cpcaauto/news/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 140,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "id": "id，默认为 news，可在对应分类页 URL 中找到",
    "type": "分类，默认为 news，可在对应分类页 URL 中找到"
  },
  "path": "/news/:type?/:id?",
  "radar": [
    {
      "source": [
        "cpcaauto.com/news.php"
      ]
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/news/10",
      "title": "行业新闻 - 国内乘用车"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/news/64",
      "title": "行业新闻 - 进口及国外乘用车"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/news/44",
      "title": "行业新闻 - 后市场"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/news/62",
      "title": "行业新闻 - 商用车"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/csjd/128",
      "title": "车市解读 - 周度"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/csjd/129",
      "title": "车市解读 - 月度"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/csjd/130",
      "title": "车市解读 - 指数"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/csjd/131",
      "title": "车市解读 - 预测"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/119",
      "title": "发布会报告 - 上海市场上牌数"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/122",
      "title": "发布会报告 - 京城车市"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/120",
      "title": "发布会报告 - 进口车市场分析"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/121",
      "title": "发布会报告 - 二手车市场分析"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/124",
      "title": "发布会报告 - 价格指数"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/125",
      "title": "发布会报告 - 热点评述"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/126",
      "title": "发布会报告 - 新能源月报"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/127",
      "title": "发布会报告 - 商用车月报"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/bgzl/123",
      "title": "发布会报告 - 政策分析"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/meeting/46",
      "title": "经济与政策 - 一周经济"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/meeting/47",
      "title": "经济与政策 - 一周政策"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/yjsy/49",
      "title": "乘联会论坛 - 论坛文章"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/yjsy/111",
      "title": "乘联会论坛 - 两会"
    },
    {
      "source": [
        "cpcaauto.com/news.php"
      ],
      "target": "/news/yjsy/113",
      "title": "乘联会论坛 - 车展看点"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "乘用车市场信息联席会（以下简称全国乘联会，英文简称CPCA）成立于1994年，原名全国轿车市场信息联谊会。全国乘联会也是中国流通协会下属的汽车市场研究分会。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71481310023733248",
      "image": "http://cpcaauto.com/undefined",
      "ownerUserId": null,
      "siteUrl": "http://cpcaauto.com/news.php?types=news&anid=10",
      "title": "中国汽车流通协会乘用车市场信息联席分会 - 行业新闻 - 国内乘用车",
      "type": "feed",
      "url": "rsshub://cpcaauto/news/news/10"
    },
    {
      "description": "乘用车市场信息联席会（以下简称全国乘联会，英文简称CPCA）成立于1994年，原名全国轿车市场信息联谊会。全国乘联会也是中国流通协会下属的汽车市场研究分会。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102272813177461760",
      "image": "http://cpcaauto.com/undefined",
      "ownerUserId": null,
      "siteUrl": "http://cpcaauto.com/news.php?types=csjd&anid=129",
      "title": "中国汽车流通协会乘用车市场信息联席分会 - 车市解读 - 月度",
      "type": "feed",
      "url": "rsshub://cpcaauto/news/csjd/129"
    }
  ],
  "url": "cpcaauto.com"
}
```
