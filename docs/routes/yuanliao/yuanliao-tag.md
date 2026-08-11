# 猿料 - 主题

## Coverage
`index-only`

## Route
- Namespace: `yuanliao`
- Namespace Name: `猿料`
- Route Path: `/yuanliao/:tag?`
- Route Name: `主题`
- Example: `/yuanliao`
- URL: `yuanliao.info`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [问题反馈](https://yuanliao.info/t/bug-report)，其源网址为 `https://yuanliao.info/t/bug-report`，请参考该 URL 指定部分构成参数，此时路由为 [`/yuanliao/bug-report`](https://rsshub.app/yuanliao/bug-report)。
:::

| 标签                                             | id                                                       |
| ------------------------------------------------ | -------------------------------------------------------- |
| [问题反馈](https://yuanliao.info/t/bug-report)   | [bug-report](https://rsshub.app/yuanliao/bug-report)     |
| [Windows](https://yuanliao.info/t/windows)       | [windows](https://rsshub.app/yuanliao/windows)           |
| [macOS](https://yuanliao.info/t/macos)           | [macos](https://rsshub.app/yuanliao/macos)               |
| [Linux](https://yuanliao.info/t/linux)           | [linux](https://rsshub.app/yuanliao/linux)               |
| [意见建议](https://yuanliao.info/t/suggestions)  | [suggestions](https://rsshub.app/yuanliao/suggestions)   |
| [插件发布](https://yuanliao.info/t/plugins)      | [plugins](https://rsshub.app/yuanliao/plugins)           |
| [插件需求](https://yuanliao.info/t/plugin-needs) | [plugin-needs](https://rsshub.app/yuanliao/plugin-needs) |
| [开发者](https://yuanliao.info/t/developers)     | [developers](https://rsshub.app/yuanliao/developers)     |

## Parameters
- `tag`: {"description": "标签，默认为全部，可在对应标签页 URL 中找到", "options": [{"label": "问题反馈", "value": "bug-report"}, {"label": "Windows", "value": "windows"}, {"label": "macOS", "value": "macos"}, {"label": "Linux", "value": "linux"}, {"label": "意见建议", "value": "suggestions"}, {"label": "插件发布", "value": "plugins"}, {"label": "插件需求", "value": "plugin-needs"}, {"label": "开发者", "value": "developers"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yuanliao.info`
  - `yuanliao.info/t/:tag`
### Rule 2
- `title`: `问题反馈`
- `source`:
  - `yuanliao.info/t/bug-report`
- `target`: `/bug-report`
### Rule 3
- `title`: `Windows`
- `source`:
  - `yuanliao.info/t/windows`
- `target`: `/windows`
### Rule 4
- `title`: `macOS`
- `source`:
  - `yuanliao.info/t/macos`
- `target`: `/macos`
### Rule 5
- `title`: `Linux`
- `source`:
  - `yuanliao.info/t/linux`
- `target`: `/linux`
### Rule 6
- `title`: `意见建议`
- `source`:
  - `yuanliao.info/t/suggestions`
- `target`: `/suggestions`
### Rule 7
- `title`: `插件发布`
- `source`:
  - `yuanliao.info/t/plugins`
- `target`: `/plugins`
### Rule 8
- `title`: `插件需求`
- `source`:
  - `yuanliao.info/t/plugin-needs`
- `target`: `/plugin-needs`
### Rule 9
- `title`: `开发者`
- `source`:
  - `yuanliao.info/t/developers`
- `target`: `/developers`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n订阅 [问题反馈](https://yuanliao.info/t/bug-report)，其源网址为 `https://yuanliao.info/t/bug-report`，请参考该 URL 指定部分构成参数，此时路由为 [`/yuanliao/bug-report`](https://rsshub.app/yuanliao/bug-report)。\n:::\n\n| 标签                                             | id                                                       |\n| ------------------------------------------------ | -------------------------------------------------------- |\n| [问题反馈](https://yuanliao.info/t/bug-report)   | [bug-report](https://rsshub.app/yuanliao/bug-report)     |\n| [Windows](https://yuanliao.info/t/windows)       | [windows](https://rsshub.app/yuanliao/windows)           |\n| [macOS](https://yuanliao.info/t/macos)           | [macos](https://rsshub.app/yuanliao/macos)               |\n| [Linux](https://yuanliao.info/t/linux)           | [linux](https://rsshub.app/yuanliao/linux)               |\n| [意见建议](https://yuanliao.info/t/suggestions)  | [suggestions](https://rsshub.app/yuanliao/suggestions)   |\n| [插件发布](https://yuanliao.info/t/plugins)      | [plugins](https://rsshub.app/yuanliao/plugins)           |\n| [插件需求](https://yuanliao.info/t/plugin-needs) | [plugin-needs](https://rsshub.app/yuanliao/plugin-needs) |\n| [开发者](https://yuanliao.info/t/developers)     | [developers](https://rsshub.app/yuanliao/developers)     |",
  "example": "/yuanliao",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 53,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "主题",
  "parameters": {
    "tag": {
      "description": "标签，默认为全部，可在对应标签页 URL 中找到",
      "options": [
        {
          "label": "问题反馈",
          "value": "bug-report"
        },
        {
          "label": "Windows",
          "value": "windows"
        },
        {
          "label": "macOS",
          "value": "macos"
        },
        {
          "label": "Linux",
          "value": "linux"
        },
        {
          "label": "意见建议",
          "value": "suggestions"
        },
        {
          "label": "插件发布",
          "value": "plugins"
        },
        {
          "label": "插件需求",
          "value": "plugin-needs"
        },
        {
          "label": "开发者",
          "value": "developers"
        }
      ]
    }
  },
  "path": "/:tag?",
  "radar": [
    {
      "source": [
        "yuanliao.info",
        "yuanliao.info/t/:tag"
      ]
    },
    {
      "source": [
        "yuanliao.info/t/bug-report"
      ],
      "target": "/bug-report",
      "title": "问题反馈"
    },
    {
      "source": [
        "yuanliao.info/t/windows"
      ],
      "target": "/windows",
      "title": "Windows"
    },
    {
      "source": [
        "yuanliao.info/t/macos"
      ],
      "target": "/macos",
      "title": "macOS"
    },
    {
      "source": [
        "yuanliao.info/t/linux"
      ],
      "target": "/linux",
      "title": "Linux"
    },
    {
      "source": [
        "yuanliao.info/t/suggestions"
      ],
      "target": "/suggestions",
      "title": "意见建议"
    },
    {
      "source": [
        "yuanliao.info/t/plugins"
      ],
      "target": "/plugins",
      "title": "插件发布"
    },
    {
      "source": [
        "yuanliao.info/t/plugin-needs"
      ],
      "target": "/plugin-needs",
      "title": "插件需求"
    },
    {
      "source": [
        "yuanliao.info/t/developers"
      ],
      "target": "/developers",
      "title": "开发者"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "macOS 标签下的所有主题 - Powered by RSSHub",
      "errorAt": "2026-03-03T02:50:45.460Z",
      "errorMessage": "d.included is not iterable\n",
      "id": "150754386348295168",
      "image": "https://yuanliao.info/assets/logo-f9tlxmqd.png",
      "ownerUserId": null,
      "siteUrl": "https://yuanliao.info/t/macos",
      "title": "macOS - 猿料社区",
      "type": "feed",
      "url": "rsshub://yuanliao/macos"
    },
    {
      "description": "Windows 标签下的所有主题 - Powered by RSSHub",
      "errorAt": "2026-03-03T22:00:40.726Z",
      "errorMessage": "d.included is not iterable\n[GET] \"https://yuanliao.info/t/windows\": <no response> fetch failed (Connect Timeout Error (attempted address: yuanliao.info:443, timeout: 10000ms))\n",
      "id": "150754313479766016",
      "image": "https://yuanliao.info/assets/logo-f9tlxmqd.png",
      "ownerUserId": null,
      "siteUrl": "https://yuanliao.info/t/windows",
      "title": "Windows - 猿料社区",
      "type": "feed",
      "url": "rsshub://yuanliao/windows"
    }
  ],
  "url": "yuanliao.info",
  "view": 0
}
```
