# WALL.E
A javaScript robot which looks like WALL.E 

# 前言
------

这是一个十足有趣的物联网项目！它运行在基于arm架构的raspiberry(树莓派）开发板上。凭借着node的出色性能和多系统支持，我们创建了这个项目。此项目涉及了前端框架vue，后端服务器框架express,硬件框架johnny.five，以及数电和模电的相关知识，不过不用担心，只要你有js相关的开发经验，你就能很快的入门物联网项目的开发。
这个项目包括了数十个页面，包括了视频实时监控，温度数据采集，机器人前进，转弯控制，距离测量等，gps定位等功能。
欢迎对物联网感兴趣的javaScript开发人员Issues
# 技术栈

> * johnny-five
> * vue vue-socket vue-router
> * express
> * chart.js 
> * mongoDB


------

# 目标功能
- [ ] 支持视频实时监控
- [ ] 支持摄像头转动
- [ ] 支持手动控制电机运行
- [ ] 支持温度采集
- [ ] 支持gps定位
- [ ] 支持距离探测
- [ ] 支持循迹功能
- [ ] 支持自由巡航

# 项目运行
### 本项目需运行在安装了ubuntu16系统的树莓派开发板上，并且安装了node v6.0及以上版本和一些软件。
```javascript
git clone https://github.com/zexiplus/WALL.E.git

cd WALL.E

npm install

npm run dev 
```




# 开发流程图 

```gantt
    title 项目开发流程
    section 项目确定
        功能分析       :a1, 2017-10-22, 5d
        页面布局构思   :after a1, 7d
    section 项目实施
        概要设计      :2017-11-01  , 5d
        详细设计      :2017-11-06, 6d
        编码          :2017-11-10, 12d
        测试          :2017-11-26, 5d
    section 发布验收
        发布: 3d
        验收: 3d
```

# 材料准备

| 模块              | 价格    |  数量  |
| --------          | -----:  | :----: |
|  树莓派开发板     |￥200    |1       |
|  履带底盘         |￥350    |1       |
|  ADC转换器        |￥15     |1       |
|  红外传感器       |￥3      |6       |
|  SG90舵机         |￥15     |1       |
|  树莓派摄像头     |￥80     |1       |
|  电池             |￥30     |1       |


# 项目展示
# 项目布局
