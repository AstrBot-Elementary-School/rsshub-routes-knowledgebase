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
  "heat": 12134,
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
      "description": "💌 협찬문의 👉DM 💋 @puremediakorea 💄 @x.level.kr ❣️ @artgravia_global 👇예하의 화보집 구매 링크👇 👉예하의 계정 대피소 : @yun_yeha 👈 🐥예하의 트위터 아이디 : @_yeha_y 🐥 - Powered by RSSHub",
      "errorAt": "2025-07-06T11:26:33.915Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "92979620002035712",
      "image": "https://sp1.pixnoy.com/a/a_51211216676_18553117281855_a5998e6b702849f9d18c467da9a109d1.jpg?o=aHR0cHM6Ly9pbnN0YWdyYW0uZmNwczItMS5mbmEuZmJjZG4ubmV0L3YvdDUxLjI4ODUtMTkvNDU3MTM4MDgzXzU1MTMzMjUxMDU1NTg1OV83MjM4OTg5OTIwMTAyODE1ODEyX24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZfbmNfaHQ9aW5zdGFncmFtLmZjcHMyLTEuZm5hLmZiY2RuLm5ldCZfbmNfY2F0PTExMSZfbmNfb2M9UTZjWjJRRTVDTm9SSkVuVW9FTzc3cEJWaGlUc2lfOTJPNFZUb1hTREZtZ2pwMmdDWDJWUzEzbWt4bW90c3pRVGVzRUZCMWVRYnpXOG1GOXVFYTJYcGllY1FRbHcmX25jX29oYz1RQ2kwRXRIMGJRZ1E3a052d0VWSkh4dyZfbmNfZ2lkPVZ0NS0wVXpMeGI2MENTd3VBVkluMmcmZWRtPUFMR2JKUE1CQUFBQSZjY2I9Ny01Jm9oPTAwX0FmUGljYW1QbmdCSExKRVpNRUZKZi04Q1MtU0dWWldWb2FoRlNYLWdYLVJkN2cmb2U9Njg2RDRGQ0ImX25jX3NpZD03ZDNhYzU=&h=796983201a948dbcc17414355729ec0d",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/_yeha_y/",
      "title": "윤예하 (@_yeha_y) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/_yeha_y"
    },
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
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
