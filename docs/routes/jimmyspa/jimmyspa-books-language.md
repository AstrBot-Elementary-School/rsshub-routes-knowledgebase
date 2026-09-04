# 幾米 JIMMY S.P.A. Official Website - Books

## Coverage
`index-only`

## Route
- Namespace: `jimmyspa`
- Namespace Name: `幾米 JIMMY S.P.A. Official Website`
- Route Path: `/jimmyspa/books/:language`
- Route Name: `Books`
- Example: `/jimmyspa/books/tw`
- URL: `www.jimmyspa.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `Cedaric`
- Source Location: `books.ts`
- Source Module: `_None_`

## Description
| language | Description |
| -------- | ----------- |
| tw       | 臺灣正體    |
| en       | English     |
| jp       | 日本語      |

## Parameters
- `language`: {"description": "语言", "options": [{"label": "臺灣正體", "value": "tw"}, {"label": "English", "value": "en"}, {"label": "日本語", "value": "jp"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.jimmyspa.com/:language/Books`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "| language | Description |\n| -------- | ----------- |\n| tw       | 臺灣正體    |\n| en       | English     |\n| jp       | 日本語      |",
  "example": "/jimmyspa/books/tw",
  "heat": 16,
  "location": "books.ts",
  "maintainers": [
    "Cedaric"
  ],
  "name": "Books",
  "parameters": {
    "language": {
      "description": "语言",
      "options": [
        {
          "label": "臺灣正體",
          "value": "tw"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "日本語",
          "value": "jp"
        }
      ]
    }
  },
  "path": "/books/:language",
  "radar": [
    {
      "source": [
        "www.jimmyspa.com/:language/Books"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "幾米 - 幾米創作(tw) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93100945524546560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jimmyspa.com/tw/Books",
      "title": "幾米 - 幾米創作(tw)",
      "type": "feed",
      "url": "rsshub://jimmyspa/books/tw"
    },
    {
      "description": "幾米 - 幾米創作(en) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182968644220997632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jimmyspa.com/en/Books",
      "title": "幾米 - 幾米創作(en)",
      "type": "feed",
      "url": "rsshub://jimmyspa/books/en"
    }
  ],
  "view": 0
}
```
