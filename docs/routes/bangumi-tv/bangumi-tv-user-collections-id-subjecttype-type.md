# Bangumi 番组计划 - 用户收藏列表

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/user/collections/:id/:subjectType/:type`
- Route Name: `用户收藏列表`
- Example: `/bangumi.tv/user/collections/sai/1/1`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `youyou-sudo, honue`
- Source Location: `user/collections.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 在用户页面地址栏查看
- `subjectType`: {"description": "全部类别: `all`、book: `1`、anime: `2`、music: `3`、game: `4`、real: `6`", "options": [{"label": "全部", "value": "all"}, {"label": "book", "value": "1"}, {"label": "anime", "value": "2"}, {"label": "music", "value": "3"}, {"label": "game", "value": "4"}, {"label": "real", "value": "6"}]}
- `type`: {"description": "全部状态: `all`、想看: `1`、看过: `2`、在看: `3`、搁置: `4`、抛弃: `5`", "options": [{"label": "全部", "value": "all"}, {"label": "想看", "value": "1"}, {"label": "看过", "value": "2"}, {"label": "在看", "value": "3"}, {"label": "搁置", "value": "4"}, {"label": "抛弃", "value": "5"}]}


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
  - `bgm.tv/anime/list/:id`
- `target`: `/user/collections/:id/all/all`
### Rule 2
- `source`:
  - `bangumi.tv/anime/list/:id`
- `target`: `/user/collections/:id/all/all`
### Rule 3
- `source`:
  - `bgm.tv/anime/list/:id/wish`
- `target`: `/user/collections/:id/2/1`
### Rule 4
- `source`:
  - `bangumi.tv/anime/list/:id/wish`
- `target`: `/user/collections/:id/2/1`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/user/collections/sai/1/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "user/collections.tsx",
  "maintainers": [
    "youyou-sudo",
    "honue"
  ],
  "name": "用户收藏列表",
  "parameters": {
    "id": "用户 id, 在用户页面地址栏查看",
    "subjectType": {
      "description": "全部类别: `all`、book: `1`、anime: `2`、music: `3`、game: `4`、real: `6`",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "book",
          "value": "1"
        },
        {
          "label": "anime",
          "value": "2"
        },
        {
          "label": "music",
          "value": "3"
        },
        {
          "label": "game",
          "value": "4"
        },
        {
          "label": "real",
          "value": "6"
        }
      ]
    },
    "type": {
      "description": "全部状态: `all`、想看: `1`、看过: `2`、在看: `3`、搁置: `4`、抛弃: `5`",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "想看",
          "value": "1"
        },
        {
          "label": "看过",
          "value": "2"
        },
        {
          "label": "在看",
          "value": "3"
        },
        {
          "label": "搁置",
          "value": "4"
        },
        {
          "label": "抛弃",
          "value": "5"
        }
      ]
    }
  },
  "path": "/user/collections/:id/:subjectType/:type",
  "radar": [
    {
      "source": [
        "bgm.tv/anime/list/:id"
      ],
      "target": "/user/collections/:id/all/all"
    },
    {
      "source": [
        "bangumi.tv/anime/list/:id"
      ],
      "target": "/user/collections/:id/all/all"
    },
    {
      "source": [
        "bgm.tv/anime/list/:id/wish"
      ],
      "target": "/user/collections/:id/2/1"
    },
    {
      "source": [
        "bangumi.tv/anime/list/:id/wish"
      ],
      "target": "/user/collections/:id/2/1"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Sai🖖想读的书籍列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88617947995623424",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/user/sai/collections",
      "title": "Sai🖖想读的书籍列表",
      "type": "feed",
      "url": "rsshub://bangumi.tv/user/collections/sai/1/1"
    },
    {
      "description": "Cfox的Bangumi收藏列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85592670812321792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/user/cfox/collections",
      "title": "Cfox的Bangumi收藏列表",
      "type": "feed",
      "url": "rsshub://bangumi.tv/user/collections/cfox/all/all"
    }
  ]
}
```
