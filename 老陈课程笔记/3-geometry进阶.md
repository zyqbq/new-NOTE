### UV

用来确定贴图的位置
(0,1)
是几何体的属性之一

![image-20240228143653715](img/image-20240228143653715.png)

![image-20240228143704739](img/image-20240228143704739.png)

### 法向量

normal
用于计算光的反射,环境贴图的反射

![image-20240228143740229](img/image-20240228143740229.png)

![image-20240228143752056](img/image-20240228143752056.png)

法向量辅助器

![image-20240228143810084](img/image-20240228143810084.png)

### 位置

物体的位置由几何体顶点位置和物体position属性的和决定
如果物体加载进来中心点不在原地,就是用顶点移动
单纯的移动物体，使用position属性移动
几何体变换

![image-20240228143834718](img/image-20240228143834718.png)

### 包围盒

![image-20240228144024072](img/image-20240228144024072.png)

包围球

![image-20240228144039094](img/image-20240228144039094.png)

### 多个物体求中心

box3继承自BufferGeometry

![image-20240228144104842](img/image-20240228144104842.png)

方法二
会自动计算物体的世界坐标(更加好用)

![image-20240228144121765](img/image-20240228144121765.png)

### 线框物体

EdgesGeometry
边缘几何体
是四边形线框

![image-20240228144142671](img/image-20240228144142671.png)

三角形线框
wireframeGeometry

![image-20240228144158079](img/image-20240228144158079.png)

### 遍历物体

traverse

![image-20240228144220592](img/image-20240228144220592.png)