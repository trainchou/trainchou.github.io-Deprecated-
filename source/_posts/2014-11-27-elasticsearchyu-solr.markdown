---
layout: post
title: "搜索引擎选择： ElasticSearch与Solr"
date: 2014-11-27 15:42:21 +0800
comments: true
categories: 大数据
---

## ElasticSearch的优点[<sup>1</sup>](http://stackoverflow.com/questions/10213009/solr-vs-elasticsearch):
> ## Advantages:

1. ElasticSearch 是分布式的。不需要单独的项目。复制几乎是实时的。
> ElasticSearch is distributed. No separate project required. Replicas are near real-time too, which is called "Push replication".

- ElasticSearch 支持 Apache Lucene 的近实时搜索。
> ElasticSearch fully supports the near real-time search of Apache Lucene.

- 处理**多用户**（[multitenancy](http://en.wikipedia.org/wiki/Multitenancy)）不需要特殊配置，而Solr则需要更多的高级设置。 
> Handling multitenancy is not a special configuration, where with Solr a more advanced setup is necessary.

- ElasticSearch 引入*网关?*（Gateway）的概念，使得完全备份更加简单。
> ElasticSearch introduces the concept of the Gateway, which makes full backups easier.

