# github-actions-bench
[byte-unixbenche](https://code.google.com/archive/p/byte-unixbench/)是一款比较好用的服务器跑分工具，跑分结果在500以上的话性能还算是OK的。
跑分的教程网上很多不再详细写了，有以下几步：
1. 禁用掉图像跑分。
2. make编译。
3. Run运行跑分。

这次的实验室是给[Github Actions](https://github.com/features/actions)跑分。Github Actions被广泛地运用在打卡和OpenWRT编译中（大雾），官方配置是2核心，7G内存？，看看他的性能如何。
