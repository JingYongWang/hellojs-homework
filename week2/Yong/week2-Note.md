# Week2

----

````
npm run-script lint
npm run lint

command line 全域

npm install npm@lastest -g


npm set init-author-name 'Jing Yong'                                                                            
npm set init-author-email 'lovedpotato@gmail.com'                                                               
npm set init-author-url 'http://domain.com'                                                                     
npm set init-author-license 'MIT'  

npm info express
(查詢expree有的相關模組資訊)

npm list
(當前目錄)

npm install eslint --save-dev

-dev 為			檢查的

在_config.yml新增


"scripts":{
  "deploy": "hexo clean && hexo deploy"
}

以下指令

npm run deploy

````

````
ES6
Promise
Arrow Function

ES7
async(下面的Functuon一定要用Promise包過)
await


[Babel]: http://babeljs.io/repl/

[MarkDown](http://markdown.tw/)語法線上說明    

http://slides.com/deleav/deck#/

````

```
TDD

Write Test Program

mocha

npm test


sequlize

````



````
(1)原本目錄底下的_config_yml

# Hexo Configuration
## Docs: https://hexo.io/docs/configuration.html
## Source: https://github.com/hexojs/hexo/

# Site
title: Yong
subtitle:
description:
author: John Doe
language:
timezone:

# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
url: http://jingyongwang.github.io/Blog/
root: /blog
permalink: :year/:month/:day/:title/
permalink_defaults:

# Directory
source_dir: source
public_dir: public
tag_dir: tags
archive_dir: archives
category_dir: categories
code_dir: downloads/code
i18n_dir: :lang
skip_render:

# Writing
new_post_name: :title.md # File name of new posts
default_layout: post
titlecase: false # Transform title into titlecase
external_link: true # Open external links in new tab
filename_case: 0
render_drafts: false
post_asset_folder: false
relative_link: false
future: true
highlight:
  enable: true
  line_number: true
  auto_detect: false
  tab_replace:

# Category & Tag
default_category: uncategorized
category_map:
tag_map:

# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss

# Pagination
## Set per_page to 0 to disable pagination
per_page: 10
pagination_dir: page

# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: landscape

# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
    type: git
    repository: https://github.com/JingYongWang/Blog.git
    branch: gh-pages
````

````
(2)themes\landscape\_config_yml

# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archive
- recent_posts

# display widgets at the bottom of index pages (pagination == 2)
index_widgets:
# - category
# - tagcloud
# - archive

# widget behavior
archive_type: 'monthly'
show_count: false

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:

````
