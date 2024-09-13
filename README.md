# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm824基于Java的在线日语培训平台的设计与实现+jsp

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1xRe2eHEsa?p=21)


# 第一章 绪论
## 1.1 选题背景
目前整个社会发展的速度，严重依赖于互联网，如果没有了互联网的存在，市场可能会一蹶不振，严重影响经济的发展水平，影响人们的生活质量。计算机的发展，不管是从硬件还是软件，都有很多技术储备，每年都有很多的技术和软件产生，纵观各个领域，无一不用互联网软件，办公用的还是电脑居多，但是人手一台智能设备已经变成了现在人们的生活日常，哪怕的普通的老百姓都成了上知天文下知地理的所在，这些都依赖于互联网技术。互联网技术在信息的传播方面是巨大的，而信息的处理就变成了各种产业管理者和维护者的重任。人们已经习惯了互联网的存在，所以经常操作一些互联网产品变成了日常，所以开发一个在线日语培训平台，让人们使用是没有一点问题的，并且在这个过程中不仅能够规范日语培训信息管理的使用流程还有信息处理流程，也能让整个信息的传播处理，都存在一种可控制的范围，最重要的是，计算机在日语培训信息管理方面可以给管理者提供更好的帮助。
## 1.2 选题意义
当开发软件变成了一个潮流之后，会发现不管任何行业都能开发适合自己的软件，不管是内部员工管理，还是财务管理，甚至业务管理都可以数据化，并且可以对这些数据集中处理，进而根据数据处理结果就自然而然的提高了管理水平，最重要的是，开发一个软件投入使用，开发过程其实就是梳理行业痛点的过程，就是让软件来弥补行业的管理漏洞，不断的优化事物的处理流程。在线日语培训平台就是一款专门开发的软件，通过Web技术，让使用者可以在任何一台智能设备上面通过浏览器进行操作使用，对数据的处理不在局限于地域距离，只要软件开发到位，使用起来方便，达到预期目的，会发现有软件和没有软件的区别是很大的，有了这款软件之后，会发现数据的存储安全方面，比起之前的满屋寻找记录的优势是多么的巨大。
## 1.3 研究内容
系统将按照如下环节来阐述。

绪论：对系统的背景，意义进行说明；

开发环境：对系统使用的数据库工具，框架技术等说明；

系统分析：对系统开发可行，分析的功能等说明；

系统设计：对系统的功能结构，数据表等说明；

系统实现：对系统的各个角色的功能操作界面进行展示和说明；

系统测试：对系统的测试进行说明；

