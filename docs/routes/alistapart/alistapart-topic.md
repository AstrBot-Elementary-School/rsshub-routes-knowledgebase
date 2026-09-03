# A List Apart - Topics

## Coverage
`index-only`

## Route
- Namespace: `alistapart`
- Namespace Name: `A List Apart`
- Route Path: `/alistapart/:topic`
- Route Name: `Topics`
- Example: `/alistapart/application-development`
- URL: `alistapart.com/articles/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
You have the option to utilize the main heading or use individual categories as topics for the path.

| **Code**                    | *code*                    |
| --------------------------- | ------------------------- |
| **Application Development** | *application-development* |
| **Browsers**                | *browsers*                |
| **CSS**                     | *css*                     |
| **HTML**                    | *html*                    |
| **JavaScript**              | *javascript*              |
| **The Server Side**         | *the-server-side*         |

| **Content**          | *content*          |
| -------------------- | ------------------ |
| **Community**        | *community*        |
| **Content Strategy** | *content-strategy* |
| **Writing**          | *writing*          |

| **Design**                 | *design*               |
| -------------------------- | ---------------------- |
| **Brand Identity**         | *brand-identity*       |
| **Graphic Design**         | *graphic-design*       |
| **Layout & Grids**         | *layout-grids*         |
| **Mobile/Multidevice**     | *mobile-multidevice*   |
| **Responsive Design**      | *responsive-design*    |
| **Typography & Web Fonts** | *typography-web-fonts* |

| **Industry & Business** | *industry-business* |
| ----------------------- | ------------------- |
| **Business**            | *business*          |
| **Career**              | *career*            |
| **Industry**            | *industry*          |
| **State of the Web**    | *state-of-the-web*  |

| **Process**            | *process*            |
| ---------------------- | -------------------- |
| **Creativity**         | *creativity*         |
| **Project Management** | *project-management* |
| **Web Strategy**       | *web-strategy*       |
| **Workflow & Tools**   | *workflow-tools*     |

| **User Experience**          | *user-experience*          |
| ---------------------------- | -------------------------- |
| **Accessibility**            | *accessibility*            |
| **Information Architecture** | *information-architecture* |
| **Interaction Design**       | *interaction-design*       |
| **Usability**                | *usability*                |
| **User Research**            | *user-research*            |

## Parameters
- `topic`: Any Topic or from the table below. Defaults to All Articles


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `alistapart.com/blog/topic/:topic`
- `target`: `/:topic`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "You have the option to utilize the main heading or use individual categories as topics for the path.\n\n| **Code**                    | *code*                    |\n| --------------------------- | ------------------------- |\n| **Application Development** | *application-development* |\n| **Browsers**                | *browsers*                |\n| **CSS**                     | *css*                     |\n| **HTML**                    | *html*                    |\n| **JavaScript**              | *javascript*              |\n| **The Server Side**         | *the-server-side*         |\n\n| **Content**          | *content*          |\n| -------------------- | ------------------ |\n| **Community**        | *community*        |\n| **Content Strategy** | *content-strategy* |\n| **Writing**          | *writing*          |\n\n| **Design**                 | *design*               |\n| -------------------------- | ---------------------- |\n| **Brand Identity**         | *brand-identity*       |\n| **Graphic Design**         | *graphic-design*       |\n| **Layout & Grids**         | *layout-grids*         |\n| **Mobile/Multidevice**     | *mobile-multidevice*   |\n| **Responsive Design**      | *responsive-design*    |\n| **Typography & Web Fonts** | *typography-web-fonts* |\n\n| **Industry & Business** | *industry-business* |\n| ----------------------- | ------------------- |\n| **Business**            | *business*          |\n| **Career**              | *career*            |\n| **Industry**            | *industry*          |\n| **State of the Web**    | *state-of-the-web*  |\n\n| **Process**            | *process*            |\n| ---------------------- | -------------------- |\n| **Creativity**         | *creativity*         |\n| **Project Management** | *project-management* |\n| **Web Strategy**       | *web-strategy*       |\n| **Workflow & Tools**   | *workflow-tools*     |\n\n| **User Experience**          | *user-experience*          |\n| ---------------------------- | -------------------------- |\n| **Accessibility**            | *accessibility*            |\n| **Information Architecture** | *information-architecture* |\n| **Interaction Design**       | *interaction-design*       |\n| **Usability**                | *usability*                |\n| **User Research**            | *user-research*            |",
  "example": "/alistapart/application-development",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "topic.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Topics",
  "parameters": {
    "topic": "Any Topic or from the table below. Defaults to All Articles"
  },
  "path": "/:topic",
  "radar": [
    {
      "source": [
        "alistapart.com/blog/topic/:topic"
      ],
      "target": "/:topic"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Application-development Articles on aListApart.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53660433450916864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://alistapart.com/blog/topic/application-development",
      "title": "A List Apart",
      "type": "feed",
      "url": "rsshub://alistapart/application-development"
    },
    {
      "description": "Code Articles on aListApart.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68624257371529216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://alistapart.com/blog/topic/code",
      "title": "A List Apart",
      "type": "feed",
      "url": "rsshub://alistapart/code"
    }
  ],
  "url": "alistapart.com/articles/"
}
```
