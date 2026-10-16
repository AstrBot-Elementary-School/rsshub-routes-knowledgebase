# Medium - Personalized Recommendations - For You

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/medium/for-you/:user`
- Route Name: `Personalized Recommendations - For You`
- Example: `/medium/for-you/imsingee`
- URL: `medium.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `for-you.ts`
- Source Module: `_None_`

## Description
::: warning
Personalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.
:::

When Medium blocks article pages, their publicly visible previews may be returned.

## Parameters
- `user`: Username


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
  "description": "::: warning\nPersonalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.\n:::\n\nWhen Medium blocks article pages, their publicly visible previews may be returned.",
  "example": "/medium/for-you/imsingee",
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
  "location": "for-you.ts",
  "maintainers": [
    "ImSingee"
  ],
  "name": "Personalized Recommendations - For You",
  "parameters": {
    "user": "Username"
  },
  "path": "/for-you/:user",
  "topFeeds": []
}
```
