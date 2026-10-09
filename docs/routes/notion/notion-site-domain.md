# Notion - Public site pages

## Coverage
`index-only`

## Route
- Namespace: `notion`
- Namespace Name: `Notion`
- Route Path: `/notion/site/:domain`
- Route Name: `Public site pages`
- Example: `/notion/site/notion`
- URL: `notion.so`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `DIYgod`
- Source Location: `site.tsx`
- Source Module: `_None_`

## Description
Lists direct child pages and their public top-level text. No Notion token is required. Private pages and database collections are not included.

## Parameters
- `domain`: Subdomain in <domain>.notion.site.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `notion.notion.site`
- `target`: `/site/notion`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Lists direct child pages and their public top-level text. No Notion token is required. Private pages and database collections are not included.",
  "example": "/notion/site/notion",
  "heat": 0,
  "location": "site.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Public site pages",
  "parameters": {
    "domain": "Subdomain in <domain>.notion.site."
  },
  "path": "/site/:domain",
  "radar": [
    {
      "source": [
        "notion.notion.site"
      ],
      "target": "/site/notion"
    }
  ],
  "topFeeds": []
}
```
