# E-Hentai - 标签

## Coverage
`index-only`

## Route
- Namespace: `e-hentai`
- Namespace Name: `E-Hentai`
- Route Path: `/e-hentai/tag/:tag?/:needTorrents?/:needImages?`
- Route Name: `标签`
- Example: `/e-hentai/tag/language:chinese`
- URL: `e-hentai.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
::: tip
参数 **需要输出种子文件**、**需要显示大图** 的说明同上，以下是一个例子：

选择浏览 [language:chinese 标签](https://e-hentai.org/tag/language:chinese)，并指定 **携带种子文件**，**不显示大图**。由于 [language:chinese 标签](https://e-hentai.org/tag/language:chinese) 的 URL `https://e-hentai.org/tag/language:chinese` 中对应标签字段为 `language:chinese`，所以对应路由为 [`/e-hentai/tag/language:chinese/true/false`](https://rsshub.app/e-hentai/tag/language:chinese/true/false)
:::

## Parameters
- `tag`: 标签，可在对应标签页中找到，默认为首页
- `needTorrents`: 需要输出种子文件，填写 true/yes 表示需要，默认需要
- `needImages`: 需要显示大图，填写 true/yes 表示需要，默认需要


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `e-hentai.org/tag/:tag`
  - `e-hentai.org/`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n参数 **需要输出种子文件**、**需要显示大图** 的说明同上，以下是一个例子：\n\n选择浏览 [language:chinese 标签](https://e-hentai.org/tag/language:chinese)，并指定 **携带种子文件**，**不显示大图**。由于 [language:chinese 标签](https://e-hentai.org/tag/language:chinese) 的 URL `https://e-hentai.org/tag/language:chinese` 中对应标签字段为 `language:chinese`，所以对应路由为 [`/e-hentai/tag/language:chinese/true/false`](https://rsshub.app/e-hentai/tag/language:chinese/true/false)\n:::",
  "example": "/e-hentai/tag/language:chinese",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "needImages": "需要显示大图，填写 true/yes 表示需要，默认需要",
    "needTorrents": "需要输出种子文件，填写 true/yes 表示需要，默认需要",
    "tag": "标签，可在对应标签页中找到，默认为首页"
  },
  "path": "/tag/:tag?/:needTorrents?/:needImages?",
  "radar": [
    {
      "source": [
        "e-hentai.org/tag/:tag",
        "e-hentai.org/"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
