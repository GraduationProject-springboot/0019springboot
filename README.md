# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0019springboot免税商品优选购物商城设计与实现代码

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=20)


# 课题开发的背景
从古至今，通过书本获取知识信息的方式完全被互联网络信息化，但是免税商品优选购物商城，对于购物商城工作来说，仍然是一项非常重要的工作。尤其是免税商品优选购物商城，传统人工记录模式已不符合当前社会发展和信息管理工作需求。对于仓储信息管理，传统的方式都是通过纸质进行对商品的查看、订单信息。随着社会的发展，科技的进步互联网技术变得越来越普及，网络交流的生活方式已经逐渐的受到了广大人民群众的喜爱，越来越多的网络爱好者开始在网络上满足自己的衣食住行及自己的工作学习，同时也渐渐的步入到了各个用户。网络有许多的优点，比如方便、快捷、效率高并且成本低，你可以足不出户就可以获取到自己所需的资产信息。因此，类似购物商城的管理系统满足了足不出户以及工作繁忙的客户的需求，目前，建立网络管理系统，本购物商城的开发是采用Java技术为基础，以Mysql为数据库进行开发的。
## 1.2 课题研究的意义
据数据调查显示，对于网络使用用户数达到5.6亿，相比往年增长较快，人们通过网络的方式已经形成了一种依赖，不管需要什么信息内容，直接在网上进行查找及操作，参考比较大，对免税商品优选购物商城的特点和其他管理系统的优势有了详细的了解，让用户有了更有针对性的选择。这也给用户带来非常大的方便，用户可以不用像传统的方式还要去实体进行购买商品、商家通过购物商城管理进行查看个人中心、商品信息管理、商品分类管理、在线客服管理、订单管理等信息，这样不仅耽误自己的时间，而且比对过程比较单一，了解不那么透彻，所以对于购物商城是人们现在所依赖的一种在线购物的一种方式。

与过去传统的购物商城方式相比，这种网络互动更具灵活性和新鲜感，更容易激发用户的需求。在网络平台上，还可以进行在线购买操作，即促进了管理员的工作，还方便后期管理信息的制定和修改。网上购物商城网络互动实现了个人中心、用户管理、商家管理、商品分类管理、商品信息管理、在线客服管理、系统管理、订单管理等信息，使得免税商品优选购物商城效率得到了极大的提高。
## 1.3 研究内容
目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的信息管理软件仍没有得到大多数人的了解或认可。本选题则旨在通过标签分类管理等方式，实现免税商品优选购物商城的各种功能，从而达到对免税商品优选购物商城相关信息的管理。

详细内容介绍，将在以下六章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。

第二章 系统开发关键技术
## 2.1 JAVA技术
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterrise JavaBeans）的全面支持，java servlet AI，JS（java server ages），和XML技术。

JAVA语言功能：

面向对象：面向对象是Java编程语言的标志之一，是一种软件开发方法。最重要的是将所有东西变成对象，然后以某种方式编程。编程时，代码和数据写在每个对象上。 面向对象编程方法的出现使得人们在编程过程中的设计思考和操作变得非常简单，同时也提高了程序的安全性。

跨平台：Java流行的一个关键特性是它的跨平台特性，这使得用Java编程变得容易。您可以用Java编写程序并在其他地方运行它，而无需在编译后更改它。

垃圾回收机制：用来将那些在程序不操作时无用的对象所占用的内存空间释放掉，C ++最被人厌恶的就是因为其不能将在编程的过程中所占用的内存空间进行及时的释放，导致随着编程时间的变长所占用的内存空间越来越多。对于一些编程高手而言，他们会在刚开始编程的时候配置一块内存地址放在堆栈上，然后在不需要的时候会对其进行释放，而一些新手和菜鸟在很多的时候会忘记删除这个内存地址，从而导致程序在运行的过程中会变得十分的不稳定，最终有可能会导致程序崩溃。所以很多C ++的高手在编写程序时往往都会将删除后的指针的值设置为NULL，然后在删除之前确定一个指针的值是否为NULL。
## 2.2 MyEclipse开发环境
MyEclipse支持广泛、兼容性高并且功能强大，是一个Eclipse 插件集合，普遍适应于JAVA和J2EE的系统开发，支持 JDBC，Hibernate，AJAX，Struts，Java Servlet，Spring，EJB3等市面上存在的几乎所有数据库链接工具和主流Eclipse产品 开发工具。 

