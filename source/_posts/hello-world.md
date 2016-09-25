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

{% asset_img cover.png Hello world %}


Now is the moment to say "Hello world" form my new blog. I will post here tutorials, examples and code snippets for technologies which I use. I hope that I can make this blog something like a bucket with knoledge, cool stuff and code boosters.
 
I will start with that how I build this simple blog. The setup is really easy and fast, it will took you less than 5 minutes (more if you want to make some customizations). 
 
What you should know to create a blog like this one:
 
1.  I am using [Hexo](https://hexo.io/) - a [node.js](https://nodejs.org/en/) blog generator from [markdown](https://en.wikipedia.org/wiki/Markdown) files. If you are not familiar with node.js and don't want to dive in the world of the Server-Side-JavaScript I suggest you to checkout other technologies like [Wordpress](https://wordpress.com/), [Jekyll](https://jekyllrb.com/), etc.

2. To continue you should have installed node.js and npm. If you don't have them you can checkout my snipet for this - [Install Node.js on Linux]().

3. Install the Hexo npm package. 
```bash
npm install -g hexo-cli
```
4. Once hexo is installed you should create a new blog project. Simply execute the following commands. 
```bash
hexo init <folder>
$ cd <folder>
$ npm install
```
	This will create a new folder with basic setup for you blog and will download all of the required dependencies. After all, you should have something like this folder structure:
```bash
.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes
```
5. The next step is to check your new blog. Hexo is comming with build-in server so you can start it and access your blog from your favorite browser. To do this just execute the command bellow:
```bash
hexo server
```
This will start a local server. By default, this is at http://localhost:4000/. You can pass some configuration details, for more information check the [official documentation](https://hexo.io/docs/commands.html#server).

You know the basics now and can continue alone. You can use the [Hexo Docs](https://hexo.io/docs/) which will answer all of your questions. 
I am still reasearching the available plugings for Hexo but I suggest you to try [Hexo Admin](https://github.com/jaredly/hexo-admin) - it is really helpfull and looks cool. Now I want to publish it as my first post and will use this handy command:

```bash
hexo deploy
```


---
date: 2016-01-28
author: Valentin Kirilov