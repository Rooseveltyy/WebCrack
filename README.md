# WebCrack
网站后台弱口令/万能密码批量检测工具

## 简介

https://yzddmr6.tk/2019/08/18/webcrack/


## PS

~~因为工具还没有写到我满意的程度，也没有想好如何让工具真正做到为安全服务，所以暂时不开源。~~

将于最近在个人星球里开源

## debug记事本

2019.9.6

今天又是debug的一天

优化了代码的结构，去掉了某些不必要的参数

比如说判断后台传参的方式

除了傻屌没人会用get吧。。。

修复了当success_flag为空时导致无法往下判断的逻辑bug

晚上跑一批url试试

2019.9.5

把special_cms的识别放到了json中作为配置文件，这样就可以自定义爆破参数啦

ecshop真是个神奇的cms。。。。

怎么他的验证这么恶心。。。


long long ago...

抓了一万个包。。。

改判断逻辑改到吐。。。

世界上的傻屌网站怎么这么多，写的一点都不规范。

增加随机UA头 随机X-Forwarded-For和 随机Client-IP

可以通过域名生成动态字典

可以探测系统是否存在因为设计缺陷而造成的万能密码漏洞

代码结构优化，提高性能

增加special_case，可以识别部分cms，并针对结果采用指定的识别方式

修复reset按钮带来的bug
