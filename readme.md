# 1. MapCutter

MapCutter 是制作覆盖图/瓦片图/金字塔图/游戏地图/切图切片的工具，它支持百度、腾讯、高德、天地图、谷歌、必应地图、MapBox等地图服务，是市面上最易用的同类软件，并支持js、webgl、leaflet、maptalks、openlayers、cesium 等地图网页输出，无偏移。可用于景区地图切图、遥感地图切图、游戏地图切图、虚拟城市地图、省市范围地图拼接等地图应用开发。

https://blog.csdn.net/surfsky/article/details/106951716
https://www.bilibili.com/video/BV11P411i7rL
https://surfsky.github.io/2020/06/18/MapTiler
https://api.github.com/repos/surfsky/MapTilerRelease/releases/latest

# 2.功能简介

- 支持地图：百度、腾讯、高德、天地图、必应、谷歌、MapBox。
- 支持超大图片（分辨率大于20480*20480），支持几十G的大图片。
- 支持标准（256*256）及高清地图切片输出（512*512)，适合手机及视网膜屏查看。
- 支持快速辅助校准地图位置，可用直观预览方式供用户快速精确定位地图。
- 支持输入图片格式：jpg, png, tiff, gif, webp, 矢量图片格式 svg 。
- 支持输出图片格式 ：png、tif、jpg、webp，并可设置输出图片的质量。
- 支持10-30级地图切图。一般web用10-18级，mobile用10-19级，google支持22级。
- 支持最新版本检测及下载、终身免费升级。
- 支持自定义图片路径，如/z/x_y.png  或 /z/x/y.png。
- 支持地图拼接，可用该功能生成省、市范围的大规模地图。
- 支持超大地图目录无缝拼接功能。
- 支持配置文件读写。
- 支持根据图片内置的经纬度数据自动定位（支持 geotiff、exif gps）。
- 支持图片旋转预览及处理。
- 支持多版本网页输出，如js、webgl、leaflet、maptalks、openlayers、cesium 等。

    Baidu : v2、v3、maptalks
    BaiduGL: gl, openlayers, cesium
    Tencent : v2、webgl、leaflet
    Gaode : v1, v2, leaflet, maptalks、openlayers、cesium
    TianDiTu : v3, v4, leaflet, maptalks、openlayers、cesium
    Bing : js, leaflet、openlayers
    Google : js, leaflet， maptalks、openlayers 
    MapBox: gl, leaflet

- 支持自定义输出模版。
- 使用内置 Web 服务器，查看需要部署成网站的地图网页不报错。
- 支持游戏地图开发，可设置图层的宽度高度，与游戏像素相匹配。
- 使用内置 Web 服务器及谷歌内核浏览器，查看地图网页通用、稳定、快速。
- 提供小型集成网页开发环境，可直接对网页进行读写、调试、展示。

如果跑不起来，请运行安装一下安装包里面的VC再发布程序 VC_redist.x64.exe


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



