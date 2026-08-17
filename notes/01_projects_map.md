#SPP Project Map

##1.Program Entry

--Entry file:当前的仓库没有唯一的全局main.py，是由多个test_*.py脚本分别启动不同实验的。
与GNSS单点定位直接对应的两个入口是：
LS-SPP的主入口，即SPP最小二乘算法的主入口：test_pntposls(line 328)
* if __name__ == "__main__" 开始
* 然后开始调用evaluate_accuracy()
* 再逐历元调用pntposls.py 中的 process函数 这是单点定位的主处理函数 
* 然后这就是独立伪距SPP流程

KF-SPP的主入口，即SPP卡尔曼滤波算法的主入口：test_pntposkf(line 201)
* 写法与ls算法相同 调用了pntposkf.py中的stdpos.process()文件