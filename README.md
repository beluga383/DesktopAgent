# DesktopAgent - 智能桌面操作助手

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue" alt="Python Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" alt="Platform">
</p>

<p align="center">
  基于视觉语言模型的智能桌面操作助手，可通过自然语言指令控制电脑执行各种桌面任务
</p>

## 🌟 项目简介

DesktopAgent 是一个基于视觉语言模型（VLM）的智能桌面操作助手，能够通过分析屏幕内容并执行鼠标、键盘等操作来完成用户指定的任务。它结合了先进的AI技术和桌面自动化功能，让用户可以通过简单的自然语言指令控制电脑。

### 核心功能
- 🎯 **视觉识别**：实时分析屏幕内容，理解当前界面状态
- 🤖 **自然语言交互**：通过自然语言描述任务需求
- 🖱️ **精准操作**：执行鼠标点击、拖拽、文本输入等操作
- ⚡ **多功能工具**：支持11种不同的桌面操作工具
- 🎨 **现代化界面**：仿微信风格的简洁优雅GUI界面
- 🛑 **任务控制**：支持随时停止正在执行的任务

## 🚀 快速开始

### 环境要求
- Python 3.7 或更高版本
- Windows/macOS/Linux 操作系统
- 网络连接（用于调用AI模型API）

### 安装依赖

pip install pyautogui pillow openai pyperclip
pip install pyperclip  # 用于更好的文本输入支持

### 配置API
打开你的main.py,更改以下内容：
      self.default_api_key = "这里写你的api"
        self.default_llm_model = "这里写一个llm模型"
        self.default_vlm_model = "这里写一个vlm模型"
        self.default_base_url = "这里写api地址"



