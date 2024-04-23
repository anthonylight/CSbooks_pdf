
more c++ idioms

C++推荐书籍、计算机能力
====


## 提升
### 1、深入理解计算机系统
这本书是CMU计算机系的教材，这本书看了大概有4-5遍的样子，现在还在桌子上，时不时拿出来翻翻。
看完这本书会对计算机底层机制有一个overview式的理解,清楚地知道一个"hello world"程序从编写,编译,链接最后实际运行的全过程。糅合了计算机组成原理,操作系统,体系结构,网络编程,并行程序设计原理等课程的基础知识。
链接: https://pan.baidu.com/s/1v9VfgGJZAF2q5cBK8F1Rvw
提取码: k8bq

### 2、操作系统概念
本书是面向操作系统导论课程的经典书籍，从第1版至今被国内外众多高校选作教材。全书共六部分，不仅详细讲解了进程管理、内存管理、存储管理、保护与安全等概念，而且涵盖重要的理论结果和案例研究，并且给出了供读者深入学习的推荐读物。这一版新增了多核系统和移动计算的内容，每一章都融入了新的技术进展，并且更新了习题和编程项目。本书既适合高等院校计算机相关专业的学生学习，也是专业技术人员的有益参考。
链接: https://pan.baidu.com/s/19qPSoxL3TvXfII9W0yiq0Q
提取码: 7qre

### 3、程序员的自我修养—链接、装载与库
将硬件与系统、机器层与实现层整合了起来，有了一个很清晰的视角。
链接: https://pan.baidu.com/s/1ChqMQMiyYB1SkifHvkgYDg
提取码: iuwp 

### 4、计算机程序的构造和解释
从数据抽象、过程抽象、迭代、高阶函数等编程和控制系统复杂性的思想，到数据结构和算法，到编译器/解释器、编程语言设计
链接: https://pan.baidu.com/s/1TC-ej8HLDq9_1stf5K-uNQ
提取码: i0ts   


# Cplusplus经典网站
https://cplusplus.com/


# stackoverflow 上对 C/C++ 问题的整理、总结和翻译。  
作者：https://github.com/ethsonliu/stackoverflow-top-cpp  

<https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list>

## 问题

这个问题是希望从每年出版的很多并不是很好的 C++ 书籍中找出一些优秀的作品。

和一些可以在网络教程直接学习的很多编程语言不同，很少有人可以在不阅读优秀的 C++ 书籍的情况下快速学会它，因为这样做太复杂了。事实上，有很多非常糟糕的 C++ 书籍，我不是指各异的编程风格，而是它们存在明显的事实错误甚至推广极其糟糕的编程风格。

