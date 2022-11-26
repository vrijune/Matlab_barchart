# Matlab_Chart

1. 条形类图形

1） 直方图
rose 函数 rose(theta,x), 其中，参数theta用于确定每一区间与远点的角度，选项x用于指定区间的划分方式。

每一个区域的高度反映落入该区域三角函数的个数，x:均匀划分的扇形区域（默认为20）

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

5） 矢量图的表型
三维图形曲线

1. plot3函数
plot3(x,y,z)组成一组曲线的坐标
例子比如： ![image](https://user-images.githubusercontent.com/81022107/159592833-76ffd986-78ae-4424-8018-26d25f2973b4.png)
![image](https://user-images.githubusercontent.com/81022107/159592856-135b54c4-b47b-4b5d-8f1a-58b465b34756.png)

1.参数x,y,z是同型矩阵时，则以x,y,z对应列元素绘制曲线，等于矩阵列数
2.参数x,y,z中有向量也有矩阵时，行向量的长度与矩阵的列相同![image](https://user-images.githubusercontent.com/81022107/159825879-bc701c17-5ef2-4eae-88f4-31828874a850.png)

![image](https://user-images.githubusercontent.com/81022107/159828669-a66a960b-4e8e-4c98-8b0f-d8565d2948dc.png)
第一个命令生成行向量t，第二个命令转至为列向量t'，调用plot3函数，以矩阵xyz为参数，绘制五条曲线，蓝色第一条，曲线的坐标对应xyz的第二点元素。也可以采用：![image](https://user-images.githubusercontent.com/81022107/160044449-266e373c-4e55-4103-bb4d-f6dc0285c3c7.png)
![image](https://user-images.githubusercontent.com/81022107/160044468-7bc3750e-4da6-419a-bbc4-a56b87b9faa7.png)
![image](https://user-images.githubusercontent.com/81022107/160044474-6228869e-736c-4dee-9540-553e2e8da61b.png)

(4) 含选项的plot3函数： plot3（x,y,z,choose）
choose用于指定曲线的线型，颜色和数据点标记,
然后进行修改。 


(5) 可以绘制空间图形 x,y,z代表三位坐标
对于三个不同的维度，我们可以这样： x=cost, y=sint,z=2t, 其中 0<t<6pi
![image](https://user-images.githubusercontent.com/81022107/164200679-39e9d5ff-3799-434d-a5c6-3a74c67834bd.png)
p:以五角星表示数据点，xlabel给三个坐标轴标号![image](https://user-images.githubusercontent.com/81022107/164200799-e9f2b616-a5ea-41de-9c1f-f1022cb4042f.png)

(6)绘制螺旋状曲线，曲线的参数方程可以如下
利用e的sin函数进行空间上的修正。t可以控制在10-12的范围内形成有效的图形
![image](https://user-images.githubusercontent.com/81022107/164201250-2ad60e55-66df-48dc-bf52-0beafc209107.png)
可以接着往肥胖lot函数后再加入第五个函数元素，比如线形和颜色。

三维的修正完成



本章
结束






