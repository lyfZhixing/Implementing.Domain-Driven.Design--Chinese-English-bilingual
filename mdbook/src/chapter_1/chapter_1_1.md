# Can I DDD

You can implement DDD if you have    

当满足下边这些条件时，你可以考虑实施DDD:

- A passion for creating excellent software every day, and the tenacity to achieve that goal   
每天都有开发卓越软件的热情,以及实现这一目标的坚韧
- The eagerness to learn and improve, and the fortitude to admit you need to   
对学习和改进的热切渴望,以及承认自己需要进步的勇气与毅力
- The aptitude to understand software patterns and how to properly apply them  
理解软件设计模式及如何正确应用它们的能力
- The skill and patience to explore design alternatives using proven agile methods   
运用经过验证的敏捷方法去探索和设计备选方案的技能和耐心
- The courage to challenge the status quo  
勇于挑战现状
- The desire and ability to pay attention to details, to experiment and discover   
注意细节、勇于实践和探索的欲望和能力
- A drive to seek ways to code smarter and better  
有寻求提升代码质量的动力

I’m not going to tell you that there isn’t a learning curve\. To put it bluntly, the learning curve can be steep\. Yet, this book has been put together to help flatten the curve as much as possible\. My goal is to help you and your team implement DDD with the greatest potential for success\.    

我不会告诉你领域驱动设计没有学习曲线。坦率地说，学习曲线可能会很陡峭。然而，这本书的编写旨在尽可能地降低学习曲线。我的目标是帮助你和你的团队在实施领域驱动设计时拥有最大的成功潜力。

DDD isn’t first and foremost about technology\. In its most central principles, DDD is about discussion, listening, understanding, discovery, and business value, all in an effort to centralize knowledge\. If you are capable of *understanding the business* in which your company works, you can at a minimum participate in the software model discovery process to produce a __Ubiquitous Language__\. Sure, you’re going to have to learn more about the business, lots more\. Still, you are on your way to succeeding with DDD already because you can comprehend the concepts of your business, you revel in developing great software, and that gives you the proper footing to take DDD all the way\.   

领域驱动设计首先并不是关于技术。在其最核心的原则中，领域驱动设计是关于讨论、倾听、理解、发现和业务价值，所有这些努力都是为了集中知识。如果你能够理解你的公司所在的业务，你至少可以参与软件模型发现过程，形成一种 __"无处不在的语言"（Ubiquitous Language）__ 。当然，你将不得不更多地了解业务，要了解很多。尽管如此，你已经走在成功实施领域驱动设计的道路上了，因为你能够理解你的业务概念，你乐于开发出色的软件，这为你全面采用领域驱动设计奠定了合适的基础。

Won’t having years, even a decade or two, of software development experience help? It might. Nevertheless, software development experience doesn’t give you the ability to listen and learn from *domain experts*, the people who know the most about some high-priority area of the business. You are at a greater advantage if you can engage with those who seldom, if ever, express themselves using technical lingo. You’re going to have to listen and listen carefully. You’re going to have to respect their viewpoint and trust that they know a lot more than you do.    

拥有几年甚至十几年的软件开发经验会有所帮助吗？可能会有帮助。然而，软件开发经验并不能让你具备倾听和学习领域专家的能力，这些专家是对业务的某个高优先级领域了解最多的人。如果你能够与那些很少甚至从不使用技术术语表达自己的人进行交流，你就处于更大的优势。你将不得不倾听，而且要非常仔细地倾听。你需要尊重他们的观点，并相信他们比你知道更多

> __There Are Big Advantages to Engaging with Domain Experts__  
You are at a greater advantage if you can engage with those who seldom, if ever, express themselves using technical lingo. Just as you are going to learn from them, there is a high probability that they are also going to learn from you.  

> __与领域专家交流有很大的益处__   
如果你能够与那些很少或从不使用技术术语表达自己的人进行交流，你就处于更大的优势。正如你将从他们那里学到东西一样，他们很可能也会从你那里学到东西。

What you may like best about DDD is that the domain experts are also going to *have to listen to you*. You are on the team just as they are. As strange as it may seem, the domain experts don’t know everything about their business, and they are also going to learn more about it. Just as you are going to learn from them, there is a high probability that they are also going to learn from you. Your questions about what they know will most likely also uncover what they don’t know. You’ll be directly involved in helping everyone on the team discover a deeper understanding of the business, *even shaping the business*.  

