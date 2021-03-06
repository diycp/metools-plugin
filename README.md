## 这是什么？
>这是一个使用 vue.js 构建的纯静态工具,包含多种格式的加密/解密，编码/解密，二维码生成/识别,百度/有道的英汉互译,md与html互转，模板替换等功能
[![Build Status](https://travis-ci.org/yimogit/metools.svg?branch=master)](https://travis-ci.org/yimogit/metools)

### 插件预览
在线访问：https://metools.js.org

![图片](https://dn-coding-net-production-pp.qbox.me/89415c80-dae3-46dc-9abe-94fcad9971f1.png)


## 项目如何启动
0. 还原依赖包: `npm install` 
1. 运行：`npm run dev` 
2. 打包：`npm run build` //会自动将manifest.json与logo.png复制到dist目录，dist目录为插件目录

## 插件安装   
0. [商店下载](https://chrome.google.com/webstore/detail/metools/gpmjnakadlflmpekiimgbflnkmkncjie)
0. [Github下载](https://github.com/yimogit/metools-plugin/releases/download/v1.0/metools.crx) 
1. 打开chrome扩展页：chrome://extensions/
2. 将扩展拖到浏览器中。。


## 插件调试
0. 你需要一个chrome浏览器
1. 打开扩展列表：[chrome://extensions/](chrome://extensions/)
2. 启用开发着模式，加载dist目录即可
![图片](https://dn-coding-net-production-pp.qbox.me/c2c608ed-90d3-4dbe-98be-e6dc0c68f5c1.png)
3. 修改后，重新执行`npm run build`，然后重新加载插件即可在右上插件查看效果
4. 在调用chrome的api时，以` if (typeof chrome != undefined && chrome.tabs) {}`判断是否为插件模式
5. 同时可以将此应用部署到coding或者GitHub使用pages服务访问

## 插件开发
Api文档：http://open.chrome.360.cn/extension_dev/overview.html
