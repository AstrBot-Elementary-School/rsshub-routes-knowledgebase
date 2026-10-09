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
MTProto connections can use a SOCKS4/5 `PROXY_URI` (for example, `socks5://127.0.0.1:1080`) or the dedicated `TELEGRAM_PROXY_HOST`, `TELEGRAM_PROXY_PORT`, and `TELEGRAM_PROXY_SECRET` MTProxy settings, which take precedence. HTTP proxies only apply to the public web feed; use a SOCKS or MTProxy endpoint for authenticated MTProto feeds.

When a reverse proxy removes a public URL prefix (for example, `/rss`), set its `X-Forwarded-Prefix` request header to that prefix so Telegram media links include it. Access-control `key` and `code` parameters are preserved in these media links.
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
| includeTelegraph       | Expand public telegra.ph article links into their full content          | 0/1/true/false                                     | false        |
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
  "description": "::: tip\nDue to Telegram restrictions, some channels involving pornography, copyright, and politics cannot be subscribed. You can confirm by visiting `https://t.me/s/:username`, it's recommended to deploy your own instance with telegram api configs (create your telegram application via `https://core.telegram.org/api/obtaining_api_id`, run this command `node ./lib/routes/telegram/scripts/get-telegram-session.mjs` to get `TELEGRAM_SESSION` and set it as Environment Variable).\nMTProto connections can use a SOCKS4/5 `PROXY_URI` (for example, `socks5://127.0.0.1:1080`) or the dedicated `TELEGRAM_PROXY_HOST`, `TELEGRAM_PROXY_PORT`, and `TELEGRAM_PROXY_SECRET` MTProxy settings, which take precedence. HTTP proxies only apply to the public web feed; use a SOCKS or MTProxy endpoint for authenticated MTProto feeds.\n\nWhen a reverse proxy removes a public URL prefix (for example, `/rss`), set its `X-Forwarded-Prefix` request header to that prefix so Telegram media links include it. Access-control `key` and `code` parameters are preserved in these media links.\n:::",
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
  "heat": 313421,
  "location": "channel.ts",
  "maintainers": [
    "DIYgod",
    "Rongronggg9",
    "synchrone",
    "pseudoyu"
  ],
  "name": "Channel",
  "parameters": {
    "routeParams": "extra parameters, see the table below\n| Key                    | Description                                                           | Accepts                                            | Defaults to  |\n| :--------------------: | :-------------------------------------------------------------------: | :------------------------------------------------: | :----------: |\n| showLinkPreview        | Show the link preview from Telegram                                   | 0/1/true/false                                     | true         |\n| showViaBot             | For messages sent via bot, show the bot                               | 0/1/true/false                                     | true         |\n| showReplyTo            | For reply messages, show the target of the reply                      | 0/1/true/false                                     | true         |\n| showFwdFrom            | For forwarded messages, show the forwarding source                    | 0/1/true/false                                     | true         |\n| showFwdFromAuthor      | For forwarded messages, show the author of the forwarding source      | 0/1/true/false                                     | true         |\n| includeTelegraph       | Expand public telegra.ph article links into their full content          | 0/1/true/false                                     | false        |\n| showInlineButtons      | Show inline buttons                                                   | 0/1/true/false                                     | false        |\n| showMediaTagInTitle    | Show media tags in the title                                          | 0/1/true/false                                     | true         |\n| showMediaTagAsEmoji    | Show media tags as emoji                                              | 0/1/true/false                                     | true         |\n| showHashtagAsHyperlink | Show hashtags as hyperlinks (`https://t.me/s/channel?q=%23hashtag`) | 0/1/true/false                                     | true         |\n| includeFwd             | Include forwarded messages                                            | 0/1/true/false                                     | true         |\n| includeReply           | Include reply messages                                                | 0/1/true/false                                     | true         |\n| includeServiceMsg      | Include service messages (e.g. message pinned, channel photo updated) | 0/1/true/false                                     | true         |\n| includeUnsupportedMsg  | Include messages unsupported by t.me                                  | 0/1/true/false                                     | false        |\n| searchQuery            | search query                                                          | keywords; replace `#hashtag` with `%23hashtag` | (no keyword) |\n\nSpecify different option values than default values can meet different needs, URL\n\n```\nhttps://rsshub.app/telegram/channel/NewlearnerChannel/showLinkPreview=0&showViaBot=0&showReplyTo=0&showFwdFrom=0&showFwdFromAuthor=0&showInlineButtons=0&showMediaTagInTitle=1&showMediaTagAsEmoji=1&includeFwd=0&includeReply=1&includeServiceMsg=0&includeUnsupportedMsg=0\n```\n\ngenerates an RSS without any link previews and annoying metadata, with emoji media tags in the title, without forwarded messages (but with reply messages), and without messages you don't care about (service messages and unsupported messages), for people who prefer pure subscriptions.\n\nFor backward compatibility reasons, invalid `routeParams` will be treated as `searchQuery` .\n",
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
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Founder of Telegram. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55779617166007296",
      "image": "https://cdn4.telesco.pe/file/aUZ3BefUgA2QivoBozQmSj0Avf_hHr5l4hzX7J0a62EKqaZcHXqhh2CkPlbXY38HH3TB7cvZmfHYAgejvLOaq4uiSuUIFzkMqmcAcbSbeH-wDl9eCRPvF5aEIws31OL4aUiXWTs7I8WmZwLF4W575PvbcAkKjPMSPU98hOHxGVyn9-Sxw2wX56BahUaZ14MuLCw4Aakq4xg1ICb9a6brXtzKKYhfnS8-UKuA32HAg_FRz6VZdw9tyyeLca_-L-MYczU9bZCVJgEpic3XN8APIimw2XpwVdhG8iJPV0gUgj_RIaU9D_bHhLKzAeBPMRh0RqPYvd4PNXiifX0mhYziww.jpg",
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/durov",
      "title": "Pavel Durov - Telegram Channel",
      "type": "feed",
      "url": "rsshub://telegram/channel/durov"
    },
    {
      "description": "本群组主要分享白嫖机场、白嫖资源、白嫖线报、以及存放一些信息，嫖友聚居地哦频道的灌水群https://t.me/anranbpbbs需要真实邮箱怎么办对于需要真实邮箱验证的，大家可以下载手机版的网易邮箱大师，可以不限量注册163的邮箱各种超低价会员：Anran杂货铺， 优酷月仅需3元，百度网盘svip 1元起，52bp.icu阿里网盘资源搜索：公众号：彳亍说，发送 阿里 资源名称 即可百度网盘、迅雷、优酷会员分享：小程序：彳亍说小屋测试 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65367894677815296",
      "image": "https://cdn5.telesco.pe/file/pC-XXeR7wW-drQ6oMiWvdpKh30Eoj0eoVfNDaKVRx9dcV9K027SpC80q_73bqd0_XNDxJp0FAPQA_HPoZtxk0IFMbgz2HAp4iHZheWZRga85qqPEiPQ9FYGDE1EHRfKygXbDM4GEg8snVkDOEs1WhPO42o7_4ce9A1Nm6c6nWfBbtcDe--ykB7J8u-Ev5hzYS9eXe2_eR2EQUUTzErQhn87nw_6-5vGagAWgIkfm2QxCIouRjS5L0kG19mBBFpauuacbG-ePYy5a7C4yCUTjTUIiIkMNWhAjsEYf3_OA382W8qe6X7AOiQUNK9gsM4e4FDF19kFzYztlS4SEXcGUmQ.jpg",
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