你可能最喜欢领域驱动设计的地方在于，领域专家也将 *不得不倾听你的意见* 。你和他们一样都是团队的一部分。尽管看起来有点奇怪，领域专家并不了解他们业务的一切，他们也会学到更多。正如你将从他们那里学到东西一样，他们很可能也会从你这里学到东西。你对他们的提问很可能也会揭示他们不知道的事情。你将直接参与帮助团队中的每个人，使其对业务更加深入理解，甚至 *塑造业务* 。

It’s great when a team learns and grows together. If you give it a chance, DDD makes that possible.   

当一个团队一起学习和成长时，那是非常棒的。如果你给它一个机会，领域驱动设计会让这成为可能。

> __But We Don’t *Have* Domain Experts__   
A domain expert is not one by job title. These are the people who know the line of business you are working in really well. They probably have a lot of background in the business domain, and they might be product designers or even your salespeople. Look past the job title. The people you are looking for know more about what you are working on than anyone else, and for sure way more than you know. *Find them. Listen. Learn. Design in code.*     

> __我们 *没有* 领域专家__   
领域专家并不一定以职称来定义。他们是那些非常了解你所从事的业务的人。他们可能在业务领域有很多背景，他们可能是产品设计师，甚至是你们的销售人员。不要只看职称，你要找的人对你正在从事的工作了解得比其他任何人都要多，肯定比你知道的更多。找到他们：倾听、学习、用代码进行设计。

So far we’re off to a pretty reassuring start. Still, I am also not going to tell you that technical ability isn’t important, that somehow you can get by without it. You will have to grasp some advanced software *domain modeling* concepts. Even so, it doesn’t necessarily mean you are going to be in over your head. If you have abilities somewhere between grasping *Head First Design Patterns* [Freeman et al.] and grokking the original *Design Patterns* [Gamma et al.] text, or even more advanced patterns, you stand a really good chance of succeeding with DDD. You can bank on this: I’m going to do everything I can to make that happen by lowering the bar, no matter what your level of experience.    

到目前为止，我们的开局相当令人放心。但是，我也不会告诉你技术能力不重要，或者你可以不依靠技术能力。你将不得不掌握一些高级软件领域建模的概念。即便如此，并不一定意味着你会一头雾水。如果你的能力介于掌握《Head First Design Patterns》[Freeman et al.]和理解原始的《Design Patterns》[Gamma et al.]，或者甚至更高级的模式之间，你成功实施领域驱动设计的机会就非常大。你可以信赖我：我会尽我所能降低门槛，让这一切发生，无论你的经验水平如何。

> __What’s a Domain Model?__   
It’s a software model of the very specific business domain you are working in. Often it’s implemented as an object model, where those objects have both data and behavior with literal and accurate business meaning.  
Creating a unique, carefully crafted domain model at the heart of a core, strategic application or subsystem is essential to practicing DDD. With DDD your domain models will tend to be smallish, very focused. Using DDD, you never try to model the whole business enterprise with a single, large domain model. Phew, that’s good!    

> __什么是领域模型?__   
一个领域模型是指你正在从事的非常具体的业务领域的软件模型。通常它被实现为一个对象模型，其中这些对象是具有文字描述和准确业务含义的数据和行为。 在核心、战略应用程序或子系统的核心创建一个独特、精心设计的领域模型对于实践领域驱动设计至关重要。在领域驱动设计中，你的领域模型往往会比较小，非常专注。使用领域驱动设计，你永远不会试图用单个大型领域模型来对整个企业进行建模。

Consider the following perspectives of the people who can benefit from DDD. I know you fit in here somewhere:   

思考下边这些人（从DDD中收益）的观点。你肯定适合其中的某些：

- __*Newbie, junior developer*:__ “I’m young, with fresh ideas, I’ve got pentup energy to code, and I’m going to have an impact. What’s got me miffed is one of the projects I sprint on. I didn’t expect that my first gig off campus would mean shoveling data back and forth using lots of almost identical yet redundant ‘objects.’ Why is this architecture so complex if that’s all that’s happening? What’s up with *that*? The code breaks a lot when I try to change it. Does anyone actually understand what it’s supposed to do? Now there are some complex new features I have to add. I regularly slap an *adapter* around legacy classes to shield me from the goo. *No joy*. I’m sure there’s something I can do besides code and debug all day and night just to finish iterations. Whatever that is, I’m going to track it down and own it. I heard some of the others talking about DDD. *It sounds like Gang of Four, but tuned for the domain model.* Nice.”

    Gotcha covered.

