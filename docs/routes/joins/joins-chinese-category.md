# 中央日报 - 中央日报中文版

## Coverage
`index-only`

## Route
- Namespace: `joins`
- Namespace Name: `中央日报`
- Route Path: `/joins/chinese/:category?`
- Route Name: `中央日报中文版`
- Example: `/joins/chinese`
- URL: `chinese.joins.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `chinese.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [财经](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1)，网址为 `https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1`。截取 `sc_section_code` 的值作为参数填入，此时路由为 [`/joins/chinese/S1N1`](https://rsshub.app/joins/chinese/S1N1)。
:::

| 分类                                                                                        | `sc_section_code`                               |
| ------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [财经](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1)                | [S1N1](https://rsshub.app/joins/chinese/S1N1)   |
| [国际](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N2)                | [S1N2](https://rsshub.app/joins/chinese/S1N2)   |
| [北韩](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N3)                | [S1N3](https://rsshub.app/joins/chinese/S1N3)   |
| [政治・社会](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N4)          | [S1N4](https://rsshub.app/joins/chinese/S1N4)   |
| [中国观察](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N5)            | [S1N5](https://rsshub.app/joins/chinese/S1N5)   |
| [社论](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N26)               | [S1N26](https://rsshub.app/joins/chinese/S1N26) |
| [专栏・观点](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N11)         | [S1N11](https://rsshub.app/joins/chinese/S1N11) |
| [军事・科技](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N6)          | [S1N6](https://rsshub.app/joins/chinese/S1N6)   |
| [娱乐体育](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N7)            | [S1N7](https://rsshub.app/joins/chinese/S1N7)   |
| [教育](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N8)                | [S1N8](https://rsshub.app/joins/chinese/S1N8)   |
| [旅游美食](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N9)            | [S1N9](https://rsshub.app/joins/chinese/S1N9)   |
| [时尚](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N10)               | [S1N10](https://rsshub.app/joins/chinese/S1N10) |
| [图集](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N12\&view_type=tm) | [S1N12](https://rsshub.app/joins/chinese/S1N12) |

## Parameters
- `category`: 分类，默认为空，可在对应分类页 URL 中找到 `sc_section_code`


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
  - `chinese.joins.com/news/articleList.html`
### Rule 2
- `title`: `财经`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N1`
### Rule 3
- `title`: `国际`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N2`
### Rule 4
- `title`: `北韩`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N3`
### Rule 5
- `title`: `政治·社会`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N4`
### Rule 6
- `title`: `中国观察`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N5`
### Rule 7
- `title`: `社论`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N26`
### Rule 8
- `title`: `专栏·观点`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N11`
### Rule 9
- `title`: `军事·科技`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N6`
### Rule 10
- `title`: `娱乐体育`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N7`
### Rule 11
- `title`: `教育`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N8`
### Rule 12
- `title`: `旅游美食`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N9`
### Rule 13
- `title`: `时尚`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N10`
### Rule 14
- `title`: `图集`
- `source`:
  - `chinese.joins.com/news/articleList.html`
- `target`: `/chinese/S1N12`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n若订阅 [财经](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1)，网址为 `https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1`。截取 `sc_section_code` 的值作为参数填入，此时路由为 [`/joins/chinese/S1N1`](https://rsshub.app/joins/chinese/S1N1)。\n:::\n\n| 分类                                                                                        | `sc_section_code`                               |\n| ------------------------------------------------------------------------------------------- | ----------------------------------------------- |\n| [财经](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N1)                | [S1N1](https://rsshub.app/joins/chinese/S1N1)   |\n| [国际](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N2)                | [S1N2](https://rsshub.app/joins/chinese/S1N2)   |\n| [北韩](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N3)                | [S1N3](https://rsshub.app/joins/chinese/S1N3)   |\n| [政治・社会](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N4)          | [S1N4](https://rsshub.app/joins/chinese/S1N4)   |\n| [中国观察](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N5)            | [S1N5](https://rsshub.app/joins/chinese/S1N5)   |\n| [社论](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N26)               | [S1N26](https://rsshub.app/joins/chinese/S1N26) |\n| [专栏・观点](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N11)         | [S1N11](https://rsshub.app/joins/chinese/S1N11) |\n| [军事・科技](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N6)          | [S1N6](https://rsshub.app/joins/chinese/S1N6)   |\n| [娱乐体育](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N7)            | [S1N7](https://rsshub.app/joins/chinese/S1N7)   |\n| [教育](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N8)                | [S1N8](https://rsshub.app/joins/chinese/S1N8)   |\n| [旅游美食](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N9)            | [S1N9](https://rsshub.app/joins/chinese/S1N9)   |\n| [时尚](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N10)               | [S1N10](https://rsshub.app/joins/chinese/S1N10) |\n| [图集](https://chinese.joins.com/news/articleList.html?sc_section_code=S1N12\\&view_type=tm) | [S1N12](https://rsshub.app/joins/chinese/S1N12) |",
  "example": "/joins/chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 74,
  "location": "chinese.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中央日报中文版",
  "parameters": {
    "category": "分类，默认为空，可在对应分类页 URL 中找到 `sc_section_code`"
  },
  "path": "/chinese/:category?",
  "radar": [
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ]
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N1",
      "title": "财经"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N2",
      "title": "国际"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N3",
      "title": "北韩"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N4",
      "title": "政治·社会"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N5",
      "title": "中国观察"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N26",
      "title": "社论"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N11",
      "title": "专栏·观点"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N6",
      "title": "军事·科技"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N7",
      "title": "娱乐体育"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N8",
      "title": "教育"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N9",
      "title": "旅游美食"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N10",
      "title": "时尚"
    },
    {
      "source": [
        "chinese.joins.com/news/articleList.html"
      ],
      "target": "/chinese/S1N12",
      "title": "图集"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "인터넷 신문 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67015768687931392",
      "image": "https://chinese.joins.com/image/logo/toplogo_20200319051833.png",
      "ownerUserId": null,
      "siteUrl": "https://chinese.joins.com/news/articleList.html?view_type=s",
      "title": "最新报道 - 韩国最大的传媒机构《中央日报》中文网",
      "type": "feed",
      "url": "rsshub://joins/chinese"
    },
    {
      "description": "인터넷 신문 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65469694593591296",
      "image": "https://chinese.joins.com/image/logo/toplogo_20200319051833.png",
      "ownerUserId": null,
      "siteUrl": "https://chinese.joins.com/news/articleList.html?view_type=s&sc_section_code=S1N1",
      "title": "财经 - 韩国最大的传媒机构《中央日报》中文网",
      "type": "feed",
      "url": "rsshub://joins/chinese/S1N1"
    }
  ],
  "url": "chinese.joins.com"
}
```
