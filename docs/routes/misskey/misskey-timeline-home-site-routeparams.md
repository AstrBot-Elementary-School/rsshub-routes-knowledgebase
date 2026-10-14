# Misskey - Home Timeline

## Coverage
`index-only`

## Route
- Namespace: `misskey`
- Namespace Name: `Misskey`
- Route Path: `/misskey/timeline/home/:site/:routeParams?`
- Route Name: `Home Timeline`
- Example: `/misskey/timeline/home/misskey.io`
- URL: `misskey.io`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `HanaokaYuzu`
- Source Location: `home-timeline.ts`
- Source Module: `_None_`

## Description
::: warning
This route is only available for self-hosted instances.
:::

## Parameters
- `site`: instance address, domain only, without `http://` or `https://` protocol header
- `routeParams`: | Key                  | Description                             | Accepted Values | Default |
| -------------------- | --------------------------------------- | --------------- | ------- |
| limit                | Number of notes to return               | integer         | 10      |
| withFiles            | Only return notes containing files      | 0/1/true/false  | false   |
| withRenotes          | Include renotes in the timeline         | 0/1/true/false  | true    |
| allowPartial         | Allow partial results                   | 0/1/true/false  | true    |
| simplifyAuthor       | Simplify author field in feed items     | 0/1/true/false  | true    |

Note: If `withFiles` is set to true, renotes will not be included in the timeline regardless of the value of `withRenotes`.

Examples:
- /misskey/timeline/home/misskey.io/limit=20&withFiles=true
- /misskey/timeline/home/misskey.io/withRenotes=false


## Features
- `requireConfig`: [{"description": "\n                    Access token for Misskey API. Requires `read:account` access.\n\n                    Visit the specified site's settings page to obtain an access token. E.g. https://misskey.io/settings/api\n                ", "name": "MISSKEY_ACCESS_TOKEN", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `misskey.io`
- `target`: `/timeline/home/misskey.io`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\nThis route is only available for self-hosted instances.\n:::",
  "example": "/misskey/timeline/home/misskey.io",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "\n                    Access token for Misskey API. Requires `read:account` access.\n\n                    Visit the specified site's settings page to obtain an access token. E.g. https://misskey.io/settings/api\n                ",
        "name": "MISSKEY_ACCESS_TOKEN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "home-timeline.ts",
  "maintainers": [
    "HanaokaYuzu"
  ],
  "name": "Home Timeline",
  "parameters": {
    "routeParams": "\n| Key                  | Description                             | Accepted Values | Default |\n| -------------------- | --------------------------------------- | --------------- | ------- |\n| limit                | Number of notes to return               | integer         | 10      |\n| withFiles            | Only return notes containing files      | 0/1/true/false  | false   |\n| withRenotes          | Include renotes in the timeline         | 0/1/true/false  | true    |\n| allowPartial         | Allow partial results                   | 0/1/true/false  | true    |\n| simplifyAuthor       | Simplify author field in feed items     | 0/1/true/false  | true    |\n\nNote: If `withFiles` is set to true, renotes will not be included in the timeline regardless of the value of `withRenotes`.\n\nExamples:\n- /misskey/timeline/home/misskey.io/limit=20&withFiles=true\n- /misskey/timeline/home/misskey.io/withRenotes=false\n        ",
    "site": "instance address, domain only, without `http://` or `https://` protocol header"
  },
  "path": "/timeline/home/:site/:routeParams?",
  "radar": [
    {
      "source": [
        "misskey.io"
      ],
      "target": "/timeline/home/misskey.io"
    }
  ],
  "topFeeds": [
    {
      "description": "Home Timeline on misskey.io - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112240058695615488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskey.io/",
      "title": "Home Timeline on misskey.io",
      "type": "feed",
      "url": "rsshub://misskey/timeline/home/misskey.io/withFiles=true&limit=20"
    }
  ],
  "view": 1
}
```
