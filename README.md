# Theme pinghsu-jekyll


## How to start

- fill the file `_config.yml`

example

```yaml
name: A Blog
author: Alfred Amboka
url: https:
resume_site: 
baseurl: 
description: you web description
github_username: alfredamboka
github: https://github.com/alfredamboka
plugins: [jekyll-paginate]
permalink: /:year-:month-:day-:title
paginate: 12
paginate_path: "/page/:num/"
exclude: ['README.md', 'Gemfile.lock', 'Gemfile', 'Rakefile']
highlighter: rouge
markdown: kramdown
comments :
analytics:
```

- add your post in path `./_post`, format : 

```md
---
layout: post
title: A Example Post
date:   1970-01-01 00:00:00 +0800
category: tutorial
thumbnail: /style/image/thumbnail.jpg
icon: book
---


* content
{:toc}

## sub title

page...

## about thumbnail

add the thumbnail url

## about icon

such as book, code, web, chat, note, game, link, design, image
```

run `bundle install` and `jekyll server` to preview site on you computer, more question about jekyll, reference to [jekyll](http://jekyllrb.com)


## Thanks

- [jekyll](http://jekyllrb.com) git page engine
- [pinghsu](https://github.com/chakhsu/pinghsu), a typecho theme, it's a great design.
- [smoothscroll](https://www.smoothscroll.net/mac/) SmoothScroll will give your mouse wheel (Finder, Safari, Chrome, etc.) buttery smooth scrolling
