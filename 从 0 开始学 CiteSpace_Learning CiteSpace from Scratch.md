> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzU5NTAzNzY2MQ==&mid=2247484967&idx=1&sn=4127ed73610ba0d8811958711dfe756f&chksm=fe795a95c90ed3830afd80b1b49b4f83d3249085d7e39217fd1cef5e9eccbb0519e0cdef26f3&token=670793253&lang=zh_CN#rd)

**研一时，有门课的课程作业之一是介绍一种方法论，**这里**把当时的课程作业分享出来**，教你如何****从 0 开始一步一步******操作 ****Cite****S****pace********。**

****Cite****S****pace** 作为文献计量法的文献处理**工具**，入门还是比较简单的。******使用工具最难的一步就在于快速入门，尽管这篇文章和这些图的质量远远没有达到发表论文的水平，不过还是有价值的。**希望对想要了解 ****Cite****S****pace****、有使用需求的人有帮助。******

**********明天会再更新一篇利用 **********Cite****S****pace 分析的**********较为完整的课程论文。**********

**目 录**

一、**Cite****S****pace**——基于文献计量法设计的数据可视化软件

（一）研究方法——文献计量法

##### （二）CiteSpace 是什么

##### （三）如何下载 CiteSpace

二、以 CNKI 为例进行案例分析

（一）数据处理

1. 获取数据 

2. 转换数据

（二）建立项目 / 设置参数

（三）可视化结果

1. 关键词共现图谱的方法论基础、含义及分析

2. 聚类的功能

三、教师驻校培养模式研究的计量学分析结果

（一）教师驻校培养模式研究文献年度分布

（二）作者分布

四、教师驻校培养模式研究热点分析

（一）研究热点主题分析

（二）研究领域分析

五、教师驻校培养模式研究的演进路径

**教师驻校培养模式研究发展及热点演进的文献计量学分析**

**——基于 CitesSpace 的可视化分析**

本文旨在通过借助工具 **Cite****S****pace**(可视化文献分析软件)，来归纳和展望国内外对于教师驻校培养模式研究的发展历程、宏观趋势以及研究热点变化，达到论述文献计量法这一方法的目的。

一、**Cite****S****pace**——基于文献计量法设计的数据可视化软件

（一）研究方法——文献计量法

##### 文献计量法是以文献体系和文献计量特征为研究对象，采用数学、统计学等计量研究方法，研究文献情报的分布结构、数量关系、变化规律和定量管理，进而探讨科学技术的某些结构、特征和规律的一门学科。CiteSpace 作为文献计量法中的一项文献处理工具，能帮助我们快速分析文献。

##### （二）**CiteSpace** 是什么

##### CiteSpace(可视化文献分析软件) 是由美国雷德赛尔大学信息科学与技术学院的陈超美博士与大连理工大学的 WISE 实验室联合开发的科学文献分析工具，该软件将文献计量法、信息可视化法以及数据挖掘法结合起来，通过绘制知识图谱以探寻不同学科领域研究热点与趋势演化的关键路径及知识转折点。利用 CiteSpace 可以对文章作者、机构和关键词进行分析。例如，在 CiteSpace 中使用关键词共现来探究该领域的研究热点，关键词突现预知研究前沿，关键词时区了解研究趋势、发文机构分析和发文作者的分析.

##### CiteSpace 的设计理念分为哲学角度和概念模型两个方面。从哲学角度来看，该软件首先参照了波普尔的三个世界理论，即整个世界被划分为物理世界（世界 Ⅰ）、精神世界（世界 Ⅱ）、客观知识世界（世界 Ⅲ）。世界 Ⅰ 是外在接触到的具体世界；世界 Ⅱ 是人类脑中的精神世界，存在隐形知识；世界 Ⅲ 是人类创造的知识体系。传统看世界的方式是人类通过世界 Ⅱ 来感知世界 Ⅰ，形成世界 Ⅲ。CiteSpace 是通过将世界 Ⅲ 中的知识内容进行知识图谱可视化来认识世界 Ⅰ，即借助世界 Ⅱ 通过世界 Ⅲ 来认识世界。

