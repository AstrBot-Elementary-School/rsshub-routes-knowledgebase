# Bluesky (bsky) - Post

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/bsky/profile/:handle/:routeParams?`
- Route Name: `Post`
- Example: `/bsky/profile/bsky.app`
- URL: `bsky.app`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
| Filter Value                | Description                                          |
| --------------------------- | ---------------------------------------------------- |
| posts\_with\_replies        | Includes Posts, Replies, and Reposts                 |
| posts\_no\_replies          | Includes Posts and Reposts, without Replies          |
| posts\_with\_media          | Shows only Posts containing media                    |
| posts\_and\_author\_threads | Shows Posts and Threads, without Replies and Reposts |

Default value for filter is `posts_and_author_threads` if not specified.

Example:

- `/bsky/profile/bsky.app/filter=posts_with_replies`

## Parameters
- `handle`: User handle, can be found in URL
- `routeParams`: Filter parameter, Use filter to customize content types


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bsky.app/profile/:handle`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "| Filter Value                | Description                                          |\n| --------------------------- | ---------------------------------------------------- |\n| posts\\_with\\_replies        | Includes Posts, Replies, and Reposts                 |\n| posts\\_no\\_replies          | Includes Posts and Reposts, without Replies          |\n| posts\\_with\\_media          | Shows only Posts containing media                    |\n| posts\\_and\\_author\\_threads | Shows Posts and Threads, without Replies and Reposts |\n\nDefault value for filter is `posts_and_author_threads` if not specified.\n\nExample:\n\n- `/bsky/profile/bsky.app/filter=posts_with_replies`",
  "example": "/bsky/profile/bsky.app",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 44012,
  "location": "posts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Post",
  "parameters": {
    "handle": "User handle, can be found in URL",
    "routeParams": "Filter parameter, Use filter to customize content types"
  },
  "path": "/profile/:handle/:routeParams?",
  "radar": [
    {
      "source": [
        "bsky.app/profile/:handle"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "official Bluesky account (check username👆) Bugs, feature requests, feedback: support@bsky.app - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61718494982401024",
      "image": "https://cdn.bsky.app/img/avatar/plain/did:plc:z72i7hdynmk6r22z27h6tvur/bafkreihwihm6kpd6zuwhhlro75p5qks5qtrcu55jp3gddbfjsieiv7wuka",
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/profile/bsky.app",
      "title": "Bluesky (@bsky.app) — Bluesky",
      "type": "feed",
      "url": "rsshub://bsky/profile/bsky.app"
    },
    {
      "description": "A ship in harbor is safe, but that is not what ships are built for. creator → @sli.dev • @unocss.dev • @vueuse.org • @vitest.dev • elk.zone core team → @nuxt.com • @vite.dev • vuejs.org maintainer → @shiki.style • eslint.style he/him → antfu.me - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74659719211441152",
      "image": "https://cdn.bsky.app/img/avatar/plain/did:plc:2pdiyh6lip2aomv7kia3f2jo/bafkreidhcyovthsjjrmh34glopiixwi6fkzp4br7es4osfduux4ajvk7vy",
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/profile/antfu.me",
      "title": "Anthony Fu (@antfu.me) — Bluesky",
      "type": "feed",
      "url": "rsshub://bsky/profile/antfu.me"
    }
  ],
  "view": 1
}
```
