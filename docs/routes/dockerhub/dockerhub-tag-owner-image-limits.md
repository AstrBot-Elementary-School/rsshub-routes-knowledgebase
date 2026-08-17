# Docker Hub - Image New Tag

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/dockerhub/tag/:owner/:image/:limits?`
- Route Name: `Image New Tag`
- Example: `/dockerhub/tag/library/mariadb`
- URL: `hub.docker.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `pseudoyu`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
::: warning
Use `library` as the `owner` for official images, such as <https://rsshub.app/dockerhub/tag/library/mysql>
:::

## Parameters
- `owner`: Image owner
- `image`: Image name
- `limits`: Tag count, 10 by default


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
  "description": "::: warning\nUse `library` as the `owner` for official images, such as <https://rsshub.app/dockerhub/tag/library/mysql>\n:::",
  "example": "/dockerhub/tag/library/mariadb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "tag.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Image New Tag",
  "parameters": {
    "image": "Image name",
    "limits": "Tag count, 10 by default",
    "owner": "Image owner"
  },
  "path": "/tag/:owner/:image/:limits?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "envyafish/byte-muse tags - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122940046833559552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/envyafish/byte-muse",
      "title": "envyafish/byte-muse tags",
      "type": "feed",
      "url": "rsshub://dockerhub/tag/envyafish/byte-muse"
    },
    {
      "description": "emby自供版 交流群：433493451 703381164 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67082647330225152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/amilys/embyserver",
      "title": "amilys/embyserver tags",
      "type": "feed",
      "url": "rsshub://dockerhub/tag/amilys/embyserver"
    }
  ]
}
```
