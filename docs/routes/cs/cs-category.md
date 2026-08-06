# 中证网 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cs`
- Namespace Name: `中证网`
- Route Path: `/cs/:category{.+}?`
- Route Name: `栏目`
- Example: `/cs`
- URL: `www.cs.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 要闻 | 公司 | 市场 | 基金 |
| ---- | ---- | ---- | ---- |
| xwzx | ssgs | gppd | tzjj |

| 科创 | 产经   | 期货     | 海外   |
| ---- | ------ | -------- | ------ |
| 5g   | cj2020 | zzqh2020 | hw2020 |

<details>
<summary>更多栏目</summary>

#### 要闻

| 财经要闻 | 观点评论 | 民生消费  |
| -------- | -------- | --------- |
| xwzx/hg  | xwzx/jr  | xwzx/msxf |

#### 公司

| 公司要闻  | 公司深度  | 公司巡礼  |
| --------- | --------- | --------- |
| ssgs/gsxw | ssgs/gssd | ssgs/gsxl |

#### 市场

| A 股市场  | 港股资讯  | 债市研究  | 海外报道  | 期货报道  |
| --------- | --------- | --------- | --------- | --------- |
| gppd/gsyj | gppd/ggzx | gppd/zqxw | gppd/hwbd | gppd/qhbd |

#### 基金

| 基金动态  | 基金视点  | 基金持仓  | 私募基金  | 基民学苑  |
| --------- | --------- | --------- | --------- | --------- |
| tzjj/jjdt | tzjj/jjks | tzjj/jjcs | tzjj/smjj | tzjj/tjdh |

#### 机构

| 券商 | 银行 | 保险 |
| ---- | ---- | ---- |
| qs   | yh   | bx   |

#### 其他

| 中证快讯 7x24 | IPO 鉴真 | 公司能见度 |
| ------------- | -------- | ---------- |
| sylm/jsbd     | yc/ipojz | yc/gsnjd   |

</details>

## Parameters
- `category`: 分类，见下表，默认为要闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `要闻`
- `source`:
  - `cs.com.cn/xwzx/`
- `target`: `/xwzx`
### Rule 2
- `title`: `公司`
- `source`:
  - `cs.com.cn/ssgs/`
- `target`: `/ssgs`
### Rule 3
- `title`: `市场`
- `source`:
  - `cs.com.cn/gppd/`
- `target`: `/gppd`
### Rule 4
- `title`: `基金`
- `source`:
  - `cs.com.cn/tzjj/`
- `target`: `/tzjj`
### Rule 5
- `title`: `科创`
- `source`:
  - `cs.com.cn/5g/`
- `target`: `/5g`
### Rule 6
- `title`: `产经`
- `source`:
  - `cs.com.cn/cj2020/`
- `target`: `/cj2020`
### Rule 7
- `title`: `期货`
- `source`:
  - `cs.com.cn/zzqh2020/`
- `target`: `/zzqh2020`
### Rule 8
- `title`: `海外`
- `source`:
  - `cs.com.cn/hw2020/`
- `target`: `/hw2020`
### Rule 9
- `title`: `财经要闻`
- `source`:
  - `cs.com.cn/xwzx/hg/`
- `target`: `/xwzx/hg`
### Rule 10
- `title`: `观点评论`
- `source`:
  - `cs.com.cn/xwzx/jr/`
- `target`: `/xwzx/jr`
### Rule 11
- `title`: `民生消费`
- `source`:
  - `cs.com.cn/xwzx/msxf/`
- `target`: `/xwzx/msxf`
### Rule 12
- `title`: `公司要闻`
- `source`:
  - `cs.com.cn/ssgs/gsxw/`
- `target`: `/ssgs/gsxw`
### Rule 13
- `title`: `公司深度`
- `source`:
  - `cs.com.cn/ssgs/gssd/`
- `target`: `/ssgs/gssd`
### Rule 14
- `title`: `公司巡礼`
- `source`:
  - `cs.com.cn/ssgs/gsxl/`
- `target`: `/ssgs/gsxl`
### Rule 15
- `title`: `A股市场`
- `source`:
  - `cs.com.cn/gppd/gsyj/`
- `target`: `/gppd/gsyj`
### Rule 16
- `title`: `港股资讯`
- `source`:
  - `cs.com.cn/gppd/ggzx/`
- `target`: `/gppd/ggzx`
### Rule 17
- `title`: `债市研究`
- `source`:
  - `cs.com.cn/gppd/zqxw/`
- `target`: `/gppd/zqxw`
### Rule 18
- `title`: `海外报道`
- `source`:
  - `cs.com.cn/gppd/hwbd/`
- `target`: `/gppd/hwbd`
### Rule 19
- `title`: `期货报道`
- `source`:
  - `cs.com.cn/gppd/qhbd/`
- `target`: `/gppd/qhbd`
### Rule 20
- `title`: `基金动态`
- `source`:
  - `cs.com.cn/tzjj/jjdt/`
- `target`: `/tzjj/jjdt`
### Rule 21
- `title`: `基金视点`
- `source`:
  - `cs.com.cn/tzjj/jjks/`
- `target`: `/tzjj/jjks`
### Rule 22
- `title`: `基金持仓`
- `source`:
  - `cs.com.cn/tzjj/jjcs/`
- `target`: `/tzjj/jjcs`
### Rule 23
- `title`: `私募基金`
- `source`:
  - `cs.com.cn/tzjj/smjj/`
- `target`: `/tzjj/smjj`
### Rule 24
- `title`: `基民学苑`
- `source`:
  - `cs.com.cn/tzjj/tjdh/`
- `target`: `/tzjj/tjdh`
### Rule 25
- `title`: `券商`
- `source`:
  - `cs.com.cn/qs/`
- `target`: `/qs`
### Rule 26
- `title`: `银行`
- `source`:
  - `cs.com.cn/yh/`
- `target`: `/yh`
### Rule 27
- `title`: `保险`
- `source`:
  - `cs.com.cn/bx/`
- `target`: `/bx`
### Rule 28
- `title`: `中证快讯 7x24`
- `source`:
  - `cs.com.cn/sylm/jsbd/`
- `target`: `/sylm/jsbd`
### Rule 29
- `title`: `IPO鉴真`
- `source`:
  - `cs.com.cn/yc/ipojz/`
- `target`: `/yc/ipojz`
### Rule 30
- `title`: `公司能见度`
- `source`:
  - `cs.com.cn/yc/gsnjd/`
- `target`: `/yc/gsnjd`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 要闻 | 公司 | 市场 | 基金 |\n| ---- | ---- | ---- | ---- |\n| xwzx | ssgs | gppd | tzjj |\n\n| 科创 | 产经   | 期货     | 海外   |\n| ---- | ------ | -------- | ------ |\n| 5g   | cj2020 | zzqh2020 | hw2020 |\n\n<details>\n<summary>更多栏目</summary>\n\n#### 要闻\n\n| 财经要闻 | 观点评论 | 民生消费  |\n| -------- | -------- | --------- |\n| xwzx/hg  | xwzx/jr  | xwzx/msxf |\n\n#### 公司\n\n| 公司要闻  | 公司深度  | 公司巡礼  |\n| --------- | --------- | --------- |\n| ssgs/gsxw | ssgs/gssd | ssgs/gsxl |\n\n#### 市场\n\n| A 股市场  | 港股资讯  | 债市研究  | 海外报道  | 期货报道  |\n| --------- | --------- | --------- | --------- | --------- |\n| gppd/gsyj | gppd/ggzx | gppd/zqxw | gppd/hwbd | gppd/qhbd |\n\n#### 基金\n\n| 基金动态  | 基金视点  | 基金持仓  | 私募基金  | 基民学苑  |\n| --------- | --------- | --------- | --------- | --------- |\n| tzjj/jjdt | tzjj/jjks | tzjj/jjcs | tzjj/smjj | tzjj/tjdh |\n\n#### 机构\n\n| 券商 | 银行 | 保险 |\n| ---- | ---- | ---- |\n| qs   | yh   | bx   |\n\n#### 其他\n\n| 中证快讯 7x24 | IPO 鉴真 | 公司能见度 |\n| ------------- | -------- | ---------- |\n| sylm/jsbd     | yc/ipojz | yc/gsnjd   |\n\n</details>",
  "example": "/cs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 347,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "category": "分类，见下表，默认为要闻"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "cs.com.cn/xwzx/"
      ],
      "target": "/xwzx",
      "title": "要闻"
    },
    {
      "source": [
        "cs.com.cn/ssgs/"
      ],
      "target": "/ssgs",
      "title": "公司"
    },
    {
      "source": [
        "cs.com.cn/gppd/"
      ],
      "target": "/gppd",
      "title": "市场"
    },
    {
      "source": [
        "cs.com.cn/tzjj/"
      ],
      "target": "/tzjj",
      "title": "基金"
    },
    {
      "source": [
        "cs.com.cn/5g/"
      ],
      "target": "/5g",
      "title": "科创"
    },
    {
      "source": [
        "cs.com.cn/cj2020/"
      ],
      "target": "/cj2020",
      "title": "产经"
    },
    {
      "source": [
        "cs.com.cn/zzqh2020/"
      ],
      "target": "/zzqh2020",
      "title": "期货"
    },
    {
      "source": [
        "cs.com.cn/hw2020/"
      ],
      "target": "/hw2020",
      "title": "海外"
    },
    {
      "source": [
        "cs.com.cn/xwzx/hg/"
      ],
      "target": "/xwzx/hg",
      "title": "财经要闻"
    },
    {
      "source": [
        "cs.com.cn/xwzx/jr/"
      ],
      "target": "/xwzx/jr",
      "title": "观点评论"
    },
    {
      "source": [
        "cs.com.cn/xwzx/msxf/"
      ],
      "target": "/xwzx/msxf",
      "title": "民生消费"
    },
    {
      "source": [
        "cs.com.cn/ssgs/gsxw/"
      ],
      "target": "/ssgs/gsxw",
      "title": "公司要闻"
    },
    {
      "source": [
        "cs.com.cn/ssgs/gssd/"
      ],
      "target": "/ssgs/gssd",
      "title": "公司深度"
    },
    {
      "source": [
        "cs.com.cn/ssgs/gsxl/"
      ],
      "target": "/ssgs/gsxl",
      "title": "公司巡礼"
    },
    {
      "source": [
        "cs.com.cn/gppd/gsyj/"
      ],
      "target": "/gppd/gsyj",
      "title": "A股市场"
    },
    {
      "source": [
        "cs.com.cn/gppd/ggzx/"
      ],
      "target": "/gppd/ggzx",
      "title": "港股资讯"
    },
    {
      "source": [
        "cs.com.cn/gppd/zqxw/"
      ],
      "target": "/gppd/zqxw",
      "title": "债市研究"
    },
    {
      "source": [
        "cs.com.cn/gppd/hwbd/"
      ],
      "target": "/gppd/hwbd",
      "title": "海外报道"
    },
    {
      "source": [
        "cs.com.cn/gppd/qhbd/"
      ],
      "target": "/gppd/qhbd",
      "title": "期货报道"
    },
    {
      "source": [
        "cs.com.cn/tzjj/jjdt/"
      ],
      "target": "/tzjj/jjdt",
      "title": "基金动态"
    },
    {
      "source": [
        "cs.com.cn/tzjj/jjks/"
      ],
      "target": "/tzjj/jjks",
      "title": "基金视点"
    },
    {
      "source": [
        "cs.com.cn/tzjj/jjcs/"
      ],
      "target": "/tzjj/jjcs",
      "title": "基金持仓"
    },
    {
      "source": [
        "cs.com.cn/tzjj/smjj/"
      ],
      "target": "/tzjj/smjj",
      "title": "私募基金"
    },
    {
      "source": [
        "cs.com.cn/tzjj/tjdh/"
      ],
      "target": "/tzjj/tjdh",
      "title": "基民学苑"
    },
    {
      "source": [
        "cs.com.cn/qs/"
      ],
      "target": "/qs",
      "title": "券商"
    },
    {
      "source": [
        "cs.com.cn/yh/"
      ],
      "target": "/yh",
      "title": "银行"
    },
    {
      "source": [
        "cs.com.cn/bx/"
      ],
      "target": "/bx",
      "title": "保险"
    },
    {
      "source": [
        "cs.com.cn/sylm/jsbd/"
      ],
      "target": "/sylm/jsbd",
      "title": "中证快讯 7x24"
    },
    {
      "source": [
        "cs.com.cn/yc/ipojz/"
      ],
      "target": "/yc/ipojz",
      "title": "IPO鉴真"
    },
    {
      "source": [
        "cs.com.cn/yc/gsnjd/"
      ],
      "target": "/yc/gsnjd",
      "title": "公司能见度"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中证新闻中心致力于为用户提供实时专业财经证券资讯,事件报导,国际国内新闻要点，覆盖宏观经济,金融市场,商业动态,上市公司,投资理财等全方位信息； - Powered by RSSHub",
      "errorAt": "2026-04-03T19:41:37.200Z",
      "errorMessage": "[GET] \"https://www.cs.com.cn/gppd/gsyj/\": 403 Forbidden\n[GET] \"https://www.cs.com.cn/gppd/gsyj/\": 403 Forbidden\n[GET] \"https://www.cs.com.cn/gppd/gsyj/\": 403 Forbidden\n",
      "id": "72507750372854784",
      "image": "https://www.cs.com.cn/images/cslogo-2018.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cs.com.cn/gppd/gsyj/",
      "title": "A股市场 - 中证网",
      "type": "feed",
      "url": "rsshub://cs/gppd/gsyj"
    },
    {
      "description": "中证新闻中心致力于为用户提供实时专业财经证券资讯,事件报导,国际国内新闻要点，覆盖宏观经济,金融市场,商业动态,上市公司,投资理财等全方位信息； - Powered by RSSHub",
      "errorAt": "2026-04-03T16:16:55.439Z",
      "errorMessage": "[GET] \"https://www.cs.com.cn/gppd/ggzx/\": 403 Forbidden\n[GET] \"https://www.cs.com.cn/gppd/ggzx/\": 403 Forbidden\n",
      "id": "72507895798413312",
      "image": "https://www.cs.com.cn/images/cslogo-2018.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cs.com.cn/gppd/ggzx/",
      "title": "港股资讯 - 中证网",
      "type": "feed",
      "url": "rsshub://cs/gppd/ggzx"
    }
  ],
  "url": "www.cs.com.cn"
}
```
