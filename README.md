# 031702221
代码查重的文件使用方法
---
（可查看main.py文件）
- 先在代码的同一个目录下，新建一个test_code的文件夹
- 将要对比的两个文件放入其中，命名为A0.txt和B0.txt
- 运行main.py文件即可输出代码重复度

*（这个其实很简单，就是要读取文件而已，可以自己手动修改）*
*（以及可以进行网页直接爬取GitHub里的代码，可以在main.py里面自行查看并修改）*
---
~~也可以搞批量的代码复杂度查看，稍微自行修改就好了，因为暂时还没出最后方案，到时候再弄~~

- main.py 里面放的是要运行的部分，以及文件读入的地方
- pre_deal.py里面放的是预处理命令
- check_it.py里面放的是主要算法的代码
- sub_variable.py放的是关于变量代换的代码
 
