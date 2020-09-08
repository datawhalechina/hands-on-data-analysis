# Hands-on data analysis

# 动手学数据分析

## 项目初衷
这件事始于datawhale以前的数据分析课程，那时我作为一名学员的以《python for data analysis》这本书为教材教材，通过刷这本教材的代码来学习数据分析，书里对于pandas和numpy操作讲的很细，但是对于数据分析的逻辑的内容，就少了很多。所以很多学习者和我学完之后发现，敲了一堆代码并不知道它们有什么用。然后我也上过datawhale的另一门课程—数据挖掘实战。这门课程又比较偏模型和实战，直接给你一个任务，让你去完成，上手难度比较大，但是它的实战性可以让你对于什么是数据挖掘，以及数据挖掘的逻辑有很好的把握。所以有没有这样一门课，以项目为主线，将知识点孕育其中，通过边学，边做以及边被引导的方式来使学习效果达到更好，学完之后既能掌握pandas等的知识点又能掌握数据分析的大致思路和流程。通过调查发现，市面上这样的项目好像没有可以完全符合这样的标准（失望.jpg）。所以datawhale的小伙伴一起来做一门这样的开源课程，完成上面所说的那些小目标，让所有使用了我们课程的小伙伴可以更好的开启他的数据分析之路。

这门课程现在是1.0版本，从基础的数据分析操作和数据分析流程讲起。之后会不断加入新的内容（比如数据挖掘的算法之类的）。这是开源课程，会不断迭代，大家共同参与，一起努力。

