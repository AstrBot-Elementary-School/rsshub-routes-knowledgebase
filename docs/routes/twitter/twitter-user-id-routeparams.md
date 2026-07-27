# X (Twitter) - User timeline

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/user/:id/:routeParams?`
- Route Name: `User timeline`
- Example: `/twitter/user/_RSSHub`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, yindaheng98, Rongronggg9, CaoMeiYouRen, pseudoyu`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: username; in particular, if starts with `+`, it will be recognized as a [unique ID](https://github.com/DIYgod/RSSHub/issues/12221), e.g. `+44196397`
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
- `requireConfig`: [{"description": "Please see above for details.", "name": "TWITTER_AUTH_TOKEN"}, {"description": "Use third-party API to query twitter data", "name": "TWITTER_THIRD_PARTY_API", "optional": true}, {"description": "Please see above for details.", "name": "TWITTER_CONSUMER_KEY"}, {"description": "Please see above for details.", "name": "TWITTER_CONSUMER_SECRET"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `x.com/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/twitter/user/_RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TWITTER_AUTH_TOKEN"
      },
      {
        "description": "Use third-party API to query twitter data",
        "name": "TWITTER_THIRD_PARTY_API",
        "optional": true
      },
      {
        "description": "Please see above for details.",
        "name": "TWITTER_CONSUMER_KEY"
      },
      {
        "description": "Please see above for details.",
        "name": "TWITTER_CONSUMER_SECRET"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 874835,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "yindaheng98",
    "Rongronggg9",
    "CaoMeiYouRen",
    "pseudoyu"
  ],
  "name": "User timeline",
  "parameters": {
    "id": "username; in particular, if starts with `+`, it will be recognized as a [unique ID](https://github.com/DIYgod/RSSHub/issues/12221), e.g. `+44196397`",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/user/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "x.com/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "https://t.co/dDtDyVssfm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "100411504863520768",
      "image": "https://pbs.twimg.com/profile_images/2035314704307081216/71U1ftM3.jpg",
      "ownerUserId": null,
      "siteUrl": "https://x.com/elonmusk",
      "title": "Twitter @Elon Musk",
      "type": "feed",
      "url": "rsshub://twitter/user/elonmusk"
    },
    {
      "description": "45th & 47th President of the United States of America🇺🇸 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57350121145773056",
      "image": "https://pbs.twimg.com/profile_images/874276197357596672/kUuht00m.jpg",
      "ownerUserId": null,
      "siteUrl": "https://x.com/realDonaldTrump",
      "title": "Twitter @Donald J. Trump",
      "type": "feed",
      "url": "rsshub://twitter/user/realDonaldTrump"
    }
  ],
  "view": 1
}
```
