# X (Twitter) - Space speaking status

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/spaces/:username`
- Route Name: `Space speaking status`
- Example: `/twitter/spaces/_RSSHub`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `spaces.ts`
- Source Module: `_None_`

## Description
Reports a user speaking in a live Space, including Spaces hosted by other users. Hosts and co-hosts are also included; listeners are excluded. Each user/Space pair has a stable entry ID and uses the actual Space start time. When the user is not speaking in a live Space, a status entry has a fixed ID and no publication date. This does not join or listen to a Space. Requires your own authorized TWITTER\_AUTH\_TOKEN on a self-hosted instance.

## Parameters
- `username`: The X username, without @.

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
- `requireConfig`: [{"description": "An authorized login session for the X web API. Developer API keys and third-party timeline providers are not used by this route.", "name": "TWITTER_AUTH_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `x.com/:username`
- `target`: `/spaces/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Reports a user speaking in a live Space, including Spaces hosted by other users. Hosts and co-hosts are also included; listeners are excluded. Each user/Space pair has a stable entry ID and uses the actual Space start time. When the user is not speaking in a live Space, a status entry has a fixed ID and no publication date. This does not join or listen to a Space. Requires your own authorized TWITTER\\_AUTH\\_TOKEN on a self-hosted instance.",
  "example": "/twitter/spaces/_RSSHub",
  "features": {
    "requireConfig": [
      {
        "description": "An authorized login session for the X web API. Developer API keys and third-party timeline providers are not used by this route.",
        "name": "TWITTER_AUTH_TOKEN"
      }
    ]
  },
  "heat": 0,
  "location": "spaces.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Space speaking status",
  "parameters": {
    "username": "The X username, without @."
  },
  "path": "/spaces/:username",
  "radar": [
    {
      "source": [
        "x.com/:username"
      ],
      "target": "/spaces/:username"
    }
  ],
  "topFeeds": []
}
```
