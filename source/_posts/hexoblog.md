---
title: hexoblog
date: 2017-01-04 09:24:47
tags:
---

# Using [Hexo](http://hexo.io), I've set up this blog so I *never* have to leave the command line to publish my thoughts to the Web.


## With just a few simple commands, I can make a new post, write it out, generate the templates, then deploy and push it to github.

1. Create new post
`hexo new hexoblog`

2. Edit file to contain writing
`nano source/_posts/hexoblog.md`

3. Generate templates, and -d Deploy
`hexo generate -d`

4. Add, Commit, then Push to Github


______

There's some necessary configuration needed in the config.yml file, for this to work so smoothly. This can be found in Hexo's deployment documentation.