既然这是一门诞生于datawhale的课程，学习它的时候搭配datawhale所配备其他资源会更好。我们提供的代码是jupyter形式的，里面有你所要完成的任务，也有我们给你的提示和引导，所以这样的形式再结合datawhale的[组队学习](https://github.com/datawhalechina/team-learning)，可以和大家一起讨论，一起补充资料，那么学习效果一定会加倍。还有，datawhale之前开源了一门pandas的教程—[Joyful-Pandas](https://github.com/datawhalechina/joyful-pandas)。里面梳理了Pandas的逻辑以及代码展示，所以在我们数据分析的课程中，关于Pandas的操作，你可以参考*Joyful-Pandas*，可以让你的数据分析学习事半功倍。

关于我们项目的名字——动手学数据分析（Hands-on data analysis）。数据分析是一个要从一堆数字中看到真相的过程。学会操作数据只是数据分析的一半功力，剩下的另一半要用我们的大脑，多多思考，多多总结，更要多动手，实打实的的敲代码。所以也希望在学习这门课时，多去推理，多去问问为什么；多多练习，确保理论实践结合起来，在课程结束的时候一定会有大收获。


## 课程编排与服用方法
课程现分为三个单元，大致可以分为：数据基础操作，数据清洗与重构，建模和评估。

1. 第一部分：我们获得一个要分析的数据，我要学会如何加载数据，查看数据，然后学习Pandas的一些基础操作，最后开始尝试探索性的数据分析。
2. 第二部分：当我们可以比较熟练的操作数据并认识这个数据之后，我们需要开始数据清洗以及重构，将原始数据变为一个可用好用的数据，为之后放入模型做准备
3. 第三单元：我们根据任务需求不同，要考虑建立什么模型，我们使用流行的sklearn库，建立模型。对于一个模型的好坏，我们是需要评估的，之后我们会评估我们的模型，对模型做优化。

#### 服用方法

我们的代码都是jupyter形式，每个部分的课程都分为课程和答案两个部分。学习期间，在课程代码中，完成所有的学习，自己查找资料，自己完成里面的代码操作，思考部分以及心得。之后可以和小伙伴讨论，分享资料和心得。关于答案部分，大家可以参考，但是由于数据分析本身是开放的，所以答案也是开放式的，更多希望大家可以有自己理解和答案。


## 内容导航

| 章节 | 小结 | 内容 |
| :---         |     :---      |          :--- |
| 第一章   |  1. 数据载入及初步观察     | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%80%E8%8A%82%E6%95%B0%E6%8D%AE%E8%BD%BD%E5%85%A5%E5%8F%8A%E5%88%9D%E6%AD%A5%E8%A7%82%E5%AF%9F-%E8%AF%BE%E7%A8%8B.ipynb)      |
|      |      | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%80%E8%8A%82%E6%95%B0%E6%8D%AE%E8%BD%BD%E5%85%A5%E5%8F%8A%E5%88%9D%E6%AD%A5%E8%A7%82%E5%AF%9F.ipynb)      |
|   | 2.pandas基础     | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%BA%8C%E8%8A%82pandas%E5%9F%BA%E7%A1%80-%E8%AF%BE%E7%A8%8B.ipynb)      |
|     |       | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%BA%8C%E8%8A%82pandas%E5%9F%BA%E7%A1%80.ipynb)      |
|    | 3.探索性数据分析    | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%E7%AC%AC%E4%B8%89%E8%8A%82%EF%BC%9A%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90-%E8%AF%BE%E7%A8%8B.ipynb)      |
|     |       | [参考答案](https://nbviewer.jupyter.org/github/datawhalechina/hands-on-data-analysis/blob/master/%E7%AC%AC%E4%B8%80%E5%8D%95%E5%85%83%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%80%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%89%E8%8A%82%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90.ipynb)       |
| 第二章	   | 1.数据清洗及特征处理     |  [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%80%E8%8A%82%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97%E5%8F%8A%E7%89%B9%E5%BE%81%E5%A4%84%E7%90%86-%E8%AF%BE%E7%A8%8B.ipynb)       |
|    |        | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%80%E8%8A%82%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97%E5%8F%8A%E7%89%B9%E5%BE%81%E5%A4%84%E7%90%86.ipynb)       |
|    | 2.数据重构1     | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Data/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%BA%8C%E8%8A%82%E6%95%B0%E6%8D%AE%E9%87%8D%E6%9E%841-%E8%AF%BE%E7%A8%8B.ipynb)     |
|    |      | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%BA%8C%E8%8A%82%E6%95%B0%E6%8D%AE%E9%87%8D%E6%9E%841.ipynb)       |
|    |  3.数据重构2	     | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%89%E8%8A%82%E6%95%B0%E6%8D%AE%E9%87%8D%E6%9E%842-%E8%AF%BE%E7%A8%8B.ipynb)       |
|     |    | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E4%B8%89%E8%8A%82%E6%95%B0%E6%8D%AE%E9%87%8D%E6%9E%842.ipynb)      |
|    | 4.数据可视化   |  [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E5%9B%9B%E8%8A%82%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96-%E8%AF%BE%E7%A8%8B.ipynb#2-%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96)      |
|      |      | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%BA%8C%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%BA%8C%E7%AB%A0%EF%BC%9A%E7%AC%AC%E5%9B%9B%E8%8A%82%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96.ipynb)      |
| 第三章   | 1.数据建模	     |  [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Data/blob/master/%E7%AC%AC%E4%B8%89%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%89%E7%AB%A0%E6%A8%A1%E5%9E%8B%E5%BB%BA%E7%AB%8B%E5%92%8C%E8%AF%84%E4%BC%B0--%E5%BB%BA%E6%A8%A1-%E8%AF%BE%E7%A8%8B.ipynb)      |
|      |       | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Data/blob/master/%E7%AC%AC%E4%B8%89%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%89%E7%AB%A0%E6%A8%A1%E5%9E%8B%E5%BB%BA%E7%AB%8B%E5%92%8C%E8%AF%84%E4%BC%B0--%E5%BB%BA%E6%A8%A1.ipynb)       |
|    | 2.模型评估	    | [课程](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Ddata/blob/master/%E7%AC%AC%E4%B8%89%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%89%E7%AB%A0%E6%A8%A1%E5%9E%8B%E5%BB%BA%E7%AB%8B%E5%92%8C%E8%AF%84%E4%BC%B0---%E8%AF%84%E4%BB%B7-%E8%AF%BE%E7%A8%8B.ipynb)     |
|     |      | [参考答案](https://nbviewer.jupyter.org/github/andongBlue/Thinking-Data/blob/master/%E7%AC%AC%E4%B8%89%E7%AB%A0%E9%A1%B9%E7%9B%AE%E9%9B%86%E5%90%88/%E7%AC%AC%E4%B8%89%E7%AB%A0%E6%A8%A1%E5%9E%8B%E5%BB%BA%E7%AB%8B%E5%92%8C%E8%AF%84%E4%BC%B0---%E8%AF%84%E4%BB%B7.ipynb)       |

## 反馈
* 如果有任何想法可以联系邮箱（chenands@qq.com）
* 欢迎大家提issues

## 成员介绍

| 姓名   | 属性                 | 地址                                                       |
| ------ | -------------------- | ---------------------------------------------------------- |
| 陈安东 | 中央民族大学         | 知乎：https://www.zhihu.com/people/wang-ya-fei-48          |
| 金娟娟 | 浙江大学硕士         | 知乎：https://www.zhihu.com/people/wu-shi-lan-xiao-wang-zi |
| 杨佳达 | 数据挖掘师 | GitHub:https://github.com/yangjiada      |
| 老表   | 公众号简说Python作者         | 个人公众号：简说Python                                                   |
| 李玲   | 算法工程师           | 知乎：https://www.zhihu.com/people/liu-yu-18-38            |
| 张文涛 | 中山大学博士研究生   | GitHub： https://github.com/Fatflower                      |
| 高立业 | 太原理工大学研究生   | GitHub：https://github.com/0-yy-0                          |

## 关注我们

扫描下方二维码，然后回复关键词“动手学数据分析”，即可加入“数据分析项目交流群”

![datawhale](./datawhale.jpeg)



## LICENSE

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)


本作品采用**知识共享署名-非商业性使用-禁止演绎 4.0 国际许可协议**进行许可。








