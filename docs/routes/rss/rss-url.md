# RSS Proxy - Feed proxy

## Coverage
`index-only`

## Route
- Namespace: `rss`
- Namespace Name: `RSS Proxy`
- Route Path: `/rss/:url{.+}`
- Route Name: `Feed proxy`
- Example: `/rss/https%3A%2F%2Fwww.nasa.gov%2Ffeed%2F`
- URL: `www.rssboard.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `DIYgod`
- Source Location: `feed.ts`
- Source Module: `_None_`

## Description
Fetch an existing RSS or Atom feed through your instance. TLS certificates are verified. Common parameters and output formats work as usual.

## Parameters
- `url`: Upstream RSS or Atom URL, encoded with encodeURIComponent.


## Features
- `requireConfig`: [{"description": "Must be true to allow fetching user-supplied feed URLs.", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Fetch an existing RSS or Atom feed through your instance. TLS certificates are verified. Common parameters and output formats work as usual.",
  "example": "/rss/https%3A%2F%2Fwww.nasa.gov%2Ffeed%2F",
  "features": {
    "requireConfig": [
      {
        "description": "Must be true to allow fetching user-supplied feed URLs.",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ]
  },
  "heat": 0,
  "location": "feed.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Feed proxy",
  "parameters": {
    "url": "Upstream RSS or Atom URL, encoded with encodeURIComponent."
  },
  "path": "/:url{.+}",
  "topFeeds": []
}
```
