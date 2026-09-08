---
layout: post
title:  "Options for creating a new site with Jekyll"
author: jane
categories: [ Jekyll, tutorial ]
image: assets/images/13.jpg
---

`jekyll new <PATH>` installs a new Jekyll site at the path specified (relative to current directory). In this case, Jekyll will be installed in a directory called `myblog`. Here are some additional details:

- To install the Jekyll site into the directory you're currently in, run `jekyll new` . If the existing directory isn't empty, you can pass the --force option with jekyll new . --force.
- `jekyll new` automatically initiates `bundle install` to install the dependencies required. (If you don't want Bundler to install the gems, use `jekyll new myblog --skip-bundle`.)
- By default, the Jekyll site installed by `jekyll new` uses a gem-based theme called Minima. With gem-based themes, some of the directories and files are stored in the theme-gem, hidden from your immediate view.
- We recommend setting up Jekyll with a gem-based theme but if you want to start with a blank slate, use `jekyll new myblog --blank`
- To learn about other parameters you can include with `jekyll new`, type `jekyll new --help`.

---
【联系我们】
行程定制、包车、机场接送、微留学、亲子游、户外游、订住宿
快客旅行（Xtravel Club）
PO Box 107129 Auckland Airport
 Auckland 2150

Mobile/手机：022 496 4978
Email/邮箱：info@xtravel.club
Web /网站：http://xtravel.club
微信号/QQ： 496 4978
扫描关注我们的企业微信号: 
![企业微信号](/assets/images/CI/WEchat.jpg "企业微信号")