# X (Twitter) - Home timeline

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/home/:routeParams?`
- Route Name: `Home timeline`
- Example: `/twitter/home`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, CaoMeiYouRen`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_

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
### Rule 1
- `source`:
  - `x.com/home`
- `target`: `/home`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/twitter/home",
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
  "heat": 39,
  "location": "home.ts",
  "maintainers": [
    "DIYgod",
    "CaoMeiYouRen"
  ],
  "name": "Home timeline",
  "path": "/home/:routeParams?",
  "radar": [
    {
      "source": [
        "x.com/home"
      ],
      "target": "/home"
    }
  ],
  "topFeeds": [
    {
      "description": "Twitter following timeline - Powered by RSSHub",
      "errorAt": "2026-03-26T13:21:38.201Z",
      "errorMessage": "No valid Twitter token found\nTwitter API is not configured\n",
      "id": "59171583511089152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/home",
      "title": "Twitter following timeline",
      "type": "feed",
      "url": "rsshub://twitter/home"
    },
    {
      "description": "Twitter following timeline - Powered by RSSHub",
      "errorAt": "2025-10-19T08:07:45.664Z",
      "errorMessage": "No valid Twitter token found\nTwitter API is not configured\n",
      "id": "166019033555010560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/home",
      "title": "Twitter following timeline",
      "type": "feed",
      "url": "rsshub://twitter/home/readable=1&authorNameBold=1&showAuthorInTitle=1&showAuthorInDesc=1&showQuotedAuthorAvatarInDesc=1&showAuthorAvatarInDesc=1&showEmojiForRetweetAndReply=1&showRetweetTextInTitle=0&addLinkForPics=1&showTimestampInDescription=1&showQuotedInTitle=1&heightOfPics=150"
    }
  ]
}
```
