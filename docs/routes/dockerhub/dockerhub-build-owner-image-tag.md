# Docker Hub - Image New Build

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/dockerhub/build/:owner/:image/:tag?`
- Route Name: `Image New Build`
- Example: `/dockerhub/build/diygod/rsshub/latest`
- URL: `hub.docker.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `build.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `owner`: Image owner, the owner of the official image fills in the library, for example: /dockerhub/build/library/mysql
- `image`: Image name
- `tag`: {"default": "latest", "description": "Image tag"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/dockerhub/build/diygod/rsshub/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 462,
  "location": "build.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Image New Build",
  "parameters": {
    "image": "Image name",
    "owner": "Image owner, the owner of the official image fills in the library, for example: /dockerhub/build/library/mysql",
    "tag": {
      "default": "latest",
      "description": "Image tag"
    }
  },
  "path": "/build/:owner/:image/:tag?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "🍰 使用 RSS 连接全世界 - Powered by RSSHub",
      "errorAt": "2026-09-08T12:42:14.774Z",
      "errorMessage": "Authentication failed. Access denied.\n/dockerhub/build/diygod/rsshub/latest\n[GET] \"https://hub.docker.com/v2/repositories/diygod/rsshub/tags/latest\": 429 Too Many Requests\n",
      "id": "56669568700797952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/diygod/rsshub",
      "title": "diygod/rsshub:latest build history",
      "type": "feed",
      "url": "rsshub://dockerhub/build/diygod/rsshub/latest"
    },
    {
      "description": "Alternative implementation of the Bitwarden server API in Rust, including the Web Vault. - Powered by RSSHub",
      "errorAt": "2026-09-08T04:18:22.276Z",
      "errorMessage": "[GET] \"https://hub.docker.com/v2/repositories/vaultwarden/server/tags/latest\": 429 Too Many Requests\n",
      "id": "56670320731116544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/vaultwarden/server",
      "title": "vaultwarden/server:latest build history",
      "type": "feed",
      "url": "rsshub://dockerhub/build/vaultwarden/server/latest"
    }
  ],
  "view": 5
}
```
