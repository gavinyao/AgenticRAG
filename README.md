# 🚀 AgenticRAG
A Agentic RAG Web UI application built with LangGraph, FastAPI and Streamlit.  

关注我的微信公众号获取最新推送

![wechat_qrcode](https://github.com/realyinchen/RAG/blob/main/imgs/wechat_qrcode.jpg)

### 主要特点
🧠 最先进的 RAG 应用开发技术 
📚 每种技术的综合文档  
🛠️ 实用的实施指南  
🌟 定期更新最新进展  

# 教程概述

本教程将以 LangGraph 框架为主介绍了各种当今流行的 Aentic RAG 应用。  

入门教程都在 tutorials 目录下。

### 运行环境

首先需要安装 VS Code，[点击下载](https://code.visualstudio.com/Download)。

1. 安装 [miniconda](https://docs.anaconda.com/miniconda/miniconda-install/)
2. 创建虚拟环境  
    ``` bash
    $ conda create -n arag python=3.12
    ```
3. 激活虚拟环境  
    ``` bash
    $ conda activate arag
    ```
4. 配置 jupyter kernel  
    ``` bash
    $ conda install -c anaconda ipykernel
    $ python -m ipykernel install --user --name arag
    ```
5. 将项目根目录下的环境变量配置文件重命名，并根据实际情况，填入你的配置信息  
    ``` bash
    $ mv .example.env .env
    ```

6. 安装依赖包
    ``` bash
    $ pip install -r requirements.txt
    ```

7. 运行后端（暂时不支持）
    ``` bash
    $ python run_service.py
    ```

8. 运行前端（暂时不支持）
    ``` bash
    $ streamlit run app.py
    ```