# 第二章 开发环境
开发本系统需要配置开发环境，除了需要开发者安装相应的软件外，也需要对开发中运用的技术进行了解和掌握。
## 2.1 Java语言
Java语言是目前最流行的语言之一，不仅可以做桌面窗口形式的程序，还可以做浏览器访问的程序，目前最流行的就是用Java语言作为基础，做各种程序的后台处理。Java语言是操作变量的语言，而变量则是Java对于数据存在形式的定义，变量用来操作内存，而内存则牵扯到计算机安全问题，这样Java语言反而有了免疫直接针对用Java语言开发出来的程序的病毒，有效的提高了Java语言开发出来程序的生存能力。Java是具有动态运行能力的一种语言，Java的类不仅仅可以用Java核心提供的基础类，还可以进行重写，这样会让Java的功能变得更加丰富，甚至可以编写一些功能模块进行封装，然后其他项目如果需要用到这些可以复用的功能，完全可以直接引用，然后在用得地方调用方法即可。Java是一种开源的语言，可以对Java里面的各种类以及引用方法进行追溯，甚至可以对已经编译过的语言进行反编译，这样不仅仅提高学习的效率，并且可以学习其他从业者提供的优雅的编程方式。Java语言发展到现在，已经在各个行业扎根，学习Java可以从事的行业很多，并且学习的方法很多，网上有很多免费的教程，甚至有些高深的知识也只需要付费就可以进行学习，而不是像Java语言之初，每一个编程人员都需要用记事本进行手动编码，现在有很多集成开发环境帮助Java从业者。选择Java语言进行编程，是一种很好的解决问题的方式。
## 2.2 MYSQL数据库
一般学习程序开发的人员如果学习数据库的话，肯定是要学习MySQL数据库，MySQL数据库通过这么多年的不断发展，社区版本都是免费的，最重要的是小巧，占用电脑空间比较小，让更多的开发人员可以不需要更换更高级的电脑就可以进行学习。学习只是一个方面，最重要的是MySQL市场占有率是世界第一，基本上十个公司就有七八个用得MySQL数据库。MySQL的优点不只是这么粗浅，MySQL首先是开源的，只要不是商用就不用花钱，并且大型的数据也是支持的，只要是市面上存在的操作系统，MySQL都可以有对应的版本可供使用。因为MySQL是开源的，如果有对MySQL有特殊需求的甚至可以自己修改源码，达到符合自己使用的目的。MySQL数据库好处多多，最重要的一点符合本设计的开发需求，可以说本设计只用到了MySQL的一些基础功能，而这点基础功能就完全够用。MySQL学习的教程网上很多，许多关于入门的教程就完全可以达到普通程序员的开发水平，只需要把基本的知识学会了，到公司里面也只是根据不同的业务逻辑进行不同的语句编写而已。
## 2.3 Eclipse开发工具
Eclipse是开源免费的，仅仅这样理解也许会给人一种免费没有好货的感觉，其实不是这样的。Eclipse是一个开发源代码的开发工具，这样会很安全，因为是开源的，如果对使用者的电脑有害，肯定能找到原因所在，所以这一点安全方面是不用担心的。Eclipse是不用安装的，这样就不用对系统盘增加压力，可以放到任何一个盘里，使用的时候打开，不用的时候关闭，不会偷偷的在后台运行，不需要增加注册表负担，启动还必须依靠Java的JDK才可以启动，有效的避免了一些病毒入侵，如果病毒入侵改变了源代码，就不能运行了，只能重新删除文件夹重新解压一份新的Eclipse即可，用起来很安全。Eclipse发展到现在，已经可以支持其他的开发语言了，家族越来越强大，功能越来越多，最重要的还是没有收费，这一点就让新手开发者省下很多的资金用来培养自己的学习，而不用花钱买了开发软件才发现自己不适合进行开发，永远免费的策略可以永远让人有想使用的机会。最重要的是Eclipse并不是免费功能就不够用，恰恰相反，不仅功能强大，用起来完全符合本设计的开发需求，所以选用了Eclipse作为开发工具。
## 2.4 SSM框架
首先SSM框架是指的三个框架，第一个S是Spring MVC的首字母，主要是作为控制视图层的一种框架，第二个S是Spring框架的意思，主要是用来作为Web层，这一层主要是用来获取浏览器提交的一些信息并且把提交的信息处理后反馈给Spring MVC来控制不同的显示页面和内容；第三个M是的意思是MyBatis框架，主要是做为持久层用得，把数据对象转换成数据库表里的值，或者从数据库获取相应的数据转换成对应的Java对象让程序可以有效的进行转换和处理。三个框架可以有效的进行结合，实现不同的作用，起到了承上启下的作用。

# 第三章 系统分析
这个阶段，需要依靠大量的资料作为研究本系统的基础数据，除了分析系统开发可行问题之外，还要再通过调查本系统针对的目标人群的需求来确定本系统功能，并在本系统的性能上做出进一步分析。
## 3.1可行性分析
在项目进行开发之前，必须要有可行性分析报告，这是实现科学开发的必要步骤。
### 3.1.1技术可行性
从技术的角度出发，目前采用开发的技术完全能满足系统开发需要。目前市场上有现成的开发工具和技术，这些能保证系统顺利开发。
### 3.1.2操作可行性
在线日语培训平台是根据用户经常使用的页面操作流程来进行设计的，并且页面保证统一，从视觉角度和操作角度上都能达到使用要求。
### 3.1.3经济可行性
在本次开发过程中，因为需要通过电脑来进行配置开发的环境，通过对技术的分析，发现目前正在使用的电脑是可以满足开发需要的，并不需要太多的金钱对电脑进行更换。所以，从经济角度上分析，可以满足开发要求。

