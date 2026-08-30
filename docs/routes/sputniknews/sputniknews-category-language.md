# Sputnik News 俄罗斯卫星通讯社 - Category

## Coverage
`index-only`

## Route
- Namespace: `sputniknews`
- Namespace Name: `Sputnik News 俄罗斯卫星通讯社`
- Route Path: `/sputniknews/:category?/:language?`
- Route Name: `Category`
- Example: `/sputniknews`
- URL: `sputniknews.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Categories for International site:

| WORLD | COVID-19 | BUSINESS | SPORT | TECH | OPINION |
| ----- | -------- | -------- | ----- | ---- | ------- |
| world | covid-19 | business | sport | tech | opinion |

Categories for Chinese site:

| 新闻 | 中国  | 俄罗斯 | 国际            | 俄中关系                 | 评论    |
| ---- | ----- | ------ | --------------- | ------------------------ | ------- |
| news | china | russia | category\_guoji | russia\_china\_relations | opinion |

Language

| Language    | Id          |
| ----------- | ----------- |
| English     | english     |
| Spanish     | spanish     |
| German      | german      |
| French      | french      |
| Greek       | greek       |
| Italian     | italian     |
| Czech       | czech       |
| Polish      | polish      |
| Serbian     | serbian     |
| Latvian     | latvian     |
| Lithuanian  | lithuanian  |
| Moldavian   | moldavian   |
| Belarusian  | belarusian  |
| Armenian    | armenian    |
| Abkhaz      | abkhaz      |
| Ssetian     | ssetian     |
| Georgian    | georgian    |
| Azerbaijani | azerbaijani |
| Arabic      | arabic      |
| Turkish     | turkish     |
| Persian     | persian     |
| Dari        | dari        |
| Kazakh      | kazakh      |
| Kyrgyz      | kyrgyz      |
| Uzbek       | uzbek       |
| Tajik       | tajik       |
| Vietnamese  | vietnamese  |
| Japanese    | japanese    |
| Chinese     | chinese     |
| Portuguese  | portuguese  |

## Parameters
- `category`: Category, can be found in URL, `news` by default
- `language`: Language, see below, English by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "traditional-media"
  ],
  "description": "Categories for International site:\n\n| WORLD | COVID-19 | BUSINESS | SPORT | TECH | OPINION |\n| ----- | -------- | -------- | ----- | ---- | ------- |\n| world | covid-19 | business | sport | tech | opinion |\n\nCategories for Chinese site:\n\n| 新闻 | 中国  | 俄罗斯 | 国际            | 俄中关系                 | 评论    |\n| ---- | ----- | ------ | --------------- | ------------------------ | ------- |\n| news | china | russia | category\\_guoji | russia\\_china\\_relations | opinion |\n\nLanguage\n\n| Language    | Id          |\n| ----------- | ----------- |\n| English     | english     |\n| Spanish     | spanish     |\n| German      | german      |\n| French      | french      |\n| Greek       | greek       |\n| Italian     | italian     |\n| Czech       | czech       |\n| Polish      | polish      |\n| Serbian     | serbian     |\n| Latvian     | latvian     |\n| Lithuanian  | lithuanian  |\n| Moldavian   | moldavian   |\n| Belarusian  | belarusian  |\n| Armenian    | armenian    |\n| Abkhaz      | abkhaz      |\n| Ssetian     | ssetian     |\n| Georgian    | georgian    |\n| Azerbaijani | azerbaijani |\n| Arabic      | arabic      |\n| Turkish     | turkish     |\n| Persian     | persian     |\n| Dari        | dari        |\n| Kazakh      | kazakh      |\n| Kyrgyz      | kyrgyz      |\n| Uzbek       | uzbek       |\n| Tajik       | tajik       |\n| Vietnamese  | vietnamese  |\n| Japanese    | japanese    |\n| Chinese     | chinese     |\n| Portuguese  | portuguese  |",
  "example": "/sputniknews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 243,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, can be found in URL, `news` by default",
    "language": "Language, see below, English by default"
  },
  "path": "/:category?/:language?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "news - Sputnik News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60322104504418309",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sputniknews.com/news",
      "title": "news - Sputnik News",
      "type": "feed",
      "url": "rsshub://sputniknews"
    },
    {
      "description": "news - Sputnik News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68844937961281540",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sputniknews.cn/news",
      "title": "news - Sputnik News",
      "type": "feed",
      "url": "rsshub://sputniknews/news/chinese"
    }
  ]
}
```
