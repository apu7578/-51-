# -基于51的微波功率测量系统-

利用两个DS18B20测量进出水口温度，霍尔流量计测量流量计算流速，计算出功率通过LCD1602显示,程序包括

1.头文件 2pt.h

2.获取DS18B20序列号 get-id-ds18b20.c

3.采集两点温度并通过LCD1602显示 get_2point_temprature.c

4.采集温度、流速，计算功率并显示 main.c(待完善)


# 存在的问题
采集到的温度不稳定，可能是传感器的问题，可以进行滤波改进


