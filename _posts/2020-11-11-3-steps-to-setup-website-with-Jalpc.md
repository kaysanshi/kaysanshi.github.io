---
layout: post
title:  "3 Steps (2 minutes) to Setup Your Personal Website with Jalpc"
date:   2020-11-11
desc: "3 Steps (2 minutes) to Setup Your Personal Website with Jalpc"
keywords: "Jalpc,Jekyll,gh-pages,website,blog,easy"
categories: [blog]
tags: [Jalpc,Jekyll]
icon: icon-html
---
闲来无事，搭建个博客

1. 去git上把模板进行给拉取下来 clone forked repository. `git clone git@github.com:github_username/Jalpc.git`.
	或者直接git我的模板地址. `git clone git@github.com:kaysanshi/kaysanshi.github.io.git`.

	<!-- ![edit]({{ site.img_path }}/3steps/edit.gif) -->
	<img src="{{ site.img_path }}/3steps/edit.gif" width="75%">

2. 去配置列表:

	* **_config.yml**: 编辑 'Website settings', 'author', 'comment' and 'analytics' items.

	* **_data/landing.yml**: index页自定义.

	* **_data/index/**: .在 **_data/index/**页编辑章节数据，请注意每个文件的注释

	* **_data/blog.yml**: 编辑博客页面的导航栏（类别），如果您有不同/更多的博客页面，请复制`blog/python.html`并将其更改为您的类别HTML文件，并将**Python**、**/Python/**编辑为项目**title**和**permalink**的类别名称，确保title与permalink相同，但大写的第一个字母（HTML除外）.

	* **CNAME**: 如果你想用自己的域名发布网站：编辑它并创建“gh pages”分支；如果你想使用*github_用户名.github.io*：留空.

	* 转到repo的设置面板，config**GitHub Pages**部分，确保网站已发布.

3.将更改推送到GitHub存储库并查看您的网站，完成！

从现在起，你可以通过在`post/`目录下创建md文件并将其推送到GitHub，你可以在发布博客之前清除这个目录下的文件。


如果你喜欢这个资料库，我很感激你成为这个资料库的star。如果您有任何问题，请随时给我发邮件或在GitHub上发布问题。希望你有一个快乐的博客时间！😊
