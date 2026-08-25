# Bandisoft - History

## Coverage
`index-only`

## Route
- Namespace: `bandisoft`
- Namespace Name: `Bandisoft`
- Route Path: `/bandisoft/history/:id?/:language?`
- Route Name: `History`
- Example: `/bandisoft/history/bandizip`
- URL: `www.bandisoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `history.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Bandizip Version History](https://www.bandisoft.com/bandizip/history/), where the source URL is `https://www.bandisoft.com/bandizip/history/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/bandisoft/history/bandizip`](https://rsshub.app/bandisoft/history/bandizip).
:::

<details>
  <summary>More languages</summary>

| Language             | ID |
| -------------------- | -- |
| English              | en |
| 中文 (简体)          | cn |
| 中文 (繁體)          | tw |
| 日本語               | jp |
| Русский              | ru |
| Español              | es |
| Français             | fr |
| Deutsch              | de |
| Italiano             | it |
| Slovenčina           | sk |
| Українська           | uk |
| Беларуская           | be |
| Dansk                | da |
| Polski               | pl |
| Português Brasileiro | br |
| Čeština              | cs |
| Nederlands           | nl |
| Slovenščina          | sl |
| Türkçe               | tr |
| ภาษาไทย              | th |
| Ελληνικά             | gr |
| Oʻzbek               | uz |
| Romanian             | ro |
| 한국어               | kr |

</details>

## Parameters
- `id`: {"description": "ID, `bandizip` by default", "options": [{"label": "Bandizip", "value": "bandizip"}, {"label": "Bandizip for Mac", "value": "bandizip.mac"}, {"label": "BandiView", "value": "bandiview"}, {"label": "Honeycam", "value": "honeycam"}]}
- `language`: {"description": "Language, `en` by default", "options": [{"label": "English", "value": "en"}, {"label": "中文(简体)", "value": "cn"}, {"label": "中文(繁體)", "value": "tw"}, {"label": "日本語", "value": "jp"}, {"label": "Русский", "value": "ru"}, {"label": "Español", "value": "es"}, {"label": "Français", "value": "fr"}, {"label": "Deutsch", "value": "de"}, {"label": "Italiano", "value": "it"}, {"label": "Slovenčina", "value": "sk"}, {"label": "Українська", "value": "uk"}, {"label": "Беларуская", "value": "be"}, {"label": "Dansk", "value": "da"}, {"label": "Polski", "value": "pl"}, {"label": "Português Brasileiro", "value": "br"}, {"label": "Čeština", "value": "cs"}, {"label": "Nederlands", "value": "nl"}, {"label": "Slovenščina", "value": "sl"}, {"label": "Türkçe", "value": "tr"}, {"label": "ภาษาไทย", "value": "th"}, {"label": "Ελληνικά", "value": "gr"}, {"label": "O'zbek", "value": "uz"}, {"label": "Romanian", "value": "ro"}, {"label": "한국어", "value": "kr"}]}


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
  - `www.bandisoft.com/:id/history`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Bandizip Version History](https://www.bandisoft.com/bandizip/history/), where the source URL is `https://www.bandisoft.com/bandizip/history/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/bandisoft/history/bandizip`](https://rsshub.app/bandisoft/history/bandizip).\n:::\n\n<details>\n  <summary>More languages</summary>\n\n| Language             | ID |\n| -------------------- | -- |\n| English              | en |\n| 中文 (简体)          | cn |\n| 中文 (繁體)          | tw |\n| 日本語               | jp |\n| Русский              | ru |\n| Español              | es |\n| Français             | fr |\n| Deutsch              | de |\n| Italiano             | it |\n| Slovenčina           | sk |\n| Українська           | uk |\n| Беларуская           | be |\n| Dansk                | da |\n| Polski               | pl |\n| Português Brasileiro | br |\n| Čeština              | cs |\n| Nederlands           | nl |\n| Slovenščina          | sl |\n| Türkçe               | tr |\n| ภาษาไทย              | th |\n| Ελληνικά             | gr |\n| Oʻzbek               | uz |\n| Romanian             | ro |\n| 한국어               | kr |\n\n</details>",
  "example": "/bandisoft/history/bandizip",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "history.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "History",
  "parameters": {
    "id": {
      "description": "ID, `bandizip` by default",
      "options": [
        {
          "label": "Bandizip",
          "value": "bandizip"
        },
        {
          "label": "Bandizip for Mac",
          "value": "bandizip.mac"
        },
        {
          "label": "BandiView",
          "value": "bandiview"
        },
        {
          "label": "Honeycam",
          "value": "honeycam"
        }
      ]
    },
    "language": {
      "description": "Language, `en` by default",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "中文(简体)",
          "value": "cn"
        },
        {
          "label": "中文(繁體)",
          "value": "tw"
        },
        {
          "label": "日本語",
          "value": "jp"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "Italiano",
          "value": "it"
        },
        {
          "label": "Slovenčina",
          "value": "sk"
        },
        {
          "label": "Українська",
          "value": "uk"
        },
        {
          "label": "Беларуская",
          "value": "be"
        },
        {
          "label": "Dansk",
          "value": "da"
        },
        {
          "label": "Polski",
          "value": "pl"
        },
        {
          "label": "Português Brasileiro",
          "value": "br"
        },
        {
          "label": "Čeština",
          "value": "cs"
        },
        {
          "label": "Nederlands",
          "value": "nl"
        },
        {
          "label": "Slovenščina",
          "value": "sl"
        },
        {
          "label": "Türkçe",
          "value": "tr"
        },
        {
          "label": "ภาษาไทย",
          "value": "th"
        },
        {
          "label": "Ελληνικά",
          "value": "gr"
        },
        {
          "label": "O'zbek",
          "value": "uz"
        },
        {
          "label": "Romanian",
          "value": "ro"
        },
        {
          "label": "한국어",
          "value": "kr"
        }
      ]
    }
  },
  "path": "/history/:id?/:language?",
  "radar": [
    {
      "source": [
        "www.bandisoft.com/:id/history"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(56) ] to not include 'bandisoft-bandizip-en-v6.13'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.bandisoft.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [Bandizip 更新记录](https://cn.bandisoft.com/bandizip/history/)，网址为 `https://cn.bandisoft.com/bandizip/history/`，请截取 `cn` 作为 `category` 参数填入，此时目标路由为 [`/bandisoft/:language?/:id?`](https://rsshub.app/bandisoft/:language?/:id?)。\n:::\n\n<details>\n  <summary>更多语言</summary>\n\n| Language             | ID |\n| -------------------- | -- |\n| English              | en |\n| 中文 (简体)          | cn |\n| 中文 (繁體)          | tw |\n| 日本語               | jp |\n| Русский              | ru |\n| Español              | es |\n| Français             | fr |\n| Deutsch              | de |\n| Italiano             | it |\n| Slovenčina           | sk |\n| Українська           | uk |\n| Беларуская           | be |\n| Dansk                | da |\n| Polski               | pl |\n| Português Brasileiro | br |\n| Čeština              | cs |\n| Nederlands           | nl |\n| Slovenščina          | sl |\n| Türkçe               | tr |\n| ภาษาไทย              | th |\n| Ελληνικά             | gr |\n| Oʻzbek               | uz |\n| Romanian             | ro |\n| 한국어               | kr |\n\n</details>",
    "name": "更新记录",
    "parameters": {
      "id": {
        "description": "ID, 默认为 `bandizip`，可在对应产品页 URL 中找到",
        "options": [
          {
            "label": "Bandizip",
            "value": "bandizip"
          },
          {
            "label": "Bandizip for Mac",
            "value": "bandizip.mac"
          },
          {
            "label": "BandiView",
            "value": "bandiview"
          },
          {
            "label": "Honeycam",
            "value": "honeycam"
          }
        ]
      },
      "language": {
        "description": "地区, 默认为 `en`",
        "options": [
          {
            "label": "English",
            "value": "en"
          },
          {
            "label": "中文(简体)",
            "value": "cn"
          },
          {
            "label": "中文(繁體)",
            "value": "tw"
          },
          {
            "label": "日本語",
            "value": "jp"
          },
          {
            "label": "Русский",
            "value": "ru"
          },
          {
            "label": "Español",
            "value": "es"
          },
          {
            "label": "Français",
            "value": "fr"
          },
          {
            "label": "Deutsch",
            "value": "de"
          },
          {
            "label": "Italiano",
            "value": "it"
          },
          {
            "label": "Slovenčina",
            "value": "sk"
          },
          {
            "label": "Українська",
            "value": "uk"
          },
          {
            "label": "Беларуская",
            "value": "be"
          },
          {
            "label": "Dansk",
            "value": "da"
          },
          {
            "label": "Polski",
            "value": "pl"
          },
          {
            "label": "Português Brasileiro",
            "value": "br"
          },
          {
            "label": "Čeština",
            "value": "cs"
          },
          {
            "label": "Nederlands",
            "value": "nl"
          },
          {
            "label": "Slovenščina",
            "value": "sl"
          },
          {
            "label": "Türkçe",
            "value": "tr"
          },
          {
            "label": "ภาษาไทย",
            "value": "th"
          },
          {
            "label": "Ελληνικά",
            "value": "gr"
          },
          {
            "label": "O'zbek",
            "value": "uz"
          },
          {
            "label": "Romanian",
            "value": "ro"
          },
          {
            "label": "한국어",
            "value": "kr"
          }
        ]
      }
    }
  }
}
```
