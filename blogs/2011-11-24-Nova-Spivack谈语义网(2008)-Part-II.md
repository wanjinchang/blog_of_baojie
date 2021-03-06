Nova Spivack谈语义网（2008）Part II
---
    
> Categories: 语义网  
> Time: 2011-11-24  
> Original url: <http://baojie.org/blog/2011/11/24/nova-spivack-2/>
    
续 [Nova Spivack谈语义网（2008）Part I](http://blog.baojie.org/2011/11/23/nova-spivack1/)

第21页：The Semantic Web = Open database layer for the Web。看起来很好理解，但是很容易误解。我能想到的几种常见的误解

- 语义网的设计和数据库类似，就是先设计好本体（schema），然后大家按这些规定好的本体来写网页的元数据
- 语义网就是一种新型的数据库。（然后会陷入和数据库社区鸡生蛋，蛋生鸡的辩论）
- 语义网就是要求开放数据互联。（能这样做当然好，但是不开放的数据一样是有极大价值的）

22-27页，介绍RDF等，意义不大，跳过

29页，Why has it Taken So Long? 为什么语义网应用发展这么慢？【括号是我的话】

- The original vision was too focused on A.I. 【不是说不要AI，而是不要太逻辑；自然语言理解，机器学习，这些都是AI，都要来补充语义网】
- Technologies and tools were insufficient 【是的，语义数据库还很原始；很多开发工具，比如本体编辑器和语义维基，和成熟的软件工程工具比，还处于婴儿时期。所以在技术选型上，保守最好。[BBC 2010 World Cup](http://www.bbc.co.uk/blogs/bbcinternet/2010/07/bbc_world_cup_2010_dynamic_sem.html)网站提供了一种技术配置样板，可以参考。】
- Needs for open data on the Web were not strong enough 【完全可以从非开放数据搞起。说实在的，大的网站为什么要有动力开放数据？数据要和商业模式结合起来，难道非要是开放数据才有商业价值？难道非要是往网页加元数据这一种方式？其实长远看，Web上的主体会不再是网页，而是各种各样的传感器（比如手机，冰箱，汽车）。语义个体本地数据（semantic desktop等），到现在也没有做出个像样的东西，大概是元数据添加方式不对】
- Keyword search and tagging were good enough…for a while 【渐进改进现有系统，不一定要有模式突变——用户难以接受】
- Lack of end-user facing killer apps 【现在有了，Siri；以后一两年，会出现更多】
- Lots of misunderstanding to clear up 【嗯。这个估计跳到黄河洗不清了。大概唯一的办法是换个马甲。所以大概以后语义网的人会集体改名字，然后接着做以前的事——过去几十年都是这么活下来的，屡试不爽了。】

30页，啊哈，Nova对上页问题的解决方案。可以和我的对比一下。

32页，开始介绍Twine【可惜Twine第二年就下课了】。Twine自称是interest network。2008年我刚到RPI的时候，头要我们大家都要试试。说实话，我用了大半年，越来越觉得这个工具对我没啥帮助，也没感觉到语义在它里面有什么出彩的表现。2009年它关门，我并不奇怪。Nova这么高瞻远瞩的人，关键问题都看到了，还是难免在几个技术设定上没有想全——他后来写了一个[很长的blog](http://www.novaspivack.com/uncategorized/evri-ties-the-knot-with-twine)，检讨经验教训，非常非常值得一读。后人创业，看花容易绣花难，Twine的案例，一定要正面反面都仔细学习。——以后我会详细写对Twine的心得。

39页，Twine 2008年架构。说实话，我觉得最大的问题就在这里：RDF和OWL是放在核心业务处理逻辑上，这在2008年，或者现在，都太超前了。[RDF是数据的一层皮](blog.baojie.org/2011/04/28/semantic-web-skin/)，内部表示，还是用更保守的结构最好。推理、查询也是如此。

本文评论[所提到的slides](http://www.slideshare.net/BlogTalk2008/spivack-blogtalk-2008)为Nova Spivack所做， http://www.mindingtheplanet.net     
    