##### 其次是托马斯 · 库恩的科学革命的结构。库恩认为，科学的推进是建立在科学革命上的一个往复无穷的过程。这个过程中会出现一个又一个的科学革命，人们的认识通过科学革命而接纳新的观点，而新观点的重要性在于对我们所观察的对象能否作出更另人信服的解释。库恩的科学革命是新旧科学范式的交替和兴衰。科学认识中会出现危机，而危机所带来的新旧范式的转换都将在学术文献里留下印记。库恩的理论给我们提供了一个具有指导意义的框架，如果科学进程真像库恩所洞察的那样，那我们就应该能从科学文献中找出范式兴衰的足迹。

##### 第三，普赖斯科学前沿理论：“论文会因为引证关系而形成网络，人们可以借助于图论和矩阵的方法来加以研究… 论文一定会聚集成一团，而形成几乎绘制成地图的‘陆地’和‘国家’”。基于普赖斯的论断，才形成了 CiteSpace 的概念模型。

##### 第四，博特的结构洞理论，即社交网络中不是每个人和所有其他人都有直接联系，如果如此，便有了结构洞，即结构上的不完备。这种情况下，信息在网络中的流动受到其结构上的约束。每个人在网络中所能接触到的信息内容不再相同，传递和接受的时间也会出现差别。Burt 发现位于结构洞周围的人往往具有更大的优势。CiteSpace 也是基于此理论来识别关键节点和关键位置

##### 第五，信息觅食理论，该理论用来解释模拟人们在网络环境中的信息搜寻行为，对获取信息的效率进行运算，以最小搜索成本获取最大利益。该理论用于 CiteSpace 网络结构探测，开发出探求知识演变路径的方法和技术。

##### CiteSpace 的概念模型认为，“如果把某一领域的研究前沿定义为一个研究领域的发展状况，那么研究前沿的引文就形成了相应的知识基础。” 在 CiteSpace 中研究前沿和知识基础被定义如下：研究前沿是指某个科学领域中的施引文献群组。从两个方面体现研究前沿的特征：1. 施引文献群组本身的内容； 2. 施引文献群组引用的参考文献。 具体可以体现为：1. 施引文献群组使用的关键词； 2. 施引文献群组引用的参考文献。 知识基础是指某个学科领域中相对于研究前沿文献集的所有前期文献集合。具体表现为文献共被引聚类。

##### 在此基础上，理论和技术的发展为 CiteSpace 提供了基础——理论基础：引文分析；技术基础：信息可视化。目前 CiteSpace 支持以下数据库导出的文献题录及参考文献数据：

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2j4aEJHGqT2q1kbejW3ztxHUznzQUhO2J26MNj6Yw7n4npjgaGBurR4w/640?wx_fmt=png)

图 1.CiteSpace 支持数据库导出的文献题录及参考文献数据 

##### 当前研究中研究英文文献主要采用 web of science 数据库，中文数据主要采用 CNKI 和 CSSCI 数据库。研究者可根据自身的需求选择数据来源，并注意其所要求的格式和文件名。需注意的是：所有手动下载的数据文件的文件名必须以 download 开头，如 download2020.txt。若需要对被引文献进行分析，必须选择具有参考文献的数据库，否则共被引部分的功能将无法实现。

##### （三）如何下载 **Cite****S****pace**

##### 1、下载网址:http://cluster.ischool.drexel.edu/~cchen/citespace/download/

##### 2、进入网站，点击 download 弹出保存后点击保存。

