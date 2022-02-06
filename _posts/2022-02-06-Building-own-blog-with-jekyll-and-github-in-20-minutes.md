---
title: "Building own blog with Jekyll and Github in 20 minutes"
tags: 
  - github
  - jekyll
toc: true
toc_sticky: true
---

## 0. Pre-requisites
 - Join Github
 - Select and download Jekyll theme in [http://jekyllthemes.org/](http://jekyllthemes.org/)
 - Create new repository and set it for homepage, and then upload the files of Jekyll theme into the new repository

## 1. Edit `/_config.yml`
 - This file is related to these settings below :
   * theme, Site settings(title, logo, etc), Site Author(name, bio, social links)

## 2. Edit '_data/navigation.yml'
 - This file is related to menus and its link
 - Each menus consists of `title` and `url`. `title` is the name of menu and `url` means a file located in `_pages` folder. You can check the example at `/test/_data/navigation.yml`
