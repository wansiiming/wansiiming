# 王子鸣 · wansiiming

在校学生，方向是大模型应用与数据分析。习惯把一个项目从数据清洗、模型训练一直做到能跑起来的系统，而不只是停在 notebook 里。

## 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=flat-square&logo=apacheecharts&logoColor=white)

## 代表项目

### [企业风险评估系统](https://github.com/wansiiming/enterprise-risk-system)

Django 4.2 + MySQL + ECharts 的企业风险量化平台。四维评分算法、1 万条企业数据、多条件组合查询、可视化看板和中文 PDF 报告；接入云端 DeepSeek 与本地 Qwen 生成风险解释，文本风险识别用一个 Docker 化的 Flask + jieba 服务实现，服务不可用时降级为本地规则。

`Python` `Django` `MySQL` `LLM` `Docker`

### [司法 AI 助手](https://github.com/wansiiming/judicial-ai-assistant)

司法领域的大模型实践，分四个阶段推进：提示工程、RAG 检索增强、SFT 监督微调、DPO 偏好对齐，每个阶段都有可运行的训练与推理脚本。

`LLM` `RAG` `SFT` `DPO`

### [RetinaFace 人脸检测](https://github.com/wansiiming/retinaface-face-detection)

PyTorch 实现 RetinaFace：骨干网络、FPN 多尺度特征融合、多尺度 Anchor 生成，分类、边框回归、五点关键点三路损失，包含训练与推理全流程。

`PyTorch` `Computer Vision`

## 其他项目

- [信贷风险评分卡](https://github.com/wansiiming/credit-risk-scorecard)：WOE/IV 分箱、单调性检验与特征分析，附分箱结果图
- [视觉模型实验](https://github.com/wansiiming/vision-model-labs)：YOLO 目标检测、RAF-DB 表情识别、ResNet18/50 微调与训练曲线可视化

## 正在学习

- 大模型应用工程化：检索增强、效果评测与部署
- 表格数据的特征工程与模型可解释性
