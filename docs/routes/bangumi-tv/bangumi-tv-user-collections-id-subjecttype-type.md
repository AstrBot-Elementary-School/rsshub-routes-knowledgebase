# Bangumi 番组计划 - Bangumi 用户收藏列表

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/user/collections/:id/:subjectType/:type`
- Route Name: `Bangumi 用户收藏列表`
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
- `subjectType`: {"description": "全部类别: `空`、book: `1`、anime: `2`、music: `3`、game: `4`、real: `6`", "options": [{"label": "all", "value": "ALL"}, {"label": "1", "value": "book"}, {"label": "2", "value": "anime"}, {"label": "3", "value": "music"}, {"label": "4", "value": "game"}, {"label": "6", "value": "real"}]}
- `type`: {"description": "全部类别: `空`、想看: `1`、看过: `2`、在看: `3`、搁置: `4`、抛弃: `5`", "options": [{"label": "all", "value": "ALL"}, {"label": "1", "value": "想看"}, {"label": "2", "value": "看过"}, {"label": "3", "value": "在看"}, {"label": "4", "value": "搁置"}, {"label": "5", "value": "抛弃"}]}


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
- `target`: `/bangumi.tv/user/collections/:id/all/all`
### Rule 2
- `source`:
  - `bangumi.tv/anime/list/:id`
- `target`: `/bangumi.tv/user/collections/:id/all/all`
### Rule 3
- `source`:
  - `bgm.tv/anime/list/:id/wish`
- `target`: `/bangumi.tv/user/collections/:id/2/1`
### Rule 4
- `source`:
  - `bangumi.tv/anime/list/:id/wish`
- `target`: `/bangumi.tv/user/collections/:id/2/1`

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
  "name": "Bangumi 用户收藏列表",
  "parameters": {
    "id": "用户 id, 在用户页面地址栏查看",
    "subjectType": {
      "description": "全部类别: `空`、book: `1`、anime: `2`、music: `3`、game: `4`、real: `6`",
      "options": [
        {
          "label": "all",
          "value": "ALL"
        },
        {
          "label": "1",
          "value": "book"
        },
        {
          "label": "2",
          "value": "anime"
        },
        {
          "label": "3",
          "value": "music"
        },
        {
          "label": "4",
          "value": "game"
        },
        {
          "label": "6",
          "value": "real"
        }
      ]
    },
    "type": {
      "description": "全部类别: `空`、想看: `1`、看过: `2`、在看: `3`、搁置: `4`、抛弃: `5`",
      "options": [
        {
          "label": "all",
          "value": "ALL"
        },
        {
          "label": "1",
          "value": "想看"
        },
        {
          "label": "2",
          "value": "看过"
        },
        {
          "label": "3",
          "value": "在看"
        },
        {
          "label": "4",
          "value": "搁置"
        },
        {
          "label": "5",
          "value": "抛弃"
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
      "target": "/bangumi.tv/user/collections/:id/all/all"
    },
    {
      "source": [
        "bangumi.tv/anime/list/:id"
      ],
      "target": "/bangumi.tv/user/collections/:id/all/all"
    },
    {
      "source": [
        "bgm.tv/anime/list/:id/wish"
      ],
      "target": "/bangumi.tv/user/collections/:id/2/1"
    },
    {
      "source": [
        "bangumi.tv/anime/list/:id/wish"
      ],
      "target": "/bangumi.tv/user/collections/:id/2/1"
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
