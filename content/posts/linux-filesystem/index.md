---
title: "Linux Filesystem"
date: 2023-07-03T15:59:19+02:00
draft: true
author: "Tamas Hoffman"
authorLink: /about-me
license: MIT
tags: 
    - "filesystem"
    - "linux"
categories: 
    - "Issue"
featuredimage: "linux-filesystem-bg.jpg"
twemoji: true
lightgallery: true
fontawesome: true
linkToMarkdown: true
---


This post is about how the linux filesystem is brokein in Windows WSL2 if folder is in mounted windows drive.

Examples: Hugo file changes are not detected

Solution: Move directory under native Linux filesystem. Like ~/folder  
That will further boost the speed as well.

https://discourse.gohugo.io/t/wsl-and-file-modification-detection-livereload-troubles/29445/4