MyEclipse在业内是所熟知的开发工具，该平台在开发的过程中运用的就是该工具。MyEclipse又被称之为企业级的工作平台，它是以Eclipse IDE为基础的。MyEclipse可以帮助我们进行数据库的研发和J2EE的使用，除此之外，还可以提高系统的运营能力，这突出表现在服务器的整合过程中。MyEclipse的功能相当完备，能够为J2EE的集成提供必要的环境支持，从而完成编码、测试、调试及发布等功能。它可以支持JSP，HTML，SQL，Javascript，Struts， CSS等。
## 2.3 Tomcat服务器
Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试JSP 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML 页面的运行提供技术支持，Tomcat 的任务则是运行Servle和JSP 页面。Tomca也具有一定的HTML页面处理功能。
## 2.4 Spring Boot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。
## 2.5 MySQL数据库
Mysql的语言是非结构化的，用户可以在数据上进行工作，并且其语言简单，学习起来比较容易，其结构也简单，功能强大，存储信息量大，Mysql主要应用于数据的查询和编程，现在普遍存在的关系数据库有很多，并得到了普遍的应用。使用Mysql数据库在编程过程中带来了极大的方便，可以对数据进行广泛地查询，Mysql数据库的应用并不需要用户了解其存储的方式，更不用掌握数据存放的方法，Mysql数据库的灵活性较强，功能也较强大，大多数情况下，在其他程序中实现某功能需要编写一大堆代码，而在Mysql数据库中只需要一小段代码就可以实现功能，所以，Mysql数据库的语言较简洁。

数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。介于数据库的功能强大等特点，本系统的开发主要应用了Mysql进行对数据的管理。





第三章 系统分析 

开发一个系统首先要对系统进行分析，是开发者针对系统实际客户对软件应用的一个调查访问和研究，弄清用户对软件需求的具体要求，同时开发者还要对系统开发的经济和可技术上是否可行进行分析，并确定系统开发的成本和进度约束。还要与用户确定总体目标等。系统分析还要充分考虑系统的市场潜力和竞争力，最终将这些问题确定并进行总结，将结果纳入系统设计规格说明中，最终确定开发功能和详细的实现。

通常选用计算机软件进行开发一款信息化管理系统，主要将软件系统功能利用Java技术和MYSQL数据库而开发。以下是对本系统的可行性研究、需求分析、功能分析及业务流程描述进行介绍。
## 3.1 系统可行性研究
1、经济可行性分析

免税商品优选购物商城的开发是由开发者自己设计研究所开发，不需要购买其他软件或者端口之类的，而且在系统的开发之前所做的市场调研及其他的免税商品优选购物商城相关系统，都是没有任何费用的，都是通过开发者自己的努力，所有的工作都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于免税商品优选购物商城的开发在经济上是完全可行的，没有任何费用支出的。

2、技术可行性

本免税商品优选购物商城在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通物商城的web服务器。免税商品优选购物商城的开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用BS开发技术，使用比较成熟的开发环境进行对功能的实现及程序的交互，根据技术语言对开发环境的安装管理，结合需求进行修改维护，可以使得购物商城运行更具有稳定性和安全性，从而完成实现网上购物商城的开发。

3、操作可行性

免税商品优选购物商城的界面简单易操作，用户只要平时有在用过电脑，都能进行访问和操作。计算机网络使人们的生活更快捷更有效率。在这个飞速发展的社会里，人们对工作效率的要求越来越高，操作性也越来越强。因此，以计算机和计算机网络为基础的管理系统是社会发展的必然趋势。日新月异的智能软件使我们逐渐从原来的手工操作转变为现在的人工智能。该系统操作简单，管理方便，交互性强，操作简单。因此，该系统在操作上是非常可行的。
## 3.2 性能分析
实用性：免税商品优选购物商城基于市场研究开发的实际需要，用户界面清晰易懂，符合使用人员的功能需求。当使用太多人时，服务器会产生大量的数据流量，响应时间会有一些延迟。

