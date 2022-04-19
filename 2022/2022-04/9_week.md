# 第九周组会汇报
## Hololens开发进展
### 一.多目标的显示
#### 1.根据HoloLens的坐标体系
![image](https://github.com/Juesqi/Dream-towering-tree/blob/main/images/pvcameratransform_px.png)

以及世界坐标系到像素坐标系的转换方程
![image](https://github.com/Juesqi/Dream-towering-tree/blob/main/images/projectequral.png)

获取了投影矩阵对应点的世界坐标，再使用c#声明RaycastHit hit的方式发射指定方向的红外光撞击空间感知的网格层。
```c#
Physics.Raycast(worldSpaceCameraPos, worldSpaceBoxPos - worldSpaceCameraPos, out hit, 20, GetSpatialMeshMask());
```
返回碰撞到物体的世界坐标并使用预制件显示

#### 2.设置跟随菜单以及语音控制对多目标进行显示
设置跟随头部移动的跟随菜单，并设置中文语音命令控制识别以及清除识别后的标签
![image](https://github.com/Juesqi/Dream-towering-tree/blob/main/images/2022-4-19speech.png)
#### 3.设置判断，对检测测出的显示器使用预设定的红色预制件进行显示
![image](https://github.com/Juesqi/Dream-towering-tree/blob/main/images/2022-4-19example.png)