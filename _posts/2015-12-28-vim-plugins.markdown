---
layout: post
title:  "记录自己的Vim插件"
date:   2015-12-28 15:19:14 +0800
categories: vim plugin
---
重新安装Ubuntu的另外一个原因是因为想使用Vim，其实在window系统上也有安装的，但是有比Vim用起来更方便的软件，我使用的是notepad++，由于惰性，经常绕道而行了。
    
现在使用Ubuntu也有使用gedit的时候，不过用了几次发现并不怎么好用，所以还是回到Vim上，强迫自己继续学习Vim。
    
###Vim插件管理：Pathogen
    
	之前vim的插件都是解压后，把相应的vim文件放到指定目录，安装多了，想要卸载，非常痛苦，安装的过程也挺繁琐的。这个就不多吐槽，相信使用过的人都能体会到。
    
	Pathogen项目地址：https://github.com/tpope/vim-pathogen
    
	安装方法，和插件管理方法在项目的Github上都有介绍的。
    
###其他插件List
    
    * matchit.zip
    * nerdtree
    * rainbow
    * syntatic
    * vim-autoformat
    * vim-colors-solarized
    * vim-indent-guides
    * vim-powerline
    
#### matchit.zip
    项目地址：https://github.com/vim-scripts/matchit.zip
    作用是可以使%自动跳转到匹配的H标签，这个在编写HTML代码时非常有用。
   
#### nerdtreee
    项目地址：https://github.com/scrooloose/nerdtree
    作用是显示树形目录插件

#### rainbow
	项目地址：https://github.com/luochen1990/rainbow
	彩虹括号增强版
	
#### syntastic
	项目地址：https://github.com/scrooloose/syntastic
	语法检测，发现有错误会报错的。这个在编码的时候很有用，可以有效避免运行时才发现错误，再保存的时候，就可以发现错误。
	
#### vim-autoformat
	项目地址：https://github.com/Chiel92/vim-autoformat
	代码格式化。
	：TODO

#### vim-colors-solarized
	项目地址：https://github.com/altercation/vim-colors-solarized
	经典配色

#### vim-indent-guides
	项目地址：https://github.com/nathanaelkane/vim-indent-guides
	缩进显示，使用颜色块来显示缩进

#### vim-powerline
	项目地址：https://github.com/Lokaltog/vim-powerline
	另外一个powerline【https://github.com/powerline/powerline】
	美观奢华的状态提示栏

目前使用到的插件是这些，等以后有机会再继续折腾别的插件。后面再把上面插件的整理一份详细的说明。
