---
title: 关于部署hexo博客和nexT主题遇见的小问题
date: 2019-12-07 16:40:29
tags: 研究
---

---
# 安装npm中国镜像

&emsp;&emsp;众所周知的一些原因，npm在中国的下载速度非常之慢，这里可以下载npm的某宝镜像来解放限速。打开terminal执行以下指令即可。

`npm install -g cnpm --registry=http://registry.npm.taobao.org`

<br/>

---
# 更改默认作者姓名
&emsp;&emsp; 进入blog的配置文件（此处为_config.yml）后在site中更改**author**。需要注意的是更改完成后需要**重启**hexo serve。

`hexo cl && hexo g && hexo s`