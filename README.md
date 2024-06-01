### 改进版说明

#### 编译exe
```
pyinstaller --hidden-import=pyqt5 --hidden-import=lxml -F -n "labelImg" -c labelImg.py -p ./libs -p ./
```

#### 常用快捷键（labelImg.py）
w : 编辑模式
s : 选择模式
x : 删除
a ：上一张图
d ：下一张图