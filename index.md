
## 什么是jupyter notebook？
jupyter notebook是基于网页的用于交互计算的应用程序。可以在网页页面直接编写代码和运行代码，代码运行结果会直接显示在代码块的下方。
同时jupyter notebook也支持将代码与文档编写到一个页面中，可以ipynb文件将其看作是一篇“博客”,在该“博客”中可以编写文档，也可以直接编写、运行代码。 
 
## jupyter notebook 有什么特点？
1. 可以直接将文档保存为HTML、LaTeX、PDF等特点
2. 可以通过浏览器运行代码，同时在代码块下方展示运行结果。
3. 编程具有语法高亮、缩进、tab补全的功能。
4. 支持LaTeX编写数学性说明


## 如何安装jupyter notebook？
在这我们推荐首先安装anaconda,之后安装jupyter notebook. 在Anaconda prompt中输入一下的命令：
```markdown
conda install jupyter notebook 
```
## 如何使用jupyter notebook？
安装之后输入
```markdown
 jupyter notebook 
```
 ![图片](https://github.com/Jin-bh/jinbh.Github.io/blob/gh-pages/jupyter%20notebook1.jpg " jupyter notebook演示")
可以打开jupyter notebook，如下图所示
```markdown
 jupyter notebook 
```
 ![图片](https://github.com/Jin-bh/jinbh.Github.io/blob/gh-pages/jupyter%20notebook2.jpg " jupyter notebook演示")
点击上方的运行按钮即可运行代码，运行结果保存在代码块的下方。（红线所画位置）

 ![图片](https://github.com/Jin-bh/jinbh.Github.io/blob/gh-pages/jupyter%20notebook3.jpg " jupyter notebook演示")
可以看到代码块的左侧有"in[]"标识，当代码处于运行状态括号内部会显示为星号。
下面提供一个使用jupyter notebook的小demo。例如将下面代码块的import子句注释掉，运行的错误信息将会显示在代码块下方，可以通过提示信息进行debug。
![图片](https://github.com/Jin-bh/jinbh.Github.io/blob/gh-pages/jupyter%20notebook4.jpg " jupyter notebook演示")
当然了jupyter notebook 还有很多其他的用法，例如上方的新建文件即可完成自己的文件的编写。
## 安装过程中遇到的其他问题
最主要的还是 jupyter notebook bad file descriptor 原因是 pyzmq版本较高，
输入如下的命令：
```markdown
 pip uninstall pyzmq
pip install pyzmq==19.0.2
```
