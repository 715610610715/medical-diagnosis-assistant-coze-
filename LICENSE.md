# 许可证说明

本仓库的代码来自多个来源，请分别遵守各自的许可条款：

## 1. 上游开源项目（二次开发的基础）

本系统基于开源项目 **sparrow-platform/disease-diagnostics-engine**（Docker Hub 镜像：
`jaylohokare/diseases-predictor`）二次开发，包括 `app.py`、`helper.py`、
`relatedSymptoms.py`、`generateLabels.py`、`cui2vec-converter.py`、`train.py`、
`en_Labels.js` 及训练数据等。使用/分发时请保留上游项目的版权与许可声明。

上游地址：https://github.com/sparrow-platform/disease-diagnostics-engine

## 2. umls/ 模块

`umls/` 目录版权归 **Boston Children's Hospital（2015）**，依据
**Apache License 2.0** 授权。完整许可文本见 `umls/LICENSE.txt`。

## 3. 本项目新增代码

`app_1119.py`、`app_gradio.py`、`medical_frontend.py`、`medical_call.py`、
`server_start.sh` 及 `README.md` 等由本项目团队编写，采用 **MIT License**：

```
MIT License

Copyright (c) 2025 本项目团队

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 4. UMLS 数据（umls.db）

UMLS（Unified Medical Language System）数据版权归美国国立医学图书馆（NLM），
使用需遵守 NLM 的 UMLS 许可协议。**`umls.db` 不随本仓库分发**，请向 NLM
申请后自行下载（见 `data/README.md`）。

> 注意：若你计划公开发布本仓库，请先确认上游项目的具体开源许可证
> （MIT/Apache 等），并在 README 中完整保留致谢与版权声明。
