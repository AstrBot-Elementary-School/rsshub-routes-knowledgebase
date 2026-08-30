# E-Hentai - 分类

## Coverage
`index-only`

## Route
- Namespace: `e-hentai`
- Namespace Name: `E-Hentai`
- Route Path: `/e-hentai/category/:category?/:needTorrents?/:needImages?`
- Route Name: `分类`
- Example: `/e-hentai/category/manga`
- URL: `e-hentai.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
参数 **需要输出种子文件** 设置为 `true` `yes` `t` `y` 等值后，RSS 会携带种子文件的路径，以供支持 RSS 的下载工具订阅下载。

同理，参数 **需要显示大图** 启用后，RSS 会携带每项内容中的大图，而不只提供缩略图。

当然，选择 **需要输出种子文件**、**需要显示大图** 后获取内容时间需要更久，同时若指定获取数量过多，可能会出现获取超时错误。此时，可以在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，或直接修改全局的超时参数 `REQUEST_TIMEOUT`（详见文档中的 [其他应用配置](https://docs.rsshub.app/install/#pei-zhi-qi-ta-ying-yong-pei-zhi)）。

以下是一个例子：

选择浏览 [Manga 分类](https://e-hentai.org/manga)，并指定 **不携带种子文件**，**只显示大图**，并只 **输出 5 个**。由于 [Manga 分类](https://e-hentai.org/manga) 的 URL `https://e-hentai.org/manga` 中对应分类字段为 `manga`，所以对应路由为 [`/e-hentai/category/manga/no/yes?limit=5`](https://rsshub.app/e-hentai/category/manga/no/yes?limit=5)
:::

| Doujinshi | Manga | Artist CG | Game CG | Western |
| --------- | ----- | --------- | ------- | ------- |
| doujinshi | manga | artistcg  | gamecg  | western |

| Non-H | Image Set | Cosplay | Asian Porn | Misc | Popular |
| ----- | --------- | ------- | ---------- | ---- | ------- |
| non-h | imageset  | cosplay | asianporn  | misc | popular |

## Parameters
- `category`: 分类，可在对应分类页中找到，默认为首页
- `needTorrents`: 需要输出种子文件，填写 true/yes 表示需要，默认需要
- `needImages`: 需要显示大图，填写 true/yes 表示需要，默认需要


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `e-hentai.org/:category`
  - `e-hentai.org/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n参数 **需要输出种子文件** 设置为 `true` `yes` `t` `y` 等值后，RSS 会携带种子文件的路径，以供支持 RSS 的下载工具订阅下载。\n\n同理，参数 **需要显示大图** 启用后，RSS 会携带每项内容中的大图，而不只提供缩略图。\n\n当然，选择 **需要输出种子文件**、**需要显示大图** 后获取内容时间需要更久，同时若指定获取数量过多，可能会出现获取超时错误。此时，可以在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，或直接修改全局的超时参数 `REQUEST_TIMEOUT`（详见文档中的 [其他应用配置](https://docs.rsshub.app/install/#pei-zhi-qi-ta-ying-yong-pei-zhi)）。\n\n以下是一个例子：\n\n选择浏览 [Manga 分类](https://e-hentai.org/manga)，并指定 **不携带种子文件**，**只显示大图**，并只 **输出 5 个**。由于 [Manga 分类](https://e-hentai.org/manga) 的 URL `https://e-hentai.org/manga` 中对应分类字段为 `manga`，所以对应路由为 [`/e-hentai/category/manga/no/yes?limit=5`](https://rsshub.app/e-hentai/category/manga/no/yes?limit=5)\n:::\n\n| Doujinshi | Manga | Artist CG | Game CG | Western |\n| --------- | ----- | --------- | ------- | ------- |\n| doujinshi | manga | artistcg  | gamecg  | western |\n\n| Non-H | Image Set | Cosplay | Asian Porn | Misc | Popular |\n| ----- | --------- | ------- | ---------- | ---- | ------- |\n| non-h | imageset  | cosplay | asianporn  | misc | popular |",
  "example": "/e-hentai/category/manga",
  "features": {
    "nsfw": true
  },
  "heat": 6,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页中找到，默认为首页",
    "needImages": "需要显示大图，填写 true/yes 表示需要，默认需要",
    "needTorrents": "需要输出种子文件，填写 true/yes 表示需要，默认需要"
  },
  "path": "/category/:category?/:needTorrents?/:needImages?",
  "radar": [
    {
      "source": [
        "e-hentai.org/:category",
        "e-hentai.org/"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "manga - E-Hentai Galleries - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "106841285260128256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/manga",
      "title": "manga - E-Hentai Galleries",
      "type": "feed",
      "url": "rsshub://e-hentai/category/manga"
    },
    {
      "description": "cosplay - E-Hentai Galleries - Powered by RSSHub",
      "errorAt": "2026-08-29T09:31:56.844Z",
      "errorMessage": "n.map is not a function\n",
      "id": "106841534145317888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/cosplay",
      "title": "cosplay - E-Hentai Galleries",
      "type": "feed",
      "url": "rsshub://e-hentai/category/cosplay"
    }
  ]
}
```
