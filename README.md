## **1. 安装 Locust（确保正确安装）**

### **(1) 检查 Python 版本**

Locust 需要 **Python 3.6+**，先确认你的 Python 版本：

```
python --version
```

如果版本低于 3.6，去 Python 官网下载最新版。

### **(2) 使用 pip 安装 Locust**

```
pip install locust
```

**验证是否安装成功**：

```
pip show locust
```

如果显示版本信息（如 `Version: 2.xx.x`），说明安装成功。

------

## 2. 启动 Locust 

### ：`python -m locust`（最稳定）**

```
python -m locust -f locustfile.py
```
