# 有用工具

> 浏览器本地工具集 — 纯前端，文件不上传服务器

一个纯前端、**文件不上传服务器** 的工具集。所有操作在浏览器本地完成。

## 功能

| 模式 | 说明 |
|------|------|
| **合并** | 将多个 PDF 按顺序合并为一个，支持拖拽调整顺序 |
| **插入** | 将某份 PDF 的指定页面插入到另一份 PDF 的任意位置 |
| **导出** | 从 PDF 中提取指定页面（全部/奇数页/偶数页/自定义范围） |
| **图片转 PDF** | 将多张图片合并为一个 PDF，每张图片为一页 |

## 使用

直接用浏览器打开 `pdf-tools.html` 即可，无需安装任何东西。

也可在线使用：[https://xiyunzhang0401.github.io/useful-tools/pdf-tools.html](https://xiyunzhang0401.github.io/useful-tools/pdf-tools.html)

> **Windows 用户注意**：下载的 PDF 如果打开时报错，请右键该 PDF 文件 → **属性** → 勾选 **解除锁定** → 确定，然后重新打开。

## 技术

- [pdf-lib](https://pdf-lib.org/) — PDF 创建与编辑
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF 渲染与预览
- 纯 HTML/CSS/JS，无后端依赖

## 隐私

所有操作在浏览器本地完成，**文件不会离开你的设备**。

## 许可

MIT
