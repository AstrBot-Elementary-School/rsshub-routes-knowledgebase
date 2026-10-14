# Shopify - App reviews

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/shopify/apps/:handle/reviews/:page?`
- Route Name: `App reviews`
- Example: `/shopify/apps/flow/reviews`
- URL: `shopify.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `PrintNow`
- Source Location: `apps/[handle].reviews.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: 例如一个 App 的链接 https://apps.shopify.com/flow，其中 flow 就是指的是 handle
- `page`: 兼容旧链接；始终返回最新评论第一页


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `apps.shopify.com/:handle/reviews`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/shopify/apps/flow/reviews",
  "heat": 0,
  "location": "apps/[handle].reviews.ts",
  "maintainers": [
    "PrintNow"
  ],
  "name": "App reviews",
  "parameters": {
    "handle": "例如一个 App 的链接 https://apps.shopify.com/flow，其中 flow 就是指的是 handle",
    "page": "兼容旧链接；始终返回最新评论第一页"
  },
  "path": "/apps/:handle/reviews/:page?",
  "radar": [
    {
      "source": [
        "apps.shopify.com/:handle/reviews"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
