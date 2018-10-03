# nodejs

## 安装

Node.js是一个基于Chrome V8引擎的JavaScript运行环境。
Node.js使用了一个事件驱动、非阻塞式I/O的模型，使其轻量又高效。
node --version

Npm是Node.js上的包管理工具。
npm --version

1. 使用淘宝镜像

npm install -g cnpm --registry=https://registry.npm.taobao.org

2. 使用淘宝镜像的命令

cnpm install [name]

3. 本地安装

npm install express

4. 全局安装

npm install express -g

## Vue

```
cnpm install vue
#全局安装 vue-cli
cnpm install --global vue-cli
#创建一个基于 webpack 模板的新项目
vue init webpack my-project
#这里需要进行一些配置，默认回车即可
cd my-project
cnpm install
cnpm run dev
```

## React

```
cnpm install -g create-react-app
create-react-app my-app
cd my-app/
npm start
```

### Ant Designer

```
cnpm install antd
yarn add antd --save
```