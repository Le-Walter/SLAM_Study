# SLAM_Study
Collect some good articles, blogs and website links <br>
[GitHub上MarkDown语言的语法简介](https://blog.csdn.net/wqvbjhc/article/details/27349209)

# 【视觉VSLAM】
[视觉SLAM漫谈](https://www.cnblogs.com/gaoxiang12/p/3695962.html)【转自-半闲居士】

# 一、开源框架
## PTAM
1、[PTAM 特征点法跟踪和建图 SLAM FAST Patch](https://blog.csdn.net/xiaoxiaowenqiang/article/details/80956013)【转自-EwenWanW】
>>说明：PTAM的算法原理、优缺点和代码（makefile工程改成了cmake工程）讲解的很详细！ <br>

2、[视觉SLAM算法框架解析：PTAM](https://www.cnblogs.com/zonghaochen/p/8442699.html)【转自-ZonghaoChen】
>>说明：简单介绍PTAM算法框架，重点是有流程图，思路清晰！ <br><br>
 
# 二、特征提取与匹配
【1-8均转自-勿在浮砂筑高台，感谢博主！】<br><br>
1、[Fast原理及源码解析](https://blog.csdn.net/luoshixian099/article/details/48294967)
>>说明：Fast检测器速度非常快，但它不具有方向性和尺度不变性。<br>

2.1、[SIFT原理与C源码剖析](https://blog.csdn.net/luoshixian099/article/details/47377611)
>>说明：SIFT（Scale-invariant feature transform）即尺度不变特征转换，提取的局部特征点具有尺度不变性，且对于旋转，亮度，噪声等有很高的稳定性。<br>

2.2、[SIFT原理之KD树+BBF算法解析](https://blog.csdn.net/luoshixian099/article/details/47606159)

3.1、[SURF原理与源码解析（一）](https://blog.csdn.net/luoshixian099/article/details/47807103)
>>说明：SURF (Speed Up Robust Features)是SIFT改进版也是加速版，提高了检测特征点的速度，综合性能要优于SIFT。<br>

3.2、[SURF原理与源码解析（二）](https://blog.csdn.net/luoshixian099/article/details/47905681)
>>说明：3.1分析了SURF的原理，3.2分析opencv中的SURF源码。<br>

4、[Harris及Shi-Tomasi原理及源码解析](https://blog.csdn.net/luoshixian099/article/details/48244255)
>>说明：角点。

5、[BRIEF特征描述子原理及源码解析](https://blog.csdn.net/luoshixian099/article/details/48338273)
>>说明：BRIEF描述子采用二进制码串(每一位非1即0)作为描述子向量，节省时间和内存，但BRIEF描述子不具有方向性，大角度旋转。<br>

6、[ORB原理与源码解析](https://blog.csdn.net/luoshixian099/article/details/48523267)
>>说明：ORB算法结合了Fast和Brief的速度优势，并做了改进，且ORB是免费。<br>

7、[PCA-SIFT原理及源码解析](https://blog.csdn.net/luoshixian099/article/details/49174869)
>>说明：PCA-SIFT是对传统SIFT算法的改进，把SIFT特征描述子从128维降到了20维，优化了描述子占用的内存，同时提高了匹配的准确性。<br>

8、[RANSAC算法原理与源码解析](https://blog.csdn.net/luoshixian099/article/details/50217655)
>>说明：随机抽样一致性（RANSAC）算法，可以在一组包含“外点”的数据集中，采用不断迭代的方法，寻找最优参数模型，不符合最优模型的点，被定义为“外点”。<br>

<br>
9、[Harris角点检测原理及C++实现](https://blog.csdn.net/linqianbi/article/details/78930239)【转自-零钱币】
