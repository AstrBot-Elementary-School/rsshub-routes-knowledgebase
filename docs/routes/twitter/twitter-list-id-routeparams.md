# X (Twitter) - List timeline

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/list/:id/:routeParams?`
- Route Name: `List timeline`
- Example: `/twitter/list/1502570462752219136`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, xyqfer, pseudoyu`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: list id, get from url
- `routeParams`: extra parameters, see the table above

## Route Notes
This namespace has additional official guidance beyond the route index.

### routeParams
Specify options in `routeParams` to control extra tweet rendering features.

| Key | Description | Accepts | Default |
| --- | --- | --- | --- |
| `readable` | Enable readable layout | `0`/`1`/`true`/`false` | `false` |
| `authorNameBold` | Display author name in bold | `0`/`1`/`true`/`false` | `false` |
| `showAuthorInTitle` | Show author name in title | `0`/`1`/`true`/`false` | `false` (`true` in `/twitter/followings`) |
| `showAuthorAsTitleOnly` | Show only author name as title | `0`/`1`/`true`/`false` | `false` |
| `showAuthorInDesc` | Show author name in description | `0`/`1`/`true`/`false` | `false` (`true` in `/twitter/followings`) |
| `showQuotedAuthorAvatarInDesc` | Show quoted tweet author avatar in description | `0`/`1`/`true`/`false` | `false` |
| `showAuthorAvatarInDesc` | Show author avatar in description | `0`/`1`/`true`/`false` | `false` |
| `showEmojiForRetweetAndReply` | Use `🔁` and `↩️`/`💬` symbols | `0`/`1`/`true`/`false` | `false` |
| `showSymbolForRetweetAndReply` | Use ` RT ` / ` Re ` text markers | `0`/`1`/`true`/`false` | `true` |
| `showRetweetTextInTitle` | Show quote comments in title | `0`/`1`/`true`/`false` | `true` |
| `addLinkForPics` | Add clickable links for tweet pictures | `0`/`1`/`true`/`false` | `false` |
| `showTimestampInDescription` | Show timestamp in description | `0`/`1`/`true`/`false` | `false` |
| `showQuotedInTitle` | Show quoted tweet in title | `0`/`1`/`true`/`false` | `false` |
| `widthOfPics` | Width of tweet pictures | Unspecified/Integer | Unspecified |
| `heightOfPics` | Height of tweet pictures | Unspecified/Integer | Unspecified |
| `sizeOfAuthorAvatar` | Size of author avatar | Integer | `48` |
| `sizeOfQuotedAuthorAvatar` | Size of quoted tweet author avatar | Integer | `24` |
| `includeReplies` | Include replies, only for `/twitter/user` | `0`/`1`/`true`/`false` | `false` |
| `includeRts` | Include retweets, only for `/twitter/user` | `0`/`1`/`true`/`false` | `true` |
| `forceWebApi` | Force Web API, only for `/twitter/user` and `/twitter/keyword` | `0`/`1`/`true`/`false` | `false` |
| `count` | `count` parameter passed to Twitter API, only for `/twitter/user` | Unspecified/Integer | Unspecified |
| `onlyMedia` | Only get tweets with media | `0`/`1`/`true`/`false` | `false` |
| `mediaNumber` | Number the medias | `0`/`1`/`true`/`false` | `false` |

### Authentication
Currently supported authentication methods:

- `TWITTER_AUTH_TOKEN` (recommended): configure a comma-separated list of logged-in Twitter Web `auth_token` cookies.
- `TWITTER_CONSUMER_KEY` and `TWITTER_CONSUMER_SECRET`: configure Twitter pay-per-use developer API keys and secrets.
- Optional: `TWITTER_ACCESS_TOKEN` and `TWITTER_ACCESS_SECRET`: provide user-authenticated developer API access.

### Deprecated Authentication
`TWITTER_USERNAME`, `TWITTER_PASSWORD`, and `TWITTER_AUTHENTICATION_SECRET` are no longer usable since Twitter mobile client attestation was implemented in October 2025.


## Features
- `requireConfig`: [{"description": "Please see above for details.", "name": "TWITTER_AUTH_TOKEN"}, {"description": "Please see above for details.", "name": "TWITTER_THIRD_PARTY_API"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `x.com/i/lists/:id`
- `target`: `/list/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/twitter/list/1502570462752219136",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TWITTER_AUTH_TOKEN"
      },
      {
        "description": "Please see above for details.",
        "name": "TWITTER_THIRD_PARTY_API"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5644,
  "location": "list.ts",
  "maintainers": [
    "DIYgod",
    "xyqfer",
    "pseudoyu"
  ],
  "name": "List timeline",
  "parameters": {
    "id": "list id, get from url",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/list/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "x.com/i/lists/:id"
      ],
      "target": "/list/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "Twitter List - 1842817257933844798 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65802121820371968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/i/lists/1842817257933844798",
      "title": "Twitter List - 1842817257933844798",
      "type": "feed",
      "url": "rsshub://twitter/list/1842817257933844798"
    },
    {
      "description": "Twitter List - 1502570462752219136 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59816386195718144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/i/lists/1502570462752219136",
      "title": "Twitter List - 1502570462752219136",
      "type": "feed",
      "url": "rsshub://twitter/list/1502570462752219136"
    }
  ]
}
```
