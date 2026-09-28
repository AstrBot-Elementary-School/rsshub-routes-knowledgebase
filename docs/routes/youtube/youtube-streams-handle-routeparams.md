# YouTube - Live Streams

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/streams/:handle/:routeParams?`
- Route Name: `Live Streams`
- Example: `/youtube/streams/@GawrGura`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `ouuan`
- Source Location: `streams.ts`
- Source Module: `_None_`

## Description
::: tip Parameter

| Name               | Description                                                                                 | Default |
| ------------------ | ------------------------------------------------------------------------------------------- | ------- |
| embed              | Whether to embed the video, fill in any value to disable embedding                          | embed   |
| includeDescription | Whether to include the description of each stream, fill in any truthy value to include them | false   |

:::

::: tip
Unlike [Live](#youtube-live), this route reads the channel's Live tab, so it also covers scheduled and finished streams, and it does not require an API key.

Every stream is categorized as `live`, `upcoming` or `completed`, so a single state can be picked out with the `filter_category` and `filterout_category` [common parameters](https://docs.rsshub.app/guide/parameters#filtering). For example, `/youtube/streams/@GawrGura?filterout_category=completed` only tracks streams that are live or about to start.

The Live tab does not carry the stream descriptions, so `includeDescription` costs one extra request per stream and is off by default.
:::

## Parameters
- `handle`: YouTube handle or channel id
- `routeParams`: Extra parameters, see the table below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/@:handle/streams`
- `target`: `/streams/@:handle`
### Rule 2
- `source`:
  - `www.youtube.com/channel/:handle/streams`
- `target`: `/streams/:handle`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "description": "::: tip Parameter\n\n| Name               | Description                                                                                 | Default |\n| ------------------ | ------------------------------------------------------------------------------------------- | ------- |\n| embed              | Whether to embed the video, fill in any value to disable embedding                          | embed   |\n| includeDescription | Whether to include the description of each stream, fill in any truthy value to include them | false   |\n\n:::\n\n::: tip\nUnlike [Live](#youtube-live), this route reads the channel's Live tab, so it also covers scheduled and finished streams, and it does not require an API key.\n\nEvery stream is categorized as `live`, `upcoming` or `completed`, so a single state can be picked out with the `filter_category` and `filterout_category` [common parameters](https://docs.rsshub.app/guide/parameters#filtering). For example, `/youtube/streams/@GawrGura?filterout_category=completed` only tracks streams that are live or about to start.\n\nThe Live tab does not carry the stream descriptions, so `includeDescription` costs one extra request per stream and is off by default.\n:::",
  "example": "/youtube/streams/@GawrGura",
  "heat": 0,
  "location": "streams.ts",
  "maintainers": [
    "ouuan"
  ],
  "name": "Live Streams",
  "parameters": {
    "handle": "YouTube handle or channel id",
    "routeParams": "Extra parameters, see the table below"
  },
  "path": "/streams/:handle/:routeParams?",
  "radar": [
    {
      "source": [
        "www.youtube.com/@:handle/streams"
      ],
      "target": "/streams/@:handle"
    },
    {
      "source": [
        "www.youtube.com/channel/:handle/streams"
      ],
      "target": "/streams/:handle"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "view": 3
}
```
