# Asuri's CTF-wiki

该项目专门为Asuri线下赛搭建，主要用于展示离线保存的所有文档，供选手们能够快速检索阅读想要查找的资料

使用方法：
```bash
rm _sidebar.md
docsify g .
docsify s
```

已知bug：
> 1. 文件过多的时候前端全局搜索爆慢，有时候甚至没动静
> 2. 文件名中如果`.`开头或者带`#`等特殊字符，路径就会死掉，然后变成404