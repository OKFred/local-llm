# ollama+open-webui+mcpo+chrome via docker

## 1. 介绍

这是一个基于Docker的项目，旨在将Ollama、Open-WebUI、MCPO和Chrome集成在一起，测试本地大模型的部署和基本的MCP调用。

## 2. 环境准备

- Docker

## 3. 部署

1. 克隆本项目到本地
2. 修改.env文件中的环境变量配置
3. 运行以下命令构建并启动Docker容器：
    ```bash
    docker compose up -d
    ```
4. 访问Open-WebUI界面，测试本地大模型的部署和MCP调用。

## 4. 停止

运行以下命令停止Docker容器：

```bash
docker compose down
```

LICENSE: MIT

Fred Zhang @ 2026
