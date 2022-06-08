## 一、yolov5与ocr 自定义识别程序
![](pptimage/danger!.JPG)
![](pptimage/firebox.JPG)
#### 1.将前面的结果显示的方式迁移至http传输的后端,实现自动连续发送图片且不阻塞线程。
#### 2.导入闪电、警示牌的模型，以便之后识别完成强调提醒。
#### 3.使用OCR检测到灭火器的字样后，自动进入识别灭火的阶段 采用设定时间间隔的发送的方式。
```mermaid 
    graph TD
        巡检系统-->Hololen程序;
        巡检系统-->后端flask;
        Hololen程序-->拍照模块;
        拍照模块-->返回分析;
        拍照模块-->结果展示;
        返回分析-->结果展示;
        后端flask-->ocr/接收route;
        后端flask-->yolo/接收route;
        
       
```
## 二、QR code识别 展示设定模型预及视频程序
#### 1.学习使用二维码识别，以及slate(面板)控件的视频导入与展示
![](pptimage/unityfire.JPG)
#### 2.学习使用HoloLens 空间锚点和场景保持功能