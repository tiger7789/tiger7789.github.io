

![](https://raw.githubusercontent.com/tiger7789/tiger7789.github.io/master/img/readme.jpg) 

[![Build Status](https://travis-ci.org/tiger7789/tiger7789.github.io.svg?branch=master)](https://travis-ci.org/tiger7789/tiger7789.github.io)
[![GitHub issues](https://img.shields.io/github/issues/qiubaiying/qiubaiying.github.io.svg?style=flat)](https://github.com/qiubaiying/qiubaiying.github.io/issues)
[![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/home-assistant/home-assistant-iOS/blob/master/LICENSE)


Special thanks to [Hux](https://github.com/Huxpro/huxpro.github.io) and [qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io)
 

>
### [Click to see my Blog 👆](http://tiger7789.github.io)



## 使用

* Blog OS
	* [Environment](#Environment)
	* [Start](#start)
	* [Writing_Blog](#writing_Blog)
* Widget
	* [Side Bar](#Sidebar)
	* [friends](#friends)



### Environment 
* Easy way: [use github to build your personal blog]
	* To start: 
		* sign up GitHub ✅
		* Search 🔍 and Fork 🔄 [tiger7789.github.io](https://github.com/tiger7789/tiger7789.github.io)
		* Setting -> Rename as yourname.github/github.io
	* Test:
		* open search engine, search yourname.github/github.io
		If you can see a page like it:


* Developer Way: [Credit to [qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io) and [Cassiel](https://github.com/Cassiel-H/Cassiel-H.github.io)]
	* You need to install [jekyll](http://jekyllcn.com/)
	* Then you need to input `jekyll serve` or  `jekyll s` in command 
	* Test and see preview on  `http://127.0.0.1:4000/`


### Start
Certainly! Here is how you can easily start building your own blog by modifying the _config.yml file: 


```
# Site settings
title: Hello				# Your website title
SEOTitle: Hello world		# SEO title
description: "Hey"			# description

# SNS settings      
github_username: tiger7789     # your github

# Build settings
# paginate: 10              # how many blog you want to put in a page 
```
In the _config.yml file, you will see various configuration options that you can modify. [Jekyll - Official Site](http://jekyllrb.com/) 中文版的在这里：[Jekyll中文](http://jekyllcn.com/).

Once you have made your changes, save the _config.yml file and your blog should now reflect the changes you made.


### Writing_Blog

In order to publish a new blog post on your site, you will need to create a new **Markdown**  file in the `_posts/` directory. The file should be formatted using `_posts/` syntax, and should include a YAML header at the top to specify metadata for the post.


Here is how the YAML header of a blog post generally looks in Markdown, and how you can set it up:

```
---
layout:     post
title:      "Welcome to my blog!"
subtitle:   Start it
date:       2022-10-13
author:     tiger7789
header-img: img/hello_world.jpg
catalog: 	 true
tags:
    - blog
    - hello
---

```

### Sidebar
* `_config.yml` -> `Sidebar settings`

```
# Sidebar settings
sidebar: true  #add sidebar
sidebar-about-description: "about yourself"
sidebar-avatar: /img/avatar-lxc.jpg     #your photo
```

### Social-media Account

Please input your social media account, comment out will invisible. 

	# SNS settings
	RSS: false 
	instagram_username:     username
	facebook_username:  username
	github_username:    username
	# wechat_username:   username
	
	

![](http://ww4.sinaimg.cn/large/006tKfTcgy1fgrgbgf77aj308i02v748.jpg)

### Friends

Show your frends
* setting in  `_config.yml`, the `Friends` section

```
# Friends
friends: [
    {
        title: "LXC Blog",
        href: "https://tiger7789.github.io/"
    },
    {
        title: "Tesla",
        href: "https://tesla.com/"
    }
]
```

## Acknowledgements

1. Fork from [Hux](https://github.com/Huxpro/huxpro.github.io) and [qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io) 
2. Thanks Jekyll、Github Pages 和 Bootstrap!
3. Thanks Cassiel

## License
[LICENSE](https://github.com/qiubaiying/qiubaiying.github.io/blob/master/LICENSE)

