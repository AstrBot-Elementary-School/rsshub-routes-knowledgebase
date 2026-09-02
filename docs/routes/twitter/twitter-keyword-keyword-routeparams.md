# X (Twitter) - Keyword

## Coverage
`partial`

## Route
- Namespace: `twitter`
- Namespace Name: `X (Twitter)`
- Route Path: `/twitter/keyword/:keyword/:routeParams?`
- Route Name: `Keyword`
- Example: `/twitter/keyword/RSSHub`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, yindaheng98, Rongronggg9, pseudoyu`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: keyword
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
  - `x.com/search`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/twitter/keyword/RSSHub",
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
  "heat": 5109,
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "yindaheng98",
    "Rongronggg9",
    "pseudoyu"
  ],
  "name": "Keyword",
  "parameters": {
    "keyword": "keyword",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/keyword/:keyword/:routeParams?",
  "radar": [
    {
      "source": [
        "x.com/search"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Twitter Keyword - AI - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53226580778291200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/search?q=AI",
      "title": "Twitter Keyword - AI",
      "type": "feed",
      "url": "rsshub://twitter/keyword/AI"
    },
    {
      "description": "Twitter Keyword - RSSHub - Powered by RSSHub",
      "errorAt": "2026-09-01T09:02:12.847Z",
      "errorMessage": "[GET] \"https://rsshub-api.twitterdata.com/i/api/graphql/hyPfJYJ_XAtDYoslQc-Rgg/SearchTimeline?variables=%7B%22rawQuery%22:%22RSSHub%22,%22count%22:20,%22querySource%22:%22typed_query%22,%22product%22:%22Latest%22%7D&features=%7B%22rweb_tipjar_consumption_enabled%22:true,%22responsive_web_graphql_exclude_directive_enabled%22:true,%22verified_phone_label_enabled%22:false,%22creator_subscriptions_tweet_preview_api_enabled%22:true,%22responsive_web_graphql_timeline_navigation_enabled%22:true,%22responsive_web_graphql_skip_user_profile_image_extensions_enabled%22:false,%22communities_web_enable_tweet_community_results_fetch%22:true,%22c9s_tweet_anatomy_moderator_badge_enabled%22:true,%22articles_preview_enabled%22:true,%22responsive_web_edit_tweet_api_enabled%22:true,%22graphql_is_translatable_rweb_tweet_is_translatable_enabled%22:true,%22view_counts_everywhere_api_enabled%22:true,%22longform_notetweets_consumption_enabled%22:true,%22responsive_web_twitter_article_tweet_consumption_enabled%22:true,%22tweet_awards_web_tipping_enabled%22:false,%22creator_subscriptions_quote_tweet_preview_enabled%22:false,%22freedom_of_speech_not_reach_fetch_enabled%22:true,%22standardized_nudges_misinfo%22:true,%22tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled%22:true,%22rweb_video_timestamps_enabled%22:true,%22longform_notetweets_rich_text_read_enabled%22:true,%22longform_notetweets_inline_media_enabled%22:true,%22responsive_web_enhance_cards_enabled%22:false%7D\": 429 Too Many Requests\nFailed to fetch\nInvalid RSSHub JSON Feed from 98292582055262208\nTwitter API is not configured\n",
      "id": "41150240545595393",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://x.com/search?q=RSSHub",
      "title": "Twitter Keyword - RSSHub",
      "type": "feed",
      "url": "rsshub://twitter/keyword/RSSHub"
    }
  ],
  "view": 1
}
```
