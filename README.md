# start-ai-docker

 使用 docker 运行各种 AI 开源项目

## Ollama

仓库: <https://github.com/ollama/ollama.git>

### 使用 Docker 运行

- Linux 和 Windows(WSL2) 可以配置 GPU 加速
- macOS 不支持GPU加速，建议直接安装 app

### 默认模型保存路径

> 可以修改环境变量 `OLLAMA_MODELS`

- macOS: ~/.ollama/models
- Linux: /usr/share/ollama/.ollama/models
- Windows: C:\Users\%username%\.ollama\models

## Ollama WebUI

仓库: <https://github.com/open-webui/open-webui.git>
