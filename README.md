# React Bits 中文汉化补丁

这是针对 [React Bits](https://github.com/DavidHDev/react-bits) 本地演示站的简体中文汉化补丁。补丁保留英文组件名、代码标识和安装命令，便于与官方文档对应。

## 当前进度

已翻译公共导航、组件目录与中文搜索、217 个组件的名称和简介、安装与 MCP 指南、部分演示控件和属性说明。工具页面、演示内容及多数组件属性说明尚未全部翻译，汉化仍在进行中。

## 使用方法

请自行获取官方项目并遵守其许可证。此补丁针对上游提交 `e12c22192ac7b4b452c5e2feb9b586d74765d696`；其他版本可能需要手动调整。

```bash
git clone https://github.com/DavidHDev/react-bits.git
cd react-bits
git checkout e12c22192ac7b4b452c5e2feb9b586d74765d696
git apply /path/to/react-bits-zh.patch
npm ci
npm run dev
```

将 `/path/to/react-bits-zh.patch` 替换为补丁文件的实际路径。Windows 上可使用绝对路径并按需要加引号。

## 权利说明

React Bits 及其组件、工具由原作者提供，适用其[原始许可证](https://github.com/DavidHDev/react-bits/blob/e12c22192ac7b4b452c5e2feb9b586d74765d696/LICENSE.md)。本仓库仅保存汉化改动，不包含原项目的完整组件或工具源码；使用前请自行查阅原始许可条款。
