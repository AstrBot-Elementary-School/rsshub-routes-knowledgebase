# Mixcloud - User

## Coverage
`index-only`

## Route
- Namespace: `mixcloud`
- Namespace Name: `Mixcloud`
- Route Path: `/mixcloud/:username/:type?`
- Route Name: `User`
- Example: `/mixcloud/dholbach/uploads`
- URL: `www.mixcloud.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Misaka13514`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Shows   | Reposts | Favorites | History | Stream |
| ------- | ------- | --------- | ------- | ------ |
| uploads | reposts | favorites | listens | stream |

## Parameters
- `username`: Username, can be found in URL
- `type`: Type, see below, uploads by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mixcloud.com/:username/:type?`
### Rule 2
- `source`:
  - `www.mixcloud.com/:username/:type?`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Shows   | Reposts | Favorites | History | Stream |\n| ------- | ------- | --------- | ------- | ------ |\n| uploads | reposts | favorites | listens | stream |",
  "example": "/mixcloud/dholbach/uploads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 5,
  "location": "index.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "name": "User",
  "parameters": {
    "type": "Type, see below, uploads by default",
    "username": "Username, can be found in URL"
  },
  "path": "/:username/:type?",
  "radar": [
    {
      "source": [
        "mixcloud.com/:username/:type?"
      ]
    },
    {
      "source": [
        "www.mixcloud.com/:username/:type?"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 410323200618 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "As a DJ I was socialised with techno music in my early days and moved on, almost exclusively to Drum'n'Bass music. I loved the energy of broken beats and enjoyed playing those tunes at parties.<br><br>These days, I enjoy whatever music makes me want to move to it, whatever style it might be. I love getting feedback, so please comment on the mixes and let me know what you think. Also all kinds of music suggestions are appreciated. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63497988872589312",
      "image": "https://thumbnailer.mixcloud.com/unsafe/480x480/profile/7/6/2/0/e1f3-227f-4027-b764-99fe8aa85db6",
      "ownerUserId": null,
      "siteUrl": "https://www.mixcloud.com/dholbach/",
      "title": "Mixcloud - dholbach's Shows",
      "type": "feed",
      "url": "rsshub://mixcloud/dholbach/uploads"
    },
    {
      "description": "I'm the creator of NPR's All Songs Considered and Tiny Desk Concerts, and I recently retired.<br>I host My Tiny Morning Show, a one-hour weekly radio show featuring new emerging creative, independent artists and groundbreaking artists from the past. The show airs weekly on WOWD-LP TakomaRadio.org.<br><br>I authored the book, \"Your Song Changed My Life, asking 35 artists, including Jimmy Page, David Byrne, Lucinda Williams, Ian MacKaye, and Smokey Robinson, about a song that changed their lives.” <br><br>I'm also a musician, formerly of Tiny Desk Unit, and these days, recording with my band Danger Painters and solo ambient projects. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "207773440624381952",
      "image": "https://thumbnailer.mixcloud.com/unsafe/480x480/profile/8/6/8/a/af6a-817d-47be-b988-a6c72beee5db",
      "ownerUserId": null,
      "siteUrl": "https://www.mixcloud.com/bob-boilen/",
      "title": "Mixcloud - Bob Boilen's Shows",
      "type": "feed",
      "url": "rsshub://mixcloud/bob-boilen"
    }
  ]
}
```
