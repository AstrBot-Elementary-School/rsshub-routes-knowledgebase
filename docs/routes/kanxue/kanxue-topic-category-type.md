# 看雪 - 论坛

## Coverage
`index-only`

## Route
- Namespace: `kanxue`
- Namespace Name: `看雪`
- Route Path: `/kanxue/topic/:category?/:type?`
- Route Name: `论坛`
- Example: `/kanxue/topic/android/digest`
- URL: `kanxue.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `renzhexigua`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 版块           | category  |
| -------------- | --------- |
| 智能设备       | iot       |
| Android 安全   | android   |
| iOS 安全       | ios       |
| HarmonyOS 安全 | harmonyos |
| 软件逆向       | re        |
| 编程技术       | coding    |
| 加壳脱壳       | unpack    |
| 密码应用       | crypto    |
| 二进制漏洞     | vuln      |
| CTF 对抗       | ctf       |
| Pwn            | pwn       |
| WEB 安全       | web       |
| 茶余饭后       | chat      |
| 极客空间       | geekzone  |
| 外文翻译       | translate |
| 全站           | all       |

| 类型     | type   |
| -------- | ------ |
| 最新主题 | latest |
| 精华主题 | digest |

## Parameters
- `category`: 版块, 缺省为`all`
- `type`: 类型, 缺省为`latest`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 版块           | category  |\n| -------------- | --------- |\n| 智能设备       | iot       |\n| Android 安全   | android   |\n| iOS 安全       | ios       |\n| HarmonyOS 安全 | harmonyos |\n| 软件逆向       | re        |\n| 编程技术       | coding    |\n| 加壳脱壳       | unpack    |\n| 密码应用       | crypto    |\n| 二进制漏洞     | vuln      |\n| CTF 对抗       | ctf       |\n| Pwn            | pwn       |\n| WEB 安全       | web       |\n| 茶余饭后       | chat      |\n| 极客空间       | geekzone  |\n| 外文翻译       | translate |\n| 全站           | all       |\n\n| 类型     | type   |\n| -------- | ------ |\n| 最新主题 | latest |\n| 精华主题 | digest |",
  "example": "/kanxue/topic/android/digest",
  "heat": 493,
  "location": "topic.ts",
  "maintainers": [
    "renzhexigua"
  ],
  "name": "论坛",
  "parameters": {
    "category": "版块, 缺省为`all`",
    "type": "类型, 缺省为`latest`"
  },
  "path": "/topic/:category?/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "看雪论坛最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56202182890270720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.kanxue.com/new-tid.htm",
      "title": "看雪论坛最新主题",
      "type": "feed",
      "url": "rsshub://kanxue/topic"
    },
    {
      "description": "看雪论坛精华主题 - Android安全 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59422035037245440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.kanxue.com/forum-161-1.htm?digest=1",
      "title": "看雪论坛精华主题 - Android安全",
      "type": "feed",
      "url": "rsshub://kanxue/topic/android/digest"
    }
  ]
}
```
