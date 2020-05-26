---
title: 记录的实用方法
date: 2020-01-17 10:49:03
tags: 方法
categories: python
---

## 提取中文
```python
$ import re
$ name = "中国china"
$ re.compile(r'[\u4e00-\u9fa5]+').findall(name)[0]
```