从以上三个角度来进行分析论证，证明了在线日语培训平台是可以正常开发并且使用的。
## 3.2系统流程分析
从系统的角色上分析，每个用户角色都代表了不同的账号身份，而不同的身份则代表着功能的异同，所以首先要区分用户的角色身份问题。设置用户登录需要输入账号，密码，系统会判断输入的信息，输入的数据正确才能进行下一步操作，如果不正确的账号密码，则拒绝用户登录，也代表着用户没有继续访问的权限，系统是无法继续提供服务的。

![](/md/blog.001.png)

图3-1 操作流程图

任何一个系统都有一个操作流程，本设计里面，对于任何数据的存储都有一定的合法要求，只有符合设定要求的数据才可以进行存储。具体步骤参考下图。

![](/md/blog.002.png)

图3-2 添加信息流程图

数据的存储并不是一成不变的，当需要对已经存在的数据进行改变的时候，同样也遵循着操作流程，想更改数据首先要确定更改之前的数据是什么，然后输入新的数据是否合法，都要符合流程，只有合法数据才可以被更新到数据库里存储。具体步骤参考下图。

![](/md/blog.003.png)

图3-3 修改信息流程图

删除操作，在数据存储方面是一件比较慎重的事件，很有可能会产生失误操作，所以一般删除操作的时候都要提示是否删除，确定删除才会更新数据库内容，实现删除目的。具体步骤参考下图。

![](/md/blog.004.png)

图3-4 删除信息流程图
## 3.3系统性能分析
系统在使用过程中，用户会享受到系统带来的便利。那么如何保持在长时间的使用过程中，不出现乱七八糟的问题，让使用系统变成一种操作上的享受，使用上的便捷，这就是需要考虑的问题。以下主要从系统的性能分析上面进行描述，从数据完整以及数据安全，包括系统的可扩展等方面进行介绍。
### 3.3.1系统安全性
注册用户与游客用户的区别就在于是否有账号，如果有账号，就有密码，密码是保证账号安全性的前提，游客只能浏览一些公共性信息，如果需要用户登录才能观看的信息，那么也需要使用账号登录的。对于系统安全性上面，主要考虑角色的密码加密问题，这样可以防止有效的密码数据拦截后的破解工作。一般密码如果有安全性要求的话，是可以考虑加密存储。密码的加密存储大致有两种设计方法，一种是密码在前台提交后就用Java Script进行MD5加密，然后直接提交密文，这样的好处是密文传输的安全性，另一种是提交密码后在后台处理的过程中对密码进行加密或者解密，这样会增加后台的处理负担。一般都居中考虑，如果登录的话会把密码在后台进行加密。目前常用的加密方式是MD5加密方式。
### 3.3.2数据完整性
系统进行开发的最重要的目的就是数据的处理，计算机有其擅长数据的存储以及处理工作，所以数据的完整性是必须保证的，不然系统的存在是没有必要的。数据不管是设计还是存储，都必须完整，从数据的输入就从各个方面保证数据的合法性，违规数据不能直接提交的。数据处理逻辑也会保证数据的加工正常，进而进行数据存储，也会保证数据设计的合理，这些都是有数据设定要求的。目前对数据的存储采用的关系型数据库，关系型数据库有多年的历史，功能强大，迁移备份以及无人值守都可以进行自动备份的。
### 3.3.3系统可扩展性
系统是有必要存在扩展性的。在设计之初就要考虑可能存在的业务，所以对系统的设计就要模块化设计，这样需要进行扩展的时候，只要在对应模块进行增加，对应逻辑进行调试即可。系统可扩展性的提升会让系统增加不必要的工作量，让程序设计更加符合规范。
## 3.4系统功能分析
本系统在功能分析上，主要是根据目标用户群的角度进行分析，为了便于展示分析结果，这里就使用用例图进行功能展示。

