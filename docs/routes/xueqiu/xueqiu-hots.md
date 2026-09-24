# 雪球 - 热帖

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/hots`
- Route Name: `热帖`
- Example: `/xueqiu/hots`
- URL: `xueqiu.com/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `hillerliao`
- Source Location: `hots.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `xueqiu.com/`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/xueqiu/hots",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3729,
  "location": "hots.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "热帖",
  "parameters": {},
  "path": "/hots",
  "radar": [
    {
      "source": [
        "xueqiu.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "雪球热门帖子 - Powered by RSSHub",
      "errorAt": "2026-09-22T10:54:21.184Z",
      "errorMessage": "Could not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\n[GET] \"https://xueqiu.com/statuses/hots.json?a=1&count=10&meigu=0&page=1&scope=day&type=status\": 400 Bad Request\nFailed to fetch\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nbrowserType.launch: Executable doesn't exist at /root/.cache/ms-playwright/chromium_headless_shell-1234/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Patchright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\n524 \n[GET] \"https://xueqiu.com/statuses/hots.json?a=1&count=10&meigu=0&page=1&scope=day&type=status\": 400 Bad Request\n500 \nbrowserType.launch: Executable doesn't exist at /root/.cache/ms-playwright/chromium_headless_shell-1228/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Patchright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\nFailed to fetch\nFailed to fetch\nlaunch: Executable doesn't exist at /.cache/ms-playwright/chromium_headless_shell-1228/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Patchright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\n[GET] \"https://xueqiu.com/statuses/hots.json?a=1&count=10&meigu=0&page=1&scope=day&type=status\": 400 Bad Request\nFailed to fetch\nFailed to fetch\n[GET] \"https://xueqiu.com/statuses/hots.json?a=1&count=10&meigu=0&page=1&scope=day&type=status\": 400 Bad Request\n",
      "id": "53033422584152064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/",
      "title": "热帖 - 雪球",
      "type": "feed",
      "url": "rsshub://xueqiu/hots"
    }
  ],
  "url": "xueqiu.com/"
}
```
