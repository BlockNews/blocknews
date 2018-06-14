# 开发环境准备

首个块闻版本将会基于微信小程序形式推出，所以我们需要准备如下工具和环境：

* [申请小程序账户，安装微信web开发者工具](https://developers.weixin.qq.com/miniprogram/dev/index.html)
* 因为微信小程序的开发基于node.js，所以我们需要安装[node.js](https://nodejs.org/en/)
* 微信开发者工具提供了一个默认的小程序框架，个人熟悉vue.js，找到了一个美团开发的[mpvue](http://mpvue.com/)小程序的前端框架。
* 如果你不太了解Vue.js，你可以到官网查看[vue.js官方文档](https://vuejs.org/)

# 环境搭建

## [申请小程序账户，安装微信web开发者工具](https://developers.weixin.qq.com/miniprogram/dev/index.html)

第一步微信小程序开发平台提供了详细的文档步骤，申请完账户后，以后我们每次登陆后台只需用绑定的微信扫描二维码就可以登陆。当然微信开发者工具也是通过二维码登陆。

## [安装node.js](https://nodejs.org/en/)

* Node.js是一个基于Chrome Javascript运行时建立的平台，是当前最流行的前端web开发技术。如果你想学习Node.js，推荐一个[Node.js教程](https://www.runoob.com/nodejs/nodejs-tutorial.html)。
* 更换npm源，我们可以通过npm下载安装和使用很多个人和公司共享发布的优秀的模块。由于默认的源比较慢，我们可以换成国内的源

`
$ npm set registry https://registry.npm.taobao.org/
$ npm get registry
`

* 如果你已经安装了node.js，想升级到最新稳定版本，运行命令

`
$ node -v
$ npm cache clean -f
$ npm install n -g
$ n stable
`

## 了解[vue.js](https://vuejs.org/)

vue.js是一个基于Node.js技术的用于构建交互式的Web界面的框架，推荐[Vue.js教程](http://www.runoob.com/vue2/vue-tutorial.html)

* 安装Vue.js，

`
$ npm install --global vue-cli
`


## 了解[mpvue](http://mpvue.com/)

mpvue是一款美团推出的使用Vue.js开发小程序的前端框架。

# 开发步骤

## 初始化项目blocknews

