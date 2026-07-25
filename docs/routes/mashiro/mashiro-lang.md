# Mashiro's Baumkuchen - Blog

## Coverage
`index-only`

## Route
- Namespace: `mashiro`
- Namespace Name: `Mashiro's Baumkuchen`
- Route Path: `/mashiro/:lang`
- Route Name: `Blog`
- Example: `/mashiro/en`
- URL: `mashiro.best`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `MuenYu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: the language of the site. Can be either `en` or `zh-cn`. Default: `en`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mashiro.best/`
  - `mashiro.best/:lang/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/mashiro/en",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "MuenYu"
  ],
  "name": "Blog",
  "parameters": {
    "lang": "the language of the site. Can be either `en` or `zh-cn`. Default: `en`"
  },
  "path": "/:lang",
  "radar": [
    {
      "source": [
        "mashiro.best/",
        "mashiro.best/:lang/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Mashiro's Baumkuchen - Powered by RSSHub",
      "errorAt": "2026-05-20T18:37:13.189Z",
      "errorMessage": "[GET] \"https://mashiro.best/zh-cn/archives/\": 404 Not Found\n[GET] \"https://mashiro.best/zh-cn/archives/\": 404 Not Found\n",
      "id": "113613880452673536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mashiro.best/zh-cn/archives/",
      "title": "Mashiro's Baumkuchen",
      "type": "feed",
      "url": "rsshub://mashiro/zh-cn"
    },
    {
      "description": "Mashiro's Baumkuchen - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113614203698257920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mashiro.best/archives/",
      "title": "Mashiro's Baumkuchen",
      "type": "feed",
      "url": "rsshub://mashiro/en"
    }
  ]
}
```
