# Code Extractor 🚀

[![Download](https://img.shields.io/github/downloads/你的用户名/code-extractor/total?label=Downloads&logo=github)](https://github.com/你的用户名/code-extractor/releases/latest)
[![Version](https://img.shields.io/github/v/release/你的用户名/code-extractor?label=Version)](https://github.com/你的用户名/code-extractor/releases/latest)

> 高效的 VS Code 代码片段管理工具 - 提取、保存、复用你的代码

## 📥 安装

1. 前往 [Releases](https://github.com/你的用户名/code-extractor/releases/latest) 下载最新 `.vsix` 文件
2. 打开 VS Code，按 `Ctrl+Shift+P`
3. 输入 `Install from VSIX`，选择下载的文件

## ✨ 功能一览

### 🎯 核心功能

| 功能 | 快捷键 | 说明 |
|:-----|:------:|:-----|
| 📥 提取代码 | `Ctrl+Alt+S` | 选中代码一键保存为片段 |
| 🔍 快速插入 | `Ctrl+Alt+I` | 模糊搜索并插入片段 |
| 📋 右键提取 | - | 选中代码右键菜单快速提取 |

### 🗂️ 片段管理

| 功能 | 说明 |
|:-----|:-----|
| 📁 文件夹分类 | 创建文件夹组织片段 |
| ⭐ 收藏置顶 | 常用片段优先显示 |
| 🏷️ 多标签 | 为片段添加多个标签 |
| 🔀 拖拽排序 | 自由调整片段顺序 |
| 📊 多种排序 | 按时间/名称/使用次数 |
| ✏️ 实时编辑 | 在编辑器中修改，自动保存 |
| 🔧 代码格式化 | 一键格式化代码 |
| 📍 源文件跳转 | 跳转到代码原始位置 |

### 🔍 智能搜索

| 功能 | 说明 |
|:-----|:-----|
| 🎯 模糊匹配 | 输入 `cl` 匹配 `Console Log` |
| ✨ 搜索高亮 | 匹配关键词高亮显示 |
| 📝 全文搜索 | 搜索标题、标签、代码内容 |

### 🔗 片段引用

| 功能 | 说明 |
|:-----|:-----|
| 📎 引用语法 | `{{ref:片段名}}` 引用其他片段 |
| 🔄 自动展开 | 插入时展开所有引用 |
| ➕ 快速添加 | 一键添加引用 |

### 📐 模板变量

插入时自动替换：

| 变量 | 值 | 变量 | 值 |
|:-----|:---|:-----|:---|
| `$DATE` | 当前日期 | `$TIME` | 当前时间 |
| `$FILE` | 文件名 | `$DIR` | 目录名 |
| `$USER` | 用户名 | `$LINE` | 行号 |
| `$RANDOM` | 随机串 | `$UUID` | 唯一ID |

### 🧱 代码模板

| 功能 | 说明 |
|:-----|:-----|
| 📦 内置模板 | Console Log、Arrow Function、Try Catch 等 |
| ⭐ 自定义模板 | 添加/删除自己的模板 |
| 🔢 占位符 | 支持 `$1` `$2` 等 Snippet 占位符 |

### 📊 使用统计

| 功能 | 说明 |
|:-----|:-----|
| 📈 数据总览 | 片段总数、使用次数 |
| 🔥 Top 5 | 最常用片段排行 |
| 📊 语言分布 | 可视化占比图 |
| 📁 文件夹分布 | 各文件夹统计 |
| 📆 7日趋势 | 使用趋势图表 |

### ☁️ 云同步

| 功能 | 说明 |
|:-----|:-----|
| 🐙 GitHub Gist | 同步备份到 Gist |
| 👥 团队服务器 | 连接自建服务器共享 |

### 🤖 AI 功能

| 功能 | 说明 |
|:-----|:-----|
| 💡 代码解释 | OpenAI 解释代码逻辑 |

### 🛠️ 导入导出

| 功能 | 说明 |
|:-----|:-----|
| 📤 导出 | 导出为 JSON |
| 📥 导入 | 从 JSON 导入 |
| 📝 生成 Snippet | 转为 VS Code 原生片段 |

## ⚙️ 设置

在 VS Code 设置中搜索 `codeExtractor`：

| 设置项 | 说明 | 默认 |
|:-------|:-----|:----:|
| `defaultFolder` | 新片段默认文件夹 | `默认` |
| `autoResolveVars` | 自动解析模板变量 | `true` |
| `maxPreviewLength` | 预览最大字符数 | `150` |
| `showUseCount` | 显示使用次数 | `true` |
| `confirmBeforeDelete` | 删除前确认 | `true` |

## 📄 License

MIT
