---
title: "Building own blog with Jekyll and Github in 20 minutes"
tags: 
  - github
  - jekyll
toc: true
toc_sticky: true
---

## Step 0. Pre-requisites
 - Join Github
 - Select and download Jekyll theme in [http://jekyllthemes.org/](http://jekyllthemes.org/)
 - Create new repository and set it for homepage, and then upload the files of Jekyll theme into the new repository

## Step 1. Edit `/_config.yml`
 - This file is relevant to theme, Site settings(title, logo, etc), Site Author(name, bio, social links)

## Step 2. Edit '/_data/navigation.yml'
 - This file is relevant to menus and its link
 - Each menus consists of `title` and `url`. `title` is the name of menu and `url` means a file located in `_pages` folder. You can set the file with checking the example at `/test/_data/navigation.yml`

## Step 3. Create '/_page' folder and menu files
 - This is relevant to creating menu files. This step is connected with previous step.
 - Menu file could be .md or .html and you can make the files with refering to the example at `/test/_pages`

## Step 4. Create '/_post' folder and .md files
 - This is relevant to posting an article in your blog
 - The name of .md file format must be `YYYY-MM-DD-POST-TITLE.md` and you can compose the article with markdown.

## Step 5. That's it
 - You can check your blog and posts that you wrote.
