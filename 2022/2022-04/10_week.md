# 第十周组会汇报
## Hololens开发进展
### 一.头戴相机的视频流传输
#### 1.局域网内视频流
相机工作在AP模式下获取视频流
Drift相机的视频流的默认传输协议为TCP方式, 即相机作为了流服务器提供H264格式的RAW视频数据，客户端采用TCP协议获取一帧一帧的H264视频帧，该种协议只支持获取视频流，没有声音。
获取RTSP视频流
相机工作为STA模式连接外部路由器或个人热点的局域网拉流模式
#### 2.因特网内视频流
Drift 相机可以采用采用rtmp协议推流到rtmp服务器中
![image](https://github.com/Juesqi/Dream-towering-tree/blob/main/images/2022-4-19speech.png)
### 二.MixedReality-WebRTC实现音视频通话
