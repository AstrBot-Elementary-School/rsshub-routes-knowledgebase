# E-Hentai - 搜索

## Coverage
`index-only`

## Route
- Namespace: `e-hentai`
- Namespace Name: `E-Hentai`
- Route Path: `/e-hentai/search/:keyword?/:needTorrents?/:needImages?`
- Route Name: `搜索`
- Example: `/e-hentai/search/f_search=haha`
- URL: `e-hentai.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
::: tip
参数 **需要输出种子文件**、**需要显示大图** 的说明同上，以下是一个例子：

选择浏览 [f\_search=cosplay 搜索结果](https://e-hentai.org/?f_search=cosplay)，并指定 **携带种子文件**，且 **显示大图**。由于 [f\_search=cosplay 搜索结果](https://e-hentai.org/?f_search=cosplay) 的 URL `https://e-hentai.org/?f_search=cosplay` 中对应关键字字段为 `?` 后的 `f_search=cosplay`，所以对应路由为 [`/e-hentai/search/f_search=cosplay/y/y`](https://rsshub.app/e-hentai/search/f_search=cosplay/y/y)
:::

## Parameters
- `keyword`: 关键字，可以在搜索结果页的 URL 中找到，默认为首页
- `needTorrents`: 需要输出种子文件，填写 true/yes 表示需要，默认需要
- `needImages`: 需要显示大图，填写 true/yes 表示需要，默认需要


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `e-hentai.org/:keyword`
  - `e-hentai.org/`
- `target`: `/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n参数 **需要输出种子文件**、**需要显示大图** 的说明同上，以下是一个例子：\n\n选择浏览 [f\\_search=cosplay 搜索结果](https://e-hentai.org/?f_search=cosplay)，并指定 **携带种子文件**，且 **显示大图**。由于 [f\\_search=cosplay 搜索结果](https://e-hentai.org/?f_search=cosplay) 的 URL `https://e-hentai.org/?f_search=cosplay` 中对应关键字字段为 `?` 后的 `f_search=cosplay`，所以对应路由为 [`/e-hentai/search/f_search=cosplay/y/y`](https://rsshub.app/e-hentai/search/f_search=cosplay/y/y)\n:::",
  "example": "/e-hentai/search/f_search=haha",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键字，可以在搜索结果页的 URL 中找到，默认为首页",
    "needImages": "需要显示大图，填写 true/yes 表示需要，默认需要",
    "needTorrents": "需要输出种子文件，填写 true/yes 表示需要，默认需要"
  },
  "path": "/search/:keyword?/:needTorrents?/:needImages?",
  "radar": [
    {
      "source": [
        "e-hentai.org/:keyword",
        "e-hentai.org/"
      ],
      "target": "/search/:keyword"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
