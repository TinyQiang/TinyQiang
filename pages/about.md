---
layout: page
title: About
description: TinyQiang's Blog
keywords: TinyQiang, sk, org.TinyQiang, Azolla, Maogu
comments: false
menu: About
permalink: /about/
---

这是 **TinyQiang** 的个人博客，始建于2019.08.04，算是个技术类博客吧（毕竟博主是个敲代码的）

从懵懂的Wordpress，至Java+Bootstrap自建，到现在的静态化Markdown。部分内容也由于格式等原因未能完全迁移

关注软件的维护性，可扩展性，致力于软件的高质量，快速开发

## 关于内容
崇尚原创

记记经历，碎碎阅历，说说屁事，谈谈破事，想想未来！


## 个人信息
男子，88年落地，在11年毕业于某省理工大学

略懂软件开发，假装对设计及架构很有研究

毕业后入职Neusoft，再经iSoftStone，而后eBaoTech，现工作于爱存不存


## 联系方式
{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}


## [简历](http://resume.qmail.com/sk/y6yYXbQSiDs)


## 技能
{% for category in site.data.skills %}
### [{{ category.name }}]({{ category.url }})
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}


## 产品
{% for product in site.data.products %}
* {{ product.desc }}：[{{ product.name }}]({{ product.url }})
{% endfor %}


## 发表

