---
title: Hexo Tips
date: 2016-03-28 00:00:00
categories: 写作
tags:
  - hexo
---
[Hexo](https://hexo.io/)能有更好的写作体验.

``` ruby
p 'Hello Hexo!!!!!!!!!'
```

### install
``` bash
$ npm install hexo-cli -g
```

<!--more-->

### deploy

``` shell
# ./d.sh
hexo g
hexo p
```

### 多地写博客
push to github
``` shell
# ./p.sh
git add --all
git commit -am 'new post'
git push
```

### rss生成
``` shell
npm i hexo-generator-feed --save

```

### 使用atom写博客

atom 插件

``` shell
apm install atom-hexo
```


more info:[Hexo](https://hexo.io/)

<!--more-->

***


Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)
