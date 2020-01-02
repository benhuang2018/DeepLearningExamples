# DeepLearningSamples

个人编写的一些深度学习小Demo，欢迎大佬们批评指正。当前有如下Demo，后面会持续更新：

- [使用TensorFlow 2.0 编写的、基于循环神经网络的古诗生成器](https://github.com/AaronJny/DeepLearningSamples/tree/master/tf2-rnn-poetry-generator)
- [使用Keras + BERT 模型编写的古诗生成器](https://github.com/AaronJny/DeepLearningSamples/tree/master/keras-bert-poetry-generator)


# 错误排除

1.当使用PyCharm打开并调试项目时，发现py文件的引用路径有误，怎么办？

答：将当前要调试的小项目的路径设置为`Sources Root`，并取消其他小项目路径的`Sources Root`设置。比如我们要调试的是`keras-bert-poetry-generator`，设置`Sources Root`的方法为`右键点击keras-bert-poetry-generator文件夹 -> Mark Directory as -> Sources Root`，取消的方法同理，取消`Sources Root`的方法为`右键点击keras-bert-poetry-generator文件夹 -> Mark Directory as -> Unmark as Sources Root`。