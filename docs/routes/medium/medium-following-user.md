# Medium - Personalized Recommendations - Following

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/medium/following/:user`
- Route Name: `Personalized Recommendations - Following`
- Example: `/medium/following/imsingee`
- URL: `medium.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `following.ts`
- Source Module: `_None_`

## Description
::: warning
Personalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.
:::

## Parameters
- `user`: Username


## Features
- `requireConfig`: [{"description": "", "name": "MEDIUM_COOKIE_*"}]
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
  "description": "::: warning\nPersonalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.\n:::",
  "example": "/medium/following/imsingee",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "MEDIUM_COOKIE_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "following.ts",
  "maintainers": [
    "ImSingee"
  ],
  "name": "Personalized Recommendations - Following",
  "parameters": {
    "user": "Username"
  },
  "path": "/following/:user",
  "topFeeds": [
    {
      "description": "ayusummer Medium Following - Powered by RSSHub",
      "errorAt": "2025-11-20T00:14:14.503Z",
      "errorMessage": "缺少 Medium 用户 ayusummer 登录后的 Cookie 值\n缺少 Medium 用户 ayusummer 登录后的 Cookie 值\n",
      "id": "105503629870477312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://medium.com/?feed=following",
      "title": "ayusummer Medium Following",
      "type": "feed",
      "url": "rsshub://medium/following/ayusummer"
    }
  ]
}
```
