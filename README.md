# Meteorology-Mapping-GUI

pyinstaller 打包py文件即可生成.exe文件

DTool.zip为绘图所需shp文件

temp.txt为测试文件

## 2021.06.03 Updated to V1.2
1. 增强了对数据header的兼容性
2. 去除axis
3. 美化colorbar
4. 增加了负号显示功能
## 2021.06.05 Updated to V1.4
简化色阶级数选择操作
## 2021.06.11 Updated to V1.5
提高图像分辨率为300dpi
## 2021.08.08 Updated to V3.0
增加了自定义色块
## 2021.08.25 Updated to V3.1
1. 修正了当图例最大值和最小值选“默认”时，图例级数与选择的级数不对应情况；
2. 修正了自定义颜色BUG：重选颜色沿用上次颜色的BUG
## 2021.09.24 Updated to V3.2
插值方法由克里金修改为Rbf
## 2023.02.09 Updated to V4.1
## 2023.02.11 Updated to V5.0
1. 解决了部分电脑无法显示中文的问题;
2. 参考QX/T180-2013标准设置色带;
3. 对加载数据做了优化，无需手动加载数据文件
