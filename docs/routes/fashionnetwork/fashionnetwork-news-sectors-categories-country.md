# FashionNetwork - News

## Coverage
`index-only`

## Route
- Namespace: `fashionnetwork`
- Namespace Name: `FashionNetwork`
- Route Path: `/fashionnetwork/news/:sectors?/:categories?/:country?`
- Route Name: `News`
- Example: `/fashionnetwork/news/5,6/15,112`
- URL: `fashionnetwork.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Sectors

Fashion 1

| Ready-to-wear | Accessories | Footwear | Sports | Denim | Lingerie | Swimwear | Eyewear | Bridal wear | Textile | Miscellaneous |
| ------------- | ----------- | -------- | ------ | ----- | -------- | -------- | ------- | ----------- | ------- | ------------- |
| 5             | 6           | 7        | 8      | 9     | 10       | 11       | 12      | 13          | 14      | 31            |

Luxury 2

| Ready-to-wear | Accessories | Footwear | Watches | Jewellery | Miscellaneous |
| ------------- | ----------- | -------- | ------- | --------- | ------------- |
| 15            | 16          | 17       | 18      | 19        | 32            |

Beauty 3

| Perfume | Cosmetics | Aesthetics | Wellness | Hair | Miscellaneous |
| ------- | --------- | ---------- | -------- | ---- | ------------- |
| 21      | 22        | 23         | 24       | 33   |               |

Lifestyle 4

| Home decor | Tableware | Hospitality | Fine foods | Tourism | Miscellaneous |
| ---------- | --------- | ----------- | ---------- | ------- | ------------- |
| 25         | 26        | 27          | 28         | 29      | 34            |

Others 30

Category

| Retail | Business | Industry | Trade shows |
| ------ | -------- | -------- | ----------- |
| 15     | 112      | 5        | 12          |

| Innovations | Collection | Catwalks | Design |
| ----------- | ---------- | -------- | ------ |
| 113         | 114        | 60       | 70     |

| Media | Campaigns | People | Events | Appointments |
| ----- | --------- | ------ | ------ | ------------ |
| 50    | 115       | 80     | 90     | 95           |

Country

| Latin America | Brazil | China | France |
| ------------- | ------ | ----- | ------ |
| pe            | br     | cn    | fr     |

| Germany | India | Italy | Japan |
| ------- | ----- | ----- | ----- |
| de      | in    | it    | jp    |

| Mexico | Portugal | Russia | Spain |
| ------ | -------- | ------ | ----- |
| mx     | pt       | ru     | es    |

| Turkey | United Kingdom | USA | Worldwide |
| ------ | -------------- | --- | --------- |
| tr     | uk             | us  | ww        |

## Parameters
- `sectors`: Sectors, see below, `all` by default
- `categories`: Categories, see below, `all` by default
- `country`: Country, see below, `ww` as Worldwide by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Sectors\n\nFashion 1\n\n| Ready-to-wear | Accessories | Footwear | Sports | Denim | Lingerie | Swimwear | Eyewear | Bridal wear | Textile | Miscellaneous |\n| ------------- | ----------- | -------- | ------ | ----- | -------- | -------- | ------- | ----------- | ------- | ------------- |\n| 5             | 6           | 7        | 8      | 9     | 10       | 11       | 12      | 13          | 14      | 31            |\n\nLuxury 2\n\n| Ready-to-wear | Accessories | Footwear | Watches | Jewellery | Miscellaneous |\n| ------------- | ----------- | -------- | ------- | --------- | ------------- |\n| 15            | 16          | 17       | 18      | 19        | 32            |\n\nBeauty 3\n\n| Perfume | Cosmetics | Aesthetics | Wellness | Hair | Miscellaneous |\n| ------- | --------- | ---------- | -------- | ---- | ------------- |\n| 21      | 22        | 23         | 24       | 33   |               |\n\nLifestyle 4\n\n| Home decor | Tableware | Hospitality | Fine foods | Tourism | Miscellaneous |\n| ---------- | --------- | ----------- | ---------- | ------- | ------------- |\n| 25         | 26        | 27          | 28         | 29      | 34            |\n\nOthers 30\n\nCategory\n\n| Retail | Business | Industry | Trade shows |\n| ------ | -------- | -------- | ----------- |\n| 15     | 112      | 5        | 12          |\n\n| Innovations | Collection | Catwalks | Design |\n| ----------- | ---------- | -------- | ------ |\n| 113         | 114        | 60       | 70     |\n\n| Media | Campaigns | People | Events | Appointments |\n| ----- | --------- | ------ | ------ | ------------ |\n| 50    | 115       | 80     | 90     | 95           |\n\nCountry\n\n| Latin America | Brazil | China | France |\n| ------------- | ------ | ----- | ------ |\n| pe            | br     | cn    | fr     |\n\n| Germany | India | Italy | Japan |\n| ------- | ----- | ----- | ----- |\n| de      | in    | it    | jp    |\n\n| Mexico | Portugal | Russia | Spain |\n| ------ | -------- | ------ | ----- |\n| mx     | pt       | ru     | es    |\n\n| Turkey | United Kingdom | USA | Worldwide |\n| ------ | -------------- | --- | --------- |\n| tr     | uk             | us  | ww        |",
  "example": "/fashionnetwork/news/5,6/15,112",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "categories": "Categories, see below, `all` by default",
    "country": "Country, see below, `ww` as Worldwide by default",
    "sectors": "Sectors, see below, `all` by default"
  },
  "path": "/news/:sectors?/:categories?/:country?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
