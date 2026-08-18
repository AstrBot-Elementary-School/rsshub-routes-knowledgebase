# 数字尾巴 - 文章

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/dgtle/article/:id?/:pushed?`
- Route Name: `文章`
- Example: `/dgtle/article/0/0`
- URL: `www.dgtle.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [数码](https://www.dgtle.com/article)，其对应分类 ID 为 `20`，此时路由为 [`/dgtle/article/20`](https://rsshub.app/dgtle/article/20)。
:::

<details>
  <summary>更多分类</summary>

| [全部](https://www.dgtle.com/article)   | [数码](https://www.dgtle.com/article)     | [手机](https://www.dgtle.com/article)     | [平板](https://www.dgtle.com/article)   | [笔电](https://www.dgtle.com/article)     |
| --------------------------------------- | ----------------------------------------- | ----------------------------------------- | --------------------------------------- | ----------------------------------------- |
| [0](https://rsshub.app/dgtle/article/0) | [20](https://rsshub.app/dgtle/article/20) | [18](https://rsshub.app/dgtle/article/18) | [4](https://rsshub.app/dgtle/article/4) | [17](https://rsshub.app/dgtle/article/17) |

| [影音](https://www.dgtle.com/article)   | [汽车](https://www.dgtle.com/article)       | [视频](https://www.dgtle.com/article)       | [摄影](https://www.dgtle.com/article)     | [露营](https://www.dgtle.com/article)       |
| --------------------------------------- | ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | ------------------------------------------- |
| [5](https://rsshub.app/dgtle/article/5) | [401](https://rsshub.app/dgtle/article/401) | [395](https://rsshub.app/dgtle/article/395) | [22](https://rsshub.app/dgtle/article/22) | [405](https://rsshub.app/dgtle/article/405) |

| [家装](https://www.dgtle.com/article)       | [活动](https://www.dgtle.com/article)       | [生活](https://www.dgtle.com/article)     | [旅行](https://www.dgtle.com/article)       | [骑行](https://www.dgtle.com/article)       |
| ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | ------------------------------------------- | ------------------------------------------- |
| [402](https://rsshub.app/dgtle/article/402) | [138](https://rsshub.app/dgtle/article/138) | [34](https://rsshub.app/dgtle/article/34) | [137](https://rsshub.app/dgtle/article/137) | [412](https://rsshub.app/dgtle/article/412) |

| [游戏](https://www.dgtle.com/article)       | [宠物](https://www.dgtle.com/article)       | [时尚](https://www.dgtle.com/article)       | [运动](https://www.dgtle.com/article)       | [应用](https://www.dgtle.com/article)       |
| ------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- |
| [411](https://rsshub.app/dgtle/article/411) | [407](https://rsshub.app/dgtle/article/407) | [406](https://rsshub.app/dgtle/article/406) | [403](https://rsshub.app/dgtle/article/403) | [135](https://rsshub.app/dgtle/article/135) |

| [玩物](https://www.dgtle.com/article)     | [周边](https://www.dgtle.com/article)     | [文具](https://www.dgtle.com/article)   | [官方](https://www.dgtle.com/article)       |
| ----------------------------------------- | ----------------------------------------- | --------------------------------------- | ------------------------------------------- |
| [75](https://rsshub.app/dgtle/article/75) | [19](https://rsshub.app/dgtle/article/19) | [7](https://rsshub.app/dgtle/article/7) | [400](https://rsshub.app/dgtle/article/400) |

</details>

## Parameters
- `id`: {"description": "分类，默认为 `0`，即最新，可在下表中找到", "options": [{"label": "全部", "value": "0"}, {"label": "数码", "value": "20"}, {"label": "手机", "value": "18"}, {"label": "平板", "value": "4"}, {"label": "笔电", "value": "17"}, {"label": "影音", "value": "5"}, {"label": "汽车", "value": "401"}, {"label": "视频", "value": "395"}, {"label": "摄影", "value": "22"}, {"label": "露营", "value": "405"}, {"label": "家装", "value": "402"}, {"label": "活动", "value": "138"}, {"label": "生活", "value": "34"}, {"label": "旅行", "value": "137"}, {"label": "骑行", "value": "412"}, {"label": "游戏", "value": "411"}, {"label": "宠物", "value": "407"}, {"label": "时尚", "value": "406"}, {"label": "运动", "value": "403"}, {"label": "应用", "value": "135"}, {"label": "玩物", "value": "75"}, {"label": "周边", "value": "19"}, {"label": "文具", "value": "7"}, {"label": "官方", "value": "400"}]}
- `pushed`: {"description": "推送排序，默认为 `0`，即最新发布", "options": [{"label": "最新发布", "value": "0"}, {"label": "首页推荐", "value": "1"}]}


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
  - `www.dgtle.com/article`
- `target`: `/article`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/0`
### Rule 3
- `title`: `数码`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/20`
### Rule 4
- `title`: `手机`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/18`
### Rule 5
- `title`: `平板`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/4`
### Rule 6
- `title`: `笔电`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/17`
### Rule 7
- `title`: `影音`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/5`
### Rule 8
- `title`: `汽车`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/401`
### Rule 9
- `title`: `视频`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/395`
### Rule 10
- `title`: `摄影`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/22`
### Rule 11
- `title`: `露营`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/405`
### Rule 12
- `title`: `家装`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/402`
### Rule 13
- `title`: `活动`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/138`
### Rule 14
- `title`: `生活`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/34`
### Rule 15
- `title`: `旅行`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/137`
### Rule 16
- `title`: `骑行`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/412`
### Rule 17
- `title`: `游戏`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/411`
### Rule 18
- `title`: `宠物`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/407`
### Rule 19
- `title`: `时尚`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/406`
### Rule 20
- `title`: `运动`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/403`
### Rule 21
- `title`: `应用`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/135`
### Rule 22
- `title`: `玩物`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/75`
### Rule 23
- `title`: `周边`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/19`
### Rule 24
- `title`: `文具`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/7`
### Rule 25
- `title`: `官方`
- `source`:
  - `www.dgtle.com/article`
- `target`: `/article/400`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [数码](https://www.dgtle.com/article)，其对应分类 ID 为 `20`，此时路由为 [`/dgtle/article/20`](https://rsshub.app/dgtle/article/20)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n| [全部](https://www.dgtle.com/article)   | [数码](https://www.dgtle.com/article)     | [手机](https://www.dgtle.com/article)     | [平板](https://www.dgtle.com/article)   | [笔电](https://www.dgtle.com/article)     |\n| --------------------------------------- | ----------------------------------------- | ----------------------------------------- | --------------------------------------- | ----------------------------------------- |\n| [0](https://rsshub.app/dgtle/article/0) | [20](https://rsshub.app/dgtle/article/20) | [18](https://rsshub.app/dgtle/article/18) | [4](https://rsshub.app/dgtle/article/4) | [17](https://rsshub.app/dgtle/article/17) |\n\n| [影音](https://www.dgtle.com/article)   | [汽车](https://www.dgtle.com/article)       | [视频](https://www.dgtle.com/article)       | [摄影](https://www.dgtle.com/article)     | [露营](https://www.dgtle.com/article)       |\n| --------------------------------------- | ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | ------------------------------------------- |\n| [5](https://rsshub.app/dgtle/article/5) | [401](https://rsshub.app/dgtle/article/401) | [395](https://rsshub.app/dgtle/article/395) | [22](https://rsshub.app/dgtle/article/22) | [405](https://rsshub.app/dgtle/article/405) |\n\n| [家装](https://www.dgtle.com/article)       | [活动](https://www.dgtle.com/article)       | [生活](https://www.dgtle.com/article)     | [旅行](https://www.dgtle.com/article)       | [骑行](https://www.dgtle.com/article)       |\n| ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | ------------------------------------------- | ------------------------------------------- |\n| [402](https://rsshub.app/dgtle/article/402) | [138](https://rsshub.app/dgtle/article/138) | [34](https://rsshub.app/dgtle/article/34) | [137](https://rsshub.app/dgtle/article/137) | [412](https://rsshub.app/dgtle/article/412) |\n\n| [游戏](https://www.dgtle.com/article)       | [宠物](https://www.dgtle.com/article)       | [时尚](https://www.dgtle.com/article)       | [运动](https://www.dgtle.com/article)       | [应用](https://www.dgtle.com/article)       |\n| ------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- |\n| [411](https://rsshub.app/dgtle/article/411) | [407](https://rsshub.app/dgtle/article/407) | [406](https://rsshub.app/dgtle/article/406) | [403](https://rsshub.app/dgtle/article/403) | [135](https://rsshub.app/dgtle/article/135) |\n\n| [玩物](https://www.dgtle.com/article)     | [周边](https://www.dgtle.com/article)     | [文具](https://www.dgtle.com/article)   | [官方](https://www.dgtle.com/article)       |\n| ----------------------------------------- | ----------------------------------------- | --------------------------------------- | ------------------------------------------- |\n| [75](https://rsshub.app/dgtle/article/75) | [19](https://rsshub.app/dgtle/article/19) | [7](https://rsshub.app/dgtle/article/7) | [400](https://rsshub.app/dgtle/article/400) |\n\n</details>",
  "example": "/dgtle/article/0/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "id": {
      "description": "分类，默认为 `0`，即最新，可在下表中找到",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "数码",
          "value": "20"
        },
        {
          "label": "手机",
          "value": "18"
        },
        {
          "label": "平板",
          "value": "4"
        },
        {
          "label": "笔电",
          "value": "17"
        },
        {
          "label": "影音",
          "value": "5"
        },
        {
          "label": "汽车",
          "value": "401"
        },
        {
          "label": "视频",
          "value": "395"
        },
        {
          "label": "摄影",
          "value": "22"
        },
        {
          "label": "露营",
          "value": "405"
        },
        {
          "label": "家装",
          "value": "402"
        },
        {
          "label": "活动",
          "value": "138"
        },
        {
          "label": "生活",
          "value": "34"
        },
        {
          "label": "旅行",
          "value": "137"
        },
        {
          "label": "骑行",
          "value": "412"
        },
        {
          "label": "游戏",
          "value": "411"
        },
        {
          "label": "宠物",
          "value": "407"
        },
        {
          "label": "时尚",
          "value": "406"
        },
        {
          "label": "运动",
          "value": "403"
        },
        {
          "label": "应用",
          "value": "135"
        },
        {
          "label": "玩物",
          "value": "75"
        },
        {
          "label": "周边",
          "value": "19"
        },
        {
          "label": "文具",
          "value": "7"
        },
        {
          "label": "官方",
          "value": "400"
        }
      ]
    },
    "pushed": {
      "description": "推送排序，默认为 `0`，即最新发布",
      "options": [
        {
          "label": "最新发布",
          "value": "0"
        },
        {
          "label": "首页推荐",
          "value": "1"
        }
      ]
    }
  },
  "path": "/article/:id?/:pushed?",
  "radar": [
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/0",
      "title": "全部"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/20",
      "title": "数码"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/18",
      "title": "手机"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/4",
      "title": "平板"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/17",
      "title": "笔电"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/5",
      "title": "影音"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/401",
      "title": "汽车"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/395",
      "title": "视频"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/22",
      "title": "摄影"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/405",
      "title": "露营"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/402",
      "title": "家装"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/138",
      "title": "活动"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/34",
      "title": "生活"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/137",
      "title": "旅行"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/412",
      "title": "骑行"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/411",
      "title": "游戏"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/407",
      "title": "宠物"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/406",
      "title": "时尚"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/403",
      "title": "运动"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/135",
      "title": "应用"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/75",
      "title": "玩物"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/19",
      "title": "周边"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/7",
      "title": "文具"
    },
    {
      "source": [
        "www.dgtle.com/article"
      ],
      "target": "/article/400",
      "title": "官方"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "致力于分享美好数字生活体验，囊括你闻所未闻的最丰富数码资讯，触所未触最抢鲜产品评测，随时随地感受尾巴们各式数字生活精彩图文、摄影感悟、旅行游记、爱物分享。旗下产品：精品电商平台「尾巴良品」 ；移动客户端「数字尾巴」 ，覆盖 iOS、Android 两大主流平台。 - Powered by RSSHub",
      "errorAt": "2026-08-16T23:26:30.921Z",
      "errorMessage": "[GET] \"https://www.dgtle.com/article\": <no response> fetch failed (Connect Timeout Error (attempted address: www.dgtle.com:443, timeout: 10000ms))\n",
      "id": "218636383991437312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dgtle.com/article",
      "title": "数字尾巴 - 全部",
      "type": "feed",
      "url": "rsshub://dgtle/article"
    }
  ],
  "url": "www.dgtle.com",
  "view": 0
}
```
