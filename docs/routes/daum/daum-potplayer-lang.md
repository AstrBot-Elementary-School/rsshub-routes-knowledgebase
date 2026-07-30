# daum - Potplayer Update History

## Coverage
`index-only`

## Route
- Namespace: `daum`
- Namespace Name: `daum`
- Route Path: `/daum/potplayer/:lang?`
- Route Name: `Potplayer Update History`
- Example: `/daum/potplayer`
- URL: `potplayer.daum.net`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `potplayer.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Potplayer Update History](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html), where the source URL is `https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/daum/potplayer/Eng`](https://rsshub.app/daum/potplayer/Eng).
:::

| Language                                                                            | Id                                           |
| ----------------------------------------------------------------------------------- | -------------------------------------------- |
| [한국어](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html)         |                                              |
| [中文 (简体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html) | [Chs](https://rsshub.app/daum/potplayer/Chs) |
| [中文 (繁体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateCht.html) | [Cht](https://rsshub.app/daum/potplayer/Cht) |
| [ENGLISH](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)     | [Eng](https://rsshub.app/daum/potplayer/Eng) |
| [Українська](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)  | [Eng](https://rsshub.app/daum/potplayer/Eng) |
| [РУССКИЙ](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateRus.html)     | [Eng](https://rsshub.app/daum/potplayer/Rus) |
| [Polski](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdatePol.html)      | [Eng](https://rsshub.app/daum/potplayer/Pol) |

## Parameters
- `lang`: {"description": "Language, Korean by default", "options": [{"label": "한국어", "value": "Kor"}, {"label": "中文(简体)", "value": "Chs"}, {"label": "中文(繁体)", "value": "Cht"}, {"label": "English", "value": "Eng"}, {"label": "Українська", "value": "Eng"}, {"label": "Русский", "value": "Rus"}, {"label": "Polski", "value": "Pol"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `potplayer.daum.net`
### Rule 2
- `title`: `한국어`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html`
- `target`: `/potplayer`
### Rule 3
- `title`: `中文(简体)`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html`
- `target`: `/potplayer/Chs`
### Rule 4
- `title`: `中文(繁体)`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateCht.html`
- `target`: `/potplayer/Cht`
### Rule 5
- `title`: `English`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html`
- `target`: `/potplayer/Eng`
### Rule 6
- `title`: `Українська`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html`
- `target`: `/potplayer/Eng`
### Rule 7
- `title`: `Русский`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateRus.html`
- `target`: `/potplayer/Rus`
### Rule 8
- `title`: `Polski`
- `source`:
  - `t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdatePol.html`
- `target`: `/potplayer/Pol`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Potplayer Update History](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html), where the source URL is `https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/daum/potplayer/Eng`](https://rsshub.app/daum/potplayer/Eng).\n:::\n\n| Language                                                                            | Id                                           |\n| ----------------------------------------------------------------------------------- | -------------------------------------------- |\n| [한국어](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html)         |                                              |\n| [中文 (简体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html) | [Chs](https://rsshub.app/daum/potplayer/Chs) |\n| [中文 (繁体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateCht.html) | [Cht](https://rsshub.app/daum/potplayer/Cht) |\n| [ENGLISH](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)     | [Eng](https://rsshub.app/daum/potplayer/Eng) |\n| [Українська](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)  | [Eng](https://rsshub.app/daum/potplayer/Eng) |\n| [РУССКИЙ](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateRus.html)     | [Eng](https://rsshub.app/daum/potplayer/Rus) |\n| [Polski](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdatePol.html)      | [Eng](https://rsshub.app/daum/potplayer/Pol) |",
  "example": "/daum/potplayer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "potplayer.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Potplayer Update History",
  "parameters": {
    "lang": {
      "description": "Language, Korean by default",
      "options": [
        {
          "label": "한국어",
          "value": "Kor"
        },
        {
          "label": "中文(简体)",
          "value": "Chs"
        },
        {
          "label": "中文(繁体)",
          "value": "Cht"
        },
        {
          "label": "English",
          "value": "Eng"
        },
        {
          "label": "Українська",
          "value": "Eng"
        },
        {
          "label": "Русский",
          "value": "Rus"
        },
        {
          "label": "Polski",
          "value": "Pol"
        }
      ]
    }
  },
  "path": "/potplayer/:lang?",
  "radar": [
    {
      "source": [
        "potplayer.daum.net"
      ]
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html"
      ],
      "target": "/potplayer",
      "title": "한국어"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html"
      ],
      "target": "/potplayer/Chs",
      "title": "中文(简体)"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateCht.html"
      ],
      "target": "/potplayer/Cht",
      "title": "中文(繁体)"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html"
      ],
      "target": "/potplayer/Eng",
      "title": "English"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html"
      ],
      "target": "/potplayer/Eng",
      "title": "Українська"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateRus.html"
      ],
      "target": "/potplayer/Rus",
      "title": "Русский"
    },
    {
      "source": [
        "t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdatePol.html"
      ],
      "target": "/potplayer/Pol",
      "title": "Polski"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 314412507031 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "PotPlayer Update History - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182729097601498112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html",
      "title": "PotPlayer Update History",
      "type": "feed",
      "url": "rsshub://daum/potplayer"
    },
    {
      "description": "PotPlayer Update History - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182729503499199488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html",
      "title": "PotPlayer Update History",
      "type": "feed",
      "url": "rsshub://daum/potplayer/Eng"
    }
  ],
  "url": "potplayer.daum.net",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [Potplayer Update History](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html)，网址为 `https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html`，请截取 `https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update` 到末尾的部分 `Chs` 作为 `lang` 参数填入，此时目标路由为 [`/daum/potplayer/Chs`](https://rsshub.app/daum/potplayer/Chs)。\n:::\n\n| Language                                                                            | Id                                           |\n| ----------------------------------------------------------------------------------- | -------------------------------------------- |\n| [한국어](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/Update.html)         |                                              |\n| [中文 (简体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateChs.html) | [Chs](https://rsshub.app/daum/potplayer/Chs) |\n| [中文 (繁体)](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateCht.html) | [Cht](https://rsshub.app/daum/potplayer/Cht) |\n| [ENGLISH](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)     | [Eng](https://rsshub.app/daum/potplayer/Eng) |\n| [Українська](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateEng.html)  | [Eng](https://rsshub.app/daum/potplayer/Eng) |\n| [РУССКИЙ](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdateRus.html)     | [Eng](https://rsshub.app/daum/potplayer/Rus) |\n| [Polski](https://t1.daumcdn.net/potplayer/PotPlayer/v4/Update2/UpdatePol.html)      | [Eng](https://rsshub.app/daum/potplayer/Pol) |",
    "name": "PotPlayer 版本更新信息",
    "parameters": {
      "lang": {
        "description": "语言，默认为韩语，可在对应页 URL 中找到",
        "options": [
          {
            "label": "한국어",
            "value": "Kor"
          },
          {
            "label": "中文(简体)",
            "value": "Chs"
          },
          {
            "label": "中文(繁体)",
            "value": "Cht"
          },
          {
            "label": "English",
            "value": "Eng"
          },
          {
            "label": "Українська",
            "value": "Eng"
          },
          {
            "label": "Русский",
            "value": "Rus"
          },
          {
            "label": "Polski",
            "value": "Pol"
          }
        ]
      }
    }
  }
}
```