稳定性：免税商品优选购物商城开发系统操作必须有一定程度的稳定性，设计使用安全技术及开发环境进行数据传输，稳定性极佳。

可伸缩性：每个程序的开发过程，不是一蹴而就的，在使用用户的过程中，会有很多不完善的地方，需要改进功能，重新添加新功能等等，这就需要程序的可扩展性、各种功能模块的开发以及独立开发的可行性。

响应性：该系统能够快速响应用户的请求，返回正确、实时的有效信息，尽可能避免失速和碰撞问题。

处理能力：对于系统的异常可以进行有效的处理，可以在异常发生后及时备份，恢复到以前的状态，对数据不进行破坏或修改。
## 3.3 [业务流程分析](#_Toc106465143)
### 3.4.1操作流程
管理员想进入系统，首先进入系统登录界面，通过正确的用户名、密码，用户名和密码输入完成后，系统会检查登录信息，信息正确，然后输入相应的功能界面，提示信息错误，登录失败。系统操作流程如图3-1所示。

![](/md/blog.001.png)

图3-1操作流程图
### 3.4.2添加信息流程
添加信息，编号系统使用自动编号模式，没有用户填写，管理员添加信息输入信息，系统将自动确认的信息和数据，验证的成功是有效的信息添加到数据库，信息无效，重新输入信息。添加信息流程如图3-2所示。

![](/md/blog.002.png)

图3-2添加信息流程图
### 3.4.3删除信息流程
管理员选择要删除的信息并单击Delete按钮，系统提示是否删除信息。如果用户想要删除信息，系统将删除信息。系统数据库删除信息。删除信息流程图如图3-3所示。

![](/md/blog.003.png)

图3-3删除信息流程图

第四章 系统的总体设计
## 4.1 系统功能结构设计
架构设计的目的是反映一个结构和其他元素之间的关系，抽象，通常用于指导大型软件系统。将一个巨大的任务细分为多个小任务的过程是系统架构的总体设计。完成小任务后，整个任务就可以完成了。具体的实现过程是分解系统，分析各部分的功能、接口和逻辑关系。信息传递的设计，最后一步是优化，系统的大体功能靠两部分展现，它们分别是前端平台和后端平台，应用MVC开发框架，页面是一个一个模块组建而成的，层次结构分明，思想运用的是面向对象，一个实体对应一个数据类型，还要对每个数据类添加一个实施类。

架构设计的用途是反映一个结构内的元素与别的元素之间的关系，有抽象性，一般用于为大型软件系统提供指导。将庞大的任务具体细分为多个小人物的过程就是系统架构的整体设计，对细小任务进行整合后就可以完成整个任务，具体实现过程是分解系统，对各个部分的功能、界面和逻辑关系、信息传输予以设计，最后是进行逐步的优化。

用户拥有最高管理权限。通过以上需求分析的调查与研究，将系统的功能定义如下图4-1所示。

![](/md/blog.004.png)

图4-1 系统管理员体功能结构图



## 4.2 数据库概述
在对软件系统分析后，就开始进行软件设计了。在对软件数据库进行设计时，就要先对软件进行一个概念性数据模型设计，来对用户的数据要求清晰明了的表达，从而减少数据运行更加的规范化和减少数据的冗余。
### 4.2.1 数据库概念设计
实现数据概念模型，我们必须采取数据作为起点，做好数据收集和处理的控制，分析它们之间的关系,得到其逻辑模型，该模型不理解的方式来实现和细节性问题，只要系统中数据的状态处理阶段。

我们分析特定用户的需求的功能系统，详细设计在线系统的ER图，我们可以在多个实体之间获得详细的关系模型，如下图所示：实体模型图之间的关系：

（1）用户E-R图

