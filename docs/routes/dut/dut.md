# 大连理工大学 - 通用

## Coverage
`index-only`

## Route
- Namespace: `dut`
- Namespace Name: `大连理工大学`
- Route Path: `/dut/*/*`
- Route Name: `通用`
- Example: `/dut`
- URL: `dutdice.dlut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `beautyyuyanli, nczitzk, ueiu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
订阅 **单级** 栏目如 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [头条关注](https://news.dlut.edu.cn/ttgz.htm) 分类栏目，分为 3 步：

1. 将 URL `https://news.dlut.edu.cn/ttgz.htm` 中 `https://` 与 `.dlut.edu.cn/` 中间的 `news` 作为 `site` 参数填入；
2. 将 `https://news.dlut.edu.cn/` 与 `.htm` 间的 `ttgz` 作为 `category` 参数填入；
3. 最终可获得 [`/dut/news/ttgz`](https://rsshub.app/dut/news/tzgg)。

订阅 **多级** 栏目如 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [人才培养](https://news.dlut.edu.cn/xwjj01/rcpy.htm) 分类栏目，同样分为 3 步：

1. 将 URL `https://news.dlut.edu.cn/xwjj01/rcpy.htm` 中 `https://` 与 `.dlut.edu.cn/` 中间的 `news` 作为 `site` 参数填入；
2. 把 `https://news.dlut.edu.cn/` 与 `.htm` 间 `xwjj01/rcpy` 作为 `category` 参数填入；
3. 最终可获得 [`/dut/news/xwjj01/rcpy`](https://rsshub.app/dut/news/xwjj01/rcpy)。

::: tip 小提示
大连理工大学大部分站点支持上述通用规则进行订阅。下方的大连理工大学相关路由基本适用于该规则，在其对应的表格中没有提及的分类栏目，可以使用上方的方法自行扩展。
:::

::: tip 小小提示
你会发现 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [人才培养](https://news.dlut.edu.cn/xwjj01/rcpy.htm) 分类栏目在下方 **新闻网** 参数表格中 `category` 参数为 `rcpy`，并非上面例子中给出的 `xwjj01/rcpy`。这意味着开发者对路由 `/dut/news/xwjj01/rcpy` 指定了快捷方式 `/dut/news/rcpy`。两者的效果是一致的。
:::

## Parameters
_None_


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "订阅 **单级** 栏目如 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [头条关注](https://news.dlut.edu.cn/ttgz.htm) 分类栏目，分为 3 步：\n\n1. 将 URL `https://news.dlut.edu.cn/ttgz.htm` 中 `https://` 与 `.dlut.edu.cn/` 中间的 `news` 作为 `site` 参数填入；\n2. 将 `https://news.dlut.edu.cn/` 与 `.htm` 间的 `ttgz` 作为 `category` 参数填入；\n3. 最终可获得 [`/dut/news/ttgz`](https://rsshub.app/dut/news/tzgg)。\n\n订阅 **多级** 栏目如 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [人才培养](https://news.dlut.edu.cn/xwjj01/rcpy.htm) 分类栏目，同样分为 3 步：\n\n1. 将 URL `https://news.dlut.edu.cn/xwjj01/rcpy.htm` 中 `https://` 与 `.dlut.edu.cn/` 中间的 `news` 作为 `site` 参数填入；\n2. 把 `https://news.dlut.edu.cn/` 与 `.htm` 间 `xwjj01/rcpy` 作为 `category` 参数填入；\n3. 最终可获得 [`/dut/news/xwjj01/rcpy`](https://rsshub.app/dut/news/xwjj01/rcpy)。\n\n::: tip 小提示\n大连理工大学大部分站点支持上述通用规则进行订阅。下方的大连理工大学相关路由基本适用于该规则，在其对应的表格中没有提及的分类栏目，可以使用上方的方法自行扩展。\n:::\n\n::: tip 小小提示\n你会发现 [大连理工大学新闻网](https://news.dlut.edu.cn) 的 [人才培养](https://news.dlut.edu.cn/xwjj01/rcpy.htm) 分类栏目在下方 **新闻网** 参数表格中 `category` 参数为 `rcpy`，并非上面例子中给出的 `xwjj01/rcpy`。这意味着开发者对路由 `/dut/news/xwjj01/rcpy` 指定了快捷方式 `/dut/news/rcpy`。两者的效果是一致的。\n:::",
  "example": "/dut",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "beautyyuyanli",
    "nczitzk",
    "ueiu"
  ],
  "name": "通用",
  "path": [
    "/*/*",
    "/:0?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-10-05T06:54:30.540Z",
      "errorMessage": "Cannot read properties of undefined (reading '0')\n",
      "id": "197554467454926849",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://dut/gs/zytz"
    }
  ]
}
```
