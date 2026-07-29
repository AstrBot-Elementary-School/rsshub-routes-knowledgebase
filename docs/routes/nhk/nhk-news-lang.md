# NHK - WORLD-JAPAN - Top Stories

## Coverage
`index-only`

## Route
- Namespace: `nhk`
- Namespace Name: `NHK`
- Route Path: `/nhk/news/:lang?`
- Route Name: `WORLD-JAPAN - Top Stories`
- Example: `/nhk/news/en`
- URL: `www3.nhk.or.jp`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL, pseudoyu, cscnk52`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language, see below", "options": [{"label": "العربية", "value": "ar"}, {"label": "বাংলা", "value": "bn"}, {"label": "မြန်မာဘာသာစကား", "value": "my"}, {"label": "中文（简体）", "value": "zh"}, {"label": "中文（繁體）", "value": "zt"}, {"label": "English", "value": "en"}, {"label": "Français", "value": "fr"}, {"label": "हिन्दी", "value": "hi"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "코리언", "value": "ko"}, {"label": "فارسی", "value": "fa"}, {"label": "Português", "value": "pt"}, {"label": "Русский", "value": "ru"}, {"label": "Español", "value": "es"}, {"label": "Kiswahili", "value": "sw"}, {"label": "ภาษาไทย", "value": "th"}, {"label": "Türkçe", "value": "tr"}, {"label": "Українська", "value": "uk"}, {"label": "اردو", "value": "ur"}, {"label": "Tiếng Việt", "value": "vi"}]}


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
  - `www3.nhk.or.jp/nhkworld/:lang/news/list/`
  - `www3.nhk.or.jp/nhkworld/:lang/news/`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/nhk/news/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1121,
  "location": "news.tsx",
  "maintainers": [
    "TonyRL",
    "pseudoyu",
    "cscnk52"
  ],
  "name": "WORLD-JAPAN - Top Stories",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language, see below",
      "options": [
        {
          "label": "العربية",
          "value": "ar"
        },
        {
          "label": "বাংলা",
          "value": "bn"
        },
        {
          "label": "မြန်မာဘာသာစကား",
          "value": "my"
        },
        {
          "label": "中文（简体）",
          "value": "zh"
        },
        {
          "label": "中文（繁體）",
          "value": "zt"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "हिन्दी",
          "value": "hi"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
        },
        {
          "label": "코리언",
          "value": "ko"
        },
        {
          "label": "فارسی",
          "value": "fa"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Kiswahili",
          "value": "sw"
        },
        {
          "label": "ภาษาไทย",
          "value": "th"
        },
        {
          "label": "Türkçe",
          "value": "tr"
        },
        {
          "label": "Українська",
          "value": "uk"
        },
        {
          "label": "اردو",
          "value": "ur"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        }
      ]
    }
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "www3.nhk.or.jp/nhkworld/:lang/news/list/",
        "www3.nhk.or.jp/nhkworld/:lang/news/"
      ],
      "target": "/news/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "undefined | NHK WORLD-JAPAN News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61596371943710720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www3.nhk.or.jp/nhkworld/en/news/list/",
      "title": "undefined | NHK WORLD-JAPAN News",
      "type": "feed",
      "url": "rsshub://nhk/news"
    },
    {
      "description": "新闻提要 | NHK WORLD-JAPAN News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61417208948286464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www3.nhk.or.jp/nhkworld/zh/news/list/",
      "title": "新闻提要 | NHK WORLD-JAPAN News",
      "type": "feed",
      "url": "rsshub://nhk/news/zh"
    }
  ],
  "view": 0
}
```
