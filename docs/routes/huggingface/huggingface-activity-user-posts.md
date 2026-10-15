# Huggingface - User Posts Activity

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/huggingface/activity/:user/posts`
- Route Name: `User Posts Activity`
- Example: `/huggingface/activity/AbstractPhil/posts`
- URL: `huggingface.co`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `qqc20043, pseudoyu`
- Source Location: `user-posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Hugging Face username


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `huggingface.co/:user/activity/posts`
- `target`: `/activity/:user/posts`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/activity/AbstractPhil/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-posts.ts",
  "maintainers": [
    "qqc20043",
    "pseudoyu"
  ],
  "name": "User Posts Activity",
  "parameters": {
    "user": "Hugging Face username"
  },
  "path": "/activity/:user/posts",
  "radar": [
    {
      "source": [
        "huggingface.co/:user/activity/posts"
      ],
      "target": "/activity/:user/posts"
    }
  ],
  "topFeeds": [],
  "url": "huggingface.co",
  "view": 1
}
```