##### 3、解压安装包，双击 “StartCiteSpace_Windows.bat” 文件，进行 CiteSpace 的安装。由于软件运行需要 java 环境，验证 java 版本地址为：https：//java.com/zh_CN/download/installed8.jsp. 安装适配电脑的 java 地址为：https：//www.java.com/en/download/. 选择适合自己的语言环境输入相应的数字后点击回车。之后根据其提示，一直点击 “下一步” 安装即可。安装完成之后，再双击 “CiteSpaceV.jar” 文件，等待一会儿，本文使用 5.7.R2(64-bit) 版本，操作界面如下：

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jqzPnLuKIE3CB3vBMdZicTDlul9ibMyvwIucKmeib4Skb8KHdvnIjWiaD5Q/640?wx_fmt=png)

图 2.StartCiteSpace 界面

##### 在问号后输入 2 选择中文语言跳转进入软件，在是否同意在文章中引用 CiteSpace 相关的文献中点击 “Agree”，即可成功打开 CiteSpace 进入以下界面 (图 3.CiteSpace 主界面)，界面主要分为上方的菜单栏、左侧上方的工程区、左侧下方的运行进度区和右侧的功能选择区。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jVBbFNGScQ3yFWUPqhCuTtqwU0DZia3ibibr9rdXVzOar5Xt4XFjau3CYg/640?wx_fmt=png)

图 3.CiteSpace 主界面

菜单栏是 CiteSpace 的功能与参数区，包括 File(文件)、Projects(项目) 、Data(数据)  Network(网络) 、Visualization(可视化) 、Geographical(地理化) 、OverlayMaps(叠加分析)  Analytics(文献网络分析报告) 、Text(文本) 、Preferences(偏好设置) 、Tutorials(教程)、Resources(资源)、Community(社区)、Help(帮助)、Donate(捐献)。

工程区又叫操作区，该区域主要用于新建项目，点击 New 即可进入新工程的设置界面。运行进度区可以展示 CiteSpace 在运行过程中的数据操作。

功能选择区包括

1、**Time slicing 时间切片区**，可以选择待分析文献的起止时间；

2、**Text Processing 文本处理区**（包括 Term source 选择聚类词来源和 Term type 聚类词类型）； 

3、**Node types 网络配置功能区**，这部分可以选择节点类型，选择将直接决定会生成什么样的图谱 (在其中，不同颜色的选项代表不同的含义：蓝色部分关于合作网络分析，对象可以是作者、机构或国家，如可以分析哪些作者、机构或文章的发文量比较多，哪些作者之间的合作比较多；绿色区是共性分析，其对象可以是主题、关键词、来源或 WOS 的分类，其中主题和关键词回答的问题是：哪些主题词或关键词出现的次数比较多，以及哪些词常常在同一篇文章中出现，反映了研究领域的热点词；红色部分是共被引分析，对象可以是参考文献、文献作者和期刊，回答的问题是哪些文献、作者和期刊被引用的次数最多，哪些常常被一起引用，这样的问题则反映了内容的相关性；灰色部分则是耦合分析)；

**4、Links 连接强度计算** (·Strength 分析对象数据之间的连接强度 ·Scope 范围)； 

5、Select criteria 阈值选择标准； 

6、Pruning 剪枝方式选择（优化结果）； 

7、Visualization 可视化模式。

**二、以 CNKI 为例进行案例分析**

本文以中国知网 (CNKI) 为例，以 “教师驻校模式” 为检索关键词用 CiteSpace 进行数据分析。分析过程包括以下几个部分：数据处理、建立项目 / 设置参数、可视化结果、结合图谱结果进行初步解读、分析结果并完成撰写报告。本文着重对前三个过程展开论述。

**（一）数据处理**

**1. 获取数据** 

（1）在桌面建立一个名为 “data for citepace”(可任意命名) 的数据库，用来专门存放 citespace 的数据。在其下以自己的研究主题再命名一个子文件夹 (如图 4，本文命名为 “教师教育”)，在子文件夹下新建四个文件夹：“input”、“output”、“project” 和 “data”。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jCeNtAzU9yjP8bIVZfubiaKB96q2A9OnotH4VN1kKPBAu9dPiaPXEDWlQ/640?wx_fmt=png)

