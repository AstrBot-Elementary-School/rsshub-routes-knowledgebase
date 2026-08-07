# 快手 - Profile

## Coverage
`index-only`

## Route
- Namespace: `kuaishou`
- Namespace Name: `快手`
- Route Path: `/kuaishou/profile/:principalId`
- Route Name: `Profile`
- Example: `/kuaishou/profile/3xk46q9cdnvgife`
- URL: `kuaishou.com/profile/:principalId`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `GuoChen-thlg`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
::: tip
The profile page of the user, which contains the user's information, videos, and other information.
:::

## Parameters
- `principalId`: 用户 id, 可在主页中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kuaishou.com/profile/:principalId`
- `target`: `/profile/:principalId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip\nThe profile page of the user, which contains the user's information, videos, and other information.\n:::",
  "example": "/kuaishou/profile/3xk46q9cdnvgife",
  "heat": 6,
  "location": "profile.ts",
  "maintainers": [
    "GuoChen-thlg"
  ],
  "name": "Profile",
  "parameters": {
    "principalId": "用户 id, 可在主页中找到"
  },
  "path": "/profile/:principalId",
  "radar": [
    {
      "source": [
        "kuaishou.com/profile/:principalId"
      ],
      "target": "/profile/:principalId"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "youbao5266的作品 - 快手 - Powered by RSSHub",
      "errorAt": "2026-06-09T00:03:38.791Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nFailed to fetch\npage.goto: Target page, context or browser has been closed\n",
      "id": "147602391664470016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "youbao5266的作品 - 快手",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/youbao5266"
    },
    {
      "description": "再无晚安了8 - Powered by RSSHub",
      "errorAt": "2025-03-17T13:35:14.200Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "124386287235780608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "再无晚安了8",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/hmy2053629"
    }
  ],
  "url": "kuaishou.com/profile/:principalId"
}
```
