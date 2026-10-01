# Alpine Linux - Packages

## Coverage
`index-only`

## Route
- Namespace: `alpinelinux`
- Namespace Name: `Alpine Linux`
- Route Path: `/alpinelinux/pkgs/:name/:routeParams?`
- Route Name: `Packages`
- Example: `/alpinelinux/pkgs/nodejs`
- URL: `alpinelinux.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`
- Source Location: `pkgs.ts`
- Source Module: `_None_`

## Description
Alpine Linux packages update

## Parameters
- `name`: Packages name
- `routeParams`: Filters of packages type. E.g. branch=edge&repo=main&arch=armv7&maintainer=Jakub%20Jirutka


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `https://pkgs.alpinelinux.org/packages`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Alpine Linux packages update",
  "example": "/alpinelinux/pkgs/nodejs",
  "heat": 5,
  "location": "pkgs.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "Packages",
  "parameters": {
    "name": "Packages name",
    "routeParams": "Filters of packages type. E.g. branch=edge&repo=main&arch=armv7&maintainer=Jakub%20Jirutka"
  },
  "path": "/pkgs/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "https://pkgs.alpinelinux.org/packages"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Alpine Linux packages update - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70019545950188544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pkgs.alpinelinux.org/packages?name=rust",
      "title": "rust - Alpine Linux packages",
      "type": "feed",
      "url": "rsshub://alpinelinux/pkgs/rust"
    },
    {
      "description": "Alpine Linux packages update - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95754111177589760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pkgs.alpinelinux.org/packages?name=nodejs",
      "title": "nodejs - Alpine Linux packages",
      "type": "feed",
      "url": "rsshub://alpinelinux/pkgs/nodejs"
    }
  ],
  "zh": {
    "description": "Alpine Linux 软件包更新",
    "name": "软件包"
  }
}
```