图 4. 新建 “data for citespace” 的数据库

（2）进入中国知网（旧版）进行数据下载，在高级检索中限定主题或者关键词（本文在高级检索中输入 “教师驻校模式” 的关键词，选择中文文献）。

（3）点击 “全选” 之后有 35 篇文献，筛选并剔除无直接相关的文献两篇，分析剩余 33 份与研究主题直接相关的。若要导出大批量数据，可以在 “每页显示” 中选择 50，再根据研究需要，如剔除报告、会议等相关文献。进入下一步，在 “导出 / 参考文献”跳转的页面 “请点击这里” 中进行筛选。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jQBkKjTQc4tib0EgFK7tK1Gfo7dMdyGN0abWwleIZkBbLf4U6mibuia1Ng/640?wx_fmt=png)

图 5. 选择数据

（4）点击 “导出 / 参考文献” 选项，点击 “文献导出格式”-“Refworks”-“导出”，将这份下载的 txt 文本格式的文件命名为 download1，并放入 “input” 的文件夹中。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jnQB7hoKFF8T1bXSib7t2wK3XyicoSZ6ooV2xjicJe3BUic5Or7CPAYBpTQ/640?wx_fmt=png)

图 6. 文献输出

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jxVSTVSd2xgpxNibZFX99a843VGwNjoZjPh7NjYPsyRDA9FiaXn0nWyZg/640?wx_fmt=png)

图 7. 命名导出的参考文献

2. 转换数据

（1）打开 5.7.R2(64-bit)，等待片刻后进入主界面 (图 3)，点击 Data(Import/Export) 选择 CNKI

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jkkG0PxeS3KgVm95I8Iutziblt1LYuhedq8cBCaUzbAlB1hIyfWibahFA/640?wx_fmt=png)

——————————————————————————

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jXVJuAr6tKhsBBp2Mhpr8vH47ibdmqQRFvnVRYmc5o9e3qZNUkKH7ia0Q/640?wx_fmt=png)

（2）Data →Import→download1

（3）Input directory 选择 “input” 文件夹，Output directory 选择 “output” 文件夹

点击 CNKI Format Conversion2.0，完成转换。可点击 output 文件夹检查数据转换与否。

（4）把 output 里的数据复制到 “data” 文件夹下

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jJINH44dd4pNzNLtVqSR64iaM72svWvj0lQFsa2yotAtsUcLkNqdXSvA/640?wx_fmt=png)

（二）建立项目 / 设置参数

1、新建项目。回到主界面，在控制面板菜单栏中点击 File 建立新项目，在 “Title” 中命名英文格式的项目，本文命名为 Teacher Residency。

2、功能选择区进行参数选择。时间切片区 From 2001 JAN To 2020 DEC，Node Types 选择 Keyword，Pruning 在循进中选择 Pruning sliced networks。点击”GO!” 出现图 8 选项。

3、点击可视化操作”Visualize”

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jIcK5UDiaJF87pfJuEmAYenibcy6Dh4oSShoy8W3QeCdvTLGIWLxeD6Eg/640?wx_fmt=png)

图 8. 可视化选项

（三）可视化结果

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jkDa8icHRicaOZhPaVAvia59bmHy3oZwfEtttACPXn5C7Sw7nY5xwHEKvQ/640?wx_fmt=png)

图 9. 菜单栏的工具功能简介

1. 关键词共现图谱的方法论基础、含义及分析

共现分析的方法论基础是心理学的邻近联系法则和知识结构及映射原则。邻近联系法则是指曾经在一起感受过的对象往往在想象中也联系在一起，以致于想起它们中的某一个的时候，其他的对象也会以曾经同时出现时的顺序想起。关键词共现、作者共现、机构共现、国家共现、论文共现、期刊共现都是共现分析的一种。其中，作者共现分为作者合作网络分析、作者共被引分析 [作者同被引]；机构共现分为机构合作网络分析；国家共现又分为国家合作网络分析；论文共现分为文献共被引分析[文献同被引] 和文献耦合。

