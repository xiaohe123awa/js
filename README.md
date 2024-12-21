## 使用

1. 安装 Node.js 环境 
  
2. `npm i`安装依赖
   
3. 终端执行：
 npm run decode -- -t type [-i input.js] [-o output.js]

type 的意思：
* common (高频局部的混淆)
* jjencode  (sojson.com 版本)
* sojson  （jsjiami.v6 版本）
* sojsonv7 （jsjiami.v7 版本）
* obfuscator  （市面上通用加密）

1.文件中不能包含除混淆代码以外的内容（非混淆代码）

2.默认输出文件为`output.js`


例如:   node src/main.js -t sojsonv7 -i input.js -o output.js
