# XML.com - Articles and News

## Coverage
`index-only`

## Route
- Namespace: `xmlcom`
- Namespace Name: `XML.com`
- Route Path: `/xmlcom/`
- Route Name: `Articles and News`
- Example: `/xmlcom`
- URL: `www.xml.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `AboutRSS`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
The official Atom feed (/feed/all/) truncates every entry to a 128 character summary and carries no category tags. This route fetches the full body from each detail page and extracts the tags of that page into category.

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.xml.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "The official Atom feed (/feed/all/) truncates every entry to a 128 character summary and carries no category tags. This route fetches the full body from each detail page and extracts the tags of that page into category.",
  "example": "/xmlcom",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "AboutRSS"
  ],
  "name": "Articles and News",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.xml.com/"
      ]
    }
  ],
  "topFeeds": []
}
```
