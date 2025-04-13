# 环境配置指南

## 1. Python环境配置
1. Python版本要求：3.10.16
2. CUDA要求：12.2
3. 操作系统：推荐 Ubuntu 20.04 或 MacOS

## 2. 依赖包安装
1. 安装基础依赖：
```bash
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```
2. 由于requirements.txt 中引用了 tiktoken包，该包的安装需要rust环境编译，所以需要安装rust环境：
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```bash
安装rust环境，需注意网络条件，可能需要更换镜像源。

## 开发工具
1. IDE选择与配置
2. 版本控制
3. 调试工具

## 基础配置
1. 项目结构
2. 配置文件
3. 环境变量

## 常见问题
1. 安装问题解决
2. 环境冲突处理
3. 性能优化建议