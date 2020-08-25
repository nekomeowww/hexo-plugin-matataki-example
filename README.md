<h1 align="center">hexo-plugin-matataki-example</h1>
<p align="center">Hexo 和 hexo-plugin-matataki 的样例配置 | Example Blog Setup for Hexo and hexo-plugin-matataki</p>

## 基础 Basics

运行此实例需要全局安装 `hexo-cli`，
To run this instance, `hexo-cli` is required to be installed gloablly
如果你使用 npm，使用 `npm install -g` 来安装
If you are using npm, use `npm install -g` to install
```
yarn global add hexo-cli
```

本项目已经集成和安装了 hexo-plugin-matataki，如果你需要在你的博客中使用的话，可以使用这个命令安装
This project has been already integrated and installed hexo-plugin-matataki
```
yarn add hexo-plugin-matataki@latest
```

## 运行 Lift up
在安装 hexo-cli 之后，你可以使用下面的命令来展开一个网页服务器，这样你就可以看到实例的实际运行状态了
```
hexo s --debug
```