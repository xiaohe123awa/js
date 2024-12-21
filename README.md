## 使用

1. 安装 nodejs环境 
  
2. `npm i`安装依赖
   
3. 运行插件：终端执行 ——> npm run xxx

或者   npm run decode -- -t type [-i input.js] [-o output.js]



`type`的意思：
* common (高频局部混淆)
* jjencode (sojson.com 版本)
* sojson
* sojsonv7
* obfuscator

1、文件中不能包含除混淆代码以外的内容（非混淆代码）
2、默认输出文件为`output.js`


例如:   node src/main.js -t sojsonv7 -i input.js -o output.js
