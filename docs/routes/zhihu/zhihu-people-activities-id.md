# 知乎 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/people/activities/:id`
- Route Name: `用户动态`
- Example: `/zhihu/people/activities/diygod`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod`
- Source Location: `activities.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "A complete d_c0 and __zse_ck cookie pair skips session initialization. Otherwise Workers use a Playwright browser session; Docker and Vercel generate credentials with JSDOM.", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/people/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/zhihu/people/activities/diygod",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "A complete d_c0 and __zse_ck cookie pair skips session initialization. Otherwise Workers use a Playwright browser session; Docker and Vercel generate credentials with JSDOM.",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5486,
  "location": "activities.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/activities/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Deep Van的逃生地牢（星球） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55789531638486016",
      "image": "https://picx.zhimg.com/v2-2161a03f1aac4c7b20a4edfa43318a7a_l.jpg?source=5a24d060&needBackground=1",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/yang-lei-96-72/activities",
      "title": "Deep Van的知乎动态",
      "type": "feed",
      "url": "rsshub://zhihu/people/activities/yang-lei-96-72"
    },
    {
      "description": "学校≠教育≠技能；文凭溢价=80%信号传递+20%人力资本 - Powered by RSSHub",
      "errorAt": "2026-09-06T16:06:26.878Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v3/moments/L.M.Sherlock/activities?limit=5&desktop=true&ws_qiangzhisafe=0\": 403 Forbidden\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "42176727619514386",
      "image": "https://picx.zhimg.com/v2-f1d7dc57926a68b812111df4bb3cef51_l.jpg?source=5a24d060&needBackground=1",
      "ownerUserId": "75467551039318016",
      "siteUrl": "https://www.zhihu.com/people/L.M.Sherlock/activities",
      "title": "Thoughts Memo的知乎动态",
      "type": "feed",
      "url": "rsshub://zhihu/people/activities/L.M.Sherlock"
    }
  ],
  "view": 0
}
```
