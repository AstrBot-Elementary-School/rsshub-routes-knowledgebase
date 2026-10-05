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
  - `www.youtube.com/:username/streams`
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
        "www.youtube.com/:username/streams",
        "www.youtube.com/channel/:username/streams"
      ],
      "target": "/live/:username"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "[April 30, 2025 Graduated.] Shark-girl Idol of Hololive EN ! 🐟 --- A descendant of the Lost City of Atlantis, who swam to Earth while saying, \"It's so boring... - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42001666786766848",
      "image": "https://yt3.googleusercontent.com/6BCfAqi9yIpZbHLbw9BAWySvB3XZf9r8jFqudO5nSOsHoGzLhlKrm1M1uuMCRabi_pXGDzl7=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCoSrY_IQQVpmIRZ9Xf-y93g/streams",
      "title": "Gawr Gura Ch. hololive-EN - Live - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/live/@GawrGura"
    },
    {
      "description": "$老高與小茉 Mr & Mrs Gao's live streaming status - Powered by RSSHub",
      "errorAt": "2026-09-28T22:00:54.900Z",
      "errorMessage": "Tab \"streams\" not found\n",
      "id": "69051964046186496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCMUnInmOkrWN4gof9KlhNmQ",
      "title": "老高與小茉 Mr & Mrs Gao's Live Status",
      "type": "feed",
      "url": "rsshub://youtube/live/@laogao"
    }
  ],
  "view": 3
}
```
