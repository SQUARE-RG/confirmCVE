# confirmCVE

更新NVD数据库：(首次部署前运行一次，接下来建议定期运行以保持同步)
```
cd src/nvdParser
python updateNVD.py
```


运行：
```
cd src/frontEnd
python server.py
```

记录测试数据：
修改`src/frontEnd/dataLoger.py`，`logdata`函数注释掉第一行的return，则可以在log.info中看到对软件包的分析结果