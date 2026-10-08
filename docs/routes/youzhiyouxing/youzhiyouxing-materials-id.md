# 有知有行 - 有知文章

## Coverage
`index-only`

## Route
- Namespace: `youzhiyouxing`
- Namespace Name: `有知有行`
- Route Path: `/youzhiyouxing/materials/:id?`
- Route Name: `有知文章`
- Example: `/youzhiyouxing/materials`
- URL: `youzhiyouxing.cn/materials`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `broven, Fatpandac, nczitzk`
- Source Location: `materials.ts`
- Source Module: `_None_`

## Description
| 编号 | 栏目 |
| :--: | :--- |
| 0 | 全部 |
| 1 | 孟岩专栏 |
| 2 | 知行黑板报 |
| 3 | 知行读书会 |
| 4 | 知行小酒馆 |
| 5 | 保险专栏 |
| 6 | 知行头条 |
| 7 | 精选文章 |
| 8 | 一周新知 |
| 9 | 一周好想法 |
| 10 | 无人知晓 |
| 11 | 你好同路人 |
| 13 | 知行周报 |
| 14 | 有理有据 |
| 15 | Ta 的投资故事 |
| 16 | 投资 ABC |
| 17 | 海外投资Blog |
| 18 | 中国大类资产投资年报 |
| 19 | 夸下海口 |

## Parameters
- `id`: {"default": "0", "description": "分类", "options": [{"label": "全部", "value": "0"}, {"label": "孟岩专栏", "value": "1"}, {"label": "知行黑板报", "value": "2"}, {"label": "知行读书会", "value": "3"}, {"label": "知行小酒馆", "value": "4"}, {"label": "保险专栏", "value": "5"}, {"label": "知行头条", "value": "6"}, {"label": "精选文章", "value": "7"}, {"label": "一周新知", "value": "8"}, {"label": "一周好想法", "value": "9"}, {"label": "无人知晓", "value": "10"}, {"label": "你好同路人", "value": "11"}, {"label": "知行周报", "value": "13"}, {"label": "有理有据", "value": "14"}, {"label": "Ta 的投资故事", "value": "15"}, {"label": "投资 ABC", "value": "16"}, {"label": "海外投资Blog", "value": "17"}, {"label": "中国大类资产投资年报", "value": "18"}, {"label": "夸下海口", "value": "19"}]}


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
  - `youzhiyouxing.cn/materials`
- `target`: `/materials`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "| 编号 | 栏目 |\n| :--: | :--- |\n| 0 | 全部 |\n| 1 | 孟岩专栏 |\n| 2 | 知行黑板报 |\n| 3 | 知行读书会 |\n| 4 | 知行小酒馆 |\n| 5 | 保险专栏 |\n| 6 | 知行头条 |\n| 7 | 精选文章 |\n| 8 | 一周新知 |\n| 9 | 一周好想法 |\n| 10 | 无人知晓 |\n| 11 | 你好同路人 |\n| 13 | 知行周报 |\n| 14 | 有理有据 |\n| 15 | Ta 的投资故事 |\n| 16 | 投资 ABC |\n| 17 | 海外投资Blog |\n| 18 | 中国大类资产投资年报 |\n| 19 | 夸下海口 |",
  "example": "/youzhiyouxing/materials",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2967,
  "location": "materials.ts",
  "maintainers": [
    "broven",
    "Fatpandac",
    "nczitzk"
  ],
  "name": "有知文章",
  "parameters": {
    "id": {
      "default": "0",
      "description": "分类",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "孟岩专栏",
          "value": "1"
        },
        {
          "label": "知行黑板报",
          "value": "2"
        },
        {
          "label": "知行读书会",
          "value": "3"
        },
        {
          "label": "知行小酒馆",
          "value": "4"
        },
        {
          "label": "保险专栏",
          "value": "5"
        },
        {
          "label": "知行头条",
          "value": "6"
        },
        {
          "label": "精选文章",
          "value": "7"
        },
        {
          "label": "一周新知",
          "value": "8"
        },
        {
          "label": "一周好想法",
          "value": "9"
        },
        {
          "label": "无人知晓",
          "value": "10"
        },
        {
          "label": "你好同路人",
          "value": "11"
        },
        {
          "label": "知行周报",
          "value": "13"
        },
        {
          "label": "有理有据",
          "value": "14"
        },
        {
          "label": "Ta 的投资故事",
          "value": "15"
        },
        {
          "label": "投资 ABC",
          "value": "16"
        },
        {
          "label": "海外投资Blog",
          "value": "17"
        },
        {
          "label": "中国大类资产投资年报",
          "value": "18"
        },
        {
          "label": "夸下海口",
          "value": "19"
        }
      ]
    }
  },
  "path": "/materials/:id?",
  "radar": [
    {
      "source": [
        "youzhiyouxing.cn/materials"
      ],
      "target": "/materials"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "有知有行 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56535849521479680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://youzhiyouxing.cn/materials?column_id=0",
      "title": "有知有行 - 全部",
      "type": "feed",
      "url": "rsshub://youzhiyouxing/materials/0"
    },
    {
      "description": "有知有行 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55311155740901376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://youzhiyouxing.cn/materials?column_id=",
      "title": "有知有行 - 全部",
      "type": "feed",
      "url": "rsshub://youzhiyouxing/materials"
    }
  ],
  "url": "youzhiyouxing.cn/materials",
  "view": 0
}
```