参数中可以看见网络的节点数、边数和网络密度。图中所示标注的点即节点，一个节点代表一个关键词。边数是关键词之间的连线数，关键词之间的连线是指关键词在同一篇文献中出现过，因此二者会有一根连线。图中圆圈大小代表关键词，频数越大圆圈越大。线条代表关键词之间的联系，线条颜色与图中上方的年份相对应，用于标志每年都有哪些关键词。

关键词是对一篇文献的核心概况，分析关键词可以对文章主题进行窥探。一篇文献中的多个关键词必然存在着某种联系，那么这种联系可以用共现的频次来表示。一般认为，词汇对同一篇文献中出现的次数越多，则代表这两个主题之间的联系越紧密。频次是关键词出现的次数，年份代表某个关键词最早出现的年份是什么时候。其中阈值越小，显示的数量越多；阈值越大显示的关键词越少。

综上所述，共词分析法，即利用文献集中词汇或者名词短语共同出现的情况，来确定这篇文献集所代表学科中各主题之间的关系。统计一组文献的主题词两两间在同一篇文献出现的频率，便可形成一个由这些词对关联所组成的共词网络。

2. 聚类的功能

共词分析法的原理是通过利用文献集中词汇对或名词短语共同出现的情况，来确定该文献集所代表学科中各主题之间的关系。掌握以上原理，是为了获得学科之间各主题之间的关系，由于主题通过使用关键词所表示，它的本质便是关键词之间的联系。同时，联系越紧密的关键词会形成一个小团体，进而能把小团体之间的关键词进行归纳总结，然后总结出一个主题，再对主题进行详细论述。以上操作步骤的本质是做聚类分析。点击”K” 查看聚类，这一功能是当看不清或看不懂图谱时可以利用的方法。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jRTNeYE4XicdiccujZCUK3RA17ibApMCmsXsjTVa9dHDUrq4l1oCkGibicibg/640?wx_fmt=png)

图 10. 关键词显示

（聚类之间的间距可以在面板中调整）

需要补充的是，上图并没有显示全部聚类，原因是 CiteSpace 默认当关键词 <10 时，不显示一部分聚类。可以在”Filters” 里取消”Show the Largest Connected Componet Only” 这个选项，再重新聚类。也可以根据自己的需求设置确定数量的聚类，此时操作”Clusters”-”Show the Largest K Clusters” 后输入自己需要的所含关键词最多的前几个聚类数；或者用序号来表示聚类。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jleDrFFyywEicRK0bV70RLrnDD21ThhicrIsMpqbx6o0oJQOe5JTnHH6w/640?wx_fmt=png)

图 11. 部分聚类显示

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jRW5KIEdtmYicoeGse0niakSWGibmLbQ4Vw9wjJudBaG4O5MLFqmCybWuw/640?wx_fmt=png)

图 12. 全部聚类显示

**三、教师驻校培养模式研究的计量学分析结果**

**（一）教师驻校培养模式研究文献年度分布**

文献发表数量的变化能够在一定程度上反映某一研究领域的发展状况。研究对近二十年来我国教师驻校模式研究文献的年度分布情况进行统计，详见下图。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jeuLadMTMOmma5Zc6TSYhoJ4IgiaZNp6TPpf3mINibOic4G8zazyN0bLJA/640?wx_fmt=png)

**（二）作者分布**

对文献作者情况进行计量学分析，不仅可以找出教师驻校培养模式研究领域的核心作者，也可以看出该领域学者之间的交流、合作情况。运行 CitesSpace，设置时间跨度为 “2000-2020 年”，时间切片为 1，节点类型中选择 “作者”，阈值为 Top=50，关键词引文数（C），关键词被引数（CC）、关键词共被引数（CCV）均设置为 0、1、20，最终得到网络节点为 42，连线数为 14，密度为 0.0163 的作者共现知识图谱，详见下图。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jOHdHlNbI24DtDthriaiakQssia1oMicULZGuibJNnia9ymDejGpIu2MulYQw/640?wx_fmt=png)

