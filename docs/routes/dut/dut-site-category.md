# 大连理工大学 - 通用

## Coverage
`index-only`

## Route
- Namespace: `dut`
- Namespace Name: `大连理工大学`
- Route Path: `/dut/:site/:category{.+}`
- Route Name: `通用`
- Example: `/dut`
- URL: `dutdice.dlut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `beautyyuyanli, nczitzk, ueiu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
将大学官网栏目地址 `https://<site>.dlut.edu.cn/<category>.htm` 中的子域名和栏目路径分别作为 `site`、`category` 参数。栏目路径可以包含多级目录。

例如，[新闻网的主页新闻](https://news.dlut.edu.cn/zyxw.htm) 对应 `/dut/news/zyxw`；省略参数的 `/dut` 也订阅此栏目。[盘锦教学与科研工作部的工作动态](https://pjteach.dlut.edu.cn/index/gzdt.htm) 对应多级路径 `/dut/pjteach/index/gzdt`。

官网改版前的快捷路径保持兼容：`/dut/news/ttgz` 订阅当前主页新闻，`/dut/news/rcpy` 和 `/dut/news/xwjj01/rcpy` 均订阅当前[人才培养](https://news.dlut.edu.cn/rcpy.htm)栏目。

大部分大学分站可按此规则订阅；需要校园内网或登录的正文页面可能只能返回公开列表中的信息。

## Parameters
- `site`: Subdomain of dlut.edu.cn, default to news
- `category`: Category path without .htm; supports the documented shortcuts and subdirectories


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
  "description": "将大学官网栏目地址 `https://<site>.dlut.edu.cn/<category>.htm` 中的子域名和栏目路径分别作为 `site`、`category` 参数。栏目路径可以包含多级目录。\n\n例如，[新闻网的主页新闻](https://news.dlut.edu.cn/zyxw.htm) 对应 `/dut/news/zyxw`；省略参数的 `/dut` 也订阅此栏目。[盘锦教学与科研工作部的工作动态](https://pjteach.dlut.edu.cn/index/gzdt.htm) 对应多级路径 `/dut/pjteach/index/gzdt`。\n\n官网改版前的快捷路径保持兼容：`/dut/news/ttgz` 订阅当前主页新闻，`/dut/news/rcpy` 和 `/dut/news/xwjj01/rcpy` 均订阅当前[人才培养](https://news.dlut.edu.cn/rcpy.htm)栏目。\n\n大部分大学分站可按此规则订阅；需要校园内网或登录的正文页面可能只能返回公开列表中的信息。",
  "example": "/dut",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "beautyyuyanli",
    "nczitzk",
    "ueiu"
  ],
  "name": "通用",
  "parameters": {
    "category": "Category path without .htm; supports the documented shortcuts and subdirectories",
    "site": "Subdomain of dlut.edu.cn, default to news"
  },
  "path": [
    "/:site/:category{.+}",
    "/:site?"
  ],
  "topFeeds": []
}
```
