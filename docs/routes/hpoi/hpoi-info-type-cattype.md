# Hpoi 手办维基 - 情报

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/hpoi/info/:type?/:catType?`
- Route Name: `情报`
- Example: `/hpoi/info/all/hobby|model`
- URL: `www.hpoi.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `sanmmm DIYgod`
- Source Location: `info.ts`
- Source Module: `_None_`

## Description
::: tip
情报类型中的*手办*、*模型*只是为了兼容，实际效果等同于**全部**, 如果只需要**手办**类型的情报，可以使用参数*catType*, e.g. /hpoi/info/all/hobby
:::

| 手办  | 动漫模型 | 真实模型 | 毛绒布偶 | doll 娃娃 | GK / 其他 |
| ----- | -------- | -------- | -------- | --------- | --------- |
| hobby | model    | real     | moppet   | doll      | gkdiy     |

## Parameters
- `type`: {"default": "all", "description": "情报类型", "options": [{"label": "全部", "value": "all"}, {"label": "制作", "value": "confirm"}, {"label": "官图更新", "value": "official_pic"}, {"label": "开订", "value": "preorder"}, {"label": "延期", "value": "delay"}, {"label": "出荷", "value": "release"}, {"label": "再版", "value": "reorder"}, {"label": "手办(拟废弃, 无效果)", "value": "hobby"}, {"label": "动漫模型(拟废弃, 无效果)", "value": "model"}]}
- `catType`: {"default": "all", "description": "手办分类过滤, 使用|分割, 支持的分类见下表"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n情报类型中的*手办*、*模型*只是为了兼容，实际效果等同于**全部**, 如果只需要**手办**类型的情报，可以使用参数*catType*, e.g. /hpoi/info/all/hobby\n:::\n\n| 手办  | 动漫模型 | 真实模型 | 毛绒布偶 | doll 娃娃 | GK / 其他 |\n| ----- | -------- | -------- | -------- | --------- | --------- |\n| hobby | model    | real     | moppet   | doll      | gkdiy     |",
  "example": "/hpoi/info/all/hobby|model",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "info.ts",
  "maintainers": [
    "sanmmm DIYgod"
  ],
  "name": "情报",
  "parameters": {
    "catType": {
      "default": "all",
      "description": "手办分类过滤, 使用|分割, 支持的分类见下表"
    },
    "type": {
      "default": "all",
      "description": "情报类型",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "制作",
          "value": "confirm"
        },
        {
          "label": "官图更新",
          "value": "official_pic"
        },
        {
          "label": "开订",
          "value": "preorder"
        },
        {
          "label": "延期",
          "value": "delay"
        },
        {
          "label": "出荷",
          "value": "release"
        },
        {
          "label": "再版",
          "value": "reorder"
        },
        {
          "label": "手办(拟废弃, 无效果)",
          "value": "hobby"
        },
        {
          "label": "动漫模型(拟废弃, 无效果)",
          "value": "model"
        }
      ]
    }
  },
  "path": "/info/:type?/:catType?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "手办维基 - 情报 - 全部 - Powered by RSSHub",
      "errorAt": "2026-01-12T06:56:07.568Z",
      "errorMessage": "[POST] \"https://www.hpoi.net/user/home/ajax?page=1&type=info&subType=all\": 404 Not Found\n",
      "id": "55126637717323806",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/user/home?type=info&subType=all&catType=all",
      "title": "手办维基 - 情报 - 全部",
      "type": "feed",
      "url": "rsshub://hpoi/info/all"
    },
    {
      "description": "手办维基 - 情报 - 全部 - Powered by RSSHub",
      "errorAt": "2026-01-12T05:51:23.861Z",
      "errorMessage": "[POST] \"https://www.hpoi.net/user/home/ajax?page=1&type=info&subType=all\": 404 Not Found\n",
      "id": "163588982506257408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/user/home?type=info&subType=all&catType=all",
      "title": "手办维基 - 情报 - 全部",
      "type": "feed",
      "url": "rsshub://hpoi/info/all/all"
    }
  ]
}
```
