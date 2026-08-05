# Mastodon - Hashtag timeline

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/tag/:site/:hashtag/:only_media?`
- Route Name: `Hashtag timeline`
- Example: `/mastodon/tag/mastodon.social/gochisou/true`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yuikisaito`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
- `hashtag`: Hashtag you want to subscribe to (without the # symbol)
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mastodon/tag/mastodon.social/gochisou/true",
  "heat": 6,
  "location": "tag.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "name": "Hashtag timeline",
  "parameters": {
    "hashtag": "Hashtag you want to subscribe to (without the # symbol)",
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/tag/:site/:hashtag/:only_media?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "#长毛象安利交换大会 Media Timeline on gochisou.photo - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173609057249857536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gochisou.photo/",
      "title": "#长毛象安利交换大会 Media Timeline on gochisou.photo",
      "type": "feed",
      "url": "rsshub://mastodon/tag/gochisou.photo/%E9%95%BF%E6%AF%9B%E8%B1%A1%E5%AE%89%E5%88%A9%E4%BA%A4%E6%8D%A2%E5%A4%A7%E4%BC%9A/true"
    },
    {
      "description": "#长毛象安利大会 Media Timeline on gochisou.photo - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173588946787373056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gochisou.photo/",
      "title": "#长毛象安利大会 Media Timeline on gochisou.photo",
      "type": "feed",
      "url": "rsshub://mastodon/tag/gochisou.photo/%E9%95%BF%E6%AF%9B%E8%B1%A1%E5%AE%89%E5%88%A9%E5%A4%A7%E4%BC%9A/true"
    }
  ],
  "view": 1
}
```
