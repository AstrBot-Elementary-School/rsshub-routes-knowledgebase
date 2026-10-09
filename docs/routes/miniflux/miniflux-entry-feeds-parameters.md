# MiniFlux - Feed entry

## Coverage
`index-only`

## Route
- Namespace: `miniflux`
- Namespace Name: `MiniFlux`
- Route Path: `/miniflux/entry/:feeds/:parameters?`
- Route Name: `Feed entry`
- Example: `/miniflux/entry/feeds=1&2&3/mark=read&limit=7&status=unread`
- URL: `miniflux.app`
- Language: `_None_`
- Categories: `other`
- Maintainers: `emdoe, DIYgod`
- Source Location: `entry.ts`
- Source Module: `_None_`

## Description
1. Support to get all content: You can obtain the content of all subscription sources by using keywords such as `/miniflux/all` or `/miniflux/default`.
2. Support to get the subscription content of a specific subscription source by its ID. Please obtain the subscription source ID on the page where it is located under `Sources` (shortcut keys `g` `f`). The URL for each category (or subscription source) displays its ID information. There are several format options available:
   1. Support `/miniflux/entry/feed=[feed_id]`, please replace `[feed_id]` with the actual ID of the subscribed feed (note that it should be just a number without brackets).
   2. Support subscribing to multiple feeds using `/miniflux/entry/feed=[feed1_id]&feed=[feed2_id]` or `/miniflux/entry/feeds=[feed1_id]&[feed2_id]`.
   3. Additionally, you can use shorthand notation by directly using feed IDs: `/miniflux/entry/[feed1_id]&[feed2_id]`.
3. Further customization options are available based on your needs:
   1. All parameters/options provided by MiniFlux are supported ([link](https://miniflux.app/docs/api.html#endpoint-get-feed-entries)). As noted in their documentation, multiple filtering options should be connected with `&`. Except for `status`, only the first occurrence of duplicate filter options will be considered.
   2. Specifically, this route defaults to sorting entries from new to old (`direction=desc`).
   3. Moreover, this route supports additional options including:
      - Using the `feed_name` parameter to control title formatting; setting `feed_name=1` will display each title as "Article Title | Feed Name," while default is set at `0`, showing only article titles.
      - Utilizing the `mark` parameter to specify actions after fetching subscriptions in RSSHub, such as maintaining unchanged state (`unchanged`, default), marking as read (`read`), removing (`removed`) or marking as unread (`unread`). Note that marking as read should not simply be understood as a means for implementing synchronization services; rather, it functions more like an aid for MiniFlux's automatic cleaning feature.
      - Future support may include utilizing the `link` parameter to control output URLs (this functionality requires corresponding interfaces from MiniFlux). It could involve generating URLs through MiniFlux entity sharing features or original content links.
      - The output content quantity can be controlled via the 'limit' parameter; although all matching contents are typically outputted by default, **it is recommended that users set this parameter**.

## Parameters
- `feeds`: Subscribe source ID or get all.
- `parameters`: Filter and set parameters, use `&` to connect multiple.


## Features
- `requireConfig`: [{"description": "The instance used by the user, by default, is the official MiniFlux [paid service address](https://reader.miniflux.app)", "name": "MINIFLUX_INSTANCE"}, {"description": "User's API key, please log in to the instance used and go to `Settings` -> `API Key` -> `Create a new API key` to obtain.", "name": "MINIFLUX_TOKEN"}]
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
    "other"
  ],
  "description": "1. Support to get all content: You can obtain the content of all subscription sources by using keywords such as `/miniflux/all` or `/miniflux/default`.\n2. Support to get the subscription content of a specific subscription source by its ID. Please obtain the subscription source ID on the page where it is located under `Sources` (shortcut keys `g` `f`). The URL for each category (or subscription source) displays its ID information. There are several format options available:\n   1. Support `/miniflux/entry/feed=[feed_id]`, please replace `[feed_id]` with the actual ID of the subscribed feed (note that it should be just a number without brackets).\n   2. Support subscribing to multiple feeds using `/miniflux/entry/feed=[feed1_id]&feed=[feed2_id]` or `/miniflux/entry/feeds=[feed1_id]&[feed2_id]`.\n   3. Additionally, you can use shorthand notation by directly using feed IDs: `/miniflux/entry/[feed1_id]&[feed2_id]`.\n3. Further customization options are available based on your needs:\n   1. All parameters/options provided by MiniFlux are supported ([link](https://miniflux.app/docs/api.html#endpoint-get-feed-entries)). As noted in their documentation, multiple filtering options should be connected with `&`. Except for `status`, only the first occurrence of duplicate filter options will be considered.\n   2. Specifically, this route defaults to sorting entries from new to old (`direction=desc`).\n   3. Moreover, this route supports additional options including:\n      - Using the `feed_name` parameter to control title formatting; setting `feed_name=1` will display each title as \"Article Title | Feed Name,\" while default is set at `0`, showing only article titles.\n      - Utilizing the `mark` parameter to specify actions after fetching subscriptions in RSSHub, such as maintaining unchanged state (`unchanged`, default), marking as read (`read`), removing (`removed`) or marking as unread (`unread`). Note that marking as read should not simply be understood as a means for implementing synchronization services; rather, it functions more like an aid for MiniFlux's automatic cleaning feature.\n      - Future support may include utilizing the `link` parameter to control output URLs (this functionality requires corresponding interfaces from MiniFlux). It could involve generating URLs through MiniFlux entity sharing features or original content links.\n      - The output content quantity can be controlled via the 'limit' parameter; although all matching contents are typically outputted by default, **it is recommended that users set this parameter**.",
  "example": "/miniflux/entry/feeds=1&2&3/mark=read&limit=7&status=unread",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "The instance used by the user, by default, is the official MiniFlux [paid service address](https://reader.miniflux.app)",
        "name": "MINIFLUX_INSTANCE"
      },
      {
        "description": "User's API key, please log in to the instance used and go to `Settings` -> `API Key` -> `Create a new API key` to obtain.",
        "name": "MINIFLUX_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "entry.ts",
  "maintainers": [
    "emdoe",
    "DIYgod"
  ],
  "name": "Feed entry",
  "parameters": {
    "feeds": "Subscribe source ID or get all.",
    "parameters": "Filter and set parameters, use `&` to connect multiple."
  },
  "path": [
    "/entry/:feeds/:parameters?",
    "/all/:parameters?",
    "/default/:parameters?"
  ],
  "topFeeds": []
}
```
