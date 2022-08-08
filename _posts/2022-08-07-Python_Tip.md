---
layout : post
title : Python Tip
comments : true
categories : 
- Python
tags : [Python]
---
# Python Tip


## Pycharm 에서 코드 내 pip install 명령어 사용하기 

1. subprocess.check_call() 함수 사용하기
```python
import subprocess

subprocess.check_call([sys.executable, "-m", "pip", "install", 'numpy'])
subprocess.check_call([sys.executable, "-m", "pip", "install", 'pandas==1.3.5'])

```

2. os.system() 함수 사용하기
```python
import os

os.system("pip install numpy")

```