# 知乎 - xhu - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/people/activities/:hexId`
- Route Name: `xhu - 用户动态`
- Example: `/zhihu/xhu/people/activities/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/activities.ts`
- Source Module: `_None_`

## Description
[xhu](https://github.com/REToys/xhu)

::: tip
用户的 16 进制 id 获取方式：

1. 可以通过 RSSHub Radar 扩展获取；
2. 或者在用户主页打开 F12 控制台，执行以下代码：`console.log(/"id":"([0-9a-f]*?)","urlToken"/.exec(document.getElementById('js-initialData').innerHTML)[1]);` 即可获取用户的 16 进制 id。

:::

## Parameters
- `hexId`: 用户的 16 进制 id，获取方式见下方说明


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
  - `www.zhihu.com/people/:id`
- `target`: `/people/activities/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "[xhu](https://github.com/REToys/xhu)\n\n::: tip\n用户的 16 进制 id 获取方式：\n\n1. 可以通过 RSSHub Radar 扩展获取；\n2. 或者在用户主页打开 F12 控制台，执行以下代码：`console.log(/\"id\":\"([0-9a-f]*?)\",\"urlToken\"/.exec(document.getElementById('js-initialData').innerHTML)[1]);` 即可获取用户的 16 进制 id。\n\n:::",
  "example": "/zhihu/xhu/people/activities/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 117,
  "location": "xhu/activities.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 用户动态",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式见下方说明"
  },
  "path": "/xhu/people/activities/:hexId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id"
      ],
      "target": "/people/activities/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "一个前端，Vue / Vite 作者。 - Powered by RSSHub",
      "errorAt": "2025-06-25T02:28:39.732Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "56350514062587904",
      "image": "https://picx.zhimg.com/7be980a0f_l.jpg?source=5a24d060&needBackground=1",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/cfdec6226ece879d2571fbc274372e9f",
      "title": "尤雨溪的知乎动态",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/activities/cfdec6226ece879d2571fbc274372e9f"
    },
    {
      "description": "有趣的AI&前沿科技→_→ 公众号：QbitAI - Powered by RSSHub",
      "errorAt": "2025-03-27T07:51:19.364Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "75439306757532679",
      "image": "https://picx.zhimg.com/v2-ca6e7ffc10a0d10edbae635cee82d007_l.jpg?source=5a24d060&needBackground=1",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/36f69162230003d316d0b8a6d8da20ba",
      "title": "量子位的知乎动态",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/activities/36f69162230003d316d0b8a6d8da20ba"
    }
  ]
}
```
