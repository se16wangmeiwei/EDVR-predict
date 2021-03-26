# EDVR-predict
这是发表在CVPR 2019年的论文EDVR，我加载其公开的模型参数，然后对数据进行预测。
(colab)environment： pytorch:1.8.0  cuda:10.1
在加载完EDVR数据之后，需把util.py导入到basicsr/utils这个路径中去。
util.py是在这个仓库下下载的https://github.com/btahir/deoldify_and_edvr

还需要改一些函数名，有些函数名和原代码不太一样。
这是最终的输出
![image](https://user-images.githubusercontent.com/31944875/112634207-43846500-8e75-11eb-9225-9b0856f80cf8.png)
