# Aljazeera - Official RSS

## Coverage
`index-only`

## Route
- Namespace: `aljazeera`
- Namespace Name: `Aljazeera`
- Route Path: `/aljazeera/:language?/rss`
- Route Name: `Official RSS`
- Example: `/aljazeera/english/rss`
- URL: `aljazeera.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
Language

| Arabic | Chinese | English |
| ------ | ------- | ------- |
| arabic | chinese | english |

::: tip
There is no RSS source for Al Jazeera Chinese, returning homepage content by default
:::

## Parameters
- `language`: Language, see below, arabic by default, as Arabic


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.aljazeera.com/xml/rss/all.xml`
  - `www.aljazeera.com/`
- `target`: `/english/rss`
### Rule 2
- `source`:
  - `www.aljazeera.net/rss`
  - `www.aljazeera.net/`
- `target`: `/arabic/rss`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Language\n\n| Arabic | Chinese | English |\n| ------ | ------- | ------- |\n| arabic | chinese | english |\n\n::: tip\nThere is no RSS source for Al Jazeera Chinese, returning homepage content by default\n:::",
  "example": "/aljazeera/english/rss",
  "heat": 0,
  "location": "rss.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Official RSS",
  "parameters": {
    "language": "Language, see below, arabic by default, as Arabic"
  },
  "path": "/:language?/rss",
  "radar": [
    {
      "source": [
        "www.aljazeera.com/xml/rss/all.xml",
        "www.aljazeera.com/"
      ],
      "target": "/english/rss"
    },
    {
      "source": [
        "www.aljazeera.net/rss",
        "www.aljazeera.net/"
      ],
      "target": "/arabic/rss"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
