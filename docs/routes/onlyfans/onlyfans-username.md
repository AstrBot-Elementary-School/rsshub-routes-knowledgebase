# OnlyFans - Creator Posts

## Coverage
`index-only`

## Route
- Namespace: `onlyfans`
- Namespace Name: `OnlyFans`
- Route Path: `/onlyfans/:username`
- Route Name: `Creator Posts`
- Example: `/onlyfans/sports`
- URL: `onlyfans.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Creator username


## Features
- `requireConfig`: [{"description": "The `Cookie` header of a logged-in session.", "name": "ONLYFANS_COOKIE", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `onlyfans.com/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/onlyfans/sports",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The `Cookie` header of a logged-in session.",
        "name": "ONLYFANS_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Creator Posts",
  "parameters": {
    "username": "Creator username"
  },
  "path": "/:username",
  "radar": [
    {
      "source": [
        "onlyfans.com/:username"
      ]
    }
  ],
  "topFeeds": [],
  "url": "onlyfans.com"
}
```
