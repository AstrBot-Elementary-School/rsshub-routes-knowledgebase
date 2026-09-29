# YouTube - Live

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/live/:username/:embed?`
- Route Name: `Live`
- Example: `/youtube/live/@GawrGura`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `sussurr127, ouuan`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
::: tip
Every stream is categorized as `live`, `upcoming` or `completed`, so a single state can be picked out with the `filter_category` and `filterout_category` [common parameters](https://docs.rsshub.app/guide/parameters#filtering). For example, `/youtube/live/@GawrGura?filterout_category=completed` only tracks streams that are live or about to start.
:::

## Parameters
- `username`: YouTube handle or channel id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/@:username/streams`
- `target`: `/live/@:username`
### Rule 2
- `source`:
  - `www.youtube.com/channel/:username/streams`
- `target`: `/live/:username`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "description": "::: tip\nEvery stream is categorized as `live`, `upcoming` or `completed`, so a single state can be picked out with the `filter_category` and `filterout_category` [common parameters](https://docs.rsshub.app/guide/parameters#filtering). For example, `/youtube/live/@GawrGura?filterout_category=completed` only tracks streams that are live or about to start.\n:::",
  "example": "/youtube/live/@GawrGura",
  "heat": 254,
  "location": "live.ts",
  "maintainers": [
    "sussurr127",
    "ouuan"
  ],
  "name": "Live",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "username": "YouTube handle or channel id"
  },
  "path": "/live/:username/:embed?",
  "radar": [
    {
      "source": [
        "www.youtube.com/@:username/streams"
      ],
      "target": "/live/@:username"
    },
    {
      "source": [
        "www.youtube.com/channel/:username/streams"
      ],
      "target": "/live/:username"
    }
  ],
  "topFeeds": [
    {
      "description": "$老高與小茉 Mr & Mrs Gao's live streaming status - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69051964046186496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCMUnInmOkrWN4gof9KlhNmQ",
      "title": "老高與小茉 Mr & Mrs Gao's Live Status",
      "type": "feed",
      "url": "rsshub://youtube/live/@laogao"
    },
    {
      "description": "$Gawr Gura Ch. hololive-EN's live streaming status - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42001666786766848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCoSrY_IQQVpmIRZ9Xf-y93g",
      "title": "Gawr Gura Ch. hololive-EN's Live Status",
      "type": "feed",
      "url": "rsshub://youtube/live/@GawrGura"
    }
  ],
  "view": 3
}
```
