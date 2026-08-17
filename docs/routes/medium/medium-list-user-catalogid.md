# Medium - List

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/medium/list/:user/:catalogId`
- Route Name: `List`
- Example: `/medium/list/imsingee/f2d8d48096a9`
- URL: `medium.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
The List ID is the last part of the URL after `-`, for example, the username in <https://medium.com/@imsingee/list/collection-7e67004f23f9> is `imsingee`, and the ID is `7e67004f23f9`.

::: warning
To access private lists, only self-hosting is supported.
:::

## Parameters
- `user`: Username
- `catalogId`: List ID


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
    "blog"
  ],
  "description": "The List ID is the last part of the URL after `-`, for example, the username in <https://medium.com/@imsingee/list/collection-7e67004f23f9> is `imsingee`, and the ID is `7e67004f23f9`.\n\n::: warning\nTo access private lists, only self-hosting is supported.\n:::",
  "example": "/medium/list/imsingee/f2d8d48096a9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "list.ts",
  "maintainers": [
    "ImSingee"
  ],
  "name": "List",
  "parameters": {
    "catalogId": "List ID",
    "user": "Username"
  },
  "path": "/list/:user/:catalogId",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "List: Favorite - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62155103767851008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://medium.com/@imsingee/list/f2d8d48096a9",
      "title": "List: Favorite",
      "type": "feed",
      "url": "rsshub://medium/list/imsingee/f2d8d48096a9"
    },
    {
      "description": "List: Apple ML Frameworks & Technologies - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126876190043098120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://medium.com/@andreask_75652/list/a258e18af77b",
      "title": "List: Apple ML Frameworks & Technologies",
      "type": "feed",
      "url": "rsshub://medium/list/andreask_75652/a258e18af77b"
    }
  ]
}
```