管理员用例图的绘制结果见图3-5。管理员登录进入本系统操作的功能包括对公告，课程留言，课程购买订单，课程信息，课程收藏信息，用户信息等进行管理。

![](/md/blog.005.png)

图3-5 管理员用例图

用户用例图的绘制结果见图3-6。用户登录进入本系统操作的功能包括购买课程，观看购买课程的视频，收藏课程，查看公告等。

![](/md/blog.006.png)

图3-6 用户用例图
# 第四章 系统设计
到目前为止，市面上已经存在了各种各样的软件系统，从系统的分类着手，主要应用范围倾向于办公系统，娱乐系统，社交系统，然后下面有很多比较细的分支系统。很多系统已经经过了市场的考验，针对不同的业务场景已经开始出现了业务模块化，程序员减代码化的各种设计方式。到目前为止，当要设计一个系统的时候，首先根据业务模型基本上都可以在网上找到类似的模板，然后根据具体业务具体分析，进而实现具体功能，大众的就是最好的，毕竟符合市场主流的就代表着肯定符合常规操作流程。
## 4.1 系统设计目标
系统设计的时候，就要制定需要达成的目标。在功能上，要严格符合设计需求，不仅仅要减少操作步骤，也要符合预期。因此，在规范化的今天设计出符合项目要求的系统，必须要达到下面设定的目标。

第一个目标就是友好性：友好性主要体现在用户使用过程中，不会对系统的操作产生一种不满，减少操作者的愤怒，这是相当重要的一个体现。前几年好多软件在这个友好性方面失去了市场，就是因为在友好性这方面没有做好。国内互联网发展初期，软件设计的目的就是能用就行，至于友好性的对比，那是不存在的，因为硬件效率比较低，计算机属于新兴行业，所以大哥不说二哥，都是不友好的。随着计算机硬件的提升，很多开发者开始注意到要牺牲一定的计算器性能来提升友好性，因为计算机发展到现在，第一印象很重要，一个软件设计的不好看，会让大部分人对其产生质疑，所以要在友好性上面下很大功夫进行雕琢。

第二个目标就是安全性：安全性其实贯穿着整个软件行业的发展史，计算机就是为解决人类重复性计算以及数据存储的目的而诞生的，很多行业都需要计算机来进行计算，减少出错几率，并且把数据保留，可以实时查询，所以数据的安全性也很重要。

只要保证数据安全性的前提，开发出符合功能需求的友好界面操作，那么就达到了系统设计的目的。
## 4.2功能结构设计
本系统主要是基于数据的增加，修改，删除等操作，使用者能够通过提前设定的登录功能进入指定的操作区，这里对使用者设计的功能进行结构展示。

管理员功能结构图的绘制结果见图4-1。管理员登录进入本系统操作的功能包括对公告，课程留言，课程购买订单，课程信息，课程收藏信息，用户信息等进行管理。

![](/md/blog.007.png)

图4-1 管理员功能结构图

用户功能结构图的绘制结果见图4-2。用户登录进入本系统操作的功能包括购买课程，观看购买课程的视频，收藏课程，查看公告等。

![](/md/blog.008.png)

