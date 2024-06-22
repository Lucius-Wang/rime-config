## 词库安装使用步骤

本文只介绍MacOS下如何安装配置Rime输入法，支持中英文混合输入、Shift切换中英文输入、emoji表情输入、并**最大化还原MacOS自带的输入法样式**。

整套配置对Rime1.0.0之前版本及1.0.0之后版本都做了兼容。

最终效果:

![输入效果](./others/input.jpg)

### 1、安装Rime

官网下载，解压缩后按步骤安装即可。https://rime.im/download/

安装完成后需要到设置->键盘->输入法 中添加鼠须管输入法

### 2、安装词库
将该词库下载到本地，然后将该路径/Users/用户名/Library/Rime下的所有目录及文件全部清除，再将下载的全部文件拷贝进去，重新部署即可。

### 3、词库更新

本词库原作者git地址：https://github.com/iDvel/rime-ice

到上述地址下载词库，并手动覆盖 cn_dicts 、en_dcits、 opencc 三个文件夹后重新部署即可。

感谢原作者的持续更新！！！

### 4、配置文件
- squirrel.custom.yaml
  该文件主要配置候选框、候选词的展示样式风格，这里默认配置的是mac风格

- default.yaml

  输入法的一些默认配置，详细配置说明见文件中注释

- custom_phrase.txt

  这个文件中可以配置一些个人常用但词库中又没有的词汇
