# Facebook - Group

## Coverage
`index-only`

## Route
- Namespace: `facebook`
- Namespace Name: `Facebook`
- Route Path: `/facebook/group/:id`
- Route Name: `Group`
- Example: `/facebook/group/613870175328566`
- URL: `www.facebook.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `group.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Group ID or group username


## Features
- `requireConfig`: [{"description": "Facebook cookie, only `c_user` and `xs` are required. Set this if you see `Rate limit exceeded`.", "name": "FACEBOOK_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.facebook.com/groups/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/facebook/group/613870175328566",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "Facebook cookie, only `c_user` and `xs` are required. Set this if you see `Rate limit exceeded`.",
        "name": "FACEBOOK_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "group.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Group",
  "parameters": {
    "id": "Group ID or group username"
  },
  "path": "/group/:id",
  "radar": [
    {
      "source": [
        "www.facebook.com/groups/:id"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.facebook.com"
}
```
