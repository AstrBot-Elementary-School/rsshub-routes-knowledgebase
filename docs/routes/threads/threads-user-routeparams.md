# Threads - User timeline

## Coverage
`index-only`

## Route
- Namespace: `threads`
- Namespace Name: `Threads`
- Route Path: `/threads/:user/:routeParams?`
- Route Name: `User timeline`
- Example: `/threads/zuck`
- URL: `threads.net`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `ninboy, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Username
- `routeParams`: {"description": "Extra parameters, see the table below\nSpecify options (in the format of query string) in parameter `routeParams` to control some extra features for threads\n\n| Key                            | Description                                                                                                                  | Accepts                | Defaults to |\n| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |\n| `showAuthorInTitle`            | Show author name in title                                                                                                    | `0`/`1`/`true`/`false` | `true`      |\n| `showAuthorInDesc`             | Show author name in description (RSS body)                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedAuthorAvatarInDesc` | Show avatar of quoted author in description (RSS body) (Not recommended if your RSS reader extracts images from description) | `0`/`1`/`true`/`false` | `false`     |\n| `showAuthorAvatarInDesc`       | Show avatar of author in description (RSS body) (Not recommended if your RSS reader extracts images from description)        | `0`/`1`/`true`/`false` | `falseP`    |\n| `showEmojiForQuotesAndReply`   | Use \"🔁\" instead of \"QT\", \"↩️\" instead of \"Re\"                                                                               | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedInTitle`            | Show quoted tweet in title                                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `replies`                      | Show replies                                                                                                                 | `0`/`1`/`true`/`false` | `true`      |"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/threads/zuck",
  "heat": 55650,
  "location": "index.ts",
  "maintainers": [
    "ninboy",
    "pseudoyu"
  ],
  "name": "User timeline",
  "parameters": {
    "routeParams": {
      "description": "Extra parameters, see the table below\nSpecify options (in the format of query string) in parameter `routeParams` to control some extra features for threads\n\n| Key                            | Description                                                                                                                  | Accepts                | Defaults to |\n| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |\n| `showAuthorInTitle`            | Show author name in title                                                                                                    | `0`/`1`/`true`/`false` | `true`      |\n| `showAuthorInDesc`             | Show author name in description (RSS body)                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedAuthorAvatarInDesc` | Show avatar of quoted author in description (RSS body) (Not recommended if your RSS reader extracts images from description) | `0`/`1`/`true`/`false` | `false`     |\n| `showAuthorAvatarInDesc`       | Show avatar of author in description (RSS body) (Not recommended if your RSS reader extracts images from description)        | `0`/`1`/`true`/`false` | `falseP`    |\n| `showEmojiForQuotesAndReply`   | Use \"🔁\" instead of \"QT\", \"↩️\" instead of \"Re\"                                                                               | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedInTitle`            | Show quoted tweet in title                                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `replies`                      | Show replies                                                                                                                 | `0`/`1`/`true`/`false` | `true`      |"
    },
    "user": "Username"
  },
  "path": "/:user/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "hecaitou (@hecaitou) on Threads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71435314045960192",
      "image": "https://scontent-yyz1-1.cdninstagram.com/v/t51.2885-19/488156102_1160633875385251_3028278818063288032_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby44NzkuYzIifQ&_nc_ht=scontent-yyz1-1.cdninstagram.com&_nc_cat=107&_nc_oc=Q6cZ2gEkJbD9CQyo7w3GbgXmqsE5Gy351x5fZzfZDb82Bdve5tZb-60gLm_Q2qCx35SW56U&_nc_ohc=IgNk3aK6dAkQ7kNvwHwUUog&_nc_gid=CsQtINaZbhcZaij8w7Vj1g&edm=APs17CUBAAAA&ccb=7-5&oh=00_AQMadWaSClAsTuuiXz06SfRHWuaWY1pysumNzakQa68o1g&oe=6AD288C4&_nc_sid=10d13b",
      "ownerUserId": null,
      "siteUrl": "https://www.threads.com/@hecaitou",
      "title": "hecaitou (@hecaitou) on Threads",
      "type": "feed",
      "url": "rsshub://threads/hecaitou"
    },
    {
      "description": "zuck (@zuck) on Threads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "45996937449535488",
      "image": "https://scontent-nrt6-1.cdninstagram.com/v/t51.82787-19/825322135_17989325280103224_1252773933700107438_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-nrt6-1.cdninstagram.com&_nc_cat=100&_nc_oc=Q6cZ2gHdRXoGuhRtIEP_chzXgl1qKJu3dsyFGnQA-4S2IbgzliSLVHNnMtztdLApljm04zc&_nc_ohc=wDv3sDktP88Q7kNvwFnl3jN&_nc_gid=GMolzqvi-HAEXbDDb62oog&edm=APs17CUBAAAA&ccb=7-5&oh=00_AQP5XBBacib3tiuuxCbyQIz3sLt1wSLaLdLOp3FfUF7B0g&oe=6AD2C4EB&_nc_sid=10d13b",
      "ownerUserId": null,
      "siteUrl": "https://www.threads.net/@zuck",
      "title": "zuck (@zuck) on Threads",
      "type": "feed",
      "url": "rsshub://threads/zuck"
    }
  ],
  "view": 1
}
```
