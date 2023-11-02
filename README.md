# Learn-Redis



# 参考

[Redis 设计与实现 — Redis 设计与实现 (redisbook.com)](http://redisbook.com/)

[how-to-read-redis-source-code]([blog/diary/2014/how-to-read-redis-source-code.rst at d9b0a5e773babca13c1a3b7d2546336172f986e8 · contestjia/blog (github.com)](https://github.com/contestjia/blog/blob/d9b0a5e773babca13c1a3b7d2546336172f986e8/diary/2014/how-to-read-redis-source-code.rst#L4))

[Redis3.0源码](https://github.com/huangz1990/redis-3.0-annotated)


- [x] sds.h
- [ ] sds.c


| 文件                                                         | 内容                        |
| ------------------------------------------------------------ | --------------------------- |
| `sds.h` 和 `sds.c`                                           | Redis 的动态字符串实现。    |
| `adlist.h` 和 `adlist.c`                                     | Redis 的双端链表实现。      |
| `dict.h` 和 `dict.c`                                         | Redis 的字典实现。          |
| `redis.h` 中的 `zskiplist` 结构和 `zskiplistNode` 结构， 以及 `t_zset.c` 中所有以 `zsl` 开头的函数， 比如 `zslCreate` 、 `zslInsert` 、 `zslDeleteNode` ，等等。 | Redis 的跳跃表实现。        |
| `hyperloglog.c` 中的 `hllhdr` 结构， 以及所有以 `hll` 开头的函数。 | Redis 的 HyperLogLog 实现。 |