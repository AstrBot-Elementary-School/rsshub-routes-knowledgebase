# Claude - Code Changelog

## Coverage
`index-only`

## Route
- Namespace: `claude`
- Namespace Name: `Claude`
- Route Path: `/claude/code/changelog`
- Route Name: `Code Changelog`
- Example: `/claude/code/changelog`
- URL: `code.claude.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `rmaced0`
- Source Location: `code-changelog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `code.claude.com/docs/en/changelog`
- `target`: `/code/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/claude/code/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 18,
  "location": "code-changelog.ts",
  "maintainers": [
    "rmaced0"
  ],
  "name": "Code Changelog",
  "path": "/code/changelog",
  "radar": [
    {
      "source": [
        "code.claude.com/docs/en/changelog"
      ],
      "target": "/code/changelog"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Changelog for Claude Code CLI - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "259003498298762240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://code.claude.com/docs/en/changelog",
      "title": "Claude Code Changelog",
      "type": "feed",
      "url": "rsshub://claude/code/changelog"
    }
  ],
  "url": "code.claude.com"
}
```
