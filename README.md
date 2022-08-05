---
home: true
modules:
  - BannerBrand
  - MdContent
  # - Footer
bannerBrand:
  heroImage: /logo.png
  heroImageStyle:
    maxWidth: '200px'
    width: '100%'
    display: block
    margin: '0 auto 2rem'
    borderRadius: '1rem'
  bgImage: '/bg.svg'
  heroText: QianXun
  tagline: qianxun（千寻）是一套基于vue3的后台管理系统框架。提供了管理系统的基本功能，并内置了一套表单设计器。简单、易用、高效是本开发框架的核心目标。
  buttons:
    - { text: 指南, link: '/docs/theme-reco/theme' }
    - { text: Demo, link: '/blogs/other/guide', type: 'plain' }
isShowTitleInHome: true
---

## 快速开始

**安装脚手架**

```bash
npm install qianxun-cli -g
```

**初始化项目**

```bash
qx-cli init
```

**开始使用**

```bash
$ cd [dir]
$ pnpm install
$ npm run dev
```
