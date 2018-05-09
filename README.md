# answer_sheet_scan
使用python3+opencv3实现的一些识别答题卡的例子

##  例子01

例子01是参考：[pyimagesearch](https://www.pyimagesearch.com/2016/10/03/bubble-sheet-multiple-choice-scanner-and-test-grader-using-omr-python-and-opencv/)网站上一个识别例子，加上自己的理解后，加上详细的注释，并在每一个关键阶段都会弹出具体的GUI窗体展示识别流程，这样便于大家更能详细的看到核心部分的细节，感兴趣的同学，可以自己在再尝试加一些更细部分的debug弹窗。

例子01的一些图片：

（1）原图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/t1.png)


（2）灰度+高斯模糊后的图
![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/02.png)

（3）使用边缘检测后的图
![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/03.png)

（4）透视变换后提取指定答题区域的灰度图
![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/04.png)

（5）使用ostu的二值化后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/05.png)

（6）最终识别答案成功后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example01/05.png)


