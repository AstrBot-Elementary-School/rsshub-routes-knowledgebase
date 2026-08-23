# Vulture - Sub-site

## Coverage
`index-only`

## Route
- Namespace: `vulture`
- Namespace Name: `Vulture`
- Route Path: `/vulture/:tag/:excludetags?`
- Route Name: `Sub-site`
- Example: `/vulture/movies`
- URL: `www.vulture.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `loganrockmore`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Supported sub-sites:

| TV | Movies | Comedy | Music | TV Recaps | Books | Theater | Art | Awards | Video |
| -- | ------ | ------ | ----- | --------- | ----- | ------- | --- | ------ | ----- |
| tv | movies | comedy | music | tvrecaps  | books | theater | art | awards | video |

## Parameters
- `tag`: The sub-site name
- `excludetags`: Comma-delimited list of tags. If an article includes one of these tags, it will be excluded from the RSS feed.


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported sub-sites:\n\n| TV | Movies | Comedy | Music | TV Recaps | Books | Theater | Art | Awards | Video |\n| -- | ------ | ------ | ----- | --------- | ----- | ------- | --- | ------ | ----- |\n| tv | movies | comedy | music | tvrecaps  | books | theater | art | awards | video |",
  "example": "/vulture/movies",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "loganrockmore"
  ],
  "name": "Sub-site",
  "parameters": {
    "excludetags": "Comma-delimited list of tags. If an article includes one of these tags, it will be excluded from the RSS feed.",
    "tag": "The sub-site name"
  },
  "path": "/:tag/:excludetags?",
  "topFeeds": []
}
```
