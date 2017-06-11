---
layout: post
comments: true
title: Importing WordPress Content in Jekyll
date: Sunday, 11 June 2017
tags: jekyll
---

I'd like to keep some of the content from my WordPress page. Luckily, there is a Jekyll importer that can convert content. It does require a local installation of Jekyll, so let's set that up first.

My setup: I'm running [Bash on Ubuntu on Windows](https://msdn.microsoft.com/en-gb/commandline/wsl/about), so hopefully Ubuntu instructions will work without any changes. This is a blank slate, so let's start with the basics. RubyGems installation instructions are from [RubyGems on GitHub](https://github.com/rubygems/rubygems):

```bash
sudo apt-get install ruby-2.4 ruby2.4-dev
# install rubygems from source:
git clone git@github.com:rubygems/rubygems.git
cd rubygems/
git submodule update -\-init
sudo ruby setup.rb
sudo gem install jekyll
```
Next up is [jekyll-import](https://github.com/jekyll/jekyll-import) + WordPress specific dependencies:

```bash
sudo gem install jekyll-import
sudo gem install hpricot
sudo gem install open_uri_redirections
```
Now all that's left is to follow the instructions from [Jekyll Importer - WordPress.com](http://import.jekyllrb.com/docs/wordpressdotcom/). The result: my previous posts are converted and added under `_posts`. Let's commit, push, and see the result.