**四、教师驻校培养模式研究热点分析**

**（一）研究热点主题分析**

关键词是一篇文章核心内容的凝练，且能反映这一领域的研究热点。[2] 本文采用 CitesSpace 对教师驻校培养模式研究文献中出现的关键词进行分析，以了解近二十年来我国教师驻校培养模式的研究热点，绘制关键词知识图谱，详见图 10。由图可以看出热点的词汇有 “教师教育”“教师培养”“驻校培养”“薄弱学校”“城市教师驻校模式”，且这些热点词汇之间的联系也较为紧密。为进一步明确我国特殊教育教师研究热点主题，将主题词中介中心性及频次导出并制作成表格，详见表 1。

表 1 高频关键词频次、中心性关键词排序

<table cellspacing="0"><tbody><tr><td width="70" valign="center"><p><strong>序号</strong></p></td><td width="141" valign="top"><p><strong>关键词</strong></p></td><td width="68" valign="top"><p><strong>频次</strong></p></td><td width="71" valign="center"><p><strong>序号</strong></p></td><td width="134" valign="top"><p><strong>关键词</strong></p></td><td width="84" valign="top"><p><strong>中心性</strong></p></td></tr><tr><td width="70" valign="center"><p>1</p></td><td width="141" valign="center"><p>教师教育</p></td><td width="68" valign="center"><p>13</p></td><td width="71" valign="center"><p>1</p></td><td width="134" valign="center"><p>教师教育</p></td><td width="84" valign="center"><p>0.51</p></td></tr><tr><td width="70" valign="center"><p>2</p></td><td width="141" valign="center"><p>美国</p></td><td width="68" valign="center"><p>12</p></td><td width="71" valign="center"><p>2</p></td><td width="134" valign="center"><p>美国</p></td><td width="84" valign="center"><p>0.38</p></td></tr><tr><td width="70" valign="center"><p>3</p></td><td width="141" valign="center"><p>城市教师驻校模式</p></td><td width="68" valign="center"><p>5</p></td><td width="71" valign="center"><p>3</p></td><td width="134" valign="center"><p>培养模式</p></td><td width="84" valign="center"><p>0.25</p></td></tr><tr><td width="70" valign="center"><p>4</p></td><td width="141" valign="center"><p>培养模式</p></td><td width="68" valign="center"><p>4</p></td><td width="71" valign="center"><p>4</p></td><td width="134" valign="center"><p>城市教师驻校模式</p></td><td width="84" valign="center"><p>0.15</p></td></tr><tr><td width="70" valign="center"><p>5</p></td><td width="141" valign="center"><p>驻校模式</p></td><td width="68" valign="center"><p>4</p></td><td width="71" valign="center"><p>5</p></td><td width="134" valign="center"><p>薄弱学校</p></td><td width="84" valign="center"><p>0.15</p></td></tr><tr><td width="70" valign="center"><p>6</p></td><td width="141" valign="center"><p>教师培养</p></td><td width="68" valign="center"><p>4</p></td><td width="71" valign="center"><p>6</p></td><td width="134" valign="center"><p>驻校教师</p></td><td width="84" valign="center"><p>0.15</p></td></tr><tr><td width="70" valign="center"><p>7</p></td><td width="141" valign="center"><p>城市教师</p></td><td width="68" valign="center"><p>3</p></td><td width="71" valign="center"><p>7</p></td><td width="134" valign="center"><p>教师培养模式</p></td><td width="84" valign="center"><p>0.11</p></td></tr><tr><td width="70" valign="center"><p>8</p></td><td width="141" valign="center"><p>模式</p></td><td width="68" valign="center"><p>3</p></td><td width="71" valign="center"><p>8</p></td><td width="134" valign="center"><p>教师培养</p></td><td width="84" valign="center"><p>0.09</p></td></tr><tr><td width="70" valign="center"><p>9</p></td><td width="141" valign="center"><p>城市校区</p></td><td width="68" valign="center"><p>3</p></td><td width="71" valign="center"><p>9</p></td><td width="134" valign="center"><p>教育硕士</p></td><td width="84" valign="center"><p>0.09</p></td></tr><tr><td width="70" valign="center"><p>10</p></td><td width="141" valign="center"><p>薄弱学校</p></td><td width="68" valign="center"><p>3</p></td><td width="71" valign="center"><p>10</p></td><td width="134" valign="center"><p>全日制教育硕士</p></td><td width="84" valign="center"><p>0.08</p></td></tr></tbody></table>

