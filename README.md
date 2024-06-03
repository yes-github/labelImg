### 改进版说明

#### 编译exe
```
pyinstaller --hidden-import=pyqt5 --hidden-import=lxml -F -n "labelImg" -c labelImg.py -p ./libs -p ./
```

#### 常用快捷键（labelImg.py）
up : 编辑模式
down : 选择模式
delete : 删除
left ：上一张图
right ：下一张图