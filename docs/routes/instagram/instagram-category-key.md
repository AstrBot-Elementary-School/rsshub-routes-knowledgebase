# Instagram - User Profile / Hashtag - Private API

## Coverage
`index-only`

## Route
- Namespace: `instagram`
- Namespace Name: `Instagram`
- Route Path: `/instagram/:category/:key`
- Route Name: `User Profile / Hashtag - Private API`
- Example: `/instagram/user/stefaniejoosten`
- URL: `www.instagram.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `oppilate, DIYgod`
- Source Location: `private-api/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "user", "description": "Feed category", "options": [{"label": "User", "value": "user"}, {"label": "Tags", "value": "tags"}]}
- `key`: Username / Hashtag name


## Features
- `requireConfig`: [{"description": "", "name": "IG_PROXY", "optional": true}, {"description": "Instagram username", "name": "IG_USERNAME"}, {"description": "Instagram password, due to [Instagram Private API](https://github.com/dilame/instagram-private-api) restrictions, you have to setup your credentials on the server. 2FA is not supported.", "name": "IG_PASSWORD"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/instagram/user/stefaniejoosten",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "IG_PROXY",
        "optional": true
      },
      {
        "description": "Instagram username",
        "name": "IG_USERNAME"
      },
      {
        "description": "Instagram password, due to [Instagram Private API](https://github.com/dilame/instagram-private-api) restrictions, you have to setup your credentials on the server. 2FA is not supported.",
        "name": "IG_PASSWORD"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 51,
  "location": "private-api/index.ts",
  "maintainers": [
    "oppilate",
    "DIYgod"
  ],
  "name": "User Profile / Hashtag - Private API",
  "parameters": {
    "category": {
      "default": "user",
      "description": "Feed category",
      "options": [
        {
          "label": "User",
          "value": "user"
        },
        {
          "label": "Tags",
          "value": "tags"
        }
      ]
    },
    "key": "Username / Hashtag name"
  },
  "path": "/:category/:key",
  "topFeeds": [
    {
      "description": "undefined (@stefaniejoosten) - Instagram - Powered by RSSHub",
      "errorAt": "2024-12-25T02:49:15.475Z",
      "errorMessage": "200 ",
      "id": "70631931772977152",
      "image": "https://scontent-ord5-2.cdninstagram.com/v/t51.2885-19/387739978_181173168359511_7722211169329121600_n.jpg?stp=dst-jpg_e0_s150x150&_nc_ht=scontent-ord5-2.cdninstagram.com&_nc_cat=103&_nc_ohc=-J4UemQ3dPsQ7kNvgFFvACb&_nc_gid=a20d273ebe7148119c1abd93d6d45d4b&edm=AEF8tYYBAAAA&ccb=7-5&oh=00_AYBVycUmjMnx2eGiiQ4dX2PDkPrT1XFznkh369Uxv2hV9A&oe=6706D955&_nc_sid=1e20d2",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/stefaniejoosten",
      "title": "undefined (@stefaniejoosten) - Instagram",
      "type": "feed",
      "url": "rsshub://instagram/user/stefaniejoosten"
    },
    {
      "description": "undefined (@arrriiaa_w) - Instagram - Powered by RSSHub",
      "errorAt": "2025-12-11T11:45:24.669Z",
      "errorMessage": "POST /api/v1/accounts/login/ - 429 Too Many Requests; Please wait a few minutes before you try again.\nPOST /api/v1/accounts/login/ - 400 Bad Request; challenge_required\n",
      "id": "62147426956831744",
      "image": "https://scontent-lax3-2.cdninstagram.com/v/t51.2885-19/279747740_420453782772871_6986839216162999403_n.jpg?stp=dst-jpg_e0_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-lax3-2.cdninstagram.com&_nc_cat=107&_nc_oc=Q6cZ2QGdZ_iENXEPn3OpzQQo0OYdf3Y3tfr2djTnFy3QSF7xZA-stNQTPT9hWlyFKFiRpng&_nc_ohc=P1f0w8MXen4Q7kNvwEAWqvY&_nc_gid=Sv_9hZ32tlXXC_LZ_100hg&edm=AEF8tYYBAAAA&ccb=7-5&oh=00_AfmvZx4fq_tU13sGypV6ChjMru8t8FbGpn8NjhYrWxD5Jg&oe=694045FB&_nc_sid=1e20d2",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/arrriiaa_w",
      "title": "undefined (@arrriiaa_w) - Instagram",
      "type": "feed",
      "url": "rsshub://instagram/user/arrriiaa_w"
    }
  ],
  "view": 1
}
```
