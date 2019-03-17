# 罗马数字与阿拉伯数字转换的函数式实现（TDD）
采用 TDD 方式开发的函数式编程简单用例，主要用于说明和练习函数式编程与 TDD 的思维方式。

其中 test 文件夹下为测试用例，分别对阿拉伯数字与罗马数字互换的两个模块进行测试说明。测试用例的顺序即代表开发思路。

script 文件夹下为两个模块的实现代码。其中未引入额外的函数式编程库（例如 Ramda.js），主要用于说明函数式中数据流向，与使用一系列纯函数完成开发的过程。

## 运行
```
npm install
npm run test 或者 npm run test-w
```