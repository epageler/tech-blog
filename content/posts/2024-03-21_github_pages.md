---
title: "Deploying a Hugo Site to GitHub Pages"
date: 2024-03-21T16:44:04-05:00
draft: false
author: Evan
categories: ["Web Development"]
tags: ["Hugo", "github Pages"]
showtoc: false
tocopen: false
---
## Instructions
Detailed instructions from Hugo website [Host on GitHub Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)

## Additional Step (Required)
Be sure to add a file entitled .gitmodules to the root of the hugo directory, with content similar to below:

```
[submodule "themes/PaperMod"]
    path = themes/PaperMod
    url = https://github.com/adityatelange/hugo-PaperMod.git
```

Edit the content appropriately to reference the name of the theme & the the github url for the link to the code of the theme.
