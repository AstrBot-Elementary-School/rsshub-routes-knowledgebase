# Yahoo - 合作媒體

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/news/list/:region/:listId`
- Route Name: `合作媒體`
- Example: `/yahoo/news/list/hk/09fcf7b0-0ab2-11e8-bf1f-4d52d4f79454`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL, williamgateszhao, tpnonthealps`
- Source Location: `news/listid.ts`
- Source Module: `_None_`

## Description
| 合作媒體 (`HK`) | `:listId`                              |
| --------------- | -------------------------------------- |
| 東方日報        | `33ddd580-0ab3-11e8-bfe1-4b555fb1e429` |
| now\.com        | `01b4d760-0ab4-11e8-af3a-54037d3dced3` |
| am730           | `c4842090-0ab2-11e8-af7f-041a72ce7398` |
| BBC             | `4d3fc9a0-fac8-11e9-87f2-564ca250983e` |
| 信報財經新聞    | `5a8a0aa0-0ab3-11e8-b3dc-d990c79d6cb1` |
| 香港電台        | `b4bfc2d0-0ab3-11e8-bf9f-c888fc09923f` |
| 法新社          | `1cc44280-facb-11e9-ad7c-f3ba971275c8` |
| Bloomberg       | `40023670-facc-11e9-9dde-9175ff306602` |
| 香港動物報      | `6058fa9c-d74d-487a-8b49-aa99a2a2978e` |

## Parameters
- `region`: `hk`, `tw`
- `listId`: 見下表


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
  - `hk.news.yahoo.com/`
### Rule 2
- `source`:
  - `tw.news.yahoo.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 合作媒體 (`HK`) | `:listId`                              |\n| --------------- | -------------------------------------- |\n| 東方日報        | `33ddd580-0ab3-11e8-bfe1-4b555fb1e429` |\n| now\\.com        | `01b4d760-0ab4-11e8-af3a-54037d3dced3` |\n| am730           | `c4842090-0ab2-11e8-af7f-041a72ce7398` |\n| BBC             | `4d3fc9a0-fac8-11e9-87f2-564ca250983e` |\n| 信報財經新聞    | `5a8a0aa0-0ab3-11e8-b3dc-d990c79d6cb1` |\n| 香港電台        | `b4bfc2d0-0ab3-11e8-bf9f-c888fc09923f` |\n| 法新社          | `1cc44280-facb-11e9-ad7c-f3ba971275c8` |\n| Bloomberg       | `40023670-facc-11e9-9dde-9175ff306602` |\n| 香港動物報      | `6058fa9c-d74d-487a-8b49-aa99a2a2978e` |",
  "example": "/yahoo/news/list/hk/09fcf7b0-0ab2-11e8-bf1f-4d52d4f79454",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "news/listid.ts",
  "maintainers": [
    "TonyRL",
    "williamgateszhao",
    "tpnonthealps"
  ],
  "name": "合作媒體",
  "parameters": {
    "listId": "見下表",
    "region": "`hk`, `tw`"
  },
  "path": "/news/list/:region/:listId",
  "radar": [
    {
      "source": [
        "hk.news.yahoo.com/"
      ]
    },
    {
      "source": [
        "tw.news.yahoo.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Yahoo 新聞 - 法新社 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78795698559475712",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://hk.news.yahoo.com/",
      "title": "Yahoo 新聞 - 法新社",
      "type": "feed",
      "url": "rsshub://yahoo/news/list/hk/1cc44280-facb-11e9-ad7c-f3ba971275c8"
    },
    {
      "description": "Yahoo 新聞 - on.cc 東網 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86337790306403328",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://hk.news.yahoo.com/",
      "title": "Yahoo 新聞 - on.cc 東網",
      "type": "feed",
      "url": "rsshub://yahoo/news/list/hk/33ddd580-0ab3-11e8-bfe1-4b555fb1e429"
    }
  ]
}
```
