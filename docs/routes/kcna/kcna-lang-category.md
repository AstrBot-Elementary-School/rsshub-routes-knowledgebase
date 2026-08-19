# Korean Central News Agency (KCNA) 朝鲜中央通讯社 - News

## Coverage
`index-only`

## Route
- Namespace: `kcna`
- Namespace Name: `Korean Central News Agency (KCNA) 朝鲜中央通讯社`
- Route Path: `/kcna/:lang/:category?`
- Route Name: `News`
- Example: `/kcna/en`
- URL: `www.kcna.kp`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Rongronggg9`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| Language | 조선어 | English | 中国语 | Русский | Español | 日本語 |
| -------- | ------ | ------- | ------ | ------- | ------- | ------ |
| `:lang`  | `kp`   | `en`    | `cn`   | `ru`    | `es`    | `jp`   |

| Category                                                         | `:category`                        |
| ---------------------------------------------------------------- | ---------------------------------- |
| WPK General Secretary **Kim Jong Un**'s Revolutionary Activities | `b0721b9f23054ddc7fe56c2811a12715` |
| Latest News (default)                                            | `a666dda1282180e0ee1b4427b0574ae7` |
| Top News                                                         | `6a47505ba5268fd7749c0fe11e4b24b4` |
| Home News                                                        | `2f7d854121ccbbfbe6feae9fdcc3556e` |
| Documents                                                        | `1afa96195f9b303902490a126ab7285f` |
| World                                                            | `ecc14533d88be93068af4178946b1b05` |
| Social Life                                                      | `680e40b40899891bbe75a7072e3285e7` |
| External                                                         | `e2f336db98b5e69c75e0da264e037e8d` |
| Revolutionary Anecdote                                           | `503e9b606704f9b1c625fa5755928cd3` |
| Always in Memory of People                                       | `7bc083f00425be6aadfb828fba1cb5a7` |

## Parameters
- `lang`: Language, refer to the table below
- `category`: Category, refer to the table below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.kcna.kp/:lang`
- `target`: `/:lang`
### Rule 2
- `source`:
  - `www.kcna.kp/:lang/article/list/:category`
- `target`: `/:lang/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Language | 조선어 | English | 中国语 | Русский | Español | 日本語 |\n| -------- | ------ | ------- | ------ | ------- | ------- | ------ |\n| `:lang`  | `kp`   | `en`    | `cn`   | `ru`    | `es`    | `jp`   |\n\n| Category                                                         | `:category`                        |\n| ---------------------------------------------------------------- | ---------------------------------- |\n| WPK General Secretary **Kim Jong Un**'s Revolutionary Activities | `b0721b9f23054ddc7fe56c2811a12715` |\n| Latest News (default)                                            | `a666dda1282180e0ee1b4427b0574ae7` |\n| Top News                                                         | `6a47505ba5268fd7749c0fe11e4b24b4` |\n| Home News                                                        | `2f7d854121ccbbfbe6feae9fdcc3556e` |\n| Documents                                                        | `1afa96195f9b303902490a126ab7285f` |\n| World                                                            | `ecc14533d88be93068af4178946b1b05` |\n| Social Life                                                      | `680e40b40899891bbe75a7072e3285e7` |\n| External                                                         | `e2f336db98b5e69c75e0da264e037e8d` |\n| Revolutionary Anecdote                                           | `503e9b606704f9b1c625fa5755928cd3` |\n| Always in Memory of People                                       | `7bc083f00425be6aadfb828fba1cb5a7` |",
  "example": "/kcna/en",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, refer to the table below",
    "lang": "Language, refer to the table below"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "www.kcna.kp/:lang"
      ],
      "target": "/:lang"
    },
    {
      "source": [
        "www.kcna.kp/:lang/article/list/:category"
      ],
      "target": "/:lang/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "朝鲜中央通讯 | 最新新闻 - Powered by RSSHub",
      "errorAt": "2026-08-17T18:51:23.224Z",
      "errorMessage": "Failed to fetch\n[GET] \"http://www.kcna.kp/cn/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf\": 404 Not Found\nFailed to fetch\n",
      "id": "213406943351213061",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.kcna.kp/cn/article/list/a666dda1282180e0ee1b4427b0574ae7",
      "title": "朝鲜中央通讯 | 最新新闻",
      "type": "feed",
      "url": "rsshub://kcna/cn"
    },
    {
      "description": "KCNA | Article | Latest News - Powered by RSSHub",
      "errorAt": "2026-05-27T10:15:40.792Z",
      "errorMessage": "Failed to fetch\n",
      "id": "185526378093555750",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.kcna.kp/en/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf",
      "title": "KCNA | Article | Latest News",
      "type": "feed",
      "url": "rsshub://kcna/en"
    }
  ]
}
```
