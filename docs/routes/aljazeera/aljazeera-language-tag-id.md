# Aljazeera - Tag

## Coverage
`index-only`

## Route
- Namespace: `aljazeera`
- Namespace Name: `Aljazeera`
- Route Path: `/aljazeera/:language?/tag/:id`
- Route Name: `Tag`
- Example: `/aljazeera/english/tag/science-and-technology`
- URL: `aljazeera.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
Language

| Arabic | Chinese | English |
| ------ | ------- | ------- |
| arabic | chinese | english |

::: tip
If you subscribe to [Al Jazeera English - Science and Technology](https://www.aljazeera.com/tag/science-and-technology), whose language is `english` and whose path is `science-and-technology`, you can get the route as [`/aljazeera/english/tag/science-and-technology`](https://rsshub.app/aljazeera/english/tag/science-and-technology)
:::

## Parameters
- `language`: Language, see below, arabic by default, as Arabic
- `id`: Tag id, can be found in URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.aljazeera.com/tag/:id`
  - `www.aljazeera.com/`
- `target`: `/english/tag/:id`
### Rule 2
- `source`:
  - `www.aljazeera.net/tag/:id`
  - `www.aljazeera.net/`
- `target`: `/arabic/tag/:id`
### Rule 3
- `source`:
  - `chinese.aljazeera.net/tag/:id`
  - `chinese.aljazeera.net/`
- `target`: `/chinese/tag/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Language\n\n| Arabic | Chinese | English |\n| ------ | ------- | ------- |\n| arabic | chinese | english |\n\n::: tip\nIf you subscribe to [Al Jazeera English - Science and Technology](https://www.aljazeera.com/tag/science-and-technology), whose language is `english` and whose path is `science-and-technology`, you can get the route as [`/aljazeera/english/tag/science-and-technology`](https://rsshub.app/aljazeera/english/tag/science-and-technology)\n:::",
  "example": "/aljazeera/english/tag/science-and-technology",
  "heat": 2,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Tag",
  "parameters": {
    "id": "Tag id, can be found in URL",
    "language": "Language, see below, arabic by default, as Arabic"
  },
  "path": "/:language?/tag/:id",
  "radar": [
    {
      "source": [
        "www.aljazeera.com/tag/:id",
        "www.aljazeera.com/"
      ],
      "target": "/english/tag/:id"
    },
    {
      "source": [
        "www.aljazeera.net/tag/:id",
        "www.aljazeera.net/"
      ],
      "target": "/arabic/tag/:id"
    },
    {
      "source": [
        "chinese.aljazeera.net/tag/:id",
        "chinese.aljazeera.net/"
      ],
      "target": "/chinese/tag/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "Science and Technology | Today's latest from Al Jazeera - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "259957908309947405",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.aljazeera.com/tag/science-and-technology",
      "title": "Science and Technology | Today's latest from Al Jazeera",
      "type": "feed",
      "url": "rsshub://aljazeera/english/tag/science-and-technology"
    }
  ]
}
```