请编辑已经被接受的回答来推荐质量高的书籍并且指明它们所适用的阅读者水平——最好是在 [C++ 聊天室](https://chat.stackoverflow.com/rooms/10/loungec) （常客们如果意见相左，可能会驳回您的建议）中讨论之后再发表。添加关于您亲自阅读/受益的每本书的简短脱口秀/描述。随意辩论质量、标题等。符合标准的书籍将被添加到列表中。如果这本书在 C/C++ 用户协会（ACCU）有书评，请添加一个链接。

## 回答

> 译注：原文采用 Amazon 的商品链接，译文已经更换为 JD 或淘宝的中文版本（译者与其店铺没有合作关系），对于没有更换链接的书籍请自行搜索购买，评价代表原回答社区的意见，可能与国内读者意见有所不同。

### 初学者

#### 介绍性书籍，之前没有编程经验

- [**C++ Primer**](https://item.jd.com/1049023087.html)  （Stanley Lippman、Josée Lajoie、and Barbara E. Moo，已更新 C++11 内容）几乎有 1000 页，它非常彻底地介绍了 C++，用可读性很高的格式事无巨细地涵盖了语言中几乎所有的东西。这本书的第5版（发行于 2012.4.16）涵盖了 C++11 内容。[「评价」](https://accu.org/bookreviews/2012/glassborow_1848/)
    * 不要将这本书与 [C++ Primer Plus](https://item.jd.com/12908688.html) （Stephen Prata） 混淆，那本书有一个不太好的 [「评价」](https://accu.org/bookreviews/2002/glassborow_1744/)
- [**C++ 程序设计原理与实践**](https://item.jd.com/10060199.html) （Bjarne Stroustrup，第二版 - 2014.5.25，已更新 C++11/C++14 内容）一本 C++ 之父写的该语言的编程教程，即使没有编程经验的初学者也可以轻松阅读，但它不仅仅是为初学者编写。

#### 介绍性书籍，之前有编程经验

- [**C++ 语言导学**](https://item.jd.com/12701398.html) （Bjarne Stroustrup，第二版为 C++17 标准）标题中的“导学”是指本书是一个所有标准 C++ 内容（语言和标准库以及如何使用 C++11）的一个快速（大约有 180 页 14 章节）概览，是以中高等水平或至少有经验的开发者的视角编写的。这本书是对工具书的拓展，它包含了《[C++ 程序设计语言](https://item.jd.com/11986384.html)》第四版的第二章到第五章。
- **[Accelerated C++](https://www.amazon.com/dp/020170353X)** （Andrew Koenig and Barbara Moo，第一版 - 2000.4.24）它的基础部分内容基本上和 《C++ Primer》相同，但这些只占它的四分之一。这是因为它并不是为了介绍如何编程，而是为已经使用其它语言编程的人介绍 C++。它有更加陡峭的学习曲线，但是啃下这本书就会发现它非常紧凑地介绍了 C++。（从历史的角度来看，它开创了新天地成为第一本使用现代语言教学方法的初学者书）尽管如此，这本书只介绍 C++98 的内容。[「评价」](https://accu.org/bookreviews/2000/glassborow_1185)

#### 最佳实践

- [**Effective C++：改善程序与设计的55个具体做法**](https://item.jd.com/10393318.html) （Scott Meyers, 第三版 - 2005.3.22）这本书是为了成为 C++ 编程者最该看的第二本书而编写的，并且它成功了。早期版本是为了帮助 C 编程者了解 C++，第三版改变了受众为使用 Java 等语言的人。它用非常易于理解的风格展示了 50 多个易于记忆的经验法则以及其原理。它关于 C++11 和 C++14 的例子和几个问题已经过时，目前《Effective Modern C++》应该是首选。[「评价」](https://accu.org/bookreviews/2000/glassborow_1185/)
- [**Effective Modern C++**](https://item.jd.com/12348026.html) （Scott Meyers）它基本上是《Effective C++》的新版本，旨在帮助 C++ 程序员从 C++03 过度到 C++11 和 C++14。
- [**Effective STL**](https://www.amazon.com/dp/0201749629) （Scott Meyers）它旨在对 C++ STL 做与《Effective C++》相同的工作：它提出了经验法则以及其原理。[「评价」](https://accu.org/bookreviews/2019/floyd_1937)

------

### 中级

- [**More Effective C++：35个改善编程与设计的有效方法**](https://item.jd.com/13008184.html) 介绍了比《Effective C++》更多的经验法则，虽然没有之前那本书介绍的内容重要，但了解一下还是有好处的。
- [**Exceptional C++**](https://www.amazon.com/dp/0201615622) （Herb Sutter）这本书表现为一组谜题，通过对包含 pimpl 技法、name lookup、良好的类设计和 C++ 内存模型的讨论外，还通过资源获取即初始化（RAII）对 C++ 中正确的资源管理和异常安全进行了极佳和彻底的讨论。[「评价」](https://accu.org/bookreviews/2000/griffiths_209)
- [**More Exceptional C++**](https://www.amazon.com/dp/020170434X) （Herb Sutter）包含了在《Exceptional C++》中没有提到的异常安全话题，并且讨论了在 C++ 中如何有效地面向对象编程和 STL 的正确使用方法。[「评价」](https://accu.org/bookreviews/2002/glassborow_784/)
- [**Exceptional C++ Style**](https://www.amazon.com/dp/0201760428) （Herb Sutter）讨论了泛型、优化以及资源管理，这本书还很好的阐述了在 C++ 中如何使用非成员函数来编写模块化代码以及单一责任原则。
- [**C++ 编程规范**](https://item.jd.com/11896170.html) （Herb Sutter and Andrei Alexandrescu）这里的“编程规范”并不是指“我的缩进应该有几个空格？”，这本书包含了 101 个最佳实践方法、编程习惯和常见的陷阱来帮助你写出正确、可读并且高效的 C++ 代码。「评价」
- [**C++ Templates**](https://item.jd.com/11216941.html)  （David Vandevoorde and Nicolai M. Josuttis）这本书包含了 C++11 之前就存在的模板。它涵盖了从很基础到最高级的模板元编程方法，解释了模板的工作原理（包括概述以及模板的实现）并讨论一些常见的陷阱。它在附录中巧妙地总结了*单一责任原则（ODR）*和*重载解析（overload resolution）*。包含 C++11、C++14 和 C++17 的第二版已经发行。[「评价」](https://accu.org/bookreviews/2020/floyd_1946)
- [**C++ 17 - The Complete Guide**](https://leanpub.com/cpp17) （Nicolai M. Josuttis）这本书描述了 C++17 中加入的新功能，从简单的“内联变量”、“`constexpr if`”一直到“*多态内存资源（PMR）*”和“利用过度对齐来分配资源”等所有内容。[「评价」](https://accu.org/bookreviews/2020/floyd_1943)
- [**C++ in Action**](http://www.worldcolleges.info/sites/default/files/C++_In_Action.pdf) （Bartosz Milewski）这本书以从头构建一个完整的应用程序来解释 C++ 的功能。[「评价」](https://eli.thegreenplace.net/2003/09/12/book-review-c-in-action-by-bartosz-milewski)
- [**C++ 函数式编程**](https://item.jd.com/12612787.html) （Ivan Čukić）这本书描述了现代 C++（C++11 或更新）中的函数式编程技巧。对于想要在项目中灵活运用函数式编程技巧的人来说，这是本非常不错的书。
- [**Professional C++**](https://www.wiley.com/en-us/Professional+C%2B%2B%2C+5th+Edition-p-9781119695400) （Marc Gregoire, 第五版 - 2021.2）提供了对 C++ 的实现的全面、详细的介绍，它充满了专业技巧提示以及简洁但内容丰富的文本范例来强调 C++20 的新功能。书中所有范例使用了诸如 `module` 和 `std::format` 等的一些 C++20 的新功能。

------

### 进阶

- [**C++ 设计新思维**](https://www.amazon.com/dp/0201704315) （Andrei Alexandrescu）一本关于高级泛型编程技术的开创性著作。它介绍了基于策略的设计、`Typelist`、基本的泛型编程习惯用法，之后解释了很多有用的，可以被高效、模块化且干净地使用泛型实现的设计模式（包括小对象分配器、仿函数、工厂模式、访问者模式以及 `multi-methods`）。[「评价」](https://accu.org/bookreviews/2001/glassborow_979/)
- [**C++ 模板元编程**](https://item.jd.com/10020602179182.html) （David Abrahams and Aleksey Gurtovoy）
- [**C++ 并发编程实战**](https://www.amazon.com/dp/1933988770) （Anthony Williams）一本涵盖 C++11 中支持并发内容的书，包括线程库、原子库、C++ 内存模型、锁和互斥锁，以及设计和调试多线程程序时会遇到的问题。覆盖 C++14 和 C++17 内容的第二版已经发行。[「评价」](https://accu.org/bookreviews/2012/glassborow_1850/)
- [**Advanced C++ Metaprogramming**](https://rads.stackoverflow.com/amzn/click/com/1460966163) （Davide Di Gennaro）一本 C++11 之前的*模板元编程（TMP）*技术手册，它更多地关注实践而不是理论。本书中有很多由于类型特征而过时的片段，尽管如此其中的技术还是很值的学习的。如果你能忍受它奇怪的格式，它会比 Alexandrescu 那本更易于阅读，甚至更有价值。对于富有经验的开发者，这是一个了解 C++ 一些不为人知的，只能从丰富的编程经验中获知的冷知识的好机会。

------

### 编程风格参考 - 所有水平适用

- [**C++ 程序设计语言**](https://item.jd.com/11986384.html) （Bjarne Stroustrup，更新了 C++11 内容）C++ 之父撰写的经典教程书，与经典 K&R 读起来相似，涵盖了从语言核心到标准库，从编程范例到语言哲学的所有内容。[「评价」](https://accu.org/bookreviews/2014/lenton_1853)
    - 注：这个问题 *[Where do I find the current C or C++ standard documents?](https://stackoverflow.com/questions/81656/where-do-i-find-the-current-c-or-c-standard-documents)* 收集了 C++ 的所有发布标准。
- [**C++ 标准库 —— 自学教程与参考手册**](https://item.jd.com/11151402.html) （Nicolai Josuttis，更新了 C++11 内容）提供了 C++ 标准库的介绍和参考，第二版（在 2012.4.9 发行）包含了 C++11。[「评价」](https://accu.org/bookreviews/2012/glassborow_1849)
- [**The C++ IO Streams and Locales**](https://rads.stackoverflow.com/amzn/click/com/0201183951) （Angelika Langer and Klaus Kreft）关于这本书几乎没什么需要说的，如果你想了解关于 `stream` 和 `locale` 的任何内容，那么这是个找到标准答案的地方。[「评价」](https://accu.org/bookreviews/2000/glassborow_200)

##### C++ 11/14/17/... 参考：

- C++ [11](https://www.iso.org/standard/50372.html)/[14](https://www.iso.org/standard/64029.html)/[17](https://www.iso.org/standard/68564.html) 标准（*INCITS/ISO/IEC 14882:2011/2014/2017*）这是最后决定 C++ 是什么的权威。但是，请注意到它只是为了愿意投入大量时间和精力去理解它的经验丰富的人编写的。C++ 17 标准以电子版发售，售价是 198 瑞士法郎。
- 你可以直接从 ISO 购买 [C++17 标准 ](https://www.iso.org/standard/68564.html)来阅读，但这种方式显然不太经济。标准发布前的 [最终草案](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2017/n4659.pdf) 对大多数人已经足够了（而且是免费下载的）。有的人会需要一份 [更新的草案](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2018/n4778.pdf) ，其中包含了可能会在 C++20 中加入的新功能。
- [**Overview of the New C++ (C++11/14)**](https://www.artima.com/shop/overview_of_the_new_cpp) （Scott Meyers，只有 PDF 版，更新了 C++14 的内容）这些是 Scott Meyers 在一个为时三天的课程中使用的演讲材料（幻灯片和一些讲义），他是 C++ 领域备受尊敬的作家，作品不多但是质量都很高。
- [**C++ 核心准则 （C++11/14/17/...）**](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md) （edited by Bjarne Stroustrup and Herb Sutter）这是一个在不断更新的关于如何使用现代 C++ 的在线文档。这些准测更多的侧重于相对高级的问题，比如接口、资源管理、内存管理、并发对应用程序架构和设计库的影响。这个项目 [由  Bjarne Stroustrup 等人在 CppCon'15 发起](https://isocpp.org/blog/2015/09/bjarne-stroustrup-announces-cpp-core-guidelines) 并且欢迎社区的贡献。其中大多数准则都补充有基本原理和示例以及有关可能支持的工具的讨论。许多规则经过专门的设计，可以用静态分析工具自动地进行检查。
- [**C++ Super-FAQ**](https://isocpp.org/faq) （Marshall Cline, Bjarne Stroustrup and others）是标准 C++ 基金会为了统一之前由 Marshall Cline 和 Bjarne Stroustrup 单独维护的 C++ FAQ 所做的努力，并且纳入新的贡献。这些问答经常以中级的水平和幽默的语言来表达。可能并不是所有条目都完全符合最新的 C++ 标准。
- [**cppreference.com (C++03/11/14/17/...)**](https://cppreference.com/) （由 Nate Kohl 发起）是一个概述了基本的核心语言功能的百科，并且提供了有关 C++ 标准库的大量文档。该文档非常准确且比正式标准文档更易于阅读，由于它 wiki 的性质又提供了良好的导航。它记录了 C++ 标准的所有版本，并且允许过滤显示特定版本的内容。[由 Nate Kohl 在  CppCon'14 上发起](https://rcj5llitxrhekyiiamopztzl4i--isocpp-org.translate.goog/blog/2015/07/cppcon-2014-cppreference.com-documenting-cpp-one-edit-at-a-time-nate-kohl)

------

### 经典书/旧书

> 注意：这些书中包含的某些信息可能已经过时或不再被视为最佳实践。

- [**C++ 语言的设计和演化**](https://e.jd.com/30668069.html?ebook=1) （Bjarne Stroustrup）你可以在这本书里找到为什么 C++ 会这么设计，它涵盖了 C++ 在标准化之前的所有内容。
- [**C++ 沉思录 **](https://item.jd.com/12994578.html) （Andrew Koenig and Barbara Moo）[「评价」](https://accu.org/bookreviews/1997/glassborow_776)
- [**Advanced C++ Programming Styles and Idioms**](https://rads.stackoverflow.com/amzn/click/com/0201548550) （James Coplien）`pattern movement` 的前身，它描述了许多 C++ 特有的“编程习惯”。如果你有空闲的话，这当然是一本非常值得一读的书，但它已经很久没有和更新的 C++ 标准适配了。
- [**大规模 C++ 程序设计**](https://item.jd.com/11567576.html) （John Lakos）Lakos 在这本书里描述了如何大型 C++ 软件项目。如果它更新了的话，当然会是一本好书。但它是在 C++98 之前编写的，并且错过了对大型项目很重要的如 `namespace` 的许多功能。如果你需要参与大型 C++ 软件项目，就很需要阅读这本要花费很多精力的书。[新版本的第一卷](https://www.amazon.com/dp/0201717069) 在 2019 年发行。
- [**深度探索C++对象模型**](https://e.jd.com/30652216.html?ebook=1) （Stanley Lippman）如果你想知道通常在多继承方案中如何实现虚函数以及基础对象是如何被布置在内存中的，以及所有这些内容对性能的影响，那么你可以在这本书中找到这些主题相关的详尽的讨论。
- [**The Annotated C++ Reference Manual**](https://rads.stackoverflow.com/amzn/click/com/0201514591) （Bjarne Stroustrup, Margaret A. Ellis）在这本书探索了 1989 年的 C++ 2.0 版本的事实上来说，它就已经过时了——尚未引入模板、异常、名称空间和新类型。话虽如此，这本书还是贯穿了当时的整个 C++ 标准，解释了该语言的基本原理、可能的实现和功能。这不是一本用来学习 C++ 编程原理和模式的书，而是一本了解 C++ 语言的各个方面的书。
- [**C++ 编程思想**](https://item.jd.com/41672638757.html) （Bruce Eckel，第二版 2000 年）分成两卷；是一本免费的入门教程书籍，可以在 [第一卷](https://ia800100.us.archive.org/10/items/TICPP2ndEdVolOne/TICPP-2nd-ed-Vol-one.zip) [第二卷](https://ia800108.us.archive.org/24/items/TICPP2ndEdVolTwo/TICPP-2nd-ed-Vol-two.zip) 下载。不幸的是，它有一些虽然不是那么重要的错误（比如坚持了 *temporaries are automatically `const`*）并且还没有官方的勘误列表。在 http://www.computersciencelab.com/Eckel.htm 有一个第三方的勘误表，但显然已经不再维护了。
- [**Scientific and Engineering C++: An Introduction to Advanced Techniques and Examples**](https://rads.stackoverflow.com/amzn/click/com/0201533936) （John Barton and Lee Nackman）这是一本非常全面且详细的书，它试图用数学方法来解释和利用 C++ 中可用的所有功能。它介绍了当时的几种新技术，比如*奇异递归模板模式*（CRTP，也被称为 *F-bound polymorphism*）。它开创了如*因次分析 (Dimensional analysis)*和*自動微分 (Automatic differentiation)*的技术。提供了很多有用的代码，包括表达式解析器到 LAPACK 包装器，代码还是可以 [在网络上查看](https://www.informit.com/store/scientific-and-engineering-c-plus-plus-an-introduction-9780201533934) 。不幸的是，这本书在风格和 C++ 功能上已经过时了，尽管如此，在当时（1994 年，STL 之前）仍然是一本极好的书。关于动态遗传的章节有点复杂、难以理解，也不太有用。如果它更新了包括移动语义和 STL 中汲取的教训在内的内容的话，将会非常棒。


_——其他参考连接——_  
[有哪些值得推荐的 C++ 经典书籍？ - 雨乐的回答 - 知乎]https://www.zhihu.com/question/20066655/answer/2456357548]  
作者：雨乐  
链接：https://www.zhihu.com/question/20066655/answer/2456357548  
来源：知乎  
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。  


## **入门**
-
1. C++大学教程
本科时候，也开设了C++这门课，但是学到的仅仅是皮毛而已。于是在读研期间，偶然一次，在图书馆看到了这本书，所以就借过来开始读。这本书讲的确实很全面，我当时每学完一节，都将课后的例子手动实现一遍。  
链接: https://pan.baidu.com/s/1ffpAAC85jCEhjzUi2I0GFg
提取码: 2ijb

2、C++primer
很多人容易被这本书名所误导，其实这本书并不适合入门，我是看完C++大学教程，开始看的这本书。  
链接: https://pan.baidu.com/s/1oXfYAJDtQvedbkvHupmPGg  
提取码: m0i2

3、C++程序设计语言
这本书作为C++之父的作品，还是很值得一看。  
链接:https://pan.baidu.com/s/1TC7XzQMz4g7MhNF4bVIbtg  
提取码: iq1u



## 进阶
1、effective C++
一本每个C++程序员都该精读几遍的圣经级书籍，一遍是绝对不够的。里面每个条款建议都值得细细品味，除非有重要理由，否则，尽量不要违反这些条款。  
链接: https://pan.baidu.com/s/16hT0ZpFmRit1ccNWhiWAXQ
提取码: ad2a

2、more effective C++   
这本书也就是上次介绍的 Effective C++ 的续集。其实这两本书本可以写在一起，但作者还是把他认为比较“高级”的部分独立出来写了两本书。  
链接: https://pan.baidu.com/s/1nZx0cVDbdHuctO9-m4a3AA
提取码: gvgk

3、exceptional C++
本书的深度非常高，正如 Herb Sutter所说的： 我期望你已经掌握了C++基础知识，如果你还没有，可以从一本介绍性和概览性的C++好书开始学习。  
可惜的是，本书已经停版。
链接: https://pan.baidu.com/s/1dg_MwKPSIRF2Duu8v4M54Q
提取码: bw2r

4、More Exceptional C++
除了模板那块劲有点大，其他都还好。
与<<Exceptional C++>>，本书已经停版。
链接: https://pan.baidu.com/s/1Rnf7724txIuD7IFOhlRLkQ
提取码: o5ab

5、 C++沉思录
这本书总共分为6篇，共32章，分别对C++语言的历史和特点、类和继承、STL与泛型编程、库的设计等几大技术话题进行了详细而深入的讨论，细微之处几乎涵盖了C++所有的设计思想和技术细节。
_这本书买了两次，第一本买的丢在了公交车上，然后又买了一本_。   
链接: https://pan.baidu.com/s/1nmoperJpABL_ReVRkQck7A  
提取码: m6o7

6、 深度探索C++对象模型
这本书我看了好多遍，前两遍看的是电子版，看完不过瘾，在图书馆借了实体书出来，看了一遍，然后又从京东买了一本。
这本书上的很多内容，我在招聘的时候都会问，比如对象模型，RAII以及虚函数的实现等等。  
链接: https://pan.baidu.com/s/1G-kjWMOerDl4GrDk8129kA
提取码: w5hi

7、 C++设计和演化
本书作者是C++之父Bjarne Stroustrup。
在这本书中，作者全面论述了C++ 的历史和发展，C++中各种重要机制的本质、意义和设计背景，这些机制的基本用途和使用方法，讨论了C++ 所适合的应用领域和未来发展前景。
链接: https://pan.baidu.com/s/1yFVLsFYJf9vdcPoEFH7JNA
提取码: s2dh

8、 提高C++性能的编程技术
这本书提供了C++性能优化的一些可以实践的技巧。特别是前面几章内存，比如构造函数，返回值优化，虚函数，临时对象，内存池还有内联。最好的实践的方法是先把书读一遍，再把例子写一遍，最后把自己的写过的代码进行一次优化，看下性能是否有所提高。  
链接: https://pan.baidu.com/s/1cdMR_VnTGFAWu4ih9a6Uyg
提取码: ifei

9、 大规模C++程序设计
这本书是专为有经验的C++软件的开发者、系统设计师、软件质量保证人员编写的。适合从事大型软件开发工作（如数据库、操作系统、编译程序和框架）的人员阅读。本书将高层设计概念与特定的C++编程细节结合起来，满足下面两个要求：
1、一本面向对象设计的书，尤其侧重于C++编程语言实现方面。
2、一本c++程序设计的书，描述如何使用C++编程语言来开发非常大型的系统。

10、Effective Modern C++  
看了C++ Primer只知道语法，不知道怎么高效使用，甚至也不知道C++语言或者说C++库的各种版本--TR1、Boost，导致没有很好地体现看了C++ Primer的效果。 
除了并发API一章几个条款没有认真看--因为对操作系统和C++并发编程心存畏惧，有待进一步学习，其它章节我都认真看了，虽然仍有几章没有看懂，但是收获良多。要在编程中将这些建议付诸行动，也要多翻翻增强记忆。 翻译可以说是不错了，虽然有些地方太过拗口，并且部分地方感觉有些急躁，总体来说读起来还是不错了。 

总之看了C++ Primer之后读这本书会很合适。
链接: https://pan.baidu.com/s/1n6cGYW_bJKwl0KvhS7IJFw
提取码: 42dk

11、 Essential C++
以四个面向来表现C++的本质：procedural（面向过程的）、generic（泛型的）、object-based（基于对象的）、objectoriented（面向对象的）。全书围绕一系列逐渐繁复的程序问题，以及用以解决这些问题的语言特性来组织。循此方式，你将不只学到C++的功能和结构，也可学到它们的设计目的和基本原理。
链接: https://pan.baidu.com/s/15s-WtC4Yfg5VgNRbhQN63w
提取码: hs1i

12、 C++并发编程实战
翻译有点差劲，可以直接看英文原版。再或者中文和英文结合着看。
链接: https://pan.baidu.com/s/1NmlqeGgHeKhgFrRCkh1vEw
提取码: q2lu

13、 C++性能优化指南
是一本C++代码优化指南。作者精选了他在近30年编程生涯中最频繁使用的技术和能够带来最大性能提升效果的技术，旨在让读者在提升C++程序的同时，思考软件优化之美。书中主要内容有：代码优化的意义和总原则，与优化有关的计算机硬件背景知识，能行分析方法及工具，优化字符串的使用，算法、查找和排序等等。
链接: https://pan.baidu.com/s/1MUMe3TLPS9k96pWO7PnPfw
提取码: 4eoj

14、 C++编程规范
这本书相当适合有一定C++编程经验的初级，中级程序员阅读。这本书讨论了101个规则，每个规则都按照，固定的格式（包括条款标题，摘要，讨论，示例等部分）进行说明。这样的编排方式即清晰又符合我们理解接受的渐进过程。
链接: https://pan.baidu.com/s/1MUMe3TLPS9k96pWO7PnPfw
提取码: 4eoj



15、 C++ Templates
这本书看完后，在项目中很少用到模板，怕被骂，哈哈哈。

虽然模板可扩展性确实不错，但是可读性实在太差了，还是推荐下吧，算是C++程序员必备技能。


....其他书籍，此处不再一一列举




