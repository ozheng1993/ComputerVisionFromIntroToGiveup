---
description: 简单的介绍OpenCV的如何在图片上绘制基本的图形与文字
---

# 基本的画图操作

## 1.文字



```python
cv2.putText(img,'OpenCV',(10,500), cv2.FONT_HERSHEY_SIMPLE, 4,(255,255,255),2,cv2.LINE_AA)
```

## 3.四边形

```python
cv2.rectangle(img,(384,0),(510,128),(0,255,0),3)
```

## 4.圆形

```python
cv2.circle(img,(447,63), 63, (0,0,255), -1)
```

## 5. 椭圆形

```python
cv2.ellipse(img,(256,256),(100,50),0,0,180,255,-1)
```

## 6.多边形

```python
pts = np.array([[10,5],[20,30],[70,20],[50,10]], np.int32)
pts = pts.reshape((-1,1,2))
cv2.polylines(img,[pts],True,(0,255,255))
```

