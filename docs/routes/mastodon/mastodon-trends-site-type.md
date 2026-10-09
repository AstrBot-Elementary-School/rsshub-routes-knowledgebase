# Mastodon - Trending posts, hashtags and links

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/trends/:site/:type?`
- Route Name: `Trending posts, hashtags and links`
- Example: `/mastodon/trends/mastodon.social`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `trends.tsx`
- Source Module: `_None_`

## Description
Instances outside the existing Mastodon domain allowlist require `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN=true` or `MASTODON_API_HOST`. Availability depends on the instance enabling public trends.

## Parameters
- `site`: Instance domain, without a protocol.
- `type`: {"default": "statuses", "description": "Trending content type.", "options": [{"label": "Posts", "value": "statuses"}, {"label": "Hashtags", "value": "tags"}, {"label": "Links", "value": "links"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mastodon.social/explore`
- `target`: `/trends/mastodon.social/statuses`
### Rule 2
- `source`:
  - `mastodon.social/explore/tags`
- `target`: `/trends/mastodon.social/tags`
### Rule 3
- `source`:
  - `mastodon.social/explore/links`
- `target`: `/trends/mastodon.social/links`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Instances outside the existing Mastodon domain allowlist require `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN=true` or `MASTODON_API_HOST`. Availability depends on the instance enabling public trends.",
  "example": "/mastodon/trends/mastodon.social",
  "heat": 0,
  "location": "trends.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Trending posts, hashtags and links",
  "parameters": {
    "site": "Instance domain, without a protocol.",
    "type": {
      "default": "statuses",
      "description": "Trending content type.",
      "options": [
        {
          "label": "Posts",
          "value": "statuses"
        },
        {
          "label": "Hashtags",
          "value": "tags"
        },
        {
          "label": "Links",
          "value": "links"
        }
      ]
    }
  },
  "path": "/trends/:site/:type?",
  "radar": [
    {
      "source": [
        "mastodon.social/explore"
      ],
      "target": "/trends/mastodon.social/statuses"
    },
    {
      "source": [
        "mastodon.social/explore/tags"
      ],
      "target": "/trends/mastodon.social/tags"
    },
    {
      "source": [
        "mastodon.social/explore/links"
      ],
      "target": "/trends/mastodon.social/links"
    }
  ],
  "topFeeds": []
}
```
