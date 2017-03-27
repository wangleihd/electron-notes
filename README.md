# electron-notes

## 安装

大陆到Electron源的下载速度极不稳定，无法下载成功时可用
- [中国](https://npm.taobao.org/mirrors/electron)

```sh

# 淘宝源开发依赖安装
ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/ npm install electron --save-dev

# 淘宝源全局安装
ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/ npm install electron -g
```

## meteor-apollo-electron

```sh
$ git clone https://github.com/apollographql/meteor-starter-kit
$ cd meteor-starter-kit
$ meteor npm install
$ ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/ meteor npm install --save-dev meteor-desktop

# 安装android或ios是为了满足--mobile-server的运行方式
$ meteor add-platform android     
$ meteor --mobile-server=127.0.0.1:3000

# 打开一个新term
$ npm run desktop -- init
$ npm run desktop
```
