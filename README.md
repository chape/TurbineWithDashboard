# Intro
combine hystrix event stream to a turbine server，and with a dashboard to monitor metrics

# Dashboard监控Hystrix或Turbine拓扑图：
![Dashboard](http://okvphnw7f.bkt.clouddn.com/20170630149880153090892.png)

只需要部署一个Hystrix Dashboard服务即可：

1. One Hystrix Metrics，Just input http://HYSTRIX_IP:PORT/hystrix.stream to Dashboard
2. Use Turbine to collect all Hystrix Metrics event stream, Just input http://TURBINE_IP:PORT/turbine.stream to Dashboard
