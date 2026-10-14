# 香港经济日报 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `hket`
- Namespace Name: `香港经济日报`
- Route Path: `/hket/:category?`
- Route Name: `新闻`
- Example: `/hket/sran001`
- URL: `www.hket.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
香港经济日报已有提供简单 RSS，详细可前往官方网站： <https://www.hket.com/rss>

此路由主要补全官方 RSS 全文输出及完善分类输出。

<details>
<summary>分类</summary>

| sran001  | sran008  | sran010  | sran011  | sran012  | srat006  |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 全部新闻 | 财经地产 | 科技信息 | 国际新闻 | 商业新闻 | 香港新闻 |

| sran009  | sran009-1 | sran009-2 | sran009-3  | sran009-4 | sran009-5 | sran009-6 |
| -------- | --------- | --------- | ---------- | --------- | --------- | --------- |
| 即时财经 | 股市      | 新股 IPO  | 新经济追踪 | 当炒股    | 宏观解读  | Hot Talk  |

| sran011-1 | sran011-2    | sran011-3    |
| --------- | ------------ | ------------ |
| 环球政治  | 环球经济金融 | 环球社会热点 |

| sran016    | sran016-1  | sran016-2  | sran016-3  | sran016-4  | sran016-5      |
| ---------- | ---------- | ---------- | ---------- | ---------- | -------------- |
| 大湾区主页 | 大湾区发展 | 大湾区工作 | 大湾区买楼 | 大湾区消费 | 大湾区投资理财 |

| srac002  | srac003  | srac004  | srac005  |
| -------- | -------- | -------- | -------- |
| 即时中国 | 经济脉搏 | 国情动向 | 社会热点 |

| srat001 | srat008 | srat055  | srat069  | srat070   |
| ------- | ------- | -------- | -------- | --------- |
| 话题    | 观点    | 休闲消费 | 娱乐新闻 | TOPick TV |

| srat052  | srat052-1 | srat052-2  | srat052-3 |
| -------- | --------- | ---------- | --------- |
| 健康主页 | 食用安全  | 医生诊症室 | 保健美颜  |

| srat053  | srat053-1 | srat053-2 | srat053-3 | srat053-4  |
| -------- | --------- | --------- | --------- | ---------- |
| 亲子主页 | 儿童健康  | 育儿经    | 教育      | 亲子好去处 |

| srat053-6   | srat053-61 | srat053-62 | srat053-63 | srat053-64 |
| ----------- | ---------- | ---------- | ---------- | ---------- |
| Band 1 学堂 | 幼稚园     | 中小学     | 尖子教室   | 海外升学   |

| srat072-1  | srat072-2  | srat072-3        | srat072-4         |
| ---------- | ---------- | ---------------- | ----------------- |
| 健康身心活 | 抗癌新方向 | 「糖」「心」解密 | 风湿不再 你我自在 |

| sraw007  | sraw009  | sraw010  | sraw011  | sraw012  | sraw014  | sraw018  | sraw019  |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 全部博客 | Bloggers | 收息攻略 | 精明消费 | 退休规划 | 个人增值 | 财富管理 | 绿色金融 |

| sraw015  | sraw015-07 | sraw015-08 | sraw015-09 | sraw015-10 |
| -------- | ---------- | ---------- | ---------- | ---------- |
| 移民百科 | 海外置业   | 移民攻略   | 移民点滴   | 海外理财   |

| sraw020  | sraw020-1    | sraw020-2 | sraw020-3 | sraw020-4 |
| -------- | ------------ | --------- | --------- | --------- |
| ESG 主页 | ESG 趋势政策 | ESG 投资  | ESG 企业  | ESG 社会  |

</details>

## Parameters
- `category`: 分类，默认为全部新闻，可在 URL 中找到，部分见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `china.hket.com/srac002`
  - `china.hket.com/srac002/*`
- `target`: `/srac002`
### Rule 2
- `source`:
  - `china.hket.com/srac003`
  - `china.hket.com/srac003/*`
- `target`: `/srac003`
### Rule 3
- `source`:
  - `china.hket.com/srac004`
  - `china.hket.com/srac004/*`
- `target`: `/srac004`
### Rule 4
- `source`:
  - `china.hket.com/srac005`
  - `china.hket.com/srac005/*`
- `target`: `/srac005`
### Rule 5
- `source`:
  - `inews.hket.com/sran001`
  - `inews.hket.com/sran001/*`
- `target`: `/sran001`
### Rule 6
- `source`:
  - `inews.hket.com/sran008`
  - `inews.hket.com/sran008/*`
- `target`: `/sran008`
### Rule 7
- `source`:
  - `inews.hket.com/sran010`
  - `inews.hket.com/sran010/*`
- `target`: `/sran010`
### Rule 8
- `source`:
  - `inews.hket.com/sran011`
  - `inews.hket.com/sran011/*`
- `target`: `/sran011`
### Rule 9
- `source`:
  - `inews.hket.com/sran012`
  - `inews.hket.com/sran012/*`
- `target`: `/sran012`
### Rule 10
- `source`:
  - `inews.hket.com/sran009`
  - `inews.hket.com/sran009/*`
- `target`: `/sran009`
### Rule 11
- `source`:
  - `inews.hket.com/sran009-1`
  - `inews.hket.com/sran009-1/*`
- `target`: `/sran009-1`
### Rule 12
- `source`:
  - `inews.hket.com/sran009-2`
  - `inews.hket.com/sran009-2/*`
- `target`: `/sran009-2`
### Rule 13
- `source`:
  - `inews.hket.com/sran009-3`
  - `inews.hket.com/sran009-3/*`
- `target`: `/sran009-3`
### Rule 14
- `source`:
  - `inews.hket.com/sran009-4`
  - `inews.hket.com/sran009-4/*`
- `target`: `/sran009-4`
### Rule 15
- `source`:
  - `inews.hket.com/sran009-5`
  - `inews.hket.com/sran009-5/*`
- `target`: `/sran009-5`
### Rule 16
- `source`:
  - `inews.hket.com/sran009-6`
  - `inews.hket.com/sran009-6/*`
- `target`: `/sran009-6`
### Rule 17
- `source`:
  - `inews.hket.com/sran011-1`
  - `inews.hket.com/sran011-1/*`
- `target`: `/sran011-1`
### Rule 18
- `source`:
  - `inews.hket.com/sran011-2`
  - `inews.hket.com/sran011-2/*`
- `target`: `/sran011-2`
### Rule 19
- `source`:
  - `inews.hket.com/sran011-3`
  - `inews.hket.com/sran011-3/*`
- `target`: `/sran011-3`
### Rule 20
- `source`:
  - `inews.hket.com/sran016`
  - `inews.hket.com/sran016/*`
- `target`: `/sran016`
### Rule 21
- `source`:
  - `inews.hket.com/sran016-1`
  - `inews.hket.com/sran016-1/*`
- `target`: `/sran016-1`
### Rule 22
- `source`:
  - `inews.hket.com/sran016-2`
  - `inews.hket.com/sran016-2/*`
- `target`: `/sran016-2`
### Rule 23
- `source`:
  - `inews.hket.com/sran016-3`
  - `inews.hket.com/sran016-3/*`
- `target`: `/sran016-3`
### Rule 24
- `source`:
  - `inews.hket.com/sran016-4`
  - `inews.hket.com/sran016-4/*`
- `target`: `/sran016-4`
### Rule 25
- `source`:
  - `inews.hket.com/sran016-5`
  - `inews.hket.com/sran016-5/*`
- `target`: `/sran016-5`
### Rule 26
- `source`:
  - `topick.hket.com/srat006`
  - `topick.hket.com/srat006/*`
- `target`: `/srat006`
### Rule 27
- `source`:
  - `topick.hket.com/srat001`
  - `topick.hket.com/srat001/*`
- `target`: `/srat001`
### Rule 28
- `source`:
  - `topick.hket.com/srat008`
  - `topick.hket.com/srat008/*`
- `target`: `/srat008`
### Rule 29
- `source`:
  - `topick.hket.com/srat055`
  - `topick.hket.com/srat055/*`
- `target`: `/srat055`
### Rule 30
- `source`:
  - `topick.hket.com/srat069`
  - `topick.hket.com/srat069/*`
- `target`: `/srat069`
### Rule 31
- `source`:
  - `topick.hket.com/srat070`
  - `topick.hket.com/srat070/*`
- `target`: `/srat070`
### Rule 32
- `source`:
  - `topick.hket.com/srat052`
  - `topick.hket.com/srat052/*`
- `target`: `/srat052`
### Rule 33
- `source`:
  - `topick.hket.com/srat052-1`
  - `topick.hket.com/srat052-1/*`
- `target`: `/srat052-1`
### Rule 34
- `source`:
  - `topick.hket.com/srat052-2`
  - `topick.hket.com/srat052-2/*`
- `target`: `/srat052-2`
### Rule 35
- `source`:
  - `topick.hket.com/srat052-3`
  - `topick.hket.com/srat052-3/*`
- `target`: `/srat052-3`
### Rule 36
- `source`:
  - `topick.hket.com/srat053`
  - `topick.hket.com/srat053/*`
- `target`: `/srat053`
### Rule 37
- `source`:
  - `topick.hket.com/srat053-1`
  - `topick.hket.com/srat053-1/*`
- `target`: `/srat053-1`
### Rule 38
- `source`:
  - `topick.hket.com/srat053-2`
  - `topick.hket.com/srat053-2/*`
- `target`: `/srat053-2`
### Rule 39
- `source`:
  - `topick.hket.com/srat053-3`
  - `topick.hket.com/srat053-3/*`
- `target`: `/srat053-3`
### Rule 40
- `source`:
  - `topick.hket.com/srat053-4`
  - `topick.hket.com/srat053-4/*`
- `target`: `/srat053-4`
### Rule 41
- `source`:
  - `topick.hket.com/srat053-6`
  - `topick.hket.com/srat053-6/*`
- `target`: `/srat053-6`
### Rule 42
- `source`:
  - `topick.hket.com/srat053-61`
  - `topick.hket.com/srat053-61/*`
- `target`: `/srat053-61`
### Rule 43
- `source`:
  - `topick.hket.com/srat053-62`
  - `topick.hket.com/srat053-62/*`
- `target`: `/srat053-62`
### Rule 44
- `source`:
  - `topick.hket.com/srat053-63`
  - `topick.hket.com/srat053-63/*`
- `target`: `/srat053-63`
### Rule 45
- `source`:
  - `topick.hket.com/srat053-64`
  - `topick.hket.com/srat053-64/*`
- `target`: `/srat053-64`
### Rule 46
- `source`:
  - `topick.hket.com/srat072-1`
  - `topick.hket.com/srat072-1/*`
- `target`: `/srat072-1`
### Rule 47
- `source`:
  - `topick.hket.com/srat072-2`
  - `topick.hket.com/srat072-2/*`
- `target`: `/srat072-2`
### Rule 48
- `source`:
  - `topick.hket.com/srat072-3`
  - `topick.hket.com/srat072-3/*`
- `target`: `/srat072-3`
### Rule 49
- `source`:
  - `topick.hket.com/srat072-4`
  - `topick.hket.com/srat072-4/*`
- `target`: `/srat072-4`
### Rule 50
- `source`:
  - `wealth.hket.com/sraw007`
  - `wealth.hket.com/sraw007/*`
- `target`: `/sraw007`
### Rule 51
- `source`:
  - `wealth.hket.com/sraw009`
  - `wealth.hket.com/sraw009/*`
- `target`: `/sraw009`
### Rule 52
- `source`:
  - `wealth.hket.com/sraw010`
  - `wealth.hket.com/sraw010/*`
- `target`: `/sraw010`
### Rule 53
- `source`:
  - `wealth.hket.com/sraw011`
  - `wealth.hket.com/sraw011/*`
- `target`: `/sraw011`
### Rule 54
- `source`:
  - `wealth.hket.com/sraw012`
  - `wealth.hket.com/sraw012/*`
- `target`: `/sraw012`
### Rule 55
- `source`:
  - `wealth.hket.com/sraw014`
  - `wealth.hket.com/sraw014/*`
- `target`: `/sraw014`
### Rule 56
- `source`:
  - `wealth.hket.com/sraw018`
  - `wealth.hket.com/sraw018/*`
- `target`: `/sraw018`
### Rule 57
- `source`:
  - `wealth.hket.com/sraw019`
  - `wealth.hket.com/sraw019/*`
- `target`: `/sraw019`
### Rule 58
- `source`:
  - `wealth.hket.com/sraw015`
  - `wealth.hket.com/sraw015/*`
- `target`: `/sraw015`
### Rule 59
- `source`:
  - `wealth.hket.com/sraw015-07`
  - `wealth.hket.com/sraw015-07/*`
- `target`: `/sraw015-07`
### Rule 60
- `source`:
  - `wealth.hket.com/sraw015-08`
  - `wealth.hket.com/sraw015-08/*`
- `target`: `/sraw015-08`
### Rule 61
- `source`:
  - `wealth.hket.com/sraw015-09`
  - `wealth.hket.com/sraw015-09/*`
- `target`: `/sraw015-09`
### Rule 62
- `source`:
  - `wealth.hket.com/sraw015-10`
  - `wealth.hket.com/sraw015-10/*`
- `target`: `/sraw015-10`
### Rule 63
- `source`:
  - `wealth.hket.com/sraw020`
  - `wealth.hket.com/sraw020/*`
- `target`: `/sraw020`
### Rule 64
- `source`:
  - `wealth.hket.com/sraw020-1`
  - `wealth.hket.com/sraw020-1/*`
- `target`: `/sraw020-1`
### Rule 65
- `source`:
  - `wealth.hket.com/sraw020-2`
  - `wealth.hket.com/sraw020-2/*`
- `target`: `/sraw020-2`
### Rule 66
- `source`:
  - `wealth.hket.com/sraw020-3`
  - `wealth.hket.com/sraw020-3/*`
- `target`: `/sraw020-3`
### Rule 67
- `source`:
  - `wealth.hket.com/sraw020-4`
  - `wealth.hket.com/sraw020-4/*`
- `target`: `/sraw020-4`
### Rule 68
- `source`:
  - `www.hket.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "香港经济日报已有提供简单 RSS，详细可前往官方网站： <https://www.hket.com/rss>\n\n此路由主要补全官方 RSS 全文输出及完善分类输出。\n\n<details>\n<summary>分类</summary>\n\n| sran001  | sran008  | sran010  | sran011  | sran012  | srat006  |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 全部新闻 | 财经地产 | 科技信息 | 国际新闻 | 商业新闻 | 香港新闻 |\n\n| sran009  | sran009-1 | sran009-2 | sran009-3  | sran009-4 | sran009-5 | sran009-6 |\n| -------- | --------- | --------- | ---------- | --------- | --------- | --------- |\n| 即时财经 | 股市      | 新股 IPO  | 新经济追踪 | 当炒股    | 宏观解读  | Hot Talk  |\n\n| sran011-1 | sran011-2    | sran011-3    |\n| --------- | ------------ | ------------ |\n| 环球政治  | 环球经济金融 | 环球社会热点 |\n\n| sran016    | sran016-1  | sran016-2  | sran016-3  | sran016-4  | sran016-5      |\n| ---------- | ---------- | ---------- | ---------- | ---------- | -------------- |\n| 大湾区主页 | 大湾区发展 | 大湾区工作 | 大湾区买楼 | 大湾区消费 | 大湾区投资理财 |\n\n| srac002  | srac003  | srac004  | srac005  |\n| -------- | -------- | -------- | -------- |\n| 即时中国 | 经济脉搏 | 国情动向 | 社会热点 |\n\n| srat001 | srat008 | srat055  | srat069  | srat070   |\n| ------- | ------- | -------- | -------- | --------- |\n| 话题    | 观点    | 休闲消费 | 娱乐新闻 | TOPick TV |\n\n| srat052  | srat052-1 | srat052-2  | srat052-3 |\n| -------- | --------- | ---------- | --------- |\n| 健康主页 | 食用安全  | 医生诊症室 | 保健美颜  |\n\n| srat053  | srat053-1 | srat053-2 | srat053-3 | srat053-4  |\n| -------- | --------- | --------- | --------- | ---------- |\n| 亲子主页 | 儿童健康  | 育儿经    | 教育      | 亲子好去处 |\n\n| srat053-6   | srat053-61 | srat053-62 | srat053-63 | srat053-64 |\n| ----------- | ---------- | ---------- | ---------- | ---------- |\n| Band 1 学堂 | 幼稚园     | 中小学     | 尖子教室   | 海外升学   |\n\n| srat072-1  | srat072-2  | srat072-3        | srat072-4         |\n| ---------- | ---------- | ---------------- | ----------------- |\n| 健康身心活 | 抗癌新方向 | 「糖」「心」解密 | 风湿不再 你我自在 |\n\n| sraw007  | sraw009  | sraw010  | sraw011  | sraw012  | sraw014  | sraw018  | sraw019  |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 全部博客 | Bloggers | 收息攻略 | 精明消费 | 退休规划 | 个人增值 | 财富管理 | 绿色金融 |\n\n| sraw015  | sraw015-07 | sraw015-08 | sraw015-09 | sraw015-10 |\n| -------- | ---------- | ---------- | ---------- | ---------- |\n| 移民百科 | 海外置业   | 移民攻略   | 移民点滴   | 海外理财   |\n\n| sraw020  | sraw020-1    | sraw020-2 | sraw020-3 | sraw020-4 |\n| -------- | ------------ | --------- | --------- | --------- |\n| ESG 主页 | ESG 趋势政策 | ESG 投资  | ESG 企业  | ESG 社会  |\n\n</details>",
  "example": "/hket/sran001",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类，默认为全部新闻，可在 URL 中找到，部分见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "china.hket.com/srac002",
        "china.hket.com/srac002/*"
      ],
      "target": "/srac002"
    },
    {
      "source": [
        "china.hket.com/srac003",
        "china.hket.com/srac003/*"
      ],
      "target": "/srac003"
    },
    {
      "source": [
        "china.hket.com/srac004",
        "china.hket.com/srac004/*"
      ],
      "target": "/srac004"
    },
    {
      "source": [
        "china.hket.com/srac005",
        "china.hket.com/srac005/*"
      ],
      "target": "/srac005"
    },
    {
      "source": [
        "inews.hket.com/sran001",
        "inews.hket.com/sran001/*"
      ],
      "target": "/sran001"
    },
    {
      "source": [
        "inews.hket.com/sran008",
        "inews.hket.com/sran008/*"
      ],
      "target": "/sran008"
    },
    {
      "source": [
        "inews.hket.com/sran010",
        "inews.hket.com/sran010/*"
      ],
      "target": "/sran010"
    },
    {
      "source": [
        "inews.hket.com/sran011",
        "inews.hket.com/sran011/*"
      ],
      "target": "/sran011"
    },
    {
      "source": [
        "inews.hket.com/sran012",
        "inews.hket.com/sran012/*"
      ],
      "target": "/sran012"
    },
    {
      "source": [
        "inews.hket.com/sran009",
        "inews.hket.com/sran009/*"
      ],
      "target": "/sran009"
    },
    {
      "source": [
        "inews.hket.com/sran009-1",
        "inews.hket.com/sran009-1/*"
      ],
      "target": "/sran009-1"
    },
    {
      "source": [
        "inews.hket.com/sran009-2",
        "inews.hket.com/sran009-2/*"
      ],
      "target": "/sran009-2"
    },
    {
      "source": [
        "inews.hket.com/sran009-3",
        "inews.hket.com/sran009-3/*"
      ],
      "target": "/sran009-3"
    },
    {
      "source": [
        "inews.hket.com/sran009-4",
        "inews.hket.com/sran009-4/*"
      ],
      "target": "/sran009-4"
    },
    {
      "source": [
        "inews.hket.com/sran009-5",
        "inews.hket.com/sran009-5/*"
      ],
      "target": "/sran009-5"
    },
    {
      "source": [
        "inews.hket.com/sran009-6",
        "inews.hket.com/sran009-6/*"
      ],
      "target": "/sran009-6"
    },
    {
      "source": [
        "inews.hket.com/sran011-1",
        "inews.hket.com/sran011-1/*"
      ],
      "target": "/sran011-1"
    },
    {
      "source": [
        "inews.hket.com/sran011-2",
        "inews.hket.com/sran011-2/*"
      ],
      "target": "/sran011-2"
    },
    {
      "source": [
        "inews.hket.com/sran011-3",
        "inews.hket.com/sran011-3/*"
      ],
      "target": "/sran011-3"
    },
    {
      "source": [
        "inews.hket.com/sran016",
        "inews.hket.com/sran016/*"
      ],
      "target": "/sran016"
    },
    {
      "source": [
        "inews.hket.com/sran016-1",
        "inews.hket.com/sran016-1/*"
      ],
      "target": "/sran016-1"
    },
    {
      "source": [
        "inews.hket.com/sran016-2",
        "inews.hket.com/sran016-2/*"
      ],
      "target": "/sran016-2"
    },
    {
      "source": [
        "inews.hket.com/sran016-3",
        "inews.hket.com/sran016-3/*"
      ],
      "target": "/sran016-3"
    },
    {
      "source": [
        "inews.hket.com/sran016-4",
        "inews.hket.com/sran016-4/*"
      ],
      "target": "/sran016-4"
    },
    {
      "source": [
        "inews.hket.com/sran016-5",
        "inews.hket.com/sran016-5/*"
      ],
      "target": "/sran016-5"
    },
    {
      "source": [
        "topick.hket.com/srat006",
        "topick.hket.com/srat006/*"
      ],
      "target": "/srat006"
    },
    {
      "source": [
        "topick.hket.com/srat001",
        "topick.hket.com/srat001/*"
      ],
      "target": "/srat001"
    },
    {
      "source": [
        "topick.hket.com/srat008",
        "topick.hket.com/srat008/*"
      ],
      "target": "/srat008"
    },
    {
      "source": [
        "topick.hket.com/srat055",
        "topick.hket.com/srat055/*"
      ],
      "target": "/srat055"
    },
    {
      "source": [
        "topick.hket.com/srat069",
        "topick.hket.com/srat069/*"
      ],
      "target": "/srat069"
    },
    {
      "source": [
        "topick.hket.com/srat070",
        "topick.hket.com/srat070/*"
      ],
      "target": "/srat070"
    },
    {
      "source": [
        "topick.hket.com/srat052",
        "topick.hket.com/srat052/*"
      ],
      "target": "/srat052"
    },
    {
      "source": [
        "topick.hket.com/srat052-1",
        "topick.hket.com/srat052-1/*"
      ],
      "target": "/srat052-1"
    },
    {
      "source": [
        "topick.hket.com/srat052-2",
        "topick.hket.com/srat052-2/*"
      ],
      "target": "/srat052-2"
    },
    {
      "source": [
        "topick.hket.com/srat052-3",
        "topick.hket.com/srat052-3/*"
      ],
      "target": "/srat052-3"
    },
    {
      "source": [
        "topick.hket.com/srat053",
        "topick.hket.com/srat053/*"
      ],
      "target": "/srat053"
    },
    {
      "source": [
        "topick.hket.com/srat053-1",
        "topick.hket.com/srat053-1/*"
      ],
      "target": "/srat053-1"
    },
    {
      "source": [
        "topick.hket.com/srat053-2",
        "topick.hket.com/srat053-2/*"
      ],
      "target": "/srat053-2"
    },
    {
      "source": [
        "topick.hket.com/srat053-3",
        "topick.hket.com/srat053-3/*"
      ],
      "target": "/srat053-3"
    },
    {
      "source": [
        "topick.hket.com/srat053-4",
        "topick.hket.com/srat053-4/*"
      ],
      "target": "/srat053-4"
    },
    {
      "source": [
        "topick.hket.com/srat053-6",
        "topick.hket.com/srat053-6/*"
      ],
      "target": "/srat053-6"
    },
    {
      "source": [
        "topick.hket.com/srat053-61",
        "topick.hket.com/srat053-61/*"
      ],
      "target": "/srat053-61"
    },
    {
      "source": [
        "topick.hket.com/srat053-62",
        "topick.hket.com/srat053-62/*"
      ],
      "target": "/srat053-62"
    },
    {
      "source": [
        "topick.hket.com/srat053-63",
        "topick.hket.com/srat053-63/*"
      ],
      "target": "/srat053-63"
    },
    {
      "source": [
        "topick.hket.com/srat053-64",
        "topick.hket.com/srat053-64/*"
      ],
      "target": "/srat053-64"
    },
    {
      "source": [
        "topick.hket.com/srat072-1",
        "topick.hket.com/srat072-1/*"
      ],
      "target": "/srat072-1"
    },
    {
      "source": [
        "topick.hket.com/srat072-2",
        "topick.hket.com/srat072-2/*"
      ],
      "target": "/srat072-2"
    },
    {
      "source": [
        "topick.hket.com/srat072-3",
        "topick.hket.com/srat072-3/*"
      ],
      "target": "/srat072-3"
    },
    {
      "source": [
        "topick.hket.com/srat072-4",
        "topick.hket.com/srat072-4/*"
      ],
      "target": "/srat072-4"
    },
    {
      "source": [
        "wealth.hket.com/sraw007",
        "wealth.hket.com/sraw007/*"
      ],
      "target": "/sraw007"
    },
    {
      "source": [
        "wealth.hket.com/sraw009",
        "wealth.hket.com/sraw009/*"
      ],
      "target": "/sraw009"
    },
    {
      "source": [
        "wealth.hket.com/sraw010",
        "wealth.hket.com/sraw010/*"
      ],
      "target": "/sraw010"
    },
    {
      "source": [
        "wealth.hket.com/sraw011",
        "wealth.hket.com/sraw011/*"
      ],
      "target": "/sraw011"
    },
    {
      "source": [
        "wealth.hket.com/sraw012",
        "wealth.hket.com/sraw012/*"
      ],
      "target": "/sraw012"
    },
    {
      "source": [
        "wealth.hket.com/sraw014",
        "wealth.hket.com/sraw014/*"
      ],
      "target": "/sraw014"
    },
    {
      "source": [
        "wealth.hket.com/sraw018",
        "wealth.hket.com/sraw018/*"
      ],
      "target": "/sraw018"
    },
    {
      "source": [
        "wealth.hket.com/sraw019",
        "wealth.hket.com/sraw019/*"
      ],
      "target": "/sraw019"
    },
    {
      "source": [
        "wealth.hket.com/sraw015",
        "wealth.hket.com/sraw015/*"
      ],
      "target": "/sraw015"
    },
    {
      "source": [
        "wealth.hket.com/sraw015-07",
        "wealth.hket.com/sraw015-07/*"
      ],
      "target": "/sraw015-07"
    },
    {
      "source": [
        "wealth.hket.com/sraw015-08",
        "wealth.hket.com/sraw015-08/*"
      ],
      "target": "/sraw015-08"
    },
    {
      "source": [
        "wealth.hket.com/sraw015-09",
        "wealth.hket.com/sraw015-09/*"
      ],
      "target": "/sraw015-09"
    },
    {
      "source": [
        "wealth.hket.com/sraw015-10",
        "wealth.hket.com/sraw015-10/*"
      ],
      "target": "/sraw015-10"
    },
    {
      "source": [
        "wealth.hket.com/sraw020",
        "wealth.hket.com/sraw020/*"
      ],
      "target": "/sraw020"
    },
    {
      "source": [
        "wealth.hket.com/sraw020-1",
        "wealth.hket.com/sraw020-1/*"
      ],
      "target": "/sraw020-1"
    },
    {
      "source": [
        "wealth.hket.com/sraw020-2",
        "wealth.hket.com/sraw020-2/*"
      ],
      "target": "/sraw020-2"
    },
    {
      "source": [
        "wealth.hket.com/sraw020-3",
        "wealth.hket.com/sraw020-3/*"
      ],
      "target": "/sraw020-3"
    },
    {
      "source": [
        "wealth.hket.com/sraw020-4",
        "wealth.hket.com/sraw020-4/*"
      ],
      "target": "/sraw020-4"
    },
    {
      "source": [
        "www.hket.com/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "提供最新國際新聞、香港新聞、財經新聞、地產樓市新聞, 美股即時新聞、即時夜期、中國新聞及科技新聞等。 - Powered by RSSHub",
      "errorAt": "2026-09-21T13:36:05.874Z",
      "errorMessage": "[GET] \"https://inews.hket.com/sran001\": 405 Method Not Allowed\n",
      "id": "94630255063479296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews.hket.com/sran001",
      "title": "國際地產財經中國即時新聞 | HKET經濟日報 | 即時新聞頻道",
      "type": "feed",
      "url": "rsshub://hket"
    },
    {
      "description": "提供最新國際新聞、香港新聞、財經新聞、地產樓市新聞, 美股即時新聞、即時夜期、中國新聞及科技新聞等。 - Powered by RSSHub",
      "errorAt": "2026-09-05T05:02:04.648Z",
      "errorMessage": "[GET] \"https://inews.hket.com/sran001\": 405 Method Not Allowed\n",
      "id": "70034910422682624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews.hket.com/sran001",
      "title": "國際地產財經中國即時新聞 | HKET經濟日報 | 即時新聞頻道",
      "type": "feed",
      "url": "rsshub://hket/sran001"
    }
  ],
  "url": "www.hket.com/"
}
```
