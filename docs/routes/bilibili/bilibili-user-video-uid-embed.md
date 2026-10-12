# 哔哩哔哩 bilibili - UP 主投稿

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/video/:uid/:embed?`
- Route Name: `UP 主投稿`
- Example: `/bilibili/user/video/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, Konano, pseudoyu`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `space.bilibili.com/:uid`
- `target`: `/user/video/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/bilibili/user/video/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 178524,
  "location": "video.ts",
  "maintainers": [
    "DIYgod",
    "Konano",
    "pseudoyu"
  ],
  "name": "UP 主投稿",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/video/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "技术爬爬虾 的 bilibili 空间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58463916731079680",
      "image": "https://i0.hdslb.com/bfs/face/333b1b477f1ac1b40091b70afcfd4444e646a7d3.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842",
      "title": "技术爬爬虾 的 bilibili 空间",
      "type": "feed",
      "url": "rsshub://bilibili/user/video/316183842"
    },
    {
      "description": "影视飓风 的 bilibili 空间 - Powered by RSSHub",
      "errorAt": "2026-10-11T13:07:59.893Z",
      "errorMessage": "Failed to fetch\nCould not find Chrome (ver. 123.0.6312.86). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nBilibili browser mode returned unexpected video list API status 412\nbrowserType.connect: WebSocket error: connect ECONNREFUSED 192.168.128.2:3000\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error connect ECONNREFUSED 192.168.128.2:3000\n  - <ws connect error> ws://browserless:3000/ connect ECONNREFUSED 192.168.128.2:3000\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\nCannot find module '/var/task/node_modules/.pnpm/patchright-core@1.63.0/node_modules/patchright-core/browsers.json'\nRequire stack:\n- /var/task/node_modules/.pnpm/patchright-core@1.63.0/node_modules/patchright-core/lib/coreBundle.js\n401 \n524 \n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1xVY26dEbz\": 412 \nFailed to fetch\n404 Not Found\nFailed to fetch\n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1gHps6yEHL\": 412 Precondition Failed\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nAuthentication failed. Access denied.\n/bilibili/user/video/946974\nGot error code -352 while fetching: 风控校验失败\nbrowserType.launch: Executable doesn't exist at /app/node_modules/.cache/ms-playwright/chromium_headless_shell-1243/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Patchright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\nbrowserType.connect: WebSocket error: getaddrinfo EAI_AGAIN browserless\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error getaddrinfo EAI_AGAIN browserless\n  - <ws connect error> ws://browserless:3000/ getaddrinfo EAI_AGAIN browserless\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n503 \n",
      "id": "55653085540614144",
      "image": "https://i0.hdslb.com/bfs/face/c1733474892caa45952b2c09a89323157df7129a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/946974",
      "title": "影视飓风 的 bilibili 空间",
      "type": "feed",
      "url": "rsshub://bilibili/user/video/946974"
    }
  ],
  "view": 3
}
```
