# Medium - Personalized Recommendations - Tag

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/medium/tag/:user/:tag`
- Route Name: `Personalized Recommendations - Tag`
- Example: `/medium/tag/imsingee/cybersecurity`
- URL: `medium.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
There are many tags, which can be obtained by clicking on a tag from the homepage and looking at the URL. For example, if the URL is `https://medium.com/?tag=web3`, then the tag is `web3`.

::: warning
Personalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.
:::

When Medium blocks article pages, their publicly visible previews may be returned.

## Parameters
- `user`: Username
- `tag`: Subscribed Tag


## Features
- `requireConfig`: [{"description": "", "name": "MEDIUM_COOKIE_*"}]
- `requirePuppeteer`: true
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
  "description": "There are many tags, which can be obtained by clicking on a tag from the homepage and looking at the URL. For example, if the URL is `https://medium.com/?tag=web3`, then the tag is `web3`.\n\n::: warning\nPersonalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.\n:::\n\nWhen Medium blocks article pages, their publicly visible previews may be returned.",
  "example": "/medium/tag/imsingee/cybersecurity",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "MEDIUM_COOKIE_*"
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "ImSingee"
  ],
  "name": "Personalized Recommendations - Tag",
  "parameters": {
    "tag": "Subscribed Tag",
    "user": "Username"
  },
  "path": "/tag/:user/:tag",
  "topFeeds": []
}
```
