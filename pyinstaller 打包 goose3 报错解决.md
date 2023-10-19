![[Pasted image 20231020003808.png]]
```python
pyinstaller -F --add-data "C:\Users\zhiqu\demo\Lib\site-packages\goose3;.\goose3" demo.py
```

把分号前面的换成自己的地址。

---
# 报错原因
goose3框架使用了文件配置，pyinstaller打包的时候没有把goose3框架里面的文件同步打包进去。