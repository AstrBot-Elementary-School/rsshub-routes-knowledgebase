# 第一财经 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/news/:id?`
- Route Name: `新闻`
- Example: `/yicai/news`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Id                       | 名称       |
| ------------------------ | ---------- |
| gushi                    | A 股       |
| kechuangban              | 科创板     |
| hongguan                 | 大政       |
| jinrong                  | 金融       |
| quanqiushichang          | 海外市场   |
| gongsi                   | 产经       |
| shijie                   | 全球       |
| kechuang                 | 科技       |
| quyu                     | 区域       |
| comment                  | 评论       |
| dafengwenhua             | 商业人文   |
| books                    | 阅读周刊   |
| loushi                   | 地产       |
| automobile               | 汽车       |
| china\_financial\_herald | 对话陆家嘴 |
| fashion                  | 时尚       |
| ad                       | 商业资讯   |
| info                     | 资讯       |
| jzfxb                    | 价值风向标 |
| shuducaijing             | 数读财经   |
| shujujiepan              | 数据解盘   |
| shudushenghuo            | 数读生活   |
| cbndata                  | CBNData    |
| dtcj                     | DT 财经    |
| xfsz                     | 消费数知   |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页中找到，默认为新闻


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
  - `yicai.com/news/:id`
  - `yicai.com/news`
- `target`: `/news/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Id                       | 名称       |\n| ------------------------ | ---------- |\n| gushi                    | A 股       |\n| kechuangban              | 科创板     |\n| hongguan                 | 大政       |\n| jinrong                  | 金融       |\n| quanqiushichang          | 海外市场   |\n| gongsi                   | 产经       |\n| shijie                   | 全球       |\n| kechuang                 | 科技       |\n| quyu                     | 区域       |\n| comment                  | 评论       |\n| dafengwenhua             | 商业人文   |\n| books                    | 阅读周刊   |\n| loushi                   | 地产       |\n| automobile               | 汽车       |\n| china\\_financial\\_herald | 对话陆家嘴 |\n| fashion                  | 时尚       |\n| ad                       | 商业资讯   |\n| info                     | 资讯       |\n| jzfxb                    | 价值风向标 |\n| shuducaijing             | 数读财经   |\n| shujujiepan              | 数据解盘   |\n| shudushenghuo            | 数读生活   |\n| cbndata                  | CBNData    |\n| dtcj                     | DT 财经    |\n| xfsz                     | 消费数知   |",
  "example": "/yicai/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 179,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页中找到，默认为新闻"
  },
  "path": "/news/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/news/:id",
        "yicai.com/news"
      ],
      "target": "/news/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "第一财经 - 新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52508301310328844",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/news",
      "title": "第一财经 - 新闻",
      "type": "feed",
      "url": "rsshub://yicai/news"
    },
    {
      "description": "第一财经 - 科技 - Powered by RSSHub",
      "errorAt": "2025-11-04T08:38:03.960Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slug')\n",
      "id": "69953039798669312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/news/kechuang",
      "title": "第一财经 - 科技",
      "type": "feed",
      "url": "rsshub://yicai/news/kechuang"
    }
  ]
}
```
