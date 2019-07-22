# CLI简单模板

## 基本思路
>用户在终端输入命令，之后再根据用户选择设置最后的操作。

## 引用的库
**chalk**
>美化终端样式的插件
>具体源码和例子可以查看<a href="https://github.com/chalk/chalk">源码</a>

**commander**
>解析命令行命令
>具体源码和例子可以查看<a href="https://github.com/tj/commander.js">源码</a>

**inquirer**
>用于交互式命令行用户界面
>具体源码和例子可以查看<a href="https://github.com/SBoudrias/Inquirer.js">源码</a>

## 特殊的内容
>执行npm link 可以将当前项目添加到全局环境中

>package.json中添加
"bin": {
    "cli-template": "./index.js"
  }
  是告诉nodejs启动文件是index.js

## 总结
>此项目可以作为cli的基本模板，也可以作为项目的练习册

## 之后
>当前项目是模拟项目，模拟的目标npm。