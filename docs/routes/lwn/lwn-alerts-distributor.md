# LWN.net - Security alerts

## Coverage
`index-only`

## Route
- Namespace: `lwn`
- Namespace Name: `LWN.net`
- Route Path: `/lwn/alerts/:distributor`
- Route Name: `Security alerts`
- Example: `/lwn/alerts/CentOS`
- URL: `lwn.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zengxs`
- Source Location: `alerts.ts`
- Source Module: `_None_`

## Description
| Distribution     | Identification     |
| :--------------- | :----------------- |
| Arch Linux       | `Arch_Linux`       |
| CentOS           | `CentOS`           |
| Debian           | `Debian`           |
| Fedora           | `Fedora`           |
| Gentoo           | `Gentoo`           |
| Mageia           | `Mageia`           |
| openSUSE         | `openSUSE`         |
| Oracle           | `Oracle`           |
| Red Hat          | `Red_Hat`          |
| Scientific Linux | `Scientific_Linux` |
| Slackware        | `Slackware`        |
| SUSE             | `SUSE`             |
| Ubuntu           | `Ubuntu`           |

## Parameters
- `distributor`: Distribution identification


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| Distribution     | Identification     |\n| :--------------- | :----------------- |\n| Arch Linux       | `Arch_Linux`       |\n| CentOS           | `CentOS`           |\n| Debian           | `Debian`           |\n| Fedora           | `Fedora`           |\n| Gentoo           | `Gentoo`           |\n| Mageia           | `Mageia`           |\n| openSUSE         | `openSUSE`         |\n| Oracle           | `Oracle`           |\n| Red Hat          | `Red_Hat`          |\n| Scientific Linux | `Scientific_Linux` |\n| Slackware        | `Slackware`        |\n| SUSE             | `SUSE`             |\n| Ubuntu           | `Ubuntu`           |",
  "example": "/lwn/alerts/CentOS",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "alerts.ts",
  "maintainers": [
    "zengxs"
  ],
  "name": "Security alerts",
  "parameters": {
    "distributor": "Distribution identification"
  },
  "path": "/alerts/:distributor",
  "topFeeds": []
}
```
