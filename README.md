# My Project

这是我 搭建的 Python 项目骨架。

## 安装依赖

```bash
pip install -r requirements.txt
```

## 运行程序

Mac / Linux:

```bash
PYTHONPATH=src python scripts/day01_hello.py
```

Windows PowerShell:

```powershell
$env:PYTHONPATH="src"; python scripts/day01_hello.py
```

## 运行测试

```bash
pytest -q
```

## 检查代码

```bash
ruff check .
```
