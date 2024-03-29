# Get_Real_IP_From_WebRTC
通过WebRTC获取用户的真实IP

**Push点史污染一下Github**

使用JS通过WebRTC获取到用户的真实IP
列出IPV4和IPV6

**手机端**挂代理后WebRTC只能获取到内网IP
```index.html``` 中增加了判断
若为局域网IP，**则改为获取出口IP进行输出**

在线示例：<https://sukap.cn/ip/>