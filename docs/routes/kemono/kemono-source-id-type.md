# Kemono - Posts

## Coverage
`index-only`

## Route
- Namespace: `kemono`
- Namespace Name: `Kemono`
- Route Path: `/kemono/:source?/:id?/:type?`
- Route Name: `Posts`
- Example: `/kemono`
- URL: `kemono.cr`
- Language: `_None_`
- Categories: `anime, popular`
- Maintainers: `nczitzk, AiraNadih`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
Sources

| Posts | Patreon | Pixiv Fanbox | Gumroad | SubscribeStar | DLsite | Discord | Fantia |
| ----- | ------- | ------------ | ------- | ------------- | ------ | ------- | ------ |
| posts | patreon | fanbox       | gumroad | subscribestar | dlsite | discord | fantia |

::: tip
When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.
There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.

Support for announcements and fancards:

- Use `/:source/:id/announcements` to get announcements
- Use `/:source/:id/fancards` to get fancards

:::

## Parameters
- `source`: Source, see below, Posts by default
- `id`: User id, can be found in URL
- `type`: Content type: announcements or fancards


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `kemono.cr/`
- `target`: ``
### Rule 2
- `source`:
  - `kemono.cr/:source/user/:id`
- `target`: `/:source/:id`
### Rule 3
- `source`:
  - `kemono.cr/:source/user/:id/announcements`
- `target`: `/:source/:id/announcements`
### Rule 4
- `source`:
  - `kemono.cr/:source/user/:id/fancards`
- `target`: `/:source/:id/fancards`
### Rule 5
- `source`:
  - `kemono.cr/discord/server/:id`
- `target`: `/discord/:id`

## Raw JSON
```json
{
  "categories": [
    "anime",
    "popular"
  ],
  "description": "Sources\n\n| Posts | Patreon | Pixiv Fanbox | Gumroad | SubscribeStar | DLsite | Discord | Fantia |\n| ----- | ------- | ------------ | ------- | ------------- | ------ | ------- | ------ |\n| posts | patreon | fanbox       | gumroad | subscribestar | dlsite | discord | fantia |\n\n::: tip\nWhen `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.\nThere is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.\n\nSupport for announcements and fancards:\n\n- Use `/:source/:id/announcements` to get announcements\n- Use `/:source/:id/fancards` to get fancards\n\n:::",
  "example": "/kemono",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1392,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk",
    "AiraNadih"
  ],
  "name": "Posts",
  "parameters": {
    "id": "User id, can be found in URL",
    "source": "Source, see below, Posts by default",
    "type": "Content type: announcements or fancards"
  },
  "path": "/:source?/:id?/:type?",
  "radar": [
    {
      "source": [
        "kemono.cr/"
      ],
      "target": ""
    },
    {
      "source": [
        "kemono.cr/:source/user/:id"
      ],
      "target": "/:source/:id"
    },
    {
      "source": [
        "kemono.cr/:source/user/:id/announcements"
      ],
      "target": "/:source/:id/announcements"
    },
    {
      "source": [
        "kemono.cr/:source/user/:id/fancards"
      ],
      "target": "/:source/:id/fancards"
    },
    {
      "source": [
        "kemono.cr/discord/server/:id"
      ],
      "target": "/discord/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Kemono Posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59871541870611456",
      "image": "https://kemono.cr/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://kemono.cr/posts",
      "title": "Kemono Posts",
      "type": "feed",
      "url": "rsshub://kemono"
    },
    {
      "description": "Posts of DaB_neko from patreon | Kemono - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72301922403997696",
      "image": "https://img.kemono.cr/icons/patreon/73991224",
      "ownerUserId": null,
      "siteUrl": "https://kemono.cr/patreon/user/73991224",
      "title": "Posts of DaB_neko from patreon | Kemono",
      "type": "feed",
      "url": "rsshub://kemono/patreon/73991224"
    }
  ]
}
```
