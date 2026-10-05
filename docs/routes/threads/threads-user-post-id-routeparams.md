# Threads - Post & Replies

## Coverage
`index-only`

## Route
- Namespace: `threads`
- Namespace Name: `Threads`
- Route Path: `/threads/:user/post/:id/:routeParams?`
- Route Name: `Post & Replies`
- Example: `/threads/@zuck/post/Ddt7cL5EfUG`
- URL: `threads.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Username
- `id`: Post ID, the last segment of the post URL
- `routeParams`: Extra parameters, in the format of query string. Accepts the same options as User timeline


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.threads.com/:user/post/:id`
- `target`: `/:user/post/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/threads/@zuck/post/Ddt7cL5EfUG",
  "heat": 0,
  "location": "post.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Post & Replies",
  "parameters": {
    "id": "Post ID, the last segment of the post URL",
    "routeParams": "Extra parameters, in the format of query string. Accepts the same options as User timeline",
    "user": "Username"
  },
  "path": "/:user/post/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "www.threads.com/:user/post/:id"
      ],
      "target": "/:user/post/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "view": 1
}
```
