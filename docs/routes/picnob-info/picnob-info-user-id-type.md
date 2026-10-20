# Instagram - User Profile - Picnob.info

## Coverage
`index-only`

## Route
- Namespace: `picnob.info`
- Namespace Name: `Instagram`
- Route Path: `/picnob.info/user/:id/:type?`
- Route Name: `User Profile - Picnob.info`
- Example: `/picnob.info/user/xlisa_olivex`
- URL: `picnob.info`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: {"default": "posts", "description": "Type of profile page", "options": [{"label": "Posts", "value": "posts"}]}


## Features
- `requireConfig`: false
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
    "social-media",
    "popular"
  ],
  "example": "/picnob.info/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10556,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Profile - Picnob.info",
  "parameters": {
    "id": "Instagram id",
    "type": {
      "default": "posts",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Posts",
          "value": "posts"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "photographer Kagawa,Japan⁡ ⁡@iwakura.shiori - Powered by RSSHub",
      "errorAt": "2026-08-02T00:00:15.280Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n503 \n",
      "id": "55459543739969536",
      "image": "https://sp1.picnob.com/a/a_309098040_38192863103628481738323638_ca470a6f5fb004f62c417c5d965134a9.jpg?o=aHR0cHM6Ly9zY29udGVudC1hdGwzLTMuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS4yODg1LTE5LzQwOTc3NTQ4XzI2MjgyOTgxNDM0OTUzNV83ODIwNDgxNjU3NTA0MjY4Mjg4X24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZlZmc9ZXlKMlpXNWpiMlJsWDNSaFp5STZJbkJ5YjJacGJHVmZjR2xqTG1ScVlXNW5ieTQzTWpJdVl6SWlmUSZfbmNfaHQ9c2NvbnRlbnQtYXRsMy0zLmNkbmluc3RhZ3JhbS5jb20mX25jX2NhdD0xMTEmX25jX29jPVE2Y1oyZ0VEeGk0RGpTTmtvTGZ1RlB1bk1nanJZeERrLWVtX20yWEhKV05ZemU4WWxPMkg5ME9ZZnFMal9PNG1RdFVFcU1aajY1RV9maTJ3djZYNjB4c0ZmRklQJl9uY19vaGM9Q0lIeEpiVlIxT2dRN2tOdndHazNIS3omX25jX2dpZD02cUUwcmVhUlFqcjkyX1hncjFKcE5nJmVkbT1BTEdiSlBNQkFBQUEmY2NiPTctNSZvaD0wMF9BUUF2SjI4OHBQT1Q0TWFaTnRlRHYzVWplSHhCQlpfdVRkUTAtSElWZ2taYlRBJm9lPTZBNkFEMzk0Jl9uY19zaWQ9N2QzYWM1&h=26bd4a1f1f7996dbc35dea11d0ae9c32",
      "ownerUserId": null,
      "siteUrl": "https://www.picnob.com/profile/iwakurashiori/",
      "title": "iwakura shiori 岩倉しおり (@iwakurashiori) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/iwakurashiori"
    },
    {
      "description": "Tokyo/Japan Photographer management : Co Agency (XICO.inc) contact : [email protected] (to manager) Director of @seeyougallery - Powered by RSSHub",
      "errorAt": "2026-08-03T22:13:01.924Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n503 \n",
      "id": "53102238519094272",
      "image": "https://sp1.picnob.com/a/a_2516750_4828632838432863281738363218_467713afabc00c1b5842b680f5d281d4.jpg?o=aHR0cHM6Ly9zY29udGVudC1vcmQ1LTMuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS4yODg1LTE5LzQ2MTg5ODA0Ml81MjY3MDUxNTY2MzAyNDhfMTQ5MzI4Nzc1NzA5MjI5NjU2Nl9uLmpwZz9zdHA9ZHN0LWpwZ19zMTUweDE1MF90dDYmZWZnPWV5SjJaVzVqYjJSbFgzUmhaeUk2SW5CeWIyWnBiR1ZmY0dsakxtUnFZVzVuYnk0eE1EZ3dMbU15SW4wJl9uY19odD1zY29udGVudC1vcmQ1LTMuY2RuaW5zdGFncmFtLmNvbSZfbmNfY2F0PTEwMCZfbmNfb2M9UTZjWjJnR2ZSVnRDX19OMXUzSHZWaHlkaW1BdzVNRmlMcUdyVmFpbUtMRHdOYnpaemlVc2l0ZjloY1hpZ2RVOHRZVG5kOEhFYmE0aE96b0I2QWNsTkY3d2I1bmMmX25jX29oYz1EZlY3WHlnZGlpZ1E3a052d0U3QXRxYSZfbmNfZ2lkPTV1bmdnRFFibzc2TmI0UkJ6cDNHbmcmZWRtPUFMR2JKUE1CQUFBQSZjY2I9Ny01Jm9oPTAwX0FRRk9SYWFCVTY2Y0Q5S3VUNU9jVGlLTjVQbUlsTy1FQXJRRTI5MFNyTFI3ckEmb2U9NkE3MENCNEQmX25jX3NpZD03ZDNhYzU=&h=ef275661d39d3f070c8f3560ad5fc8d9",
      "ownerUserId": null,
      "siteUrl": "https://www.picnob.com/profile/sakaitakahiro_/",
      "title": "酒井貴弘 / Sakai Takahiro (@sakaitakahiro_) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/sakaitakahiro_"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
