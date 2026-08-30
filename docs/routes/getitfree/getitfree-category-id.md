# 正版中国 - 分类

## Coverage
`index-only`

## Route
- Namespace: `getitfree`
- Namespace Name: `正版中国`
- Route Path: `/getitfree/category/:id{.+}?`
- Route Name: `分类`
- Example: `/getitfree/category/pc`
- URL: `getitfree.cn`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `sanmmm, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
可以叠加使用得到分类结果并集，如 [`/getitfree/category/pc,android`](https://rsshub.app/getitfree/category/pc,android)

亦可与标签组合使用，如 [`/getitfree/category/pc/tag/ai`](https://rsshub.app/getitfree/category/pc/tag/ai)
:::

| 所有类别 | Android | iOS | Mac | PC | UWP | 公告         | 永久免费 | 限时免费 | 正版折扣 |
| -------- | ------- | --- | --- | -- | --- | ------------ | -------- | -------- | -------- |
|          | android | ios | mac | pc | uwp | notification | free     | giveaway | discount |

## Parameters
- `id`: 分类，见下表，可在对应分类页中找到，默认为所有类别


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `getitfree.cn/category/:id`
- `target`: `/category/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n可以叠加使用得到分类结果并集，如 [`/getitfree/category/pc,android`](https://rsshub.app/getitfree/category/pc,android)\n\n亦可与标签组合使用，如 [`/getitfree/category/pc/tag/ai`](https://rsshub.app/getitfree/category/pc/tag/ai)\n:::\n\n| 所有类别 | Android | iOS | Mac | PC | UWP | 公告         | 永久免费 | 限时免费 | 正版折扣 |\n| -------- | ------- | --- | --- | -- | --- | ------------ | -------- | -------- | -------- |\n|          | android | ios | mac | pc | uwp | notification | free     | giveaway | discount |",
  "example": "/getitfree/category/pc",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "sanmmm",
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类，见下表，可在对应分类页中找到，默认为所有类别"
  },
  "path": "/category/:id{.+}?",
  "radar": [
    {
      "source": [
        "getitfree.cn/category/:id"
      ],
      "target": "/category/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "正版中国（GetItFree）成立于2015年7月,以提供正版软件限时免费信息为途径,引导用户养成使用正版软件的习惯,以此促进国内版权氛围的改进。目前已经得到上百家软件开发者的支持！ - Powered by RSSHub",
      "errorAt": "2025-07-27T04:21:48.277Z",
      "errorMessage": "[GET] \"https://getitfree.cn/wp-json/wp/v2/categories?search=pc\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: getitfree.cn. is not in the cert's altnames: DNS:linhtrucsang.space)\n",
      "id": "82378651141339164",
      "image": "https://getitfree.cn/wp-content/uploads/site_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://getitfree.cn/category/",
      "title": "Getitfree",
      "type": "feed",
      "url": "rsshub://getitfree/category/pc"
    }
  ],
  "url": "getitfree.cn"
}
```
