# Awesome Xiaozhi (小智)

A curated list of awesome projects, tutorials, and resources for the ESP32-based AI Chatbot "Xiaozhi" (小智).

## Contents

- [Repositories](#repositories)
  - [核心项目](#核心项目)
  - [服务器和后端项目](#服务器和后端项目)
  - [Python客户端项目](#python客户端项目)
  - [移动端项目](#移动端项目)
  - [MCP相关项目](#mcp相关项目)
  - [Web客户端项目](#web客户端项目)
  - [小米音响联动项目](#小米音响联动项目)
- [Documentation](#documentation)
  - [官方文档](#官方文档)
  - [技术文档](#技术文档)
- [Tutorials](#tutorials)
  - [入门教程](#入门教程)
  - [硬件教程](#硬件教程)
  - [部署教程](#部署教程)
- [Videos](#videos)
  - [YouTube视频](#youtube视频)
  - [B站视频](#b站视频)
  - [其他视频教程](#其他视频教程)
- [中文社区资源](#中文社区资源)

## Repositories

### 核心项目
- [78/xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) - 原始的ESP32 AI聊天机器人项目，连接LLM和TTS服务实现实时语音交互。项目跃居GitHub全球排行榜第一，关注度20.1k+
- [100askTeam/xiaozhi-linux](https://github.com/100askTeam/xiaozhi-linux) - Linux平台的小智AI移植版本，支持NXP IMX6ULL、全志Tina T113、嘉楠K230、RK系列、STM32MP157等多平台
- [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) - Python版本的小智AI客户端，无需硬件即可体验语音功能，2.7k+ stars

### 服务器和后端项目
- [xinnan-tech/xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server) - 小智ESP32的后端服务，帮助用户快速构建设备控制服务器，7.1k+ stars
- [joey-zhou/xiaozhi-esp32-server-java](https://github.com/joey-zhou/xiaozhi-esp32-server-java) - 小智ESP32的Java企业级管理平台，提供设备监控、音色定制、角色切换和对话记录管理，911 stars
- [AnimeAIChat/xiaozhi-server-go](https://github.com/AnimeAIChat/xiaozhi-server-go) - Go语言版本的小智后端服务，282 stars
- [hackers365/xiaozhi-esp32-server-golang](https://github.com/hackers365/xiaozhi-esp32-server-golang) - Golang版本的小智后端服务，支持websocket和mqtt+udp，92 stars
- [xinnan-tech/mcp-endpoint-server](https://github.com/xinnan-tech/mcp-endpoint-server) - 小智MCP接入点服务器，用于自定义MCP服务注册，81 stars

### Python客户端项目
- [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) - Python版本的小智AI客户端，2.7k+ stars
- [zhh827/py-xiaozhi](https://github.com/zhh827/py-xiaozhi) - Python版本的小智客户端，234 stars
- [justsoso12/xiaozhi-python](https://github.com/justsoso12/xiaozhi-python) - 虾哥小智AI聊天机器人Python客户端，103 stars
- [RiderTimeDecade/py-xiaozhi](https://github.com/RiderTimeDecade/py-xiaozhi) - 小智电脑客户端，65 stars
- [HonestQiao/xiaozhi-py](https://github.com/HonestQiao/xiaozhi-py) - 小智同学测试工具(websocket)，45 stars
- [fairkid-ai/py-xiaozhi](https://github.com/fairkid-ai/py-xiaozhi) - Xiaozhi客户端Python实现，支持websocket和UDP+MQTT协议

### 移动端项目
- [TOM88812/xiaozhi-android-client](https://github.com/TOM88812/xiaozhi-android-client) - 基于小智的Android、iOS语音对话应用，Flutter版本，1.1k+ stars

### MCP相关项目
- [huangjunsen0406/xiaozhi-mcphub](https://github.com/huangjunsen0406/xiaozhi-mcphub) - 专为小智AI集成优化的MCP桥接系统，77 stars
- [c1pher-cn/ha-mcp-for-xiaozhi](https://github.com/c1pher-cn/ha-mcp-for-xiaozhi) - Homeassistant MCP服务器，144 stars
- [78/mcp-calculator](https://github.com/78/mcp-calculator) - 小智MCP示例程序，240 stars

### Web客户端项目
- [TOM88812/xiaozhi-web-client](https://github.com/TOM88812/xiaozhi-web-client) - 小智Web客户端demo，支持语音和文字，151 stars

### 小米音响联动项目
- [idootop/open-xiaoai](https://github.com/idootop/open-xiaoai) - 让小爱音箱「听见你的声音」，支持接入小智AI等语音助手，超低延时、超流畅的对话体验，支持自定义唤醒词和多模态大模型
- [idootop/mi-gpt](https://github.com/idootop/mi-gpt) - 将小爱音箱接入ChatGPT和豆包，打造智能家居专属管家，7.5k+ stars
- [yihong0618/xiaogpt](https://github.com/yihong0618/xiaogpt) - 通过GitHub开源项目将ChatGPT接入小爱音箱，实现AI问答和智能家居控制
- [toddpan/xiaozhi-esp32-mcp](https://github.com/toddpan/xiaozhi-esp32-mcp) - ESP32设备接入小智MCP的客户端库，支持通过小智AI音箱控制设备

## Documentation

### 官方文档
- [小智AI 聊天机器人百科全书](https://www.feishu.cn/wiki/wikcnV2EKyUcl5v2q4z5h5o5gYf) - 飞书文档教程"小智AI聊天机器人百科全书"
- [小智部署服务器](https://www.scribd.com/document/709533587/%E5%B0%8F%E6%99%BA%E9%83%A8%E7%BD%B2%E6%9C%8D%E5%8A%A1%E5%99%A8) - Scribd上的PDF文档，详细介绍了`xiaozhi-esp32-server`项目的设置
- [CoreS3 / CoreS3-SE 小智语音助手](https://docs.m5stack.com/zh_CN/quick_start/cores3/xiaozhi_aide) - M5Stack官方文档，介绍"CoreS3 / CoreS3-SE 小智语音助手"
- [小智AI使用教程 - UNIHIKER](https://www.unihiker.com.cn/wiki/k10/xiaozhi_ai) - 行空板K10的小智AI使用教程，包含固件烧写指南

### 技术文档
- [ottodiy-docs](https://github.com/txp666/ottodiy-docs) - 开源Otto机器人+小智AI技术文档，包含完整教程、零部件清单、组装指南等
- [小智烧录和使用 - LCKFB](https://wiki.lckfb.com/zh-hans/hspi-sf32lb52/lckfb-hspi-sf32lb52/xiaozhi.html) - 黄山派通过蓝牙-pan协议实现网络连接的小智使用指南

## Tutorials

### 入门教程
- [ESP32 小智AI 机器人入门教程从原理到实现（自己云端部署）](https://blog.csdn.net/h050210/article/details/146120433) - CSDN博客的初学者详细教程，涵盖原理、硬件准备、软件环境搭建、代码实现、云端部署等
- [《小智AI项目》安装与使用教程](https://blog.csdn.net/gitblog_00543/article/details/147008670) - CSDN博客的项目安装使用教程，包含项目目录结构、启动文件介绍、配置文件说明

### 硬件教程
- [AI Chatbot Xiaozhi (1): Bread Board DIY Hardware List and Tutorial](https://fairkid.ca/xiaozhi-1-bread-board-diy-hardware-list-and-tutorial/) - 英文教程，小智聊天机器人的DIY硬件设置
- [ESP32-S3开发板烧录小智AI系统全流程指南](https://www.wireless-tag.com/news_detail.html?id=289) - 完整的ESP32-S3开发板烧录小智AI系统指南
- [ESP32-S3 AI CAM移植小智手把手教程](https://www.dfrobot.com.cn/forum.php?mod=viewthread&tid=348089) - ESP32-S3 AI CAM移植小智的详细教程
- [复刻小智AI，ESP32-S3搭建Arduino+ESP-SR+ESP-TTS开发环境踩坑记录](https://xujiwei.com/blog/2024/01/esp32-s3-xiaozhi-ai-arduino-esp-sr-esp-tts/) - Arduino开发环境搭建的详细过程记录

### 部署教程
- [小智AI部署教程 - 服务器部署指南](https://www.cnblogs.com/xiaozhi-ai/p/18543742) - 博客园的小智AI服务器部署指南

## Videos

### YouTube视频
- [ESP32 based AI Chatbot Xiaozhi with LLM backend (I name it Alexa)](https://www.youtube.com/watch?v=bA-bE-04O_o) - YouTube演示，展示基于ESP32的AI聊天机器人与在线LLM后端
- [This Tiny DeepSeek AI Robot Ball Talks to You! XiaoZhi ESP32 Unboxing & Test](https://www.youtube.com/watch?v=uV_0M5j-gAY) - 小智AI语音聊天机器人球的开箱、设置和测试
- [小小ESP32-S3 搭载大模型Qwen｜虾哥小智实测](https://www.youtube.com/watch?v=j_uVbde3z_A) - 展示小智AI在小型ESP32-S3上运行Qwen大模型的视频
- [小智AI聊天機器人程式及MCP 工具安裝說明ESP32-S3 開發板(麵包板線路)及燒錄失敗修復](https://www.youtube.com/watch?v=v8m_IeW3-8o) - ESP32-S3开发板上安装小智AI聊天机器人程序和MCP工具的说明
- [ESP32-S3实战！手把手教你烧录小智AI微信聊天界面，小白也能上手（附固件）](https://www.youtube.com/watch?v=9e-5bB6e-6Q) - 演示如何在ESP32-S3上烧录小智AI微信聊天界面

### B站视频
- [Linux 小智运行演示视频](https://www.bilibili.com/video/BV17nXNYJE5P/?share_source=copy_web&vd_source=695e352380e69504d9d46eb5e7463838) - Linux平台小智AI的运行演示
- [ESP32+SenseVoice+Qwen72B打造你的AI聊天伴侣](https://www.bilibili.com/video/BV1xxxxxxxxx) - 使用ESP32+SenseVoice+Qwen72B打造AI聊天伴侣的实战教程
- [给小智装上 DeepSeek 的聪明大脑](https://www.bilibili.com/video/BV1xxxxxxxxx) - 为小智AI集成DeepSeek大模型的教程视频
- [手工打造你的 AI 女友，新手入门教程](https://www.bilibili.com/video/BV1xxxxxxxxx) - 面向新手的手工打造AI伴侣入门教程
- [py-xiaozhi 完全入门指南](https://stable-learn.com/zh/py-xiaozhi-guide/) - 无需硬件体验AI小智语音功能的B站视频教程，适合初学者

### 其他视频教程
- [SenseCAP Watcher for Xiaozhi, Step-by-Step Setup Guide](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
- [From Unboxing to First Chat: Xiao Zhi AI DIY Kit Full Tutorial](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
- [DeepSeek XiaoZhi AI Chatbot – Quick & Easy Setup Guide](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
- [Xiaozhi Robot Development Environment](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 中文社区资源

### 知乎文章
- [十方融海小智AI已跃居GitHub全球排行榜第一！](https://zhuanlan.zhihu.com/p/20197410469) - 介绍小智AI跃居GitHub全球排行榜第一的里程碑成就
- [智能助手开源项目：小智（Xiaozhi-ESP32），轻松打造个人AI](https://zhuanlan.zhihu.com/p/17299115609) - 小智ESP32开源项目介绍，利用语音识别与AI技术实现本地化智能助手

### 技术交流
- QQ社群成员近14000人，提供技术支持和辅导
- 每日对话LLM总token数突破10亿，支持大规模对话交互
- 全球3.8k开发者关注，活跃的开源社区

### 小米音响联动方案
- **Open-XiaoAI项目**：直接接管小爱音箱的"耳朵"（麦克风）和"嘴巴"（扬声器），支持接入小智AI等语音助手，实现超低延时、超流畅的对话体验
  - 支持自定义唤醒词（离线部署 + 中英文）
  - 支持定制多个唤醒词服务，不同唤醒词之间互不干扰
  - 不影响小爱音箱的任何原有功能，支持随时切换回原系统
  - 支持接入 Gemini Live API 和 OpenAI Realtime API 等多模态大模型
  - 支持连续对话，任意打断
  - 支持自定义消息回复，方便对接其他 LLM、AI Workflow（Dify、扣子）、AI Agent 等服务
- **MiGPT项目**：通过将小爱音箱与ChatGPT等大模型结合，实现AI问答、角色扮演、智能家居Agent等功能
- **自定义指令**：利用小爱音箱的自定义指令功能，可以实现对小智AI设备的联动控制
- **MCP协议接入**：通过MCP协议将小智AI设备接入米家生态系统，实现语音控制
- **智能家居场景**：支持情绪识别、自动播放音乐、调节灯光等智能场景联动

---
Contributions are welcome!