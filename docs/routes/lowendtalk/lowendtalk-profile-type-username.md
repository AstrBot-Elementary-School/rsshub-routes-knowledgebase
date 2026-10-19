# LowEndTalk - User Discussions / Comments

## Coverage
`index-only`

## Route
- Namespace: `lowendtalk`
- Namespace Name: `LowEndTalk`
- Route Path: `/lowendtalk/profile/:type/:username`
- Route Name: `User Discussions / Comments`
- Example: `/lowendtalk/profile/discussions/Ikoula`
- URL: `lowendtalk.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "Content type", "options": [{"label": "Discussions", "value": "discussions"}, {"label": "Comments", "value": "comments"}]}
- `username`: Username, can be found in the profile URL


## Features
- `requireConfig`: [{"description": "The `Cookie` header of a logged-in session. Profile pages are only visible to signed-in users.", "name": "LOWENDTALK_COOKIE"}]

## Radar
### Rule 1
- `source`:
  - `lowendtalk.com/profile/:type/:username`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/lowendtalk/profile/discussions/Ikoula",
  "features": {
    "requireConfig": [
      {
        "description": "The `Cookie` header of a logged-in session. Profile pages are only visible to signed-in users.",
        "name": "LOWENDTALK_COOKIE"
      }
    ]
  },
  "heat": 0,
  "location": "profile.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Discussions / Comments",
  "parameters": {
    "type": {
      "description": "Content type",
      "options": [
        {
          "label": "Discussions",
          "value": "discussions"
        },
        {
          "label": "Comments",
          "value": "comments"
        }
      ]
    },
    "username": "Username, can be found in the profile URL"
  },
  "path": "/profile/:type/:username",
  "radar": [
    {
      "source": [
        "lowendtalk.com/profile/:type/:username"
      ]
    }
  ],
  "topFeeds": [],
  "url": "lowendtalk.com"
}
```
