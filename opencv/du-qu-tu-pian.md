---
description: 如何读取，展示和保存图片
---

# 图片操作

## 1.读取图片

 **cv2.imread\(\)** 是OpenCV 在 Python中读取图片的接口。对应的图片需要放在对应的文件夹下或者输入图片完整的文件路径。

**cv2.imread\(\)** 通过第二个变量来定义读入图片的类型：

```python
cv2.imread('xx.jpg'，1)#读取彩色图,默认的图片类型
cv2.imread('xx.jpg'，0)#读取灰度图
cv2.imread('xx.jpg'，-1)#读取带有透明度（alpha channel)的图片
```

以下是读取图片的代码：

```python
#加载 python 库
import numpy as np
import cv2
# 输入路径读取图片
img = cv2.imread('xx.jpg')
```

## 2.展示图片

**cv2.imshow\(\)** 是OpenCV 在 Python中展示图片的接口。一般来说窗口大小或自动匹配图片的大小。它 的第一个变量是定义窗口的名字，第二个变量是之前定义的图片变量。

```python
cv2.imshow('windows name',img)
```

**cv2.waitKey\(\)的作用是设置对键盘操作的等待时间（毫秒）。通常情况下我们会放入0**

```python
cv2.waitKey(0)
```

**cv2.destroyAllWindows（）的作用是销毁我们之前创建的所有窗口。**

**cv2.destroyWindow\(\)** **的作用是销毁特定的某个窗口窗口。**



