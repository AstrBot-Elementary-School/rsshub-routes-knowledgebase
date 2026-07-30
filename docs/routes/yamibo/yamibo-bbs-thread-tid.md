# 百合会 - BBS - 讨论串

## Coverage
`index-only`

## Route
- Namespace: `yamibo`
- Namespace Name: `百合会`
- Route Path: `/yamibo/bbs/thread/:tid`
- Route Name: `BBS - 讨论串`
- Example: `/yamibo/bbs/thread/541914`
- URL: `yamibo.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `bbs/thread.ts`
- Source Module: `_None_`

## Description
::: warning
百合会 BBS 访问部分讨论串需要用户登录认证，请参考配置说明
:::

## Parameters
- `tid`: 讨论串 id，可从URL中提取。https://bbs.yamibo.com/forum.php?mod=viewthread&tid=xxxx中的xxx或https://bbs.yamibo.com/thread-aaa-b-c.html中的aaa部分即为tid值


## Features
- `antiCrawler`: true
- `requireConfig`: [{"description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_saltkey 值", "name": "YAMIBO_SALT", "optional": true}, {"description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_auth 值", "name": "YAMIBO_AUTH", "optional": true}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: warning\n百合会 BBS 访问部分讨论串需要用户登录认证，请参考配置说明\n:::",
  "example": "/yamibo/bbs/thread/541914",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_saltkey 值",
        "name": "YAMIBO_SALT",
        "optional": true
      },
      {
        "description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_auth 值",
        "name": "YAMIBO_AUTH",
        "optional": true
      }
    ]
  },
  "heat": 28,
  "location": "bbs/thread.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "BBS - 讨论串",
  "parameters": {
    "tid": "讨论串 id，可从URL中提取。https://bbs.yamibo.com/forum.php?mod=viewthread&tid=xxxx中的xxx或https://bbs.yamibo.com/thread-aaa-b-c.html中的aaa部分即为tid值"
  },
  "path": "/bbs/thread/:tid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "[个人翻译][长篇][羽田宇佐]一周一次买下同班同学的那些事（2026.6.7更新至第419话） - 轻小说/译文区 - Powered by RSSHub",
      "errorAt": "2026-06-09T06:57:01.888Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "99377084384904192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.yamibo.com/forum.php?mod=viewthread&tid=521519&ordertype=1",
      "title": "[个人翻译][长篇][羽田宇佐]一周一次买下同班同学的那些事（2026.6.7更新至第419话） - 轻小说/译文区",
      "type": "feed",
      "url": "rsshub://yamibo/bbs/thread/521519"
    },
    {
      "description": "百合小说生肉安利专楼 - 轻小说/译文区 - Powered by RSSHub",
      "errorAt": "2026-06-08T21:31:45.653Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "97881720287716352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.yamibo.com/forum.php?mod=viewthread&tid=535989&ordertype=1",
      "title": "百合小说生肉安利专楼 - 轻小说/译文区",
      "type": "feed",
      "url": "rsshub://yamibo/bbs/thread/535989"
    }
  ]
}
```
