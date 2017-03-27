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

## meteor-apollo-electron 集成

```sh
$ git clone https://github.com/apollographql/meteor-starter-kit
$ cd meteor-starter-kit
$ meteor npm install
$ ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/ meteor npm install --save-dev meteor-desktop

#you need to have any mobile platform added (ios/android)
$ meteor add-platform android     
$ meteor --mobile-server=127.0.0.1:3000

 # open new terminal
$ npm run desktop -- init
$ npm run desktop
```
