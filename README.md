# About

地图定位辅助工具

Author：surfsky.github.com
LastUpdate：2022-07


# 功能

- 拖动地图定位
- 查找地址定位
- 定位到当前位置
- 定位时显示经纬度（包含度分秒表达式）
- 拷贝经纬度

# 计划任务

- 使用靠谱的查找服务（如高德），并转化为天地图坐标（大地2000，约等于WGS84）***
- 使用Leaflets 或 MapTalks 来重构。天地图在手机上拖拽有点问题。
- 可切换使用各种地图进行定位
- 扩展任务
    1. 叠加三方矢量图层（如社区网格）
    2. 叠加三方地图服务（如切块）
    3. 叠加点位列表并展示

# 注意

    定位需要在网站环境 + https 环境下使用
    高德、腾讯等地图需要网站环境下使用


# HISTORY

2022-07-19

    - 查找时不进行逆地址解析
    - 经纬度转化为度分秒

2022-01-04

    - 实现搜索能力（天地、腾讯、高德、百度）
    - 实现输入坐标能力

2021-11-15

    - 默认使用混合地图类型（遥感加道路文本注释）
    - 显示放缩级别
    - 阻止safari浏览器双击放大功能
    - 实现跳到当前位置按钮

2021-11-06

    - 初版