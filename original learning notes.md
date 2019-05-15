# 最小二乘法线性拟合的画图 

## 一.某些杂乱无关的设置选项：  

1.字体选Times Roman 

2.线性拟合过后的那根线取名为best fit line 

## 二.画图方法（按顺序）：

1.输入数据获得散点图。在试验中侧得一组数据，只需输入到origin的data对话框中，选中数据，然后点击左下角的Scatter键即可得到散点图，以待进一步处理。

![初次表格.png](https://i.loli.net/2019/05/12/5cd798c21e148.png)  

![scatter1](https://i.loli.net/2019/05/12/5cd824faacdcf.png)

![scatter2](https://i.loli.net/2019/05/12/5cd8256d71ddd.png)

2.连接点获得趋势图。如果只需要将各点以折线连接 起来，则在获得散点图时可直接点击Line+symbol。(这一点是补充说明功能，跟线性拟合无关)  

![折线连接1](https://i.loli.net/2019/05/12/5cd826a0921d6.png)

![折线连接2](https://i.loli.net/2019/05/12/5cd82718ed457.png)

3.在散点图的基础上获得趋势线。如果想获得的不是折线图，而是希望用平滑的曲线表示趋势，则只需在折线基础上进一步加工如下：“双击折B线”—“选择Line”------“connect”----- “选择曲线类型”----“Apply”(这一点也是补充说明折线的非线性拟合，与线性拟合无关)

![折线后的曲线模拟1](https://i.loli.net/2019/05/12/5cd8293188e38.png)

![折线后的曲线模拟2](https://i.loli.net/2019/05/12/5cd82a44c7971.png)

4.线性拟合：实际应用做多的拟合即是线性拟合。  
  操作如下：首先要生成一个散点图，在散点图的基础上：  
  Analysis----Fit Linear---Open Dialog...，打开对话框，按下图一样设置（其实有了散点图过后什么都不用修改，直接默认的设置），最后点击OK。  

![线性拟合1](https://i.loli.net/2019/05/12/5cd82b562b782.png)
![线性拟合2](https://i.loli.net/2019/05/13/5cd8d45f7e9ed12554.png)
![线性拟合3](https://i.loli.net/2019/05/13/5cd8d494e659297814.png)

进行以上三步操作过后生成了graph，graph上有个表格，点开（如红笔标示），表格里已经算好了线性拟合过后的slope,intercept的值和标准差（standered error）
![线性拟合4](https://i.loli.net/2019/05/13/5cd8d5074d0cc89054.png)

5.线性拟合的整体框架已经形成了，现在需要的是边角要求的补充。

&#160; &nbsp;  ***a.调整横纵坐标的range和最小分度值（双击坐标轴进行设置）***
* Frorr To 来调坐标轴的range

* Major Ticks 主坐标分为几段，这里填6，如下图，0-12被分成了6份

* Minor Ticks 被分成6份的每个部分又分成了10个小份，记得这里填9（特殊记住，理解为中间部分被分成了9份，一共是10份）

![调x-axis1](https://i.loli.net/2019/05/13/5cd8da80a877854334.png)
![调x-axis2](https://i.loli.net/2019/05/13/5cd8dd2f5280d30692.png)

**同理把y轴调到合适的：**

![调y-axis1](https://i.loli.net/2019/05/13/5cd8ddcc9202774046.png)
![调y-axis2](https://i.loli.net/2019/05/13/5cd8de0435dbe18507.png)

**整体效果如下：**
![修改完成xy轴range，最小分度值](https://i.loli.net/2019/05/13/5cd8de35a0df880364.png)

&#160; &nbsp;  ***b.标注图上的文字部分***
* 标题（x versus y of ....)
* 图上数据的解释（Data， best fit line)
* 坐标轴的物理意义，物理量要写全称/字母，单位
* 作业提交需要的名字，学号，日期（此处忘记学号了，平时画图不用写这一步）
![标注图上的文字部分](https://i.loli.net/2019/05/13/5cd8e0d8d1d8967194.png)
* 所有文字部分采用times new roman格式（设置如下图所示）(上图没有采用times new roman格式，平时画图其实无所谓)
![设置文字格式为 times new roman](https://i.loli.net/2019/05/13/5cd8e264da49b20140.png)

&#160; &nbsp;  ***c.添加上和右边框效果***
* 添加右边和上边的边框
![添加边框1](https://i.loli.net/2019/05/13/5cd8e3acd9f3342507.png)

* 去除添加的边框 里面和外面的最小分度格（点开添加的边框，按照下图设置【Title&Format--->右侧Top/Right--->Major Ticks,Minor Ticks 设置成None】），再删掉旁边标的数字（直接选中delete就行了）
![添加边框2](https://i.loli.net/2019/05/13/5cd8e612d6bd168838.png) 

最终效果图如下：
![添加边框3](https://i.loli.net/2019/05/13/5cd8edf70f1d236138.png)

&#160; &nbsp;  ***d.添加网格***

* 在scale选项卡中，横纵坐标的最小刻度数minor选择9。
* 在grid lines选项卡中，横纵坐标选择灰色虚线。

![添加网格1](https://i.loli.net/2019/05/13/5cd8f459757a847358.png)

![添加网格2](https://i.loli.net/2019/05/13/5cd8f3e60676610993.png)

* 最终效果图如下：

![添加网格](https://i.loli.net/2019/05/13/5cd8f4b36f1eb23414.png)