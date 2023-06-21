# Changelog for package mipi_cam

tros_2.0.0 (2023-05-11)
------------------
1. 更新package.xml，支持应用独立打包
2. 更新应用启动launch脚本
3. 适配X3 Module板

tros_1.1.5 (2023-2-10)
------------------
1. 优化mipi_cam图像发布时间戳，使用硬件时间戳并调整曝光时间

tros_1.1.4rc1 (2023-1-9)
------------------
1. 修复启动时sensor状态未初始化导致自适应video_device失败的问题

tros_1.1.4 (2022-11-28)
------------------
1. mipi_cam自适应video_device

tros_1.1.3rc1 (2022-11-28)
------------------
1. 解决mipi_cam重复启动，第一次启动的程序异常退出问题

tros_1.1.3 (2022-11-16)
------------------
1. mipi_cam适配imx219, imx477, ov5647

tros_1.1.2rc1 (2022-10-18)
------------------
1. 解决mipi_cam重复启动，log不提示相关信息问题
2. 启动前，增加分辨率检查，不支持时输出错误日志
3. 增加判断是否连接摄像头以及摄像头类型是否正确功能

tros_1.1.2 (2022-09-28)
------------------
1. 优化mipi_cam输出日志

tros_1.1.1 (2022-09-20)
------------------
1. 更改相机标定文件的读取路径

hhp_1.0.6RC1 (2022-09-09)
------------------
1. 将默认的相机标定文件读取路径更换为绝对路径
2. 增加launch文件中的参数：相机标定文件读取路径

hhp_1.0.6 (2022-08-30)
------------------
1. 新增F37和GC4663两款摄像头的标定文件
2. 新增读取相机标定文件并发布相机内参的功能

hhp_1.0.4 (2022-08-02)
------------------
1. 新增imx586和gc4c33配置

v1.0.1 (2022-06-23)
------------------