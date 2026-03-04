---
title: 'Activate Typora'
publishDate: 2025-03-09
description: 'This article introduces the steps and precautions for activating the Typora editor on the Windows system.'
tags:
  - 经验分享
language: 'English'
heroImage: { src: './thumbnail.jpg', color: '#C2B280' }
comment: true
---

### Activation steps

Under Typora’s installation directory, open the folder `Typora\resources\page-dist\static\js`.

Open the JS file whose name starts with **LicenseIndex**, e.g. `LicenseIndex.180dd4c7.bffb5802.chunk.js`.

```js
// # Change e.hasActivated="true"==e.hasActivated to
e.hasActivated = true;
```

Save the file as administrator, then restart Typora.

### Activated

The app will show as activated.

![Activated](https://cdn.blog.saneko.me/Blog/blog_250309_232354.png)