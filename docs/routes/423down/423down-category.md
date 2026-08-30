# 423Down - 423Down

## Coverage
`index-only`

## Route
- Namespace: `423down`
- Namespace Name: `423Down`
- Route Path: `/423down/:category{.+}?`
- Route Name: `423Down`
- Example: `/423down`
- URL: `423down.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [Android - 423Down](https://www.423down.com/apk)，网址为 `https://www.423down.com/apk`。截取 `https://www.423down.com/` 到末尾的部分 `apk` 作为参数填入，此时路由为 [`/423down/apk`](https://rsshub.app/423down/apk)。
:::

#### [安卓软件](https://www.423down.com/apk)

| [安卓软件](https://www.423down.com/apk) |
| --------------------------------------- |
| [apk](https://rsshub.app/423down/apk)   |

#### 电脑软件

| [原创软件](https://www.423down.com/zd423) | [媒体播放](https://www.423down.com/multimedia)      | [网页浏览](https://www.423down.com/browser)   | [图形图像](https://www.423down.com/image) | [聊天软件](https://www.423down.com/im) |
| ----------------------------------------- | --------------------------------------------------- | --------------------------------------------- | ----------------------------------------- | -------------------------------------- |
| [zd423](https://rsshub.app/423down/zd423) | [multimedia](https://rsshub.app/423down/multimedia) | [browser](https://rsshub.app/423down/browser) | [image](https://rsshub.app/423down/image) | [im](https://rsshub.app/423down/im)    |

| [办公软件](https://www.423down.com/work) | [上传下载](https://www.423down.com/down) | [实用软件](https://www.423down.com/softtool)    | [系统辅助](https://www.423down.com/systemsoft)      | [系统必备](https://www.423down.com/systemplus)      |
| ---------------------------------------- | ---------------------------------------- | ----------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| [work](https://rsshub.app/423down/work)  | [down](https://rsshub.app/423down/down)  | [softtool](https://rsshub.app/423down/softtool) | [systemsoft](https://rsshub.app/423down/systemsoft) | [systemplus](https://rsshub.app/423down/systemplus) |

| [安全软件](https://www.423down.com/security)    | [补丁相关](https://www.423down.com/patch) | [硬件相关](https://www.423down.com/hardware)    |
| ----------------------------------------------- | ----------------------------------------- | ----------------------------------------------- |
| [security](https://rsshub.app/423down/security) | [patch](https://rsshub.app/423down/patch) | [hardware](https://rsshub.app/423down/hardware) |

#### 操作系统

| [Windows 11](https://www.423down.com/win11) | [Windows 10](https://www.423down.com/win10) | [Windows 7](https://www.423down.com/win7) | [Windows XP](https://www.423down.com/win7/winxp)    | [WinPE](https://www.423down.com/pe-system)        |
| ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | --------------------------------------------------- | ------------------------------------------------- |
| [win11](https://rsshub.app/423down/win11)   | [win10](https://rsshub.app/423down/win10)   | [win7](https://rsshub.app/423down/win7)   | [win7/winxp](https://rsshub.app/423down/win7/winxp) | [pe-system](https://rsshub.app/423down/pe-system) |

## Parameters
- `category`: 分类，默认为首页，可在对应分类页 URL 中找到


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
  - `423down.com/:category`
  - `423down.com`
### Rule 2
- `title`: `首页`
- `source`:
  - `www.423down.com`
- `target`: `/`
### Rule 3
- `title`: `安卓软件`
- `source`:
  - `www.423down.com/apk`
- `target`: `/apk`
### Rule 4
- `title`: `电脑软件 - 原创软件`
- `source`:
  - `www.423down.com/zd423`
- `target`: `/zd423`
### Rule 5
- `title`: `电脑软件 - 媒体播放`
- `source`:
  - `www.423down.com/multimedia`
- `target`: `/multimedia`
### Rule 6
- `title`: `电脑软件 - 网页浏览`
- `source`:
  - `www.423down.com/browser`
- `target`: `/browser`
### Rule 7
- `title`: `电脑软件 - 图形图像`
- `source`:
  - `www.423down.com/image`
- `target`: `/image`
### Rule 8
- `title`: `电脑软件 - 聊天软件`
- `source`:
  - `www.423down.com/im`
- `target`: `/im`
### Rule 9
- `title`: `电脑软件 - 办公软件`
- `source`:
  - `www.423down.com/work`
- `target`: `/work`
### Rule 10
- `title`: `电脑软件 - 上传下载`
- `source`:
  - `www.423down.com/down`
- `target`: `/down`
### Rule 11
- `title`: `电脑软件 - 实用软件`
- `source`:
  - `www.423down.com/softtool`
- `target`: `/softtool`
### Rule 12
- `title`: `电脑软件 - 系统辅助`
- `source`:
  - `www.423down.com/systemsoft`
- `target`: `/systemsoft`
### Rule 13
- `title`: `电脑软件 - 系统必备`
- `source`:
  - `www.423down.com/systemplus`
- `target`: `/systemplus`
### Rule 14
- `title`: `电脑软件 - 安全软件`
- `source`:
  - `www.423down.com/security`
- `target`: `/security`
### Rule 15
- `title`: `电脑软件 - 补丁相关`
- `source`:
  - `www.423down.com/patch`
- `target`: `/patch`
### Rule 16
- `title`: `电脑软件 - 硬件相关`
- `source`:
  - `www.423down.com/hardware`
- `target`: `/hardware`
### Rule 17
- `title`: `操作系统 - Windows 11`
- `source`:
  - `www.423down.com/win11`
- `target`: `/win11`
### Rule 18
- `title`: `操作系统 - Windows 10`
- `source`:
  - `www.423down.com/win10`
- `target`: `/win10`
### Rule 19
- `title`: `操作系统 - Windows 7`
- `source`:
  - `www.423down.com/win7`
- `target`: `/win7`
### Rule 20
- `title`: `操作系统 - Windows XP`
- `source`:
  - `www.423down.com/win7/winxp`
- `target`: `/win7/winxp`
### Rule 21
- `title`: `操作系统 - WinPE`
- `source`:
  - `www.423down.com/pe-system`
- `target`: `/pe-system`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\n若订阅 [Android - 423Down](https://www.423down.com/apk)，网址为 `https://www.423down.com/apk`。截取 `https://www.423down.com/` 到末尾的部分 `apk` 作为参数填入，此时路由为 [`/423down/apk`](https://rsshub.app/423down/apk)。\n:::\n\n#### [安卓软件](https://www.423down.com/apk)\n\n| [安卓软件](https://www.423down.com/apk) |\n| --------------------------------------- |\n| [apk](https://rsshub.app/423down/apk)   |\n\n#### 电脑软件\n\n| [原创软件](https://www.423down.com/zd423) | [媒体播放](https://www.423down.com/multimedia)      | [网页浏览](https://www.423down.com/browser)   | [图形图像](https://www.423down.com/image) | [聊天软件](https://www.423down.com/im) |\n| ----------------------------------------- | --------------------------------------------------- | --------------------------------------------- | ----------------------------------------- | -------------------------------------- |\n| [zd423](https://rsshub.app/423down/zd423) | [multimedia](https://rsshub.app/423down/multimedia) | [browser](https://rsshub.app/423down/browser) | [image](https://rsshub.app/423down/image) | [im](https://rsshub.app/423down/im)    |\n\n| [办公软件](https://www.423down.com/work) | [上传下载](https://www.423down.com/down) | [实用软件](https://www.423down.com/softtool)    | [系统辅助](https://www.423down.com/systemsoft)      | [系统必备](https://www.423down.com/systemplus)      |\n| ---------------------------------------- | ---------------------------------------- | ----------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |\n| [work](https://rsshub.app/423down/work)  | [down](https://rsshub.app/423down/down)  | [softtool](https://rsshub.app/423down/softtool) | [systemsoft](https://rsshub.app/423down/systemsoft) | [systemplus](https://rsshub.app/423down/systemplus) |\n\n| [安全软件](https://www.423down.com/security)    | [补丁相关](https://www.423down.com/patch) | [硬件相关](https://www.423down.com/hardware)    |\n| ----------------------------------------------- | ----------------------------------------- | ----------------------------------------------- |\n| [security](https://rsshub.app/423down/security) | [patch](https://rsshub.app/423down/patch) | [hardware](https://rsshub.app/423down/hardware) |\n\n#### 操作系统\n\n| [Windows 11](https://www.423down.com/win11) | [Windows 10](https://www.423down.com/win10) | [Windows 7](https://www.423down.com/win7) | [Windows XP](https://www.423down.com/win7/winxp)    | [WinPE](https://www.423down.com/pe-system)        |\n| ------------------------------------------- | ------------------------------------------- | ----------------------------------------- | --------------------------------------------------- | ------------------------------------------------- |\n| [win11](https://rsshub.app/423down/win11)   | [win10](https://rsshub.app/423down/win10)   | [win7](https://rsshub.app/423down/win7)   | [win7/winxp](https://rsshub.app/423down/win7/winxp) | [pe-system](https://rsshub.app/423down/pe-system) |",
  "example": "/423down",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 601,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "423Down",
  "parameters": {
    "category": "分类，默认为首页，可在对应分类页 URL 中找到"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "423down.com/:category",
        "423down.com"
      ]
    },
    {
      "source": [
        "www.423down.com"
      ],
      "target": "/",
      "title": "首页"
    },
    {
      "source": [
        "www.423down.com/apk"
      ],
      "target": "/apk",
      "title": "安卓软件"
    },
    {
      "source": [
        "www.423down.com/zd423"
      ],
      "target": "/zd423",
      "title": "电脑软件 - 原创软件"
    },
    {
      "source": [
        "www.423down.com/multimedia"
      ],
      "target": "/multimedia",
      "title": "电脑软件 - 媒体播放"
    },
    {
      "source": [
        "www.423down.com/browser"
      ],
      "target": "/browser",
      "title": "电脑软件 - 网页浏览"
    },
    {
      "source": [
        "www.423down.com/image"
      ],
      "target": "/image",
      "title": "电脑软件 - 图形图像"
    },
    {
      "source": [
        "www.423down.com/im"
      ],
      "target": "/im",
      "title": "电脑软件 - 聊天软件"
    },
    {
      "source": [
        "www.423down.com/work"
      ],
      "target": "/work",
      "title": "电脑软件 - 办公软件"
    },
    {
      "source": [
        "www.423down.com/down"
      ],
      "target": "/down",
      "title": "电脑软件 - 上传下载"
    },
    {
      "source": [
        "www.423down.com/softtool"
      ],
      "target": "/softtool",
      "title": "电脑软件 - 实用软件"
    },
    {
      "source": [
        "www.423down.com/systemsoft"
      ],
      "target": "/systemsoft",
      "title": "电脑软件 - 系统辅助"
    },
    {
      "source": [
        "www.423down.com/systemplus"
      ],
      "target": "/systemplus",
      "title": "电脑软件 - 系统必备"
    },
    {
      "source": [
        "www.423down.com/security"
      ],
      "target": "/security",
      "title": "电脑软件 - 安全软件"
    },
    {
      "source": [
        "www.423down.com/patch"
      ],
      "target": "/patch",
      "title": "电脑软件 - 补丁相关"
    },
    {
      "source": [
        "www.423down.com/hardware"
      ],
      "target": "/hardware",
      "title": "电脑软件 - 硬件相关"
    },
    {
      "source": [
        "www.423down.com/win11"
      ],
      "target": "/win11",
      "title": "操作系统 - Windows 11"
    },
    {
      "source": [
        "www.423down.com/win10"
      ],
      "target": "/win10",
      "title": "操作系统 - Windows 10"
    },
    {
      "source": [
        "www.423down.com/win7"
      ],
      "target": "/win7",
      "title": "操作系统 - Windows 7"
    },
    {
      "source": [
        "www.423down.com/win7/winxp"
      ],
      "target": "/win7/winxp",
      "title": "操作系统 - Windows XP"
    },
    {
      "source": [
        "www.423down.com/pe-system"
      ],
      "target": "/pe-system",
      "title": "操作系统 - WinPE"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "423Down - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55913439252283392",
      "image": "https://www.423down.com/wp-content/themes/D7/img/423Down.png",
      "ownerUserId": null,
      "siteUrl": "https://www.423down.com/",
      "title": "423Down",
      "type": "feed",
      "url": "rsshub://423down"
    },
    {
      "description": "安卓软件下载_Android应用APK下载 (破解版/去广告/纯净版) - 423Down - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68887846273620992",
      "image": "https://www.423down.com/wp-content/themes/D7/img/423Down.png",
      "ownerUserId": null,
      "siteUrl": "https://www.423down.com/apk",
      "title": "Android - 423Down",
      "type": "feed",
      "url": "rsshub://423down/apk"
    }
  ],
  "url": "423down.com"
}
```
