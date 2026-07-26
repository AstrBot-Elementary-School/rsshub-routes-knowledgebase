# X (Twitter) - User likes

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/likes/:id/:routeParams?`
- Route Name: `User likes`
- Example: `/twitter/likes/DIYgod`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `likes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: username
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
- `requireConfig`: [{"description": "Please see above for details.", "name": "TWITTER_AUTH_TOKEN"}]
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
    "social-media"
  ],
  "example": "/twitter/likes/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TWITTER_AUTH_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "likes.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "User likes",
  "parameters": {
    "id": "username",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/likes/:id/:routeParams?",
  "topFeeds": [
    {
      "description": "Twitter Likes - DIYgod - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54122407526122496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/DIYgod/likes",
      "title": "Twitter Likes - DIYgod",
      "type": "feed",
      "url": "rsshub://twitter/likes/DIYgod"
    },
    {
      "description": "Twitter Likes - nanoni_nuneno - Powered by RSSHub",
      "errorAt": "2025-06-03T19:04:07.860Z",
      "errorMessage": "No valid Twitter token found\n",
      "id": "152739734061137920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/nanoni_nuneno/likes",
      "title": "Twitter Likes - nanoni_nuneno",
      "type": "feed",
      "url": "rsshub://twitter/likes/nanoni_nuneno"
    }
  ]
}
```
