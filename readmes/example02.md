# answer_sheet_scan
使用python3+opencv3实现的一些识别答题卡的例子

##  识别例子02

例子02是[ayoungprogrammer](http://blog.ayoungprogrammer.com/2013/03/tutorial-creating-multiple-choice.html/)博客上参考作者原版C++代码和思路，然后改造成python版本的，先在本地运行成功之后，然后加上自己的理解，给大多数核心代码加上了详细的中文注释，并在每一个关键阶段都会弹出具体的窗体展示识别流程，这样便于大家更能详细的看到核心部分的细节，感兴趣的同学，可以自己在再尝试加一些更细部分的debug弹窗。

本地PyCharm运行后一些截图：

（1）原图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/01.jpg)


（2）灰度后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/02.jpg)


（3）自适应二值化后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/03.jpg)


（4）标记轮廓后的原图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/04.jpg)


（5）提取答题内容区后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/05.jpg)


（6）对答题内容区进行自适应二值化后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/06.jpg)


（7）标记答案后的图

![image](https://github.com/qindongliang/answer_sheet_scan/blob/master/imgs/example02/07.jpg)



