# Telegram - Channel

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/telegram/channel/:username/:routeParams?`
- Route Name: `Channel`
- Example: `/telegram/channel/awesomeRSSHub`
- URL: `t.me`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, Rongronggg9, synchrone, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
::: tip
Due to Telegram restrictions, some channels involving pornography, copyright, and politics cannot be subscribed. You can confirm by visiting `https://t.me/s/:username`, it's recommended to deploy your own instance with telegram api configs (create your telegram application via `https://core.telegram.org/api/obtaining_api_id`, run this command `node ./lib/routes/telegram/scripts/get-telegram-session.mjs` to get `TELEGRAM_SESSION` and set it as Environment Variable).
:::

## Parameters
- `username`: channel username
- `routeParams`: extra parameters, see the table below
| Key                    | Description                                                           | Accepts                                            | Defaults to  |
| :--------------------: | :-------------------------------------------------------------------: | :------------------------------------------------: | :----------: |
| showLinkPreview        | Show the link preview from Telegram                                   | 0/1/true/false                                     | true         |
| showViaBot             | For messages sent via bot, show the bot                               | 0/1/true/false                                     | true         |
| showReplyTo            | For reply messages, show the target of the reply                      | 0/1/true/false                                     | true         |
| showFwdFrom            | For forwarded messages, show the forwarding source                    | 0/1/true/false                                     | true         |
| showFwdFromAuthor      | For forwarded messages, show the author of the forwarding source      | 0/1/true/false                                     | true         |
| showInlineButtons      | Show inline buttons                                                   | 0/1/true/false                                     | false        |
| showMediaTagInTitle    | Show media tags in the title                                          | 0/1/true/false                                     | true         |
| showMediaTagAsEmoji    | Show media tags as emoji                                              | 0/1/true/false                                     | true         |
| showHashtagAsHyperlink | Show hashtags as hyperlinks (`https://t.me/s/channel?q=%23hashtag`) | 0/1/true/false                                     | true         |
| includeFwd             | Include forwarded messages                                            | 0/1/true/false                                     | true         |
| includeReply           | Include reply messages                                                | 0/1/true/false                                     | true         |
| includeServiceMsg      | Include service messages (e.g. message pinned, channel photo updated) | 0/1/true/false                                     | true         |
| includeUnsupportedMsg  | Include messages unsupported by t.me                                  | 0/1/true/false                                     | false        |
| searchQuery            | search query                                                          | keywords; replace `#hashtag` with `%23hashtag` | (no keyword) |

Specify different option values than default values can meet different needs, URL

```
https://rsshub.app/telegram/channel/NewlearnerChannel/showLinkPreview=0&showViaBot=0&showReplyTo=0&showFwdFrom=0&showFwdFromAuthor=0&showInlineButtons=0&showMediaTagInTitle=1&showMediaTagAsEmoji=1&includeFwd=0&includeReply=1&includeServiceMsg=0&includeUnsupportedMsg=0
```

generates an RSS without any link previews and annoying metadata, with emoji media tags in the title, without forwarded messages (but with reply messages), and without messages you don't care about (service messages and unsupported messages), for people who prefer pure subscriptions.

For backward compatibility reasons, invalid `routeParams` will be treated as `searchQuery` .


