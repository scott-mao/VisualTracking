# VisualTracking
Some code in visual tracking

## 1. KCFcpp 
是从KCF作者官网下载下来的c++代码（代码链接：http://www.robots.ox.ac.uk/~joao/circulant/index.html），
里面根据网上的解释和自己的学习做了一些注释，这里把 build文件夹也放进来了，因为一开始编译出build文件夹之后如果要运行，是需要在build文件夹里面新建images.txt 和 region.txt 文件的，这里是给出一个样例，当然大家自己在用的时候要把这个build文件夹删掉重新建立。我在csdn上也写了一篇博客说明应该怎么运行程序，有兴趣的可以去看看。
  https://blog.csdn.net/weixin_44100850/article/details/103592168
 
 ## 2. KCF
 KCF的matlab代码，里面ncc.m、vot.m、kcf.m三个文件是使用vot数据集时候使用的接口函数，原代码里面没有，是后来自己加的。
 
 ## 3. KCF_HC
 KCF算法中加入了CN特征，里面有代码注释
  
 ## 4. ColorNaming
很多目标跟踪算法用到的CN特征
paper：
J. van de Weijer, C. Schmid, J. J. Verbeek, and D. Larlus. Learning color names for real-world applications. TIP,
18(7):1512–1524, 2009. 2, 3

 ## 5. ColorTracking_code
 CN目标跟踪算法，出自：
Danelljan M, Shahbaz Khan F, Felsberg M, et al. Adaptive color attributes for real-time visual tracking[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2014: 1090-1097.
这里是matlab代码，里面根据自己的理解做了一些注释


