# pixiv - User Novels

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/user/novels/:id/:full_content?`
- Route Name: `User Novels`
- Example: `/pixiv/user/novels/27104704`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL, SnowAgar25`
- Source Location: `novels.ts`
- Source Module: `_None_`

## Description
| 小說類型 Novel Type | full\_content | PIXIV\_REFRESHTOKEN | 返回內容 Content |
| ------------------- | ------------- | ------------------- | ---------------- |
| Non R18             | false         | 不需要 Not Required | 簡介 Basic info  |
| Non R18             | true          | 不需要 Not Required | 全文 Full text   |
| R18                 | false         | 需要 Required       | 簡介 Basic info  |
| R18                 | true          | 需要 Required       | 全文 Full text   |

Default value for `full_content` is `false` if not specified.

Example:

- `/pixiv/user/novels/79603797` → 簡介 Basic info
- `/pixiv/user/novels/79603797/true` → 全文 Full text

## Parameters
- `id`: User id, available in user's homepage URL
- `full_content`: {"default": "false", "description": "Enable or disable the display of full content. ", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


## Features
- `requireConfig`: [{"description": "\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\nrefresh_token after Pixiv login, required for accessing R18 novels\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)", "name": "PIXIV_REFRESHTOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `User Novels (簡介 Basic info)`
- `source`:
  - `www.pixiv.net/users/:id/novels`
  - `www.pixiv.net/users/:id`
  - `www.pixiv.net/en/users/:id/novels`
  - `www.pixiv.net/en/users/:id`
- `target`: `/user/novels/:id`
### Rule 2
- `title`: `User Novels (全文 Full text)`
- `source`:
  - `www.pixiv.net/users/:id/novels`
  - `www.pixiv.net/users/:id`
  - `www.pixiv.net/en/users/:id/novels`
  - `www.pixiv.net/en/users/:id`
- `target`: `/user/novels/:id/true`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 小說類型 Novel Type | full\\_content | PIXIV\\_REFRESHTOKEN | 返回內容 Content |\n| ------------------- | ------------- | ------------------- | ---------------- |\n| Non R18             | false         | 不需要 Not Required | 簡介 Basic info  |\n| Non R18             | true          | 不需要 Not Required | 全文 Full text   |\n| R18                 | false         | 需要 Required       | 簡介 Basic info  |\n| R18                 | true          | 需要 Required       | 全文 Full text   |\n\nDefault value for `full_content` is `false` if not specified.\n\nExample:\n\n- `/pixiv/user/novels/79603797` → 簡介 Basic info\n- `/pixiv/user/novels/79603797/true` → 全文 Full text",
  "example": "/pixiv/user/novels/27104704",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\nrefresh_token after Pixiv login, required for accessing R18 novels\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)",
        "name": "PIXIV_REFRESHTOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 72,
  "location": "novels.ts",
  "maintainers": [
    "TonyRL",
    "SnowAgar25"
  ],
  "name": "User Novels",
  "parameters": {
    "full_content": {
      "default": "false",
      "description": "Enable or disable the display of full content. ",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    },
    "id": "User id, available in user's homepage URL"
  },
  "path": "/user/novels/:id/:full_content?",
  "radar": [
    {
      "source": [
        "www.pixiv.net/users/:id/novels",
        "www.pixiv.net/users/:id",
        "www.pixiv.net/en/users/:id/novels",
        "www.pixiv.net/en/users/:id"
      ],
      "target": "/user/novels/:id",
      "title": "User Novels (簡介 Basic info)"
    },
    {
      "source": [
        "www.pixiv.net/users/:id/novels",
        "www.pixiv.net/users/:id",
        "www.pixiv.net/en/users/:id/novels",
        "www.pixiv.net/en/users/:id"
      ],
      "target": "/user/novels/:id/true",
      "title": "User Novels (全文 Full text)"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Coco要做人啦！（闭关中） 的 pixiv 最新小说 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "171616028489447424",
      "image": "https://pixiv.rss3.workers.dev/user-profile/img/2024/09/20/22/49/43/26387649_59dfd297e633748236bf3623acea457c_170.png",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/43420481/novels",
      "title": "Coco要做人啦！（闭关中）'s novels - pixiv",
      "type": "feed",
      "url": "rsshub://pixiv/user/novels/43420481"
    },
    {
      "description": "兴趣使然的瑟琴写手 的 pixiv 最新小说 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77022618395189248",
      "image": "https://pixiv.rss3.workers.dev/user-profile/img/2020/07/16/18/34/46/18999686_40ea820c8991c9648c5c5120aaaaed82_170.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/11118328/novels",
      "title": "兴趣使然的瑟琴写手's novels - pixiv",
      "type": "feed",
      "url": "rsshub://pixiv/user/novels/11118328/true"
    }
  ],
  "view": 0
}
```
