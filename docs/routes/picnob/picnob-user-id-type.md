# Instagram - User Profile - Picnob

## Coverage
`index-only`

## Route
- Namespace: `picnob`
- Namespace Name: `Instagram`
- Route Path: `/picnob/user/:id/:type?`
- Route Name: `User Profile - Picnob`
- Example: `/picnob/user/xlisa_olivex`
- URL: `www.instagram.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL, micheal-death, AiraNadih, DIYgod, hyoban, Rongronggg9`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: Type of profile page (profile or tagged)


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.picnob.com/profile/:id`
- `target`: `/user/:id`
### Rule 2
- `source`:
  - `www.picnob.com/profile/:id/tagged`
- `target`: `/user/:id/tagged`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/picnob/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 401898,
  "location": "user.ts",
  "maintainers": [
    "TonyRL",
    "micheal-death",
    "AiraNadih",
    "DIYgod",
    "hyoban",
    "Rongronggg9"
  ],
  "name": "User Profile - Picnob",
  "parameters": {
    "id": "Instagram id",
    "type": "Type of profile page (profile or tagged)"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "www.picnob.com/profile/:id"
      ],
      "target": "/user/:id"
    },
    {
      "source": [
        "www.picnob.com/profile/:id/tagged"
      ],
      "target": "/user/:id/tagged"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "🇨🇳🇰🇷在韩国留学的中国人 你的娇妻在这里👇🏻👇🏻👇🏻 - Powered by RSSHub",
      "errorAt": "2026-03-29T09:18:31.526Z",
      "errorMessage": "Failed to fetch\nInvalid RSSHub JSON Feed from 98292582055262208\nFailed to fetch\n522 \n530 \n503 \n",
      "id": "68681825883121664",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/418357932_713653904080321_8470046270490216982_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=101&_nc_oc=Q6cZ2gGTV3an_fzezN2zRMUL1DuaKiXnYA96q5e7kQyjj4nnisFg5mx7bH_1mMW89OMjVEw&_nc_ohc=tv50NXv0mZoQ7kNvwH98cE-&_nc_gid=5J8qHJn3xk9ue-hAyNHw6Q&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GKyi7xjB-XF-EIkCABYKse80pot1bkULAAAB3203200j-ccb7-5&oh=00_Afzy_VAugHKKJ-vfLlTX9-ADN9MkdPUrAXezO7aZEi0r6g&oe=69CEA57F&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/ciu7777/",
      "title": "ciu7 (@ciu7777) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/ciu7777"
    },
    {
      "description": "🧣：琳铛 🇨🇳🇨🇳 No other ins accounts‼️‼️ More content 👇👇 - Powered by RSSHub",
      "errorAt": "2026-01-20T01:20:00.752Z",
      "errorMessage": "Failed to fetch\nInvalid RSSHub JSON Feed from 98292582055262208\nFailed to fetch\n522 \n530 \nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "62461951970682880",
      "image": "https://sp1.pixnoy.com/a/a_66595339937_3438151834381512121225_8794553825c4d7abe3aff1d0de99fab5.jpg?o=aHR0cHM6Ly9zY29udGVudC1pYWQzLTIuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS4yODg1LTE5LzQ1ODE2OTAwMV83OTMzMDIyNDQwMTYwMDQ1XzEyNDc1MzUwODM1MDg0NzEwMjJfbi5qcGc/c3RwPWRzdC1qcGdfczE1MHgxNTBfdHQ2JmVmZz1leUoyWlc1amIyUmxYM1JoWnlJNkluQnliMlpwYkdWZmNHbGpMbVJxWVc1bmJ5NDVORFF1WXpJaWZRJl9uY19odD1zY29udGVudC1pYWQzLTIuY2RuaW5zdGFncmFtLmNvbSZfbmNfY2F0PTEwNSZfbmNfb2M9UTZjWjJRRzRWVVh1c0xRdnRvRlp6YmxheGtreXQ2ZHNIOXl6WHViM3B6a2Q4aDdtVW9Oc25SenNvMHVLZzJYWmlrVHlLVkt0N0dmQWd2LTZqMS1YeDd6YUNHYmImX25jX29oYz1ZWE1tN3lUM25BNFE3a052d0d0M0xScSZfbmNfZ2lkPTMtNkpCZTFpNW92M1BWRWtKNmhGU2cmZWRtPUFMR2JKUE1CQUFBQSZjY2I9Ny01Jm9oPTAwX0FmcXBYMG5Sb0dmU19nRkg5MDBOb19oeFI0V0I3UXIwTTQ2LTRKbEgyVnBJdGcmb2U9Njk3MjBGRDkmX25jX3NpZD03ZDNhYzU=&h=bb970d4a02046b507a95edfff5e5d824",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/peppapig6077/",
      "title": "Lin lin (@peppapig6077) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/peppapig6077"
    }
  ],
  "view": 2
}
```
