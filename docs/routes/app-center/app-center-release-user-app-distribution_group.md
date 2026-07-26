# App Center - Release

## Coverage
`index-only`

## Route
- Namespace: `app-center`
- Namespace Name: `App Center`
- Route Path: `/app-center/release/:user/:app/:distribution_group`
- Route Name: `Release`
- Example: `/app-center/release/cloudflare/1.1.1.1-windows/beta`
- URL: `install.appcenter.ms`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Rongronggg9`
- Source Location: `release.tsx`
- Source Module: `_None_`

## Description
::: tip
The parameters can be extracted from the Release page URL: `https://install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`
:::

## Parameters
- `user`: User
- `app`: App name
- `distribution_group`: Distribution group


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`
  - `install.appcenter.ms/orgs/:user/apps/:app/distribution_groups/:distribution_group`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nThe parameters can be extracted from the Release page URL: `https://install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`\n:::",
  "example": "/app-center/release/cloudflare/1.1.1.1-windows/beta",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "release.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "Release",
  "parameters": {
    "app": "App name",
    "distribution_group": "Distribution group",
    "user": "User"
  },
  "path": "/release/:user/:app/:distribution_group",
  "radar": [
    {
      "source": [
        "install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group",
        "install.appcenter.ms/orgs/:user/apps/:app/distribution_groups/:distribution_group"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Cloudflare WARP Windows Beta (Beta) for Windows by Cloudflare - App Center Releases - Powered by RSSHub",
      "errorAt": "2025-08-12T15:37:01.285Z",
      "errorMessage": "[GET] \"https://install.appcenter.ms/api/v0.1/apps/cloudflare/1.1.1.1-windows/distribution_groups/beta/releases/3916?is_install_page=true\": 410 Gone\n",
      "id": "83739691836196864",
      "image": "https://coreservicesstorgeprod.blob.core.windows.net/app-avatar-container/ccc0b4bf-bc67-4fb7-bf82-f9f6d26e0cee?sv=2024-11-04&spr=https&st=2025-01-24T04%3A14%3A08Z&se=2025-01-31T04%3A19%3A08Z&skoid=05571020-ed2f-4af9-8176-0df11ddebe41&sktid=975f013f-7f24-47e8-a7d3-abc4752bf346&skt=2025-01-24T04%3A14%3A08Z&ske=2025-01-31T04%3A19%3A08Z&sks=b&skv=2024-11-04&sr=b&sp=r&sig=gD2n2uv4Deh%2BJp91w4kZL8hel9cw37cq27pr0ZIPHUU%3D",
      "ownerUserId": null,
      "siteUrl": "https://install.appcenter.ms/users/cloudflare/apps/1.1.1.1-windows/distribution_groups/beta",
      "title": "Cloudflare WARP Windows Beta (Beta) for Windows by Cloudflare - App Center Releases",
      "type": "feed",
      "url": "rsshub://app-center/release/cloudflare/1.1.1.1-windows/beta"
    },
    {
      "description": "Fluent Search (Alpha) (Exe) for Windows by Adir Hudayfi - App Center Releases - Powered by RSSHub",
      "errorAt": "2025-08-12T08:26:04.771Z",
      "errorMessage": "Failed to fetch\n",
      "id": "68581349461664768",
      "image": "https://coreservicesstorgeprod.blob.core.windows.net/app-avatar-container/e258e325-a757-40c3-9a33-4bac28ddbe42?sv=2024-11-04&spr=https&st=2025-02-11T10%3A01%3A43Z&se=2025-02-18T10%3A06%3A43Z&skoid=05571020-ed2f-4af9-8176-0df11ddebe41&sktid=975f013f-7f24-47e8-a7d3-abc4752bf346&skt=2025-02-11T10%3A01%3A43Z&ske=2025-02-18T10%3A06%3A43Z&sks=b&skv=2024-11-04&sr=b&sp=r&sig=ckJfAuRk4ojBU22HZQSgIkYeL3%2FUTy9pq%2FOa%2BOeeXyQ%3D",
      "ownerUserId": null,
      "siteUrl": "https://install.appcenter.ms/users/adirh3-gmail.com/apps/fluent-search-alpha/distribution_groups/exe",
      "title": "Fluent Search (Alpha) (Exe) for Windows by Adir Hudayfi - App Center Releases",
      "type": "feed",
      "url": "rsshub://app-center/release/adirh3-gmail.com/fluent-search-alpha/exe"
    }
  ]
}
```
