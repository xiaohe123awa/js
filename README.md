<details>
<summary> <-- https://pxx917144686.github.io/pxxjs</summary>

[![Preview](./xx/4.png)](https://pxx917144686.github.io/pxxjs/)
</details> 



## 使用

安装 Node.js 环境 ——> 官方版本  [Node.js](https://nodejs.org/zh-cn/download/prebuilt-installer)

## 推荐版本——>v22.12.0 (LTS)
<details>
<summary>Node.js 是一个开源的、跨平台的 JavaScript 运行时环境</summary>
Node.js 是一个开源的、跨平台的 JavaScript 运行时环境，允许开发者使用 JavaScript 在服务器端运行代码，从而构建各种网络应用，如网站、API、实时聊天应用等。它基于 Chrome 的 V8 引擎，具有高性能和高效的事件驱动架构，非常适合构建可扩展的网络应用。

LTS 是 Long Term Support（长期支持）的缩写。在 Node.js 的版本发布周期中，LTS 版本指的是那些经过充分测试、稳定且适合用于生产环境的版本。这些版本会在较长的时间内（通常是 30 个月）获得官方的维护和支持

大多数教程和学习资料都是基于 LTS 版本编写的

![Preview](./xx/5.png)
</details>   

### 下载链接 [js-main.zip](https://github.com/pxx917144686/js/archive/refs/heads/main.zip)
### 解压 `js-main.zip`
## 终端执行：
   cd js文件夹
```bash
cd js.main
```

  安装依赖  ——> 
```bash
npm i
```
  解码 ——>
```bash
node src/main.js -t sojsonv7 -i input.js -o output.js
```

## 使用 例子
```bash
node src/main.js -t sojsonv7 -i /Users/pxx917144686/Downloads/result.js -o output.js
```

node src/main.js -t sojsonv7 -i     #使用node（Node.js 环境）执行——>src/main.js -t sojsonv7

/Users/pxx917144686/Downloads/result.js   #需要解密的那个文件  可以直接拖入终端

-o output.js     #解密成功生成文件output.js 默认在脚本文件夹内

<details>
<summary>关于 ——> sojsonv7   可以替换</summary>

👇
* common (高频局部的混淆)
* jjencode  (sojson.com 版本)
* sojson  （jsjiami.v6 版本）
* sojsonv7 （jsjiami.v7 版本）
* obfuscator  （市面上通用加密）
</details> 

<details>
<summary>点击 ——> 提醒注意</summary>
注意:

* 文件中不能包含除混淆代码以外的内容（非混淆代码）

* 默认输出 ——> 文件为`output.js`
</details> 

<details>
<summary>jsjiami.v7 截图</summary>

jsjiami.com.v7 版本  👉  https://raw.githubusercontent.com/Yu9191/Rewrite/refs/heads/main/PDFexpert.js

![Preview](./xx/1.jpg)

👇
![Preview](./xx/2.jpg)

👇
![Preview](./xx/3.jpg)

</details> 
