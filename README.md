## 这是一个关于用hexo创建个人博客的网站

## Hexo 怎么避免 .md 文件被解析？

在Hexo目录下的source根目录下添加一个README.md。修改Hexo目录下的_config.yml。将skip_render参数的值设置上：


```
skip_render:
 - README.md

```