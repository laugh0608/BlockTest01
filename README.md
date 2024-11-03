## BlockTest01

基于CAPE-OPENv1.1开发的一个测试闪蒸模块

环境：VS2022、Win11、64位debug模式
MFC环境：AspenPlusV11

测试条件：

组分：水
进口温度：25C
进口压力：1.1bar

测试结果：无报错无警告

COFE无法运行，猜测是获取流股对象时使用了智能指针而非热力学对象，还在完善中