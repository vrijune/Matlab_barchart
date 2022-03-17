# Matlab_Chart

1. 条形类图形

1） 直方图
rose 函数 rose(theta,x), 其中，参数theta用于确定每一区间与远点的角度，选项x用于指定区间的划分方式。

每一个区域的高度反映落入该区域三角函数的个数，x:均匀划分的扇形区域（默认20）

![image](https://user-images.githubusercontent.com/81022107/157791771-f1770a31-c466-476f-8535-01a796c3d44b.png)

2. 面积类图形
1） 扇形图 
pie函数
比如 pie(x,explode) 其中，参数x存储待统计数据，选项explode控制图块的显示模式
![image](https://user-images.githubusercontent.com/81022107/157792128-eb811efa-8d7f-440f-9b06-595cdca1dcfd.png)

2）面积图
area函数

3）散点图
scatter函数：散点
例： scatter(x,y,choose,'filled') 参数x，y用于定位数据点，选项用于指定线形，颜色，数据点的标记，filled可以填充数据点标块，省略时数据点空心
stairs函数：阶梯
stem函数：杆图

![image](https://user-images.githubusercontent.com/81022107/157792623-1f83ffd2-dd17-4c19-a62b-b08fca0520e5.png)

4) 矢量类图形
compass函数：罗盘图
feather函数：羽毛图
quiver函数：箭头图
quiver函数的调用格式为：quiver(x,y,u,v), 其中，（x，y）指定矢量起点，（u，v）指定矢量终点
其中，(x,y),(u,v)是大小相同的向量。
![image](https://user-images.githubusercontent.com/81022107/158746538-8c3c6da6-962f-46fd-ab5d-5180e8098a20.png)

Text:分别为三点标注





