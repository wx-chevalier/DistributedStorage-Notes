[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey.svg)][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/wx-chevalier/DistributedSystem-Series">
    <img src="header.svg" alt="Logo" style="width: 100vw;height: 400px" />
  </a>

  <p align="center">
    <a href="https://wx-chevalier.github.io/DistributedSystem-Series"><strong>在线阅读 >> </strong></a>
    <br />
    <br />
    <a href="https://github.com/wx-chevalier/Awesome-CheatSheets">速览手册</a>
    ·
    <a href="./examples">代码案例</a>
    ·
       <a href="https://github.com/wx-chevalier/Awesome-Lists">参考资料</a>
    ·
    <a href="./README.en.md">English Version</a>

  </p>
</p>

![](https://i.postimg.cc/Z56JHk17/image.png)

# 分布式存储

分布式存储系统，广义上来讲，将文件存储抽象化，之前提到的块存储和对象存储都建立在这个系统之上。从某些角度来讲，存储系统相当于中间件，建立在底层的 SATA 或者 SSD 磁盘之上，而服务于上层的块存储。

## 挑战

分布式存储系统（Distributed Storage System）的核心不外乎两点：分片策略（Sharding Strategy）与元数据存储（Metadata Storage）机制，我们在保证存储系统弹性可扩展（Elastic Scalability）的同时需要保证系统的透明性（Transpant）与一致性（Consistent）。

## Nav | 关联导航

- 如果你想了解微服务/云原生等分布式系统的应用实践，可以参阅；如果你想了解数据库相关，可以参阅 [Database-Series](https://github.com/wx-chevalier/Database-Series)；如果你想了解虚拟化与云计算相关，可以参阅 [Cloud-Series](https://github.com/wx-chevalier/Cloud-Series)；如果你想了解 Linux 与操作系统相关，可以参阅 [Linux-Series](https://github.com/wx-chevalier/Linux-Series)。

# About

## Copyright & More | 延伸阅读

笔者所有文章遵循 [知识共享 署名-非商业性使用-禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。您还可以前往 [NGTE Books](https://wx-chevalier.github.io/books/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

[![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)](https://wx-chevalier.github.io/books/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/wx-chevalier/DistributedSystem-Series.svg?style=flat-square
[contributors-url]: https://github.com/wx-chevalier/DistributedSystem-Series/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/wx-chevalier/DistributedSystem-Series.svg?style=flat-square
[forks-url]: https://github.com/wx-chevalier/DistributedSystem-Series/network/members
[stars-shield]: https://img.shields.io/github/stars/wx-chevalier/DistributedSystem-Series.svg?style=flat-square
[stars-url]: https://github.com/wx-chevalier/DistributedSystem-Series/stargazers
[issues-shield]: https://img.shields.io/github/issues/wx-chevalier/DistributedSystem-Series.svg?style=flat-square
[issues-url]: https://github.com/wx-chevalier/DistributedSystem-Series/issues
[license-shield]: https://img.shields.io/github/license/wx-chevalier/DistributedSystem-Series.svg?style=flat-square
[license-url]: https://github.com/wx-chevalier/DistributedSystem-Series/blob/master/LICENSE.txt