-  __*Midlevel developer* :__ “Over the past few months I’ve been included on the new system. It’s my turn to make a difference. I get it, but what I’m missing are profound insights when I’m meeting with the senior developers. Sometimes things seem whacked, but I’m not sure why. I’m going to help change the way things are done around here. I know that throwing technology at a problem only takes you so far, and that’s basically not far enough. What I need is *a sound software development technique* that’s going to help me become a wise and experienced software practitioner. One of the senior architects, the new guy, made a pitch for something called DDD. I’m listening.”

    You’re sounding senior already. Read on. Your forward-thinking attitude will be rewarded. 

- __*Senior developer, architect* :__ “I’ve used DDD on a few projects, but not since landing this new position. I like the power of the *tactical patterns*, but there’s a lot more I could apply, with *strategic design *being one. What I found most insightful when reading [Evans] was the Ubiquitous Lan- guage. *That’s powerful stuff*. I’ve had discussions with a number of my teammates and management, trying to influence DDD’s adoption here. One of the new kids and a few of the midlevel and senior members are jazzed about the prospects. Management isn’t so excited. I recently joined this company, and although I was brought in to lead, it seems that the organization is less interested in disruptive advancements than I thought. Whatever. I’m not giving up. With other developers psyched about it, *I know we can make it happen*. The payoffs are going to be much greater than anticipated. We’ll draw the pure business people—the domain experts—closer to our technical teams, and *we’ll actually invest in our solutions*, not just grunt them out iteration after iteration.”

    Now *that’s* what a leader does. This book has lots of guidance that shows how to succeed with *strategic design*.

- __*Domain expert* :__ “I’ve been involved in specifying the IT solutions to our business challenges for a long time now. Maybe it’s too much to expect, but I wish the developers understood better what we do here. They’re always talking down to us like we’re stupid. What they don’t understand is, if it wasn’t for us there wouldn’t be jobs here for them to mess around with computers. The developers always have some strange way of talking about what our software does. If we talk about A, they say it’s really called B. *It’s like we have to have some sort of dictionary and road map on hand every time we try to communicate what we need*. If we don’t let them have their way by calling B what we know is A, they don’t cooperate. We waste so much time in this mode. *Why can’t the software just work the way the real experts think about the business?*”

    You’ve got that right. One of the biggest problems is the false need for translation between business people and techies\. This chapter is for you\. As you’re going to see, *DDD puts you and developers on level ground*\.    

    And, surprise\! You’ve got some developers already leaning your way\. Help them here\.

- __*Manager* :__ “We are shipping software\. It’s not always with the greatest result, and changes seem to take longer than they should\. The developers keep talking about some domain something\-or\-another\. I’m not sure we need to get high centered on yet another technique or methodology, like it’s some kind of silver bullet\. I’ve heard all that a thousand times before\. We try, the fad dies, and we are right back to the same\-old same\-old\. I keep saying that we need to stay the course and stop dreaming, but the<a id="Why You Should Do DDD"></a> <a id="_bookmark21"></a>team keeps hounding me\. They’ve worked hard, so I owe them a listen\. *They are smart people and they all deserve a chance to improve things* before they get torqued and move on\. I could allow them some time to learn and adjust if I can get backing from upper management\. I think I could get that approval if I can convince my boss of the team’s claims of *achieving critical software investment and a centralization of business knowledge* \. Truth is, it will make my job easier if *I can do something to inspire trust and cooperation between my teams and business experts*\. Anyway, that’s what I am hearing I can do\.”

    Good manager\!

Whoever you are, here’s an important heads\-up\. To succeed with DDD *you are going to have to learn something*, and actually a lot of somethings\. That shouldn’t be a big deal, though\. You are smart and you have to learn all the time\. Yet we all face this challenge:

> Personally I’m always ready to learn, although I do not always like being taught\.   
&nbsp;&nbsp;&nbsp;  — Sir Winston Churchill

That’s where this book comes in\. I’ve tried to make the teaching as pleas\- ant as possible while delivering the vital understanding you need to implement DDD with success\.

Your question, though, is: “Why should I do DDD?” That’s fair\.
