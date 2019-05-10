<!--
 * @LastEditors: Tiger
 * @Description: In User Settings Edit
 * @Author: Tiger
 * @Date: 2019-05-10 14:43:35
 * @LastEditTime: 2019-05-10 14:49:11
 -->

**_vscode 透明主题_**

- mac 版本

* 安装插件 Custom CSS and JS Loader
* 配置 css 和 js 文件
* 添加 vscode 的 setting 设置
  `// 全局透明主题 需安装Custom CSS and JS Loader 并配置css和js文件 "vscode_custom_css.imports": [ "file:///Users/apple/Documents/custom.css", "file:///Users/apple/Documents/custom.js" ], "vscode_custom_css.policy": true, // 终端透明 "terminal.integrated.rendererType": "dom",`
* cmd+shift+p -> Reload Custom CSS and JS
* 重启 vscode