图4-2 用户功能结构图
## 4.3数据库设计 
如果说设计系统的功能很重要，那么设计该系统的数据库将更重要，毕竟系统服务于用户，数据库服务于系统，用户访问系统，操作系统的所有数据都要依赖于数据库，而系统的数据几乎都是保存在数据库中的，所以，一个高质量的程序，必然拥有一个安全，快速响应，稳定可靠的数据库。本系统的MySQL数据库可以通过SQL语言来实现对系统数据的管理，包括在指定表中插入数据，在规定的表中更改数据，以及删除指定表中的部分数据等操作。一般来说，像MySQL这样的关系型数据库，对于结构化查询语言SQL都能很好的进行支持。在编程中，通过合理运用SQL语言便能操作数据库的各种数据，真是非常方便快捷！
### 4.3.1 数据库概念设计
本节内容主要是使用图形的方式来描述数据库中的实体，每个实体的相应属性，还有实体之间的相互联系，常用的Visio工具即可满足绘制E-R图的需求。E-R图是由矩形，椭圆，菱形等图形元素组成，矩形框中主要写实体的名称，椭圆框中主要是登记该实体的属性，而菱形框中主要是登记实体之间的联系名称，最后使用实心线段把这些图形元素进行连接，即可完成E-R图的绘制。当初步得到一个E-R图时，需要进行检查，使用分析的方式去修改，重构E-R图，以达到消除数据冗余，或者是消除实体间联系冗余的目的。从而保持数据库的完整性，以及降低数据库维护上面的难度。

（1）使用Visio这样的常用的实体属性图绘制工具来绘制课程留言实体属性图，绘制结果见图4-3。

![](/md/blog.009.png)

图4-3 课程留言实体属性图

（2）使用Visio这样的常用的实体属性图绘制工具来绘制课程实体属性图，绘制结果见图4-4。

![](/md/blog.010.png)

图4-4 课程实体属性图

（3）使用Visio这样的常用的实体属性图绘制工具来绘制用户实体属性图，绘制结果见图4-5。

![](/md/blog.011.png)

图4-5用户实体属性图

（4）使用Visio这样的常用的实体属性图绘制工具来绘制课程购买订单实体属性图，绘制结果见图4-6。

![](/md/blog.012.png)

图4-6 课程购买订单实体属性图

（5）绘制的上述实体间存在的联系见图4-7。

![](/md/blog.013.png)

图4-7 实体间关系E-R图
### 4.3.2 数据库物理设计
本系统数据在数据库中都是通过各种二维表进行记录保存的，在数据库中设计这样的二维表也是比较重要的内容，因为它影响着数据的存储效率。在设计二维表也就是关系模型之前，一些有关二维表方面的常用概念需要进行充分了解。

关系：一张具体的数据表即表示关系，关系的名称与数据表的名称保持一致；

元组：数据表中，每行显示的数据即代表元组；

属性：数据表中，每列表示的数据即代表属性；

关键字：数据表中，为了与其他数据表进行区分，则需要在每张表中进行主键的设置；

通过上节内容可以知晓数据库中的各个实体，并通过一定方式把这些实体表示的内容进行数据表的转换，通常来说，每个实体都会对应一张具体的数据表，在本系统指定的数据库中创建命名好的数据库，才可以对数据表进行创建与设计。在线日语培训平台数据表设计结果展示如下：

表4-1 用户表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|yonghu\_name|用户姓名 |varchar(200)|是|
|yonghu\_phone|用户手机号|varchar(200)|是|
|yonghu\_id\_number|用户身份证号|varchar(200)|是|
|yonghu\_photo|用户头像|varchar(200)|是|
|sex\_types|性别|int(11)|是|
|yonghu\_email|电子邮箱|varchar(200)|是|
|new\_money|余额|decimal(10,2)|是|
|create\_time|创建时间|timestamp|是|
表4-2 课程表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|kecheng\_name|课程名称 |varchar(200)|是|
|kecheng\_uuid\_number|课程编号 |varchar(200)|是|
|kecheng\_photo|课程照片|varchar(200)|是|
|kecheng\_video|课程视频|varchar(200)|是|
|kecheng\_types|课程类型 |int(11)|是|
|kecheng\_old\_money|课程原价|decimal(10,2)|是|
|kecheng\_new\_money|现价|decimal(10,2)|是|
|kecheng\_clicknum|课程热度|int(11)|是|
|kecheng\_content|课程介绍|text|是|
|shangxia\_types|是否上架|int(11)|是|
|kecheng\_delete|逻辑删除|int(11)|是|
|create\_time|创建时间 |timestamp|是|
表4-3 课程收藏表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|kecheng\_id|课程|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|kecheng\_collection\_types|类型|int(11)|是|
|insert\_time|收藏时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|

