# Android HotFix And Plugin Framework

热修复随着移动端的发展也在近几年变得火热起来，所谓需求推动技术，热修复相较传统的开发流程有着明显的优势：

- 无需重新发版，修复实时高效，最大程度降低线上bug带来的损失。
- 无需下载新应用，增量更新，代价更小。

热修复方案也是百花齐放百家争鸣，最主要的两大方案是阿里系的底层替换方案与腾讯系的类加载方案。

- 底层替换方案：限制多，但是时效性好，加载块，立即生效。
- 类加载方案：时效性差，重新冷启动后才能生效，但是限制少。

我们来看下主流的方案的对比。

<img src=""/>
