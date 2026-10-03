# Instagram - User Profile - Picnob.info

## Coverage
`index-only`

## Route
- Namespace: `picnob.info`
- Namespace Name: `Instagram`
- Route Path: `/picnob.info/user/:id/:type?`
- Route Name: `User Profile - Picnob.info`
- Example: `/picnob.info/user/xlisa_olivex`
- URL: `picnob.info`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: {"default": "posts", "description": "Type of profile page", "options": [{"label": "Posts", "value": "posts"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/picnob.info/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10194,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Profile - Picnob.info",
  "parameters": {
    "id": "Instagram id",
    "type": {
      "default": "posts",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Posts",
          "value": "posts"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "♡ LCK Oner ♡ / Cosplayer • 📨 Business : DM • 🪽Twitter(X) : nun__nyang - Powered by RSSHub",
      "errorAt": "2026-01-19T08:00:47.294Z",
      "errorMessage": "Failed to fetch\n",
      "id": "69002849547984896",
      "image": "https://sp1.pixnoy.com/a/a_63545940649_151015181555281513_df36f62931706b58b23ab3105541ca18.jpg?o=aHR0cHM6Ly9zY29udGVudC1hdGwzLTMuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS4yODg1LTE5LzU2MDA1ODE4Ml8xNzkyNTU0NzkwNTExNjY1MF82MDUxNzczNjg1NzgwNjIwODY1X24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZlZmc9ZXlKMlpXNWpiMlJsWDNSaFp5STZJbkJ5YjJacGJHVmZjR2xqTG1ScVlXNW5ieTR4TURnd0xtTXlJbjAmX25jX2h0PXNjb250ZW50LWF0bDMtMy5jZG5pbnN0YWdyYW0uY29tJl9uY19jYXQ9MTEwJl9uY19vYz1RNmNaMlFGdS1iVkk4bVZ6SFVBM01RbnplQW13TG5WNElDSFRjcnVGdGhHc3pWXzVyZkpqZGlvTUtacng1OExDNUtLM0t2ZV9FMHd0OFpfbDZrRlNQU3ZCMWFORiZfbmNfb2hjPXZJbUg0blBTeHE4UTdrTnZ3RTBPZ3dKJl9uY19naWQ9OEZxYmxFSVQ1X1RJZjc2SUlKZ0U2QSZlZG09QUxHYkpQTUJBQUFBJmNjYj03LTUmb2g9MDBfQWZwR3l0NC15TjhwcGFpWWdlWkZmMFhhUDFuZjhLQlM3aEl2czRlbXVlazRkdyZvZT02OTczMkQzNSZfbmNfc2lkPTdkM2FjNQ==&h=f3c7a491f1e876c12553b49b39265ef3",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/kxbatx/",
      "title": "누 나 (@kxbatx) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/kxbatx"
    },
    {
      "description": "45th & 47th President of the United States - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67508720925455360",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/343276689_801823474149940_2996871766977206771_n.jpg?stp=dst-jpg_s320x320_tt6&cb=8438d1d6-eb76aa66&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4zOTUuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_oc=Q6cZ2gHwE0zQ9UC0xqvTYxWLAbZVO39DDSjbUGjAvzrrR1471uIT7iETR4-rGBGXovXna3k&_nc_ohc=yHde1BHyyWsQ7kNvwE2TCMK&_nc_gid=M_Jbd2uBuqRp-WTaW3RYLA&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GJH8dRQ0alkTQdkCAPPZEnT_BpcpbkULAAAB3203200j-ccb7-5-cb8438d1d6-eb76aa66&oh=00_Af2NLrkMAUPZ6EahiByCJPS9Xsg23Bjsd_QeGl5VgR_Q4Q&oe=69F11BD1&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/realdonaldtrump/",
      "title": "President Donald J. Trump (@realdonaldtrump) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/realdonaldtrump"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
