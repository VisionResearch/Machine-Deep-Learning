# ML&DL&Linux&Python笔记

在cs231n笔记的基础上**进一步扩展**, 是我ML&DL学习总结的记录.

---

> changelog:
>
> 2018年11月15日: 
>
> 最近在看目标检测部分内容, 主要会看RCNN->SPP-Net->Fast RCNN->Faster RCNN, 总结的书写方式要改变下, 为了节省时间, 提高效率, 更多增加自己的思考, 决定不再弄论文的翻译复制过来, 在上面的基础上做笔记这样的方式了, 准备按照架构的流程, 理清架构的思路, 以问题推动思考的方式来进行学习.
>
> 希望可以帮助自己更深入的理解.

---

## 更新计划

1. 论文
    1. 2012
        1. AlexNet-1
    2. 2013
        1. NiN-1
    3. 2014
        1. OverFeat-1
        2. GoogLeNet-1
        3. VGG-1
    4. 2015
        1. BN-GoogLeNet-1
        2. InceptionV2/V3-1
        3. ResNet-1
        4. FCN-1
        5. Learning Deconvolution Network for Semantic Segmentation-1
    5. 2016
    6. 2017
        1. SeNet-1
        2. DenseNet-1
        3. SqueezeNet(-1
    7. 2018

2.other

- Xception-0
- InceptionV4-0
- Inception ResNet V1/V2-0
- ResNeXt-0
- Mobile系列-0

3. 调整文件结构

**其他补充**

---

## 关于CS231n笔记部分内容

CS231n课程笔记的翻译，始于@杜客在一次回答问题“应该选择TensorFlow还是Theano？”中的机缘巧合，在取得了授权后申请了**知乎专栏智能单元 - 知乎专栏**独自翻译。随着翻译的进行，更多的知友参与进来。他们是@ShiqingFan，@猴子，@堃堃和@李艺颖。

大家因为认同这件事而聚集在一起，牺牲了很多个人的时间来进行翻译，校对和润色。而翻译的质量，我们不愿意自我表扬，还是请各位知友自行阅读评价吧。现在笔记翻译告一段落，下面是团队成员的简短感言：

@ShiqingFan：一个偶然的机会让自己加入到这个翻译小队伍里来。CS231n给予了我知识的源泉和思考的灵感，前期的翻译工作也督促自己快速了学习了这门课程。虽然科研方向是大数据与并行计算，不过因为同时对深度学习比较感兴趣，于是乎现在的工作与两者都紧密相连。Merci!

@猴子：在CS231n翻译小组工作的两个多月的时间非常难忘。我向杜客申请加入翻译小组的时候，才刚接触这门课不久，翻译和校对的工作让我对这门课的内容有了更深刻的理解。作为一个机器学习的初学者，我非常荣幸能和翻译小组一起工作并做一点贡献。希望以后能继续和翻译小组一起工作和学习。

@堃堃：感谢组内各位成员的辛勤付出，很幸运能够参与这份十分有意义的工作，希望自己的微小工作能够帮助到大家，谢谢！

@李艺颖：当你真正沉下心来要做一件事情的时候才是学习和提高最好的状态；当你有热情做事时，并不会觉得是在牺牲时间，因为那是有意义并能带给你成就感和充实感的；不需要太过刻意地在乎大牛的巨大光芒，你只需像傻瓜一样坚持下去就好了，也许回头一看，你已前进了很多。就像老杜说的，我们就是每一步慢慢走，怎么就“零星”地把这件事给搞完了呢？

@杜客：做了一点微小的工作，哈哈。

> 感谢对于CS231n的笔记的翻译。

## 关于Linux相关知识

Linux新手，总是遇到各种问题，希望收集起来，可以作为一个知识的积累。

## 关于Python

主要穿插在笔记代码中。

## 关于`Net-Paper`中的paper

大多数是直接参考slim的代码和http://noahsnail.com博客内容, 博客中没有的直接谷歌.

> https://github.com/tensorflow/models/tree/master/research/slim
>
> "通天塔(有很多论文翻译, 虽然翻译的一般, 但是可以看)": http://tongtianta.site/
>
> https://arxiv.org/

---

感谢开源社区，感谢网络世界，感谢帮助到我的所有人。

笔记随时在补充，更新。
