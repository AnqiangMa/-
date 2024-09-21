# 二维码生成器 Chrome 扩展

这是一个简单的 Chrome 扩展，可以将当前页面或自定义 URL 转换为二维码。

## 功能

- 自动生成当前页面 URL 的二维码
- 支持输入自定义 URL 生成二维码
- 可为生成的二维码命名
- 保存历史记录，支持置顶和删除操作
- 一键清除所有历史记录

## 安装

1. 下载或克隆此仓库到本地
2. 打开 Chrome 浏览器，进入 `chrome://extensions/`
3. 开启右上角的"开发者模式"
4. 点击"加载已解压的扩展程序"
5. 选择包含此扩展的文件夹

## 使用

1. 点击 Chrome 工具栏中的扩展图标打开弹出窗口
2. 默认显示当前页面 URL 的二维码
3. 可以在输入框中输入自定义 URL 并为其命名
4. 点击"生成二维码"按钮生成新的二维码
5. 历史记录会显示在右侧，可以进行置顶和删除操作
6. 点击"清除全部历史记录"可以删除所有历史记录

## 文件结构

- `manifest.json`: 扩展的配置文件
- `popup.html`: 弹出窗口的 HTML 结构
- `popup.js`: 弹出窗口的 JavaScript 逻辑
- `styles.css`: 弹出窗口的样式表
- `qrcode.min.js`: 用于生成二维码的库
- `images/logo.png`: 扩展图标

## 依赖

- [QRCode.js](https://github.com/davidshimjs/qrcodejs): 用于生成二维码的 JavaScript 库

## 许可

[MIT License](LICENSE)