![](/md/blog.005.png)

图4-2管理员E-R图

（2）商品类别E-R图

![](/md/blog.006.png)

图4-3仓库资产类别E-R图

（3）商品信息E-R图

![](/md/blog.007.png)

图4-4 商品信息E-R图

（4）订单信息E-R图

![](/md/blog.008.png)

图4-5 订单信息E-R图
### 4.2.2 数据库逻辑设计
我们可以根据数据结构的详细分析要求，我们根据输入和输出数据量的要求进行分析，确定什么表表，结构之间的关系，我们可以验证， 调整和完善，查询和浏览过程，可以实现数据库，以使用户对数据和功能有更多要求。

表4-1：address信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|userid|bigint|20|DEFAULT NULL|
|address|varchar|200|DEFAULT NULL|
|name|varchar|200|DEFAULT NULL|
|phone|varchar|200|DEFAULT NULL|
|isdefault|varchar|200|DEFAULT NULL|
表4-2：cart信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|tablename|varchar|200|DEFAULT NULL|
|userid|bigint|20|DEFAULT NULL|
|goodid|bigint|20|DEFAULT NULL|
|goodname|varchar|200|DEFAULT NULL|
|picture|varchar|200|DEFAULT NULL|
|buynumber|int|11|DEFAULT NULL|
表4-3：chat信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|tablename|bigint|20|DEFAULT NULL|
|userid|bigint|20|DEFAULT NULL|
|goodid|bigint|20|DEFAULT NULL|
|goodname|varchar|200|DEFAULT NULL|
|picture|varchar|200|DEFAULT NULL|
|buynumber|int|11|DEFAULT NULL|
表4-4：config信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|refid|bigint|20|DEFAULT NULL|
|userid|bigint|20|DEFAULT NULL|
|nickname|varchar|200|DEFAULT NULL|

表4-5：gongyingshang信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|name|varchar|100|DEFAULT NULL|
|value|varchar|100|DEFAULT NULL|
表4-6：discussshangpinxinxi信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|refid|bigint|20|DEFAULT NULL|
|userid|bigint|20|DEFAULT NULL|
|nickname|varchar|200|DEFAULT NULL|

表4-7：news信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|title|varchar|200|DEFAULT NULL|
|picture|varchar|200|DEFAULT NULL|
表4-8：orders信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|orderid|varchar|200|DEFAULT NULL|
|tablename|varchar|200|DEFAULT NULL|
|userid|bigint|200|DEFAULT NULL|
|goodid|bigint|200|DEFAULT NULL|
|guige|varchar|200|DEFAULT NULL|
|goodname|varchar|200|DEFAULT NULL|
|picture|varchar|200|DEFAULT NULL|
|type|int|11|DEFAULT NULL|
|status|varchar|200|DEFAULT NULL|
|address|varchar|200|DEFAULT NULL|
表4-9：shangjia信息表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|20|PRIMARY KEY|
|shangjiazhanghao|varchar|200|DEFAULT NULL|
|mima|varchar|200|DEFAULT NULL|
|shangjiaxingming|varchar|200|DEFAULT NULL|
|dianpudizhi|varchar|200|DEFAULT NULL|
|lianxiren|varchar|200|DEFAULT NULL|
|lianxifangshi|varchar|200|DEFAULT NULL|
|shangjiatupian|varchar|200|DEFAULT NULL|
|jingyingfanwei|varchar|200|DEFAULT NULL|
|sfsh|varchar|200|DEFAULT NULL|


第五章 系统的实现
## 5.1登录界面
登录窗口，用户通过登录窗口可以进行登录,进行输入用户名、密码等信息，进行登录操作，如图5-1所示。

![](/md/blog.009.png)

图5-1登录界面
## 5.2管理员功能模块
管理员登录成功后，可以进行查看个人中心、用户管理、商家管理、商品分类管理、商品信息管理、在线客服管理、系统管理、订单管理等功能模块。进行相对应操作。

用户管理：通过列表可以获取账号、用户名、姓名、性别、头像、联系电话、照片、地址等信息，进行查看详情、修改或删除操作，如图5-2所示。

