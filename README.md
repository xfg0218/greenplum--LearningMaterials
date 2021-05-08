# greenplum--LearningMaterials
	主要介绍作者在网上收集相关的Greenplum想的学习资料，如果大家有好的资料欢迎大家分享
	

# Greenplum 新版本相关

## Greenplum 6新特性

1、[Greenplum6为你带来持续惊喜](https://mp.weixin.qq.com/s/UIKbir2y03E8u7ND_AHpYw)

2、[官方最强解读Greenplum6.0！](https://mp.weixin.qq.com/s/21IwOhFU_G_o5yzNWg6pTw)

3、[最新版本Greenplum 6.10已发布](https://mp.weixin.qq.com/s/S2Kn0DCmbp93hTCVXJX6Kg)



## Greenplum 7新特性

1、[当谈起Greenplum 7时,我们在谈什么?之组件篇](https://mp.weixin.qq.com/s/a2t8DjJVL9ZB-jC3DmnJQA)

2、[当谈起Greenplum 7时,我们在谈什么?之内核篇](https://mp.weixin.qq.com/s/sI7Fk-up3VlufP2UJ-IRvQ)


# Greenplum 配置相关

# Greenplum 优化相关



# Greenplum 组件相关

## 扩容插件GPExpand

1、[Greenplum6新特性,在线扩容工具GPExpand剖析](https://mp.weixin.qq.com/s/21IwOhFU_G_o5yzNWg6pTw)

## Pgbouncer最佳实践

1、[Pgbouncer最佳实践 之 概念篇](https://mp.weixin.qq.com/s/GhlHAdKHR1H40VRiziIJDg)

2、[Pgbouncer最佳实践 之 性能提升篇](https://mp.weixin.qq.com/s/hbGjmSCgb30Xp2vz_UIQRg)

3、[Pgbouncer最佳实践 之 池模式篇](https://mp.weixin.qq.com/s/MMGX0WV01ZX_Ha9B7CJ92A)

4、[Pgbouncer最佳实践 之 部署篇](https://mp.weixin.qq.com/s/2VAUaUZmsQyBN-FFD_M7UQ)


# Greenplum 插件相关


# Greenplum 巡检相关

# Greenplum 内核相关

1、[Brin Index在Greenplum 7中的理论与实现](https://www.modb.pro/event/301)



# Greenplum 常见问题汇总

## 1、relation "" contains more than "max_fsm_pages" pages with useful free space

1、[大量使用临时表带来的系统表如pg_attribute膨胀问题](https://billtian.github.io/digoal.blog/2016/06/15/01.html)

2、[Greenplum数据库的vacuum操作与max_fsm_pages参数的关系](http://www.voidcn.com/article/p-ankrklkc-mm.html)

## 2、 ERROR:  Unable to get sizes from segments (dbsize.c:92)
	
	1、检查master和每台segments上的配置信息select * from gp_segment_configuration;
	
	2、修改成语master一致即可
