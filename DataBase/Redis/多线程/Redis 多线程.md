## Redis 多线程

![微信图片_20200615110720](assets/微信图片_20200615110720-1592190461788.jpg)



## 阿里的Redis多线程的时序交互图



![微信图片_20200615110555](assets/微信图片_20200615110555.jpg)



## Redis 6.0 

Redis也只是在网络数据读写这块支持了多线程，其他的命令执行依然是单线程执行。这样也避免了很多多线程的复杂性问题。



## 参考资料

https://mp.weixin.qq.com/s/VzNIM9UEJbnvdmb1Eaosnw