---
layout: post
title:  "Using Jekyll to build Github Pages"
date:   2016-02-10 09:56:05 -0800
categories: jekyll
---
As I just walked though a quick tutorial, I thought I would share a bit about my finding on creating a blog using [Jekyll][jekyll].  Overall, it was very easy and allows creation of a blog within a few minutes.

# Steps
I am working on OSX but this could easilly be done in another OS.

*	Install or verify that ruby is installed
	*	ruby --version
	*	Verify that your ruby version >= 2.0.0
*	Install jekyll
	*	gem install jekyll
*	Create a new github project under your user
	*	Go to Github
	*	Create a repository called \<github_user\>.github.io
*	Clone it on your system
	*	git clone https://github.com/\<github_user\>/\<github_user\>.github.io.git
*	Generate a jekyll site
	*	jekyll new \<github_user\>.github.io
*	Run your site
	*	cd \<github_user\>/github.io
	*	jekyll server
	*	Goto http://127.0.0.1:4000
*	Personalize your site
	*	Update _config.yml with your site name, twitter user, github user, etc
*	Create blog posts
	*	cd _posts
	*	Create a new file with the format YYYY-MM-DD-\<topic\>.markdown
	*	Edit the file and add your content using markdown format
*	Profit?

Hope this was informative.  Look for more posts to come.

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll]:      http://jekyllrb.com
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
