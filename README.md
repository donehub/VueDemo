# vue-demo

## 项目搭建

### 一、基础介绍

1. IDE: [WebStorm](https://www.jetbrains.com/webstorm/download/) / [VS Code](https://code.visualstudio.com/);
2. 构建工具: [Node.js](http://nodejs.cn/) & [NPM](https://www.npmjs.com/);
3. 组件库: [Element](https://element.eleme.cn/#/zh-CN/component/installation)
   / [Iview](http://v1.iviewui.com/docs/introduce) / [cube](https://didi.github.io/cube-ui/#/zh-CN/docs/introduction);

### 二、安装 Node.js & NPM

目前 `Nodejs` 已内置 `NPM`，直接安装 `Nodejs` 就好了。`NPM` 是国外镜像，包加载速度慢，建议安装淘宝镜像 `CNPM`(这个理念类似于 Maven 仓库配置); 用管理员身份运行命令框，操作如下：

```
// Windows 命令框操作
>node -v
v14.15.4

>npm -v
6.14.10

>npm install -g cnpm --registry=https://registry.npm.taobao.org

>cnpm -v
cnpm 版本信息
```

### 三、安装模块打包器(webpack)

```
// Windows 命令框操作
>cnpm install webpack -g

// 安装过程中, 会提示安装 webpack 脚手架，默认 yes 或手动执行 (cnpm install -D webpack-cli)
>webpack -v
webpack 5.20.1
webpack-cli 4.5.0
```

### 四、安装 VUE-CLI

```
// Windows 命令框操作
>cnpm install --global vue-cli

>vue -V
2.9.6
```

### 五、创建第一个 VUE 项目

```
// IDE 操作步骤 (以 WebStorm 为例)
Open WebStorm > New Project > 选择 Vue.js > 定义项目名称 > Finish
```

### 六、运行第一个 VUE 项目

```
// 编译器终端操作
>cnpm install

>npm run server
```
