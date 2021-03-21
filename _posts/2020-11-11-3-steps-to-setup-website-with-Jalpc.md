---
layout: post
title:  "3 Steps  to Setup Your Personal Website with Jalpc "
date:   2020-11-11
desc: "3 Steps (2 minutes) to Setup Your Personal Website with Jalpc"
keywords: "Jalpc,Jekyll,gh-pages,website,blog,easy "
categories: [html]
tags: [Jalpc,Jekyll]
icon: icon-html
---
​
## 闲来无事，搭建个博客

### 博客搭建流程

这是我通过上篇的<a href="http://www.kaysanshi.top/blog/2020/11/11/%E6%88%91%E5%9C%A8github%E4%B8%8A%E5%88%9B%E5%BB%BA%E4%BA%86%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5-%E6%9D%A5%E8%A7%82%E6%91%A9%E4%B8%80%E4%B8%8B.html">我搭建了个博客</a> 这篇只是简单的使用了一个单页面，这里我将详细说明我根据Jekyll搭建的流程。

1. **去git上把模板进行给拉取下来 clone forked repository.**
	

 `git clone git@github.com:github_username/Jalpc.git`.
	
	或者直接git我的模板地址. 
	
	`git clone git@github.com:kaysanshi/kaysanshi.github.io.git`.

<!-- ![edit]({{ site.img_path }}/3steps/edit.gif) -->
<img src="{{ site.img_path }}/3steps/edit.gif" width="75%">



2. **去配置列表:**

  * **_config.yml**: 编辑 'Website settings', 'author', 'comment' and 'analytics' items.

  * **_data/landing.yml**: index页自定义.

  * **_data/index/**: .在 **_data/index/**页编辑章节数据，请注意每个文件的注释

  * **_data/blog.yml**: 编辑博客页面的导航栏（类别），如果您有不同/更多的博客页面，请复制`blog/python.html`并将其更改为您的类别HTML文件，并将**Python**、**/Python/**编辑为项目**title**和**permalink**的类别名称，确保title与permalink相同，但大写的第一个字母（HTML除外）.

  * **CNAME**: 如果你想用自己的域名发布网站：编辑它并创建“gh pages”分支；如果你想使用*github_用户名.github.io*：留空.

  * **CNAME** 同样可以去git上的设置的地方进行配置，配置完成后git会自动在这个文件中书写你的域名如图所示。
  <br/>

  <a href="https://imgchr.com/i/BzXQQf"><img src="https://s3.ax1x.com/2020/11/12/BzXQQf.png" alt="BzXQQf.png" border="0" /></a>

  * 转到repo的设置面板，config**GitHub Pages**部分，确保网站已发布.




**3.将更改推送到GitHub存储库并查看您的网站，完成！**

从现在起，你可以通过在`post/`目录下创建md文件并将其推送到GitHub，你可以在发布博客之前清除这个目录下的文件。


如果你喜欢这个资料库，我很感激你成为这个资料库的star。如果您有任何问题，请随时给我发邮件或在GitHub上发布问题。希望你有一个快乐的博客时间！😊

### 后记：
在这个博客搭建需要注意以下方面：

1. 在博客中引入分类时必须分类名称的首字母大写

2. 博客的文章必须是以yyyy-mm-dd的形式开头否者不能解析。

3. 我为了适配我修改了样式，同时自家加入了一些动画，和挑整。你可以直接拿着我的进行git.然后去见自己的网站。

4. 这里面引入了谷歌的分析，不过现在我通过代理域名还未实现。

5. 这里同时引入了开源的disques 就是为了评论  https://kaysanshi-github-io.disqus.com/admin/
<a href="https://imgchr.com/i/BzxyTg"><img src="https://s3.ax1x.com/2020/11/12/BzxyTg.png" alt="BzxyTg.png" border="0" /></a>

6. 还有一个没有搞明白就是那个google的广告。后序给他搞明白 