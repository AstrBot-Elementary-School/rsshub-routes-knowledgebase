# 知识星球 - 用户足迹

## Coverage
`index-only`

## Route
- Namespace: `zsxq`
- Namespace Name: `知识星球`
- Route Path: `/zsxq/user/:id`
- Route Name: `用户足迹`
- Example: `/zsxq/user/2414218251`
- URL: `zsxq.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户id，从网页端url中获取


## Features
- `requireConfig`: [{"description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值", "name": "ZSXQ_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `wx.zsxq.com/dweb2/index/footprint/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zsxq/user/2414218251",
  "features": {
    "requireConfig": [
      {
        "description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值",
        "name": "ZSXQ_ACCESS_TOKEN"
      }
    ]
  },
  "heat": 13,
  "location": "user.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "用户足迹",
  "parameters": {
    "id": "用户id，从网页端url中获取"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "wx.zsxq.com/dweb2/index/footprint/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "知识星球 - 金豆子 - Powered by RSSHub",
      "errorAt": "2025-11-19T02:18:17.338Z",
      "errorMessage": "[GET] \"https://api.zsxq.com/v2/users/551142184514\": 401 Unauthorized\n该 RSS 源由于配置不正确而被禁用：令牌丢失。\n",
      "id": "92395671277165568",
      "image": "https://images.zsxq.com/Fh9xrKafarmQ__aSZ67aSWIT9lPA?imageMogr2/auto-orient/thumbnail/150x/format/jpg/blur/1x0/quality/75/ignore-error/1&e=1767196799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:ClAGum-gk0vn6BaoBwQTgu1Xdps=",
      "ownerUserId": null,
      "siteUrl": "https://wx.zsxq.com/dweb2/index/footprint/551142184514",
      "title": "知识星球 - 金豆子",
      "type": "feed",
      "url": "rsshub://zsxq/user/551142184514"
    },
    {
      "description": "知识星球 - 七爷 - Powered by RSSHub",
      "errorAt": "2025-11-19T07:54:33.646Z",
      "errorMessage": "该 RSS 源由于配置不正确而被禁用：令牌丢失。\n",
      "id": "92393906365792256",
      "image": "https://images.zsxq.com/FtqALUPIX5gNVZXFTCzN58SWG2nU?imageMogr2/auto-orient/thumbnail/150x/format/jpg/blur/1x0/quality/75/ignore-error/1&e=1767196799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:8jU6uH43pMQ4HXoDvtLNPDJWjkM=",
      "ownerUserId": null,
      "siteUrl": "https://wx.zsxq.com/dweb2/index/footprint/88518551114282",
      "title": "知识星球 - 七爷",
      "type": "feed",
      "url": "rsshub://zsxq/user/88518551114282"
    }
  ]
}
```