中介中心性代表着以该关键词为主题的研究对网络图谱中其他关键词的中介效果，中介中心性越高，其影响越显著。[3] 因此，该研究将频次与中介中心性共同作为研究热点的判断依据。频次排名较高且中介性大于 0.1 的关键词包括 “教师教育”“美国”“培养模式”“城市教师驻校模式”“薄弱学校”“教师培养模式” 等。这些关键词基本反应我国近二十年来教师驻校模式研究的热点及核心主题。

**（二）研究领域分析**

关键词聚类可将共现知识图谱中复杂的连线关系进行分析，以形成当前教师驻校模式主要研究领域。在调节关键词共现知识图谱的基础上，标识每个聚类，详见图 11。第一个聚类为 “城区教师驻校模式”。第二个聚类为 “培养模式”。第三个聚类为 “教师培养”。第四个聚类为 “模式探析”。第五个聚类为 “教师”。第六个聚类为 “全日制教育硕士”。

**五、教师驻校培养模式研究的演进路径**

在聚类图的基础上，选择信息可视化中的时区视图选项统计并绘制关键词前沿时序图谱，详见图 13。关键词突变用以显示研究的前沿是什么，在本文中由于文献数量太少无关键词突变，可以判断出在教师教育领域驻校模式的研究仍然较为分散，没有成体系的研究初步尝试期、巩固发展期及繁荣发展期等连续性的过渡阶段，因此想要通过预测该研究领域的演进路径还较为困难。

![](https://mmbiz.qpic.cn/mmbiz_png/wBDSlDW0GuGwkMF8R8MOsQia7e7HvNF2jJD2RPzF9ZsNYYcicMGCrqhMHVV1s5LESMyU2tico1xqnhxLibjBeLziaFg/640?wx_fmt=png)

图 13. 教师驻校培养模式关键词前沿时序图谱

补充说明：以上操作仅供参考。这一年有关这个主题的文献已经增加了许多，大家可以沿用以上的操作方式看看有什么变化。

参考文献：

[1] 陈悦. 引文空间分析原理与应用 [M]. 科学出版社，2014.

[2] 李杰，陈超美. citespace：科技文本挖掘及可视化 [M]. 首都经济贸易大学出版社，2016.

[3] 冯永刚, 彭兰香. 近十五年我国德育研究热点及前沿趋势探微——基于文献计量学和科学知识图谱的可视化分析 [J]. 山东师范大学学报 (人文社会科学版),2018,63(05):70-82.

[4] Chaomei Chen. Science Mapping:A Systematic Review of the Literature[J]. Journal of Data and Information Science,2017,2(2):1-40.

[5] Chaomei Chen,Zhigang Hu,Shengbo Liu & Hung Tseng. Emerging trends in regenerative medicine:A scientometric analysis in CiteSpace [J]. Expert Opinionon Biological Therapy,2012, 12(5): 593-608.

信息计量学 |CiteSpace 使用教程 (https://www.jianshu.com/p/49d41d0ccd7f)