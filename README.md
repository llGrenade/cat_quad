# cat_quad
the quad called cat

## server
 服务器上部署

 client_io 用于用户请求的返回
 uav_io 用于无人机请求接口

## uav
 无人机上部署，fmc (飞控) 随无人机系统启动，fmc启动完成后，webio启动

## 注意
1. client 和 uav 在 p2p 穿透失败后需要经过server进行交互