![](/md/blog.010.png)

图5-2用户管理界面

商家管理：通过列表可以获取商家的详细信息内容，进行查看详情或删除操作，如图5-3所示。

![](/md/blog.011.png)

图5-3商家管理界面

订单管理：通过列表可以获取订单编号、商品名称、商品图片、购买数量、价格、总价格、支付类型、状态、地址等信息，进行查看详情或发货、删除操作，如图5-4所示。

![](/md/blog.012.png)

图5-4订单管理界面图



## 5.3商家功能模块
商家通过点击后台管理进入后台系统可以进行查看个人中心、商品信息管理、商品分类管理、在线客服管理、订单管理等功能模块，进行相对应操作，通过点击个人信息页面可以进行查看员工的基本信息，进行查看或修改操作，如图5-5所示。

![](/md/blog.013.png)

图5-5商家信息界面

商品信息管理：通过列表可以获取商品名称、商品类型、规格、图片、商家账号、商家姓名、价格等信息内容，进行查看详情、在线客服、查看评论、新增或删除操作，如图5-6所示。

![](/md/blog.014.png)

图5-6商品信息管理界面

在线客服管理：通过列表可以获取客服编号、内容、账号、姓名、商家账号、商家姓名、客服回复等信息，进行查看详情、修改、删除操作，如图5-7所示。

![](/md/blog.015.png)

图5-7在线客服管理界面

我的收藏管理：通过列表可以获取收藏名称、收藏图片等信息，进行查看详情、修改或删除操作，如图5-8所示。

![](/md/blog.016.png)

图5-8我的收藏管理界面

订单管理：通过列表可以获取订单编号、商品名称、商品图片、购买数量、价格、总价格、支付类型、状态、地址等信息，进行查看详情或删除操作，如图5-9所示。

![](/md/blog.017.png)

图5-9订单管理界面

## 5.2用户前台功能模块
用户通过家免税商品优选购物商城系统，可以进行查看首页、商品信息、商城快讯、个人中心、后台管理、购物车等功能，可以进行相对应的操作，如图5-10所示。

![](/md/blog.018.png)

图5-10首页系统界面

商品信息详情：通过页面可以进行查看商品名称、商品价格、商品类型、规格、商家账号、商家账号、商家姓名、点击次数等信息，进行添加到购物车或立即购买、点我收藏，如图5-11所示。

![](/md/blog.019.png)

图5-11商品信息界面

个人中心：通过页面可以进行查看获取个人中心、我的订单、我的地址、我的收藏四个子模块，个人中心：通过页面可以进行查看个人信息或进行更新个人信息，进行提交保存操作，如图5-12所示。我的订单：通过列表可以获取订单编号、商品、价格、数量、总价、地址等信息，进行查看我的订单或进行退款操作，如图5-13所示。我的地址：通过页面可以进行查看联系人、手机号码、选择地址等信息，进行查看或修改、删除操作，并通过输入添加新地址进行添加操作，如图5-14所示。

![](/md/blog.020.png)

图5-12个人信息界面

![](/md/blog.021.png)

图5-13我的订单界面

![](/md/blog.022.png)

图5-14我的地址界面图

## 5.3用户后台功能模块
用户通过点击后台管理进入后台系统可以进行查看个人中心、商品信息管理、在线客服管理、我的收藏管理、订单管理等功能模块，进行相对应操作，如图5-15所示。

![](/md/blog.023.png)

图5-15用户后台系统界面

在线客服管理：通过列表可以获取客服编号、内容、账号、姓名、商家账号、商家姓名、客服回复等信息，进行查看详情操作，如图5-16所示。

![](/md/blog.024.png)

图5-16在线客服管理界面

商品信息管理：通过列表可以获取商品名称、商品类型、规格、图片、商家账号、商家姓名、价格等信息内容，进行查看详情、在线客服、查看评论、新增或删除操作，如图5-17所示。

![](/md/blog.025.png)

图5-17商品信息管理界面

第六章 系统测试
# 系统测试的










