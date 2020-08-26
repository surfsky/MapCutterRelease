# 1. MapTiler

地图叠加层瓦片图（金字塔图）创建工具，可用于制作自定义区域地图，如园区地图。支持百度地图、腾讯地图、高德地图等。
Map tile images builder for baidu map, tencent map, google map, ...
Add Custom Map Overlay to map.

https://surfsky.github.io/2020/06/18/MapTiler
https://api.github.com/repos/surfsky/MapTilerRelease/releases/latest

# 2. 支持的地图

- [x] Baidu map
- [x] Tencent map
- [x] Gaode map
- [x] Tiande map
- [x] Bing map
- [x] Google map
- [ ] MapBar map
- [ ] MapBox map
- [ ] LeafLet
- [ ] OpenLayer

# 3. 操作步骤

（1）基础设置

![](./Doc/step_basic.png)

（2）地图点位设置

![](./Doc/step_map.png)
![](./Doc/step_pos.png)

（3）预览及截图

![](./Doc/step_preview.png)

# 4. 效果

![](./Doc/map_baidu.png)
![](./Doc/map_tencent.png)
![](./Doc/map_gaode.png)
![](./Doc/map_tiandi.png)
![](./Doc/map_bing.png)
![](./Doc/map_google.png)


# 6. Roadmap

- 超大地图图片的处理，大于 20480*20480
- LeafLet
- OpenLayer

# 5. History


2.6.2

    完善异常捕捉，避免程序崩溃
    显示对应级别的切图信息：图片大小、切图数
    2020-08-12

2.6.1

    支持版本检测
    2020-07-02

2.6.0

    支持 Google Map（需先解决网络问题）
    优化百度地图位置设置窗口，增加label辅助显示
    优化地图类别展示，文本改为中文，增大行距
    2020-07-02

2.5

    支持 Bing Map
    2020-06-30

2.4.2

    优化预览窗口：显示半透明图片(支持百度、腾讯、高德)
    修正地图定位窗口：查找结束后显示中心红点
    2020-06-18

2.4.1

    支持天地图
    2020-06-10

2.4.0
    支持高德地图
    2020-06-08

2.4.0

    支持腾讯地图
    2020-06-04

1.5.0

    支持百度地图
    2020-05-25


# 6. 可发布博文

- Bing 地图居中显示定位点，拖拽始终居中
- Bing 自定义瓦片地图

