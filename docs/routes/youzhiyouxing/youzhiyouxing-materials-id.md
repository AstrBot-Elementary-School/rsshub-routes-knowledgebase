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
| 全部 | 知行小酒馆 | 知行黑板报 | 无人知晓 | 孟岩专栏 | 知行读书会 | 你好，同路人 |
| :--: | :--------: | :--------: | :------: | :------: | :--------: | :----------: |
|   0  |      4     |      2     |    10    |     1    |      3     |      11      |

## Parameters
- `id`: {"default": "0", "description": "分类", "options": [{"label": "全部", "value": "0"}, {"label": "知行小酒馆", "value": "4"}, {"label": "知行黑板报", "value": "2"}, {"label": "无人知晓", "value": "10"}, {"label": "孟岩专栏", "value": "1"}, {"label": "知行读书会", "value": "3"}, {"label": "你好，同路人", "value": "11"}]}


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
  "description": "| 全部 | 知行小酒馆 | 知行黑板报 | 无人知晓 | 孟岩专栏 | 知行读书会 | 你好，同路人 |\n| :--: | :--------: | :--------: | :------: | :------: | :--------: | :----------: |\n|   0  |      4     |      2     |    10    |     1    |      3     |      11      |",
  "example": "/youzhiyouxing/materials",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3006,
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
          "label": "知行小酒馆",
          "value": "4"
        },
        {
          "label": "知行黑板报",
          "value": "2"
        },
        {
          "label": "无人知晓",
          "value": "10"
        },
        {
          "label": "孟岩专栏",
          "value": "1"
        },
        {
          "label": "知行读书会",
          "value": "3"
        },
        {
          "label": "你好，同路人",
          "value": "11"
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
