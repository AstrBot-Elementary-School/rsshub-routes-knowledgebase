# Blind - Popular and channel posts

## Coverage
`index-only`

## Route
- Namespace: `teamblind`
- Namespace Name: `Blind`
- Route Path: `/teamblind/posts/:channel?`
- Route Name: `Popular and channel posts`
- Example: `/teamblind/posts/tech`
- URL: `www.teamblind.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `posts.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: Channel slug from /channels/:channel. Omit for the popular homepage feed.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `teamblind.com/channels/:channel`
- `target`: `/posts/:channel`
### Rule 2
- `source`:
  - `teamblind.com`
- `target`: `/posts`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/teamblind/posts/tech",
  "heat": 0,
  "location": "posts.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Popular and channel posts",
  "parameters": {
    "channel": "Channel slug from /channels/:channel. Omit for the popular homepage feed."
  },
  "path": "/posts/:channel?",
  "radar": [
    {
      "source": [
        "teamblind.com/channels/:channel"
      ],
      "target": "/posts/:channel"
    },
    {
      "source": [
        "teamblind.com"
      ],
      "target": "/posts"
    }
  ],
  "topFeeds": []
}
```
