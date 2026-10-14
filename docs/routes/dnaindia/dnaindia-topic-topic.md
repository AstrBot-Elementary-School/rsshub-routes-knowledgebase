# DNA India - Topic

## Coverage
`index-only`

## Route
- Namespace: `dnaindia`
- Namespace Name: `DNA India`
- Route Path: `/dnaindia/topic/:topic`
- Route Name: `Topic`
- Example: `/dnaindia/topic/dna-verified`
- URL: `www.dnaindia.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Rjnishant530`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
Topics:

| DNA verified |
| ------------ |
| dna-verified |

::: tip
The URL of the form `https://www.dnaindia.com/topic/dna-verified` demonstrates the utilization of the subdomain `topic`.
:::

## Parameters
- `topic`: Find it in the URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dnaindia.com/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Topics:\n\n| DNA verified |\n| ------------ |\n| dna-verified |\n\n::: tip\nThe URL of the form `https://www.dnaindia.com/topic/dna-verified` demonstrates the utilization of the subdomain `topic`.\n:::",
  "example": "/dnaindia/topic/dna-verified",
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Topic",
  "parameters": {
    "topic": "Find it in the URL"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "www.dnaindia.com/topic/:topic"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.dnaindia.com"
}
```
