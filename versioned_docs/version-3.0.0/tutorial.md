---
title: 框架
---

## 项目目录结构

    ├── dist                   编译结果目录
    ├── config                 配置目录
    |   ├── dev.js             开发时配置
    |   ├── index.js           默认配置
    |   └── prod.js            打包时配置
    ├── src                    源码目录
    |   ├── pages              页面文件目录
    |   |   ├── index          index 页面目录
    |   |   |   ├── index.js   index 页面逻辑
    |   |   |   └── index.css  index 页面样式
    |   ├── app.css            项目总通用样式
    |   ├── app.config.js      项目全局配置
    |   └── app.js             项目入口文件
    └── package.json

## 入口文件

入口文件默认是 `src` 目录下的 `app.js`。

代码示例请根据你选择的框架进行查看：[React](./react.html), [Nerv](./nerv.html), [Vue](./vue.html)。

### 全局配置


#### 配置项列表

Taro 中全局配置所包含的配置项及各端支持程度如下

| 属性 | 类型 | 必填 | 描述 | 微信小程序 | 百度小程序 | 字节跳动小程序 | 支付宝小程序 | H5 | RN
| - | - | - | - | - | - | - | - | - | - |
| [pages](#pages) | String Array | 
