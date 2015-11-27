

## 博客英语词汇直通车  
**config** - onfiguration file is a software file used to configure the initial settings for a computer program——配置，初始化参数  
  
**tagline** - In entertainment, a tagline (or tag line[1][2]) is a small amount of text which serves to clarify a thought for, or designed with a form of, dramatic effect. Many tagline slogans are reiterated phrases associated with an individual, social group, or product. As a variant of a branding slogan, taglines can be used in marketing materials and advertising.
——宣传词，标语，口号或者信条。  
>"One ring to rule them all." – The Lord of the Rings[11]  
"Love means never having to say you're sorry" – Love Story[12][13][14]  
"To boldly go where no man has gone before" – Star Trek[15]   
"The truth is out there." – The X-Files[16]    

**URL** - 网页地址；网址
A URL is an address that shows where a particular page can be found on the World Wide Web. URL is an abbreviation for (缩略=) 'Uniform Resource Locator'.  

**bio**
个人简历(biography的缩写)  

**gravatar**- 全球通用头像  
[gravatar介绍网站](http://www.iplaysoft.com/gravatar.html)   
 
		相关词汇——avatar  头像
	n. 天神下凡,神之化身,具体化； （论坛、MSN等上使用的）头  像；;电影《阿凡达》 阿凡达  


**favicion**- A favicon is that small graphic that appears next to the URL in the address bar.
Favicon就是出现在地址栏URL旁边的图形.网站图标  

**head footer**Page Mode shows headers, footers, footnotes and page numbers.
页面模式可以显示页眉、页脚、脚注和页码。  

**nav** - 导航栏 

**sidebar** - 侧边栏  

**svg** - Scalable Vector Graphics (SVG) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. 可缩放矢量图形（Scalable Vector Graphics，SVG）是基于可扩展标记语言（XML），用于描述二维矢量图形的一种图形格式。SVG由W3C制定，是一个开放标准  

**yearly-archive** - 每年的存档  

**lightbox** -  灯箱特效  
[csdn解释](http://www.csdn123.com/html/20130206/53/bf7afd2efb1a5489f71786bef23f8186.htm)  
[扩展-10款插件](http://www.open-open.com/news/view/1c78bc4)  
<http://www.ijquery.cn/?p=160>  

* 大坑之安装ruby rubygems 安装jekyll等  图灵社区的一本书有具体指导 
<http://www.ituring.com.cn/article/66338>   
- 问题1（已解决） ：安装jekyll失败
- 尝试：改了gem sources之后（我复制[淘宝镜像网站](https://ruby.taobao.org) 的更换gem sources命令 --add https://ruby.taobao.org/命令可以 但是用--a它就报错）就安装jekyll成功了。  
- 问题2：（未解决）我运行jekyll serve的时候又报错   
```
       Deprecation: You appear to have pagination turned on, but you haven't included the `jekyll-paginate` gem. Ensure you have `gems: [jekyll-paginate]` in your configuration file.  
```  

## 背景
- 系统: mac 酋长石
- 版本: ruby 2.2.3p173 
所有的代码在这里  
```
wangxiaoyudeMacBook-Pro:Time-lady.github.io YoYo$ jekyll serve
Configuration file: /Users/YoYo/Time-lady.github.io/_config.yml
       Deprecation: You appear to have pagination turned on, but you haven't included the `jekyll-paginate` gem. Ensure you have `gems: [jekyll-paginate]` in your configuration file.
            Source: /Users/YoYo/Time-lady.github.io
       Destination: /Users/YoYo/Time-lady.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
       Deprecation: Collection#each should be called on the #docs array directly.
                    Called by /Users/YoYo/Time-lady.github.io/_plugins/author_generator.rb:74:in `write_author_indexes'.
author person @dir /author/person
author someone @dir /author/someone
author someone @dir /author/someone
author someone @dir /author/someone
author someone @dir /author/someone
author person @dir /author/person
author someone @dir /author/someone
author someone @dir /author/someone
author someone @dir /author/someone
author someone @dir /author/someone
author someone @dir /author/someone
                    done in 1.129 seconds.
       Deprecation: You appear to have pagination turned on, but you haven't included the `jekyll-paginate` gem. Ensure you have `gems: [jekyll-paginate]` in your configuration file.
 Auto-regeneration: enabled for '/Users/YoYo/Time-lady.github.io'
Configuration file: /Users/YoYo/Time-lady.github.io/_config.yml
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
^CwangxiaoyudeMacBook-Pro:Time-lady.github.io YoYo$ 
```  
- 判断：我的配置文档里好像缺了个东西，还在研究中......
