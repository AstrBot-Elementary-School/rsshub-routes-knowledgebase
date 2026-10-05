# Facebook - Page

## Coverage
`index-only`

## Route
- Namespace: `facebook`
- Namespace Name: `Facebook`
- Route Path: `/facebook/page/:id`
- Route Name: `Page`
- Example: `/facebook/page/NASA`
- URL: `www.facebook.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `page.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Page ID


## Features
- `requireConfig`: [{"description": "Facebook cookie, only `c_user` and `xs` are required.", "name": "FACEBOOK_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.facebook.com/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/facebook/page/NASA",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "Facebook cookie, only `c_user` and `xs` are required.",
        "name": "FACEBOOK_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "page.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Page",
  "parameters": {
    "id": "Page ID"
  },
  "path": "/page/:id",
  "radar": [
    {
      "source": [
        "www.facebook.com/:id"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.facebook.com"
}
```
