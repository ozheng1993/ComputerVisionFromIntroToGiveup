---
description: 我们可以通过调用CV2 包以验证OpenCV是否安装成功
---

# 安装-验证

安装完成后，右侧的复选框会呈现被选中状态

![](../.gitbook/assets/screen-shot-2019-06-09-at-1.59.25-pm.png)

### 

此时我们可以双击左侧Home按钮回到主界面，在双击Jupyter Notebook（没有安装的双击install即可安装）。

![](../.gitbook/assets/screen-shot-2019-06-09-at-2.02.35-pm.png)

在Jupyter notebook中导航到你希望存放文件的文件夹，双击右上角New按钮创建新的python 3文件

![](../.gitbook/assets/screen-shot-2019-06-09-at-2.04.26-pm.png)

双击进入刚刚创建的Python 3文件，输入一下代码

```python
import cv2
cv2.__version__
```

如果获得和下图一样的输出，即可证明OpenCV已安装成功

![](../.gitbook/assets/screen-shot-2019-06-09-at-2.07.24-pm.png)

