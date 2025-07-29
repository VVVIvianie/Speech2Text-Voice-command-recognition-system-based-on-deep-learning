# Speech2Text-Voice-command-recognition-system-based-on-deep-learning
Aimed at implementing a lightweight voice command recognition system

# 🗣️ Speech2Text：基于深度学习的语音命令识别系统

## 项目简介
本项目旨在构建一个高效的语音命令识别系统，利用 Google Speech Commands 数据集，通过卷积神经网络（CNN）与 Transformer+CTC 架构实现对多种基本语音命令（如 "yes", "no", "up", "down"）的识别。该项目涵盖完整的音频处理流程、模型训练与评估，并分析两种主流架构在语音识别任务中的性能差异。
This project aims to build an efficient speech command recognition system, utilizing the Google Speech Commands dataset, and achieving recognition of various basic speech commands (such as "yes", "no", "up", "down") through a Convolutional Neural Network (CNN) and Transformer+CTC architecture. The project covers the complete audio processing workflow, model training and evaluation, and analyzes the performance differences between two mainstream architectures in speech recognition tasks.

## 技术栈
- Python
- Librosa / torchaudio
- PyTorch
- Scikit-learn
- Matplotlib / Seaborn

## 🧱 项目结构

Speech2Text-Command-Recognition/
│
├── data/                 # 音频数据
├── notebooks/            # 各阶段 Jupyter Notebook
├── src/                  # 模型与工具代码
├── report/               # 分析报告与可视化图
├── requirements.txt      # 依赖包
└── README.md             # 项目说明文档

## 🚀 项目阶段
- ✅ 阶段一：数据下载与音频探索  
- ⏳ 阶段二：特征提取（MFCC、Log-Mel）  
- ⏳ 阶段三：CNN 模型构建与训练  
- ⏳ 阶段四：Transformer + CTC 模型开发  
- ⏳ 阶段五：模型对比分析与结果总结

## 📊 项目目标
- 实现语音命令识别模型准确率 >90%
- 对比 CNN 与 Transformer 架构在小样本语音任务中的表现
- 整理项目报告

## 📁 数据来源
Google Speech Commands v0.02 数据集：  
[https://www.tensorflow.org/datasets/catalog/speech_commands](https://www.tensorflow.org/datasets/catalog/speech_commands)

## 📌 联系我
项目作者：蓝郁（Crystal）  
如需交流，可通过 GitHub Issues 
