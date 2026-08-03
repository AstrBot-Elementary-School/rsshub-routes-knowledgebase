# RSSHub - Transformation - HTML

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/rsshub/transform/html/:url/:routeParams`
- Route Name: `Transformation - HTML`
- Example: `/rsshub/transform/html/https%3A%2F%2Fwechat2rss.xlab.app%2Fposts%2Flist%2F/item=div%5Bclass%3D%27post%2Dcontent%27%5D%20p%20a`
- URL: `docs.rsshub.app`
- Language: `_None_`
- Categories: `other, popular`
- Maintainers: `ttttmr, hyoban`
- Source Location: `transform/html.ts`
- Source Module: `_None_`

## Description
Pass URL and transformation rules to convert HTML/JSON into RSS.

Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from HTML.

| Key               | Meaning                                                                                                 | Accepted Values | Default                |
| ----------------- | ------------------------------------------------------------------------------------------------------- | --------------- | ---------------------- |
| `title`           | The title of the RSS                                                                                    | `string`        | Extract from `<title>` |
| `item`            | The HTML elements as `item` using CSS selector                                                          | `string`        | html                   |
| `itemTitle`       | The HTML elements as `title` in `item` using CSS selector                                               | `string`        | `item` element         |
| `itemTitleAttr`   | The attributes of `title` element as title                                                              | `string`        | Element text           |
| `itemLink`        | The HTML elements as `link` in `item` using CSS selector                                                | `string`        | `item` element         |
| `itemLinkAttr`    | The attributes of `link` element as link                                                                | `string`        | `href`                 |
| `itemDesc`        | The HTML elements as `descrption` in `item` using CSS selector                                          | `string`        | `item` element         |
| `itemDescAttr`    | The attributes of `descrption` element as description                                                   | `string`        | Element html           |
| `itemPubDate`     | The HTML elements as `pubDate` in `item` using CSS selector                                             | `string`        | `item` element         |
| `itemPubDateAttr` | The attributes of `pubDate` element as pubDate                                                          | `string`        | Element html           |
| `itemContent`     | The HTML elements as `description` in `item` using CSS selector ( in `itemLink` page for full content ) | `string`        |                        |
| `encoding`        | The encoding of the HTML content                                                                        | `string`        | utf-8                  |

Parameters parsing in the above example:

| Parameter     | Value                                     |
| ------------- | ----------------------------------------- |
| `url`         | `https://wechat2rss.xlab.app/posts/list/` |
| `routeParams` | `item=div[class='post-content'] p a`      |

Parsing of `routeParams` parameter:

| Parameter | Value                           |
| --------- | ------------------------------- |
| `item`    | `div[class='post-content'] p a` |

## Parameters
- `url`: `encodeURIComponent`ed URL address
- `routeParams`: Transformation rules, requires URL encode


## Features
- `requireConfig`: [{"description": "", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]
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
    "other",
    "popular"
  ],
  "description": "Pass URL and transformation rules to convert HTML/JSON into RSS.\n\nSpecify options (in the format of query string) in parameter `routeParams` parameter to extract data from HTML.\n\n| Key               | Meaning                                                                                                 | Accepted Values | Default                |\n| ----------------- | ------------------------------------------------------------------------------------------------------- | --------------- | ---------------------- |\n| `title`           | The title of the RSS                                                                                    | `string`        | Extract from `<title>` |\n| `item`            | The HTML elements as `item` using CSS selector                                                          | `string`        | html                   |\n| `itemTitle`       | The HTML elements as `title` in `item` using CSS selector                                               | `string`        | `item` element         |\n| `itemTitleAttr`   | The attributes of `title` element as title                                                              | `string`        | Element text           |\n| `itemLink`        | The HTML elements as `link` in `item` using CSS selector                                                | `string`        | `item` element         |\n| `itemLinkAttr`    | The attributes of `link` element as link                                                                | `string`        | `href`                 |\n| `itemDesc`        | The HTML elements as `descrption` in `item` using CSS selector                                          | `string`        | `item` element         |\n| `itemDescAttr`    | The attributes of `descrption` element as description                                                   | `string`        | Element html           |\n| `itemPubDate`     | The HTML elements as `pubDate` in `item` using CSS selector                                             | `string`        | `item` element         |\n| `itemPubDateAttr` | The attributes of `pubDate` element as pubDate                                                          | `string`        | Element html           |\n| `itemContent`     | The HTML elements as `description` in `item` using CSS selector ( in `itemLink` page for full content ) | `string`        |                        |\n| `encoding`        | The encoding of the HTML content                                                                        | `string`        | utf-8                  |\n\nParameters parsing in the above example:\n\n| Parameter     | Value                                     |\n| ------------- | ----------------------------------------- |\n| `url`         | `https://wechat2rss.xlab.app/posts/list/` |\n| `routeParams` | `item=div[class='post-content'] p a`      |\n\nParsing of `routeParams` parameter:\n\n| Parameter | Value                           |\n| --------- | ------------------------------- |\n| `item`    | `div[class='post-content'] p a` |",
  "example": "/rsshub/transform/html/https%3A%2F%2Fwechat2rss.xlab.app%2Fposts%2Flist%2F/item=div%5Bclass%3D%27post%2Dcontent%27%5D%20p%20a",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7572,
  "location": "transform/html.ts",
  "maintainers": [
    "ttttmr",
    "hyoban"
  ],
  "name": "Transformation - HTML",
  "parameters": {
    "routeParams": "Transformation rules, requires URL encode",
    "url": "`encodeURIComponent`ed URL address"
  },
  "path": "/transform/html/:url/:routeParams",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Proxy https://imnks.com/ - Powered by RSSHub",
      "errorAt": "2026-08-02T04:55:24.314Z",
      "errorMessage": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\nThis RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\nAuthentication failed. Access denied.\n/rsshub/transform/html/https%3A%2F%2Fimnks.com%2F/item=article&itemTitle=span%5Bclass=entry-title%5D&itemLink=span%5Bclass=entry-title%5D+a&itemDesc=div%5Bclass*=entry-summary%5D&itemPubDate=div%5Bclass=entry-meta%5D+time&itemPubDateAttr=datetime\nThis RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\n[GET] \"https://imnks.com/\": 522 Origin Connection Time-out\n",
      "id": "68731140035191863",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://imnks.com/",
      "title": "我不是矿神 - 群晖,威联通,铁威马,绿联UGOS,万由UNAS,飞牛fnOS,UNRAID,ESXI,PVE,OPENWRT",
      "type": "feed",
      "url": "rsshub://rsshub/transform/html/https%3A%2F%2Fimnks.com%2F/item=article&itemTitle=span%5Bclass=entry-title%5D&itemLink=span%5Bclass=entry-title%5D+a&itemDesc=div%5Bclass*=entry-summary%5D&itemPubDate=div%5Bclass=entry-meta%5D+time&itemPubDateAttr=datetime"
    },
    {
      "description": "Proxy https://javdb.com/uncensored - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70337524894135296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/uncensored",
      "title": "javDB无码",
      "type": "feed",
      "url": "rsshub://rsshub/transform/html/https%3A%2F%2Fjavdb.com%2Funcensored/title%3DjavDB%E6%97%A0%E7%A0%81"
    }
  ]
}
```
