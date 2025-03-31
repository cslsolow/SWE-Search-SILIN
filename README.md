** Thanks to the original author of this paper SWE-Search for the open source project. ** <https://github.com/aorwall/moatless-tree-search>  <https://arxiv.org/abs/2410.20285>

* .env配置API，必须得配置一个是模型的API和一个是voyage AI的API用于embedding
* tmp目录下面是repository和index_store，前者是git下来的有问题的库，后者是有问题的库的embedding
* 我写的search_tree在moatless/silinchen/search_tree里面，区别不是很大
* 我用的是jupyter notebook一个一个运行，可以观察输出结果在SilinTree.ipynb里面，用的是print不是logger
