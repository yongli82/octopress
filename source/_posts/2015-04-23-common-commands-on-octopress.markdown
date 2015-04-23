---
layout: post
title: "Common commands on octopress"
date: 2015-04-23 05:57:25 -0400
comments: true
categories: 
---

My markdown posts is in the location: '/home/octopress/octopress/source/_posts'

Get to this location and then use the command: 

```
rake new_post['post title']
```

It will generate a new post file on this directory.

Use vim to edit it.

After editing, use command:

```
rake generate
```

It will re-build the octopress site.


