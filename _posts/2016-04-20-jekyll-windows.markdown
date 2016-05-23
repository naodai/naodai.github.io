---
layout: post
title:  "Jekyll Windows"
date:   2016-04-20 11:45:14 +0800
categories: jekyll windows
---
换了电脑,系统又折腾回Win10了.

之前的博客空间到期了,由于好久没有打理了,也就没再续费,域名到年底吧,也不打算要了.以后就在github上写点东西了.

之前使用Ubuntu的时候把Jekyll装好了,现在在windows上还想装上,以便可以方便写东西,今天搜了下,终于找到了安装的方法.

http://jekyll-windows.juthilo.com/

前面两步都比较顺利,在线安装Jekyll的时候,大陆抽风的网络一直连不上,之前在ubuntu上安装的时候,这个步骤也重试了很多次,看来还是要继续碰运气了.

1. 安装Ruby for Windows
2. 安装Ruby DevKit
3. 安装jekyll

```php
E:\jekyll>gem install jekyll
ERROR:  While executing gem ... (Gem::RemoteFetcher::FetchError)
    Errno::ECONNRESET: An existing connection was forcibly closed by the remote host. - SSL_connect (https://api.rubygems.org/quick/Marshal.4.8/jekyll-3.1.3.gemspec.rz)
E:\jekyll>gem install jekyll
ERROR:  While executing gem ... (Gem::RemoteFetcher::FetchError)
    Errno::ECONNRESET: An existing connection was forcibly closed by the remote host. - SSL_connect (https://api.rubygems.org/quick/Marshal.4.8/jekyll-3.1.3.gemspec.rz)
E:\jekyll>gem install jekyll
Fetching: safe_yaml-1.0.4.gem (100%)
Successfully installed safe_yaml-1.0.4
Fetching: rouge-1.10.1.gem (100%)
Successfully installed rouge-1.10.1
Fetching: mercenary-0.3.6.gem (100%)
Successfully installed mercenary-0.3.6
Fetching: liquid-3.0.6.gem (100%)
Successfully installed liquid-3.0.6
Fetching: kramdown-1.10.0.gem (100%)
Successfully installed kramdown-1.10.0
Fetching: ffi-1.9.10-x64-mingw32.gem (100%)
Successfully installed ffi-1.9.10-x64-mingw32
Fetching: rb-inotify-0.9.7.gem (100%)
Successfully installed rb-inotify-0.9.7
Fetching: rb-fsevent-0.9.7.gem (100%)
Successfully installed rb-fsevent-0.9.7
Fetching: listen-3.0.6.gem (100%)
Successfully installed listen-3.0.6
Fetching: jekyll-watch-1.3.1.gem (100%)
Successfully installed jekyll-watch-1.3.1
Fetching: sass-3.4.22.gem (100%)
Successfully installed sass-3.4.22
Fetching: jekyll-sass-converter-1.4.0.gem (100%)
Successfully installed jekyll-sass-converter-1.4.0
Fetching: colorator-0.1.gem (100%)
Successfully installed colorator-0.1
Fetching: jekyll-3.1.3.gem (100%)
Successfully installed jekyll-3.1.3
Parsing documentation for safe_yaml-1.0.4
Installing ri documentation for safe_yaml-1.0.4
Parsing documentation for rouge-1.10.1
Installing ri documentation for rouge-1.10.1
Parsing documentation for mercenary-0.3.6
Installing ri documentation for mercenary-0.3.6
Parsing documentation for liquid-3.0.6
Installing ri documentation for liquid-3.0.6
Parsing documentation for kramdown-1.10.0
Installing ri documentation for kramdown-1.10.0
Parsing documentation for ffi-1.9.10-x64-mingw32
Installing ri documentation for ffi-1.9.10-x64-mingw32
Parsing documentation for rb-inotify-0.9.7
Installing ri documentation for rb-inotify-0.9.7
Parsing documentation for rb-fsevent-0.9.7
Installing ri documentation for rb-fsevent-0.9.7
Parsing documentation for listen-3.0.6
Installing ri documentation for listen-3.0.6
Parsing documentation for jekyll-watch-1.3.1
Installing ri documentation for jekyll-watch-1.3.1
Parsing documentation for sass-3.4.22
Installing ri documentation for sass-3.4.22
Parsing documentation for jekyll-sass-converter-1.4.0
Installing ri documentation for jekyll-sass-converter-1.4.0
Parsing documentation for colorator-0.1
Installing ri documentation for colorator-0.1
Parsing documentation for jekyll-3.1.3
Installing ri documentation for jekyll-3.1.3
Done installing documentation for safe_yaml, rouge, mercenary, liquid, kramdown, ffi, rb-inotify, rb-fsevent, listen, jekyll-watch, sass, jekyll-sass-converter, colorator, jekyll after 16 seconds
14 gems installed
```