# Hexo - Blog using Yilia theme

## Coverage
`index-only`

## Route
- Namespace: `hexo`
- Namespace Name: `Hexo`
- Route Path: `/hexo/yilia/:url`
- Route Name: `Blog using Yilia theme`
- Example: `/hexo/yilia/joeybling.github.io`
- URL: `hexo.io`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `aha2mao`
- Source Location: `yilia.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `url`: the blog URL without the protocol (http:// and https://)


## Features
- `requireConfig`: [{"description": "Allow user supplied domain", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/hexo/yilia/joeybling.github.io",
  "features": {
    "requireConfig": [
      {
        "description": "Allow user supplied domain",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ]
  },
  "heat": 0,
  "location": "yilia.ts",
  "maintainers": [
    "aha2mao"
  ],
  "name": "Blog using Yilia theme",
  "parameters": {
    "url": "the blog URL without the protocol (http:// and https://)"
  },
  "path": "/yilia/:url",
  "topFeeds": []
}
```
