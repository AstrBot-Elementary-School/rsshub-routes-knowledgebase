# Disqus - Comment

## Coverage
`index-only`

## Route
- Namespace: `disqus`
- Namespace Name: `Disqus`
- Route Path: `/disqus/posts/:forum`
- Route Name: `Comment`
- Example: `/disqus/posts/diygod-me`
- URL: `disqus.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `forum`: forum, disqus name of the target website


## Features
- `requireConfig`: [{"description": "Disqus API key", "name": "DISQUS_API_KEY", "optional": true}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/disqus/posts/diygod-me",
  "features": {
    "requireConfig": [
      {
        "description": "Disqus API key",
        "name": "DISQUS_API_KEY",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "posts.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Comment",
  "parameters": {
    "forum": "forum, disqus name of the target website"
  },
  "path": "/posts/:forum",
  "topFeeds": []
}
```