## Features
- `requireConfig`: [{"description": "Telegram API Authentication", "name": "TELEGRAM_SESSION", "optional": true}, {"description": "Telegram API ID", "name": "TELEGRAM_API_ID", "optional": true}, {"description": "Telegram API Hash", "name": "TELEGRAM_API_HASH", "optional": true}, {"description": "Telegram Max Concurrent Downloads", "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS", "optional": true}, {"description": "Telegram Proxy Host", "name": "TELEGRAM_PROXY_HOST", "optional": true}, {"description": "Telegram Proxy Port", "name": "TELEGRAM_PROXY_PORT", "optional": true}, {"description": "Telegram Proxy Secret", "name": "TELEGRAM_PROXY_SECRET", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `t.me/s/:username`
- `target`: `/channel/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "::: tip\nDue to Telegram restrictions, some channels involving pornography, copyright, and politics cannot be subscribed. You can confirm by visiting `https://t.me/s/:username`, it's recommended to deploy your own instance with telegram api configs (create your telegram application via `https://core.telegram.org/api/obtaining_api_id`, run this command `node ./lib/routes/telegram/scripts/get-telegram-session.mjs` to get `TELEGRAM_SESSION` and set it as Environment Variable).\n:::",
  "example": "/telegram/channel/awesomeRSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Telegram API Authentication",
        "name": "TELEGRAM_SESSION",
        "optional": true
      },
      {
        "description": "Telegram API ID",
        "name": "TELEGRAM_API_ID",
        "optional": true
      },
      {
        "description": "Telegram API Hash",
        "name": "TELEGRAM_API_HASH",
        "optional": true
      },
      {
        "description": "Telegram Max Concurrent Downloads",
        "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS",
        "optional": true
      },
      {
        "description": "Telegram Proxy Host",
        "name": "TELEGRAM_PROXY_HOST",
        "optional": true
      },
      {
        "description": "Telegram Proxy Port",
        "name": "TELEGRAM_PROXY_PORT",
        "optional": true
      },
      {
        "description": "Telegram Proxy Secret",
        "name": "TELEGRAM_PROXY_SECRET",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 302387,
  "location": "channel.ts",
  "maintainers": [
    "DIYgod",
    "Rongronggg9",
    "synchrone",
    "pseudoyu"
  ],
  "name": "Channel",
  "parameters": {
    "routeParams": "extra parameters, see the table below\n| Key                    | Description                                                           | Accepts                                            | Defaults to  |\n| :--------------------: | :-------------------------------------------------------------------: | :------------------------------------------------: | :----------: |\n| showLinkPreview        | Show the link preview from Telegram                                   | 0/1/true/false                                     | true         |\n| showViaBot             | For messages sent via bot, show the bot                               | 0/1/true/false                                     | true         |\n| showReplyTo            | For reply messages, show the target of the reply                      | 0/1/true/false                                     | true         |\n| showFwdFrom            | For forwarded messages, show the forwarding source                    | 0/1/true/false                                     | true         |\n| showFwdFromAuthor      | For forwarded messages, show the author of the forwarding source      | 0/1/true/false                                     | true         |\n| showInlineButtons      | Show inline buttons                                                   | 0/1/true/false                                     | false        |\n| showMediaTagInTitle    | Show media tags in the title                                          | 0/1/true/false                                     | true         |\n| showMediaTagAsEmoji    | Show media tags as emoji                                              | 0/1/true/false                                     | true         |\n| showHashtagAsHyperlink | Show hashtags as hyperlinks (`https://t.me/s/channel?q=%23hashtag`) | 0/1/true/false                                     | true         |\n| includeFwd             | Include forwarded messages                                            | 0/1/true/false                                     | true         |\n| includeReply           | Include reply messages                                                | 0/1/true/false                                     | true         |\n| includeServiceMsg      | Include service messages (e.g. message pinned, channel photo updated) | 0/1/true/false                                     | true         |\n| includeUnsupportedMsg  | Include messages unsupported by t.me                                  | 0/1/true/false                                     | false        |\n| searchQuery            | search query                                                          | keywords; replace `#hashtag` with `%23hashtag` | (no keyword) |\n\nSpecify different option values than default values can meet different needs, URL\n\n```\nhttps://rsshub.app/telegram/channel/NewlearnerChannel/showLinkPreview=0&showViaBot=0&showReplyTo=0&showFwdFrom=0&showFwdFromAuthor=0&showInlineButtons=0&showMediaTagInTitle=1&showMediaTagAsEmoji=1&includeFwd=0&includeReply=1&includeServiceMsg=0&includeUnsupportedMsg=0\n```\n\ngenerates an RSS without any link previews and annoying metadata, with emoji media tags in the title, without forwarded messages (but with reply messages), and without messages you don't care about (service messages and unsupported messages), for people who prefer pure subscriptions.\n\nFor backward compatibility reasons, invalid `routeParams` will be treated as `searchQuery` .\n",
    "username": "channel username"
  },
  "path": "/channel/:username/:routeParams?",
  "radar": [
    {
      "source": [
        "t.me/s/:username"
      ],
      "target": "/channel/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Founder of Telegram. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55779617166007296",
      "image": "https://cdn4.telesco.pe/file/pWBOiSk4459119GYOHx2ImFvS2vQA9MNjdFXa5beC_XpwHGMA25SDmsRIKtebsaFDzu8a1tNfxlL4ZlLgs_BHnTzgoFXufojmUT9NO6Mwqoc6PKK-62Fa9gOHtPEfCjChzUjYAGQdfMLWmrHqg8Rfl_6-ONhH1biHpepbunSRpyiYiRAIM_EbEtd8ge17ayU6FS0_bqwD74gaberfxHPbudbo5yTiJaB8FFaJuNY1cZhQMRcFBt7YT0jgpOWmAKWOAB_NMNB_Y4Qp2wzASS4fK01_zehP5Pt66zzj9i7Iw5A7oAmOa5D5au2Rh2z8bjRBj1gUxwZxfpK40Yz3J-Irg.jpg",
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/durov",
      "title": "Pavel Durov - Telegram Channel",
      "type": "feed",
      "url": "rsshub://telegram/channel/durov"
    },
    {
      "description": "本群组主要分享白嫖机场、白嫖资源、白嫖线报、以及存放一些信息，嫖友聚居地哦频道的灌水群https://t.me/anranbpbbs需要真实邮箱怎么办对于需要真实邮箱验证的，大家可以下载手机版的网易邮箱大师，可以不限量注册163的邮箱各种超低价会员：Anran杂货铺， 优酷月仅需3元，百度网盘svip 1元起，52bp.icu阿里网盘资源搜索：公众号：彳亍说，发送 阿里 资源名称 即可百度网盘、迅雷、优酷会员分享：小程序：彳亍说小屋测试 - Powered by RSSHub",
      "errorAt": "2026-08-23T14:43:48.810Z",
      "errorMessage": "200 ",
      "id": "65367894677815296",
      "image": "https://cdn5.telesco.pe/file/qmxa3MAOjTpQK6XMZA6aNE3eiO2MgLC5-E6--LZcsh1FDFeHd02McYhiX4fg_7oB_JPVAl1OwSN6agWVnHA8HzhVXF_12Z-1MX7pcgkdCoDnL5FZJ9ZQJmQ9z0hXcSJ-nTy_vNL14WlOZoahKTYpnU03m0YoZ5p2rsVxK_7icdyAJVOT9tbzSneeZsOvOU_rRv-7R_l4As7sI-o3MCdPFSbU1CclAcBHRsvTIgnPq5jZVWjz9kK0ndsW6xS92tHhNKICPBBVGItD94Nxvw4WDQ9upZKfRl4cwkUMPa9r5Krm11FkZury0AFJRx79_P5gCmhomZbxcGW_lwi9bN5luw.jpg",
      "ownerUserId": "181859263110382592",
      "siteUrl": "https://t.me/s/anranbp",
      "title": "我爱白嫖 - Telegram Channel",
      "type": "feed",
      "url": "rsshub://telegram/channel/anranbp"
    }
  ],
  "view": 1
}
```
