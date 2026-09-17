# South Plus - 论坛帖子

## Coverage
`index-only`

## Route
- Namespace: `south-plus`
- Namespace Name: `South Plus`
- Route Path: `/south-plus/forum/:fid?`
- Route Name: `论坛帖子`
- Example: `/south-plus/forum/8`
- URL: `south-plus.net`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `NicholasYZ`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
::: tip 常用版块 ID

| fid | 版块名称 | 需要登录 |
| --- | -------- | :------: |
| 48  | 询问求物 |    是    |
| 8   | ACG 交流 |    否    |
| 12  | 轻小说   |    是    |
| 9   | 茶馆     |    是    |
| 201 | COSPLAY  |    是    |
| 6   | 游戏资源 |    是    |
| 5   | 实用漫画 |    是    |
| 4   | 实用动画 |    是    |
| 128 | 同人音声 |    是    |
| 208 | AI 交流  |    是    |

:::

::: tip Cookie 示例

```
eb9e6_winduser=XXXX...XXXX%3D%3D; eb9e6_cknum=YYYY...YYYY%3D; eb9e6_ck_info=%2F%09; cf_clearance=ZZZZ...ZZZZ; eb9e6_lastpos=other; eb9e6_ol_offset=123456; eb9e6_readlog=%2C...; eb9e6_threadlog=%2C...; eb9e6_lastvisit=...; peacemaker=1
```

`eb9e6_winduser` 和 `eb9e6_cknum` 是必需的认证 cookie，其余可选。
:::

::: tip UA 说明
South Plus 服务器会校验 Cookie 与浏览器 User-Agent 的绑定关系。Cookie 仅在登录时使用的浏览器版本下有效，不同版本或不同平台的 UA 均会被拒绝。

如需更换 Cookie，请同时设置 `SOUTHPLUS_UA` 为对应浏览器的 UA 字符串。未设置时 RSSHub 会自动生成随机的浏览器 UA。

如果 Cookie 是通过代理获取的，需设置 RSSHub 全局环境变量 `PROXY_URI`（如 `http://host:port`），否则服务器会拒绝认证。
:::
:::

## Parameters
- `fid`: 论坛版块 ID，默认为 8（ACG交流）。可在 thread.php?fid-XXX.html 中找到。常用 fid 见下方说明


## Features
- `requireConfig`: [{"description": "登录 Cookie，格式为分号+空格分隔的 key=value 对。核心字段：eb9e6_winduser（认证令牌）、eb9e6_cknum（会话校验）。从浏览器登录后导出完整 cookie 字符串即可。", "name": "SOUTHPLUS_COOKIE", "optional": true}, {"description": "浏览器 User-Agent，需与获取 Cookie 时使用的浏览器版本完全一致。可从浏览器 F12 → Network → 请求头中复制。未设置时由 RSSHub 自动生成随机浏览器 UA。", "name": "SOUTHPLUS_UA", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `south-plus.net/thread.php`
  - `snow-plus.net/thread.php`
- `target`: `/forum/:fid`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip 常用版块 ID\n\n| fid | 版块名称 | 需要登录 |\n| --- | -------- | :------: |\n| 48  | 询问求物 |    是    |\n| 8   | ACG 交流 |    否    |\n| 12  | 轻小说   |    是    |\n| 9   | 茶馆     |    是    |\n| 201 | COSPLAY  |    是    |\n| 6   | 游戏资源 |    是    |\n| 5   | 实用漫画 |    是    |\n| 4   | 实用动画 |    是    |\n| 128 | 同人音声 |    是    |\n| 208 | AI 交流  |    是    |\n\n:::\n\n::: tip Cookie 示例\n\n```\neb9e6_winduser=XXXX...XXXX%3D%3D; eb9e6_cknum=YYYY...YYYY%3D; eb9e6_ck_info=%2F%09; cf_clearance=ZZZZ...ZZZZ; eb9e6_lastpos=other; eb9e6_ol_offset=123456; eb9e6_readlog=%2C...; eb9e6_threadlog=%2C...; eb9e6_lastvisit=...; peacemaker=1\n```\n\n`eb9e6_winduser` 和 `eb9e6_cknum` 是必需的认证 cookie，其余可选。\n:::\n\n::: tip UA 说明\nSouth Plus 服务器会校验 Cookie 与浏览器 User-Agent 的绑定关系。Cookie 仅在登录时使用的浏览器版本下有效，不同版本或不同平台的 UA 均会被拒绝。\n\n如需更换 Cookie，请同时设置 `SOUTHPLUS_UA` 为对应浏览器的 UA 字符串。未设置时 RSSHub 会自动生成随机的浏览器 UA。\n\n如果 Cookie 是通过代理获取的，需设置 RSSHub 全局环境变量 `PROXY_URI`（如 `http://host:port`），否则服务器会拒绝认证。\n:::\n:::",
  "example": "/south-plus/forum/8",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "登录 Cookie，格式为分号+空格分隔的 key=value 对。核心字段：eb9e6_winduser（认证令牌）、eb9e6_cknum（会话校验）。从浏览器登录后导出完整 cookie 字符串即可。",
        "name": "SOUTHPLUS_COOKIE",
        "optional": true
      },
      {
        "description": "浏览器 User-Agent，需与获取 Cookie 时使用的浏览器版本完全一致。可从浏览器 F12 → Network → 请求头中复制。未设置时由 RSSHub 自动生成随机浏览器 UA。",
        "name": "SOUTHPLUS_UA",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "NicholasYZ"
  ],
  "name": "论坛帖子",
  "parameters": {
    "fid": "论坛版块 ID，默认为 8（ACG交流）。可在 thread.php?fid-XXX.html 中找到。常用 fid 见下方说明"
  },
  "path": "/forum/:fid?",
  "radar": [
    {
      "source": [
        "south-plus.net/thread.php",
        "snow-plus.net/thread.php"
      ],
      "target": "/forum/:fid"
    }
  ],
  "topFeeds": []
}
```
