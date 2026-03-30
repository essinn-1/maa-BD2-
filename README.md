  用MaaEnd改的BD2小助手（贴上本尊 github.com/MaaEnd/MaaEnd ），真的好用，离开了maaend本人都不想玩终末地了（懒得做每日）
  这个项目是边学（学，指将看不懂的东西丢给ai）边做的，可能会出问题还请多多包涵~~~
  话说隔壁（ github.com/sunyink/MFABD2  ）老师们的这个作品完善多了，本人之前搓这个小助手的时候没有看到（流泪），
又（像老师们说的“拒绝给游戏打工！”）所以才试着写了这个东西~
  不嫌弃的话可以试试用这个，虽然很多功能碍于本人技术实现不了（一个不成熟的项目~），推荐去用各大佬写的更加完善的内容~


# MAA BrownDust Assistant

基于 MAA (MaaAssistantArknights) 框架的 BrownDust 游戏自动化助手。

## 项目简介

本项目是基于 [MAA](https://github.com/MaaAssistantArknights/MaaAssistantArknights) 框架开发的 BrownDust 游戏自动化工具，支持自动日常任务、资源收集等功能。

## 开源许可证

### 本项目许可证
本项目基于 **AGPL-3.0** 协议开源。

[AGPL-3.0 License](LICENSE)

### 使用的开源项目

本项目使用了以下开源项目：

#### 1. MAA (MaaAssistantArknights)
- **项目地址**: https://github.com/MaaAssistantArknights/MaaAssistantArknights
- **许可证**: AGPL-3.0
- **用途**: 游戏自动化框架基础

#### 2. PaddleOCR (PP-OCRv5)
- **项目地址**: https://github.com/PaddlePaddle/PaddleOCR
- **许可证**: Apache License 2.0
- **用途**: 游戏内文字识别（OCR）
- **使用方式**: 调用 PP-OCRv5 移动端文本检测模型

## 声明

根据 AGPL-3.0 协议要求：
- 本项目及其衍生项目必须开源
- 任何对本项目的修改必须公开源代码
- 本项目仅供学习交流使用

根据 Apache License 2.0 要求：
- 本项目使用了 PaddleOCR，保留其版权声明
- 详见 [NOTICE](NOTICE) 文件

## 下载与使用

### 方式一：下载发布版本（推荐）
访问 [Releases](https://github.com/essinn-1/maa-assistant/releases) 页面下载最新版本。

### 方式二：从源码编译
```bash
# 克隆仓库
git clone https://github.com/essinn-1/maa-assistant.git

# 安装依赖
# 具体编译步骤请参考文档