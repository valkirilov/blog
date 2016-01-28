title: Hello World
tags:
  - valkirilov
  - valentin
  - kirilov
categories:
  - en
date: 2016-01-28 19:53:00
---
---

{% asset_img cover.gif Hello world %}


Now is the moment to say "Hello world" form my new blog. I will post here tutorials, examples and code snippets for technologies which I use. So I hope that can make this blog something like a bucket with knoledge, cool stuff and code boosters.
 
I will start with that how I build this simple blog. The setup is really easy and fast, it will took you less than 1 hour (if you want to make some customizations). 
 
What you should know to create a blog like this one:
 
1.  I am using [Hexo](https://hexo.io/) - a [node.js](https://nodejs.org/en/) blog generator from [markdown](https://en.wikipedia.org/wiki/Markdown) files. If you are not familiar with node.js and don't want to dive in the world of the Server-Side-JavaScript I suggest you to checkout other technologies like [Wordpress](https://wordpress.com/), [Jekyll](https://jekyllrb.com/), etc.

2. To continue you should have installed node.js and npm. If you don't have them you can refer to my snipet for this - [Install Node.js on Linux]().

3. Install the Hexo npm package. 

```bash
npm install -g hexo
```


 
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

---
date: 2016-01-28 19:53:33
author: Valentin Kirilov