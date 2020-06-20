### 项目概述

LIGHT-UI组件库是一款基于[chameleon](https://github.com/didi/chameleon)开发一组跨多端的组件库。



### 功能支持

提供的组件包括弹层、消息提示、操作列表等组件，具备良好的跨多端能力。

### 如何使用

首先需要全局安装chameleon-tool

```
npm i chameleon-tool -g
```

然后初始化chameleon工程

```
cml init project
```

在初始化的chameleon工程中,安装组件库，`npm i @cmlkit/light-ui`

[配置babel-path](http://cml.didi.cn/docs/config.html#%E9%85%8D%E7%BD%AEbabel-loader%E5%A4%84%E7%90%86%E7%9A%84%E6%96%87%E4%BB%B6)

```javascript
const path = require('path');
cml.config.merge({
  babelPath: [path.resolve(__dirname, 'node_modules/test/')],
});
```

具体使用方式[文档参考](http://lightui.didi.cn/)
