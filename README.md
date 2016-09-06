# Webpack 中文指南

[Webpack](https://github.com/webpack/webpack) 是当下最热门的前端资源模块化管理和打包工具。它可以将许多松散的模块按照依赖和规则打包成符合生产环境部署的前端资源。还可以将按需加载的模块进行代码分隔，等到实际需要的时候再异步加载。通过 `loader` 的转换，任何形式的资源都可以视作模块，比如 CommonJs 模块、 AMD 模块、 ES6 模块、CSS、图片、 JSON、Coffeescript、 LESS 等。

[主站](http://zhaoda.net/webpack-handbook) · [下载电子版](https://www.gitbook.com/book/zhaoda/webpack/details) · [国内镜像1](http://webpackdoc.com)（掘金）· [国内镜像2](http://wiki.jikexueyuan.com/project/webpack-handbook)（极客学院）

## 贡献内容

如果你想参与这本书的共同创作，修改或添加内容，可以先 [Fork](https://github.com/zhaoda/webpack-handbook) 这本书的仓库，然后将修改的内容提交 [Pull requests](https://github.com/zhaoda/webpack-handbook/pulls) ；或者创建 [Issues](https://github.com/zhaoda/webpack-handbook/issues)。

Fork 后的仓库如何同步本仓库？

```bash
// 添加 upstream 源，只需执行一次
$ git remote add upstream git@github.com:zhaoda/webpack-handbook.git

// 拉取远程代码
$ git pull upstream master

// 提交修改
$ git add .
$ git commit

// 更新 fork 仓库
$ git push origin master
```

更多参考： [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