表4-4 课程留言表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|kecheng\_id|课程|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|kecheng\_liuyan\_text|留言内容|text|是|
|insert\_time|留言时间|timestamp|是|
|reply\_text|回复内容|text|是|
|update\_time|回复时间|timestamp|是|
|create\_time|创建时间|timestamp|是|
表4-5 课程购买订单表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|kecheng\_order\_uuid\_number|订单号 |varchar(200)|是|
|kecheng\_id|课程|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|kecheng\_order\_true\_price|实付价格|decimal(10,2)|是|
|insert\_time|购买时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4-6 管理员表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|bigint(20)|否|
|username|用户名|varchar(100)|否|
|password|密码|varchar(100)|否|
表4-7 公告表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|gonggao\_name|公告名称 |varchar(200)|是|
|gonggao\_photo|公告图片|varchar(200)|是|
|gonggao\_types|公告类型 |int(11)|否|
|insert\_time|公告发布时间|timestamp|是|
|gonggao\_content|公告详情|text|是|
|create\_time|创建时间 |timestamp|是|

# 第五章 系统实现
这里主要是对系统设计实现进行描述，通过系统的设计和数据库的设计，通过编码后变成了可以进行操作的界面，让一切想法变成了结果，通过文字和具体程序操作界面的截图之间的配合，可以把功能更直观的描述起来。
## 5.1管理员功能实现
### 5.1.1 课程管理
管理员进入如图5-1所示的课程管理界面之后，管理员点击信息显示栏中最右侧的下架，修改，删除按钮可依次完成包含有课程视频，课程编号，课程热度等数据的课程信息的下架，修改，删除。

![](/md/blog.014.png)

图5-1 课程管理界面
### 5.1.2 课程留言管理
管理员进入如图5-2所示的课程留言管理界面之后，管理员点击信息显示栏中最右侧的查看，回复按钮可依次完成包含有回复内容，留言内容等数据的课程留言信息的查看，回复。

![](/md/blog.015.png)

图5-2 课程留言管理界面
### 5.1.3 课程购买订单管理
管理员进入如图5-3所示的课程购买订单管理界面之后，管理员点击信息显示栏右侧的查看按钮可完成包含有课程照片，实付价格，订单号等数据的课程购买订单信息的查看。查询课程购买订单信息的查询条件有用户姓名，课程类型，订单号等。

![](/md/blog.016.png)

图5-3 课程购买订单管理界面
### 5.1.4 用户管理
管理员进入如图5-4所示的用户管理界面之后，管理员查看用户余额信息，用户的身份证号以及手机号等信息都能查看，修改，查询。

![](/md/blog.017.png)

图5-4 用户管理界面
## 5.2用户功能实现
### 5.2.1 课程信息
用户进入如图5-5所示的课程信息界面之后，用户查看课程热度等一些介绍课程的信息，用户如果没有购买课程，就不能观看课程的视频，只有已经购买课程的用户才可以直接观看课程的视频。

![](/md/blog.018.png)

图5-5 课程信息界面
### 5.2.2 观看课程视频
用户进入如图5-6所示的观看课程视频界面之后，用户可以根据自身情况播放课程视频，比如暂停播放，快进播放，调节播放视频的音量，下载视频，设置全屏播放视频等。

![](/md/blog.019.png)

图5-6 观看课程视频界面
### 5.2.3 课程购买订单
用户进入如图5-7所示的课程购买订单界面之后，用户查看已经购买的课程，查看购买课程的时间，购买课程的实付价格，课程名称等信息。

![](/md/blog.020.png)

图5-7 课程购买订单界面
### 5.2.4 课程收藏
用户进入如图5-8所示的课程收藏界面之后，用户之前查看课程信息时，收藏的课程都会在课程收藏界面展示，用户能够删除课程收藏信息，可以查询课程收藏信息，查询条件有课程名称，课程编号等。

![](/md/blog.021.png)

图5-8 课程收藏界面













