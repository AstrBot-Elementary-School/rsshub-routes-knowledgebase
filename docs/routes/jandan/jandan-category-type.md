# 煎蛋 - Section

## Coverage
`index-only`

## Route
- Namespace: `jandan`
- Namespace Name: `煎蛋`
- Route Path: `/jandan/:category/:type?`
- Route Name: `Section`
- Example: `/jandan/top`
- URL: `jandan.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `section.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "板块", "options": [{"label": "热榜", "value": "top"}, {"label": "问答", "value": "qa"}, {"label": "树洞", "value": "treehole"}, {"label": "随手拍", "value": "ooxx"}, {"label": "无聊图", "value": "pic"}, {"label": "鱼塘", "value": "bbs"}]}
- `type`: {"default": "4hr", "description": "热榜类型，仅当 category 选择 `top` 时有效", "options": [{"label": "4小时热门", "value": "4hr"}, {"label": "3天内无聊图", "value": "pic3days"}, {"label": "7天内无聊图", "value": "pic7days"}]}


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
  - `i.jandan.net/:category`
- `target`: `/jandan/:category?`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/jandan/top",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 529,
  "location": "section.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Section",
  "parameters": {
    "category": {
      "description": "板块",
      "options": [
        {
          "label": "热榜",
          "value": "top"
        },
        {
          "label": "问答",
          "value": "qa"
        },
        {
          "label": "树洞",
          "value": "treehole"
        },
        {
          "label": "随手拍",
          "value": "ooxx"
        },
        {
          "label": "无聊图",
          "value": "pic"
        },
        {
          "label": "鱼塘",
          "value": "bbs"
        }
      ]
    },
    "type": {
      "default": "4hr",
      "description": "热榜类型，仅当 category 选择 `top` 时有效",
      "options": [
        {
          "label": "4小时热门",
          "value": "4hr"
        },
        {
          "label": "3天内无聊图",
          "value": "pic3days"
        },
        {
          "label": "7天内无聊图",
          "value": "pic7days"
        }
      ]
    }
  },
  "path": "/:category/:type?",
  "radar": [
    {
      "source": [
        "i.jandan.net/:category"
      ],
      "target": "/jandan/:category?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "热榜 - 4小时热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42107730549411843",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://i.jandan.net/top",
      "title": "热榜 - 4小时热门",
      "type": "feed",
      "url": "rsshub://jandan/top"
    },
    {
      "description": "无聊图 - 蛋友贴图专版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58385313249043456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://i.jandan.net/pic",
      "title": "无聊图 - 蛋友贴图专版",
      "type": "feed",
      "url": "rsshub://jandan/pic"
    }
  ]
}
```
