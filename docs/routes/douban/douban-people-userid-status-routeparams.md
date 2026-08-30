# 豆瓣 - 用户广播

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/people/:userid/status/:routeParams?`
- Route Name: `用户广播`
- Example: `/douban/people/75118396/status`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `alfredcai`
- Source Location: `people/status.ts`
- Source Module: `_None_`

## Description
::: tip

- **目前只支持整数型 id**
- 字母型的 id，可以通过头像图片链接来找到其整数型 id，图片命名规则`ul[userid]-*.jpg`或`u[userid]-*.jpg`，即取文件名中间的数字
- 例如：用户 id: `MovieL`他的头像图片链接：`https://img1.doubanio.com/icon/ul1128221-98.jpg`他的整数型 id: `1128221`

:::

对于豆瓣用户广播内容，在 `routeParams` 参数中以 query string 格式设置如下选项可以控制输出的样式

| 键                         | 含义                                                           | 接受的值       | 默认值 |
| -------------------------- | -------------------------------------------------------------- | -------------- | ------ |
| readable                   | 是否开启细节排版可读性优化                                     | 0/1/true/false | false  |
| authorNameBold             | 是否加粗作者名字                                               | 0/1/true/false | false  |
| showAuthorInTitle          | 是否在标题处显示作者                                           | 0/1/true/false | true   |
| showAuthorInDesc           | 是否在正文处显示作者                                           | 0/1/true/false | false  |
| showAuthorAvatarInDesc     | 是否在正文处显示作者头像（若阅读器会提取正文图片，不建议开启） | 0/1/true/false | false  |
| showEmojiForRetweet        | 显示 “🔁” 取代 “Fw”（转发）                                    | 0/1/true/false | false  |
| showRetweetTextInTitle     | 在标题出显示转发评论（置为 false 则在标题只显示被转发的广播）  | 0/1/true/false | false  |
| addLinkForPics             | 为图片添加可点击的链接                                         | 0/1/true/false | false  |
| showTimestampInDescription | 在正文处显示广播的时间戳                                       | 0/1/true/false | false  |
| showComments               | 在正文处显示评论                                               | 0/1/true/false | false  |
| widthOfPics                | 广播配图宽（生效取决于阅读器）                                 | 不指定 / 数字  | 不指定 |
| heightOfPics               | 广播配图高（生效取决于阅读器）                                 | 不指定 / 数字  | 不指定 |
| sizeOfAuthorAvatar         | 作者头像大小                                                   | 数字           | 48     |

指定更多与默认值不同的参数选项可以改善 RSS 的可读性，如

<https://rsshub.app/douban/people/113894409/status/readable=1&authorNameBold=1&showAuthorInTitle=1&showAuthorInDesc=1&showAuthorAvatarInDesc=1&showEmojiForRetweet=1&showRetweetTextInTitle=1&addLinkForPics=1&showTimestampInDescription=1&showComments=1&widthOfPics=100>

的效果为

  <img loading="lazy" src="/img/readable-douban.png" alt="豆瓣读书的可读豆瓣广播 RSS" />

## Parameters
- `userid`: 整数型用户 id
- `routeParams`: 额外参数；见下


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip\n\n- **目前只支持整数型 id**\n- 字母型的 id，可以通过头像图片链接来找到其整数型 id，图片命名规则`ul[userid]-*.jpg`或`u[userid]-*.jpg`，即取文件名中间的数字\n- 例如：用户 id: `MovieL`他的头像图片链接：`https://img1.doubanio.com/icon/ul1128221-98.jpg`他的整数型 id: `1128221`\n\n:::\n\n对于豆瓣用户广播内容，在 `routeParams` 参数中以 query string 格式设置如下选项可以控制输出的样式\n\n| 键                         | 含义                                                           | 接受的值       | 默认值 |\n| -------------------------- | -------------------------------------------------------------- | -------------- | ------ |\n| readable                   | 是否开启细节排版可读性优化                                     | 0/1/true/false | false  |\n| authorNameBold             | 是否加粗作者名字                                               | 0/1/true/false | false  |\n| showAuthorInTitle          | 是否在标题处显示作者                                           | 0/1/true/false | true   |\n| showAuthorInDesc           | 是否在正文处显示作者                                           | 0/1/true/false | false  |\n| showAuthorAvatarInDesc     | 是否在正文处显示作者头像（若阅读器会提取正文图片，不建议开启） | 0/1/true/false | false  |\n| showEmojiForRetweet        | 显示 “🔁” 取代 “Fw”（转发）                                    | 0/1/true/false | false  |\n| showRetweetTextInTitle     | 在标题出显示转发评论（置为 false 则在标题只显示被转发的广播）  | 0/1/true/false | false  |\n| addLinkForPics             | 为图片添加可点击的链接                                         | 0/1/true/false | false  |\n| showTimestampInDescription | 在正文处显示广播的时间戳                                       | 0/1/true/false | false  |\n| showComments               | 在正文处显示评论                                               | 0/1/true/false | false  |\n| widthOfPics                | 广播配图宽（生效取决于阅读器）                                 | 不指定 / 数字  | 不指定 |\n| heightOfPics               | 广播配图高（生效取决于阅读器）                                 | 不指定 / 数字  | 不指定 |\n| sizeOfAuthorAvatar         | 作者头像大小                                                   | 数字           | 48     |\n\n指定更多与默认值不同的参数选项可以改善 RSS 的可读性，如\n\n<https://rsshub.app/douban/people/113894409/status/readable=1&authorNameBold=1&showAuthorInTitle=1&showAuthorInDesc=1&showAuthorAvatarInDesc=1&showEmojiForRetweet=1&showRetweetTextInTitle=1&addLinkForPics=1&showTimestampInDescription=1&showComments=1&widthOfPics=100>\n\n的效果为\n\n  <img loading=\"lazy\" src=\"/img/readable-douban.png\" alt=\"豆瓣读书的可读豆瓣广播 RSS\" />",
  "example": "/douban/people/75118396/status",
  "heat": 1055,
  "location": "people/status.ts",
  "maintainers": [
    "alfredcai"
  ],
  "name": "用户广播",
  "parameters": {
    "routeParams": "额外参数；见下",
    "userid": "整数型用户 id"
  },
  "path": "/people/:userid/status/:routeParams?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣广播 - 豆瓣读书排行榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61011025725344832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/people/180457410/statuses",
      "title": "豆瓣广播 - 豆瓣读书排行榜",
      "type": "feed",
      "url": "rsshub://douban/people/180457410/status"
    },
    {
      "description": "豆瓣广播 - DIYgod - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65438587764467712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/people/62759792/statuses",
      "title": "豆瓣广播 - DIYgod",
      "type": "feed",
      "url": "rsshub://douban/people/62759792/status"
    }
  ],
  "view": 1
}
```
