# [Getting Started with DDD](#_bookmark0)

> *Design is not just what it looks like and feels like\.*  
*Design is how it works\.*   
*—Steve Jobs*   

> 设计不仅限于外观和使用感受。  
设计的更重要体现是如何工作。  
——史蒂夫·乔布斯

We strive to produce quality in the software we develop\. We achieve some qual\- ity by using tests to help us avoid delivering software with a fatal number of bugs\. Yet, even if we could produce completely bug\-free software, that in itself does not necessarily mean that a quality software model is designed\. The soft\- ware model—the *way* the software expresses the solution to the business goal being sought—could still suffer greatly\. Delivering software with few defects is obviously good\. Still, we can reach higher for a well\-designed software model that explicitly reflects the intended business objective, and our work may even reach the level of *great*\.    

我们在努力开发高质量的软件。我们通过使用测试来避免交付带有大量致命bug的软件，从而在一定程度上提高了质量。然而，即使我们可以开发出完全没有bug的软件，这本身并不一定意味着设计出了高质量的软件模型。软件模型（软件通过何种方式体现解决业务目标的解决方案）依然可能存在很大问题。交付几乎没有缺陷的软件当然是好的，不过，我们还可以更进一步,设计能够明确体现预期业务目标的高质量软件模型,或许我们的工作成果甚至能达到卓越的水平。  
> ps: 通过实现测试来提高软件质量仅是一个方面,更重要的是设计软件模型时能够正确表达和实现业务目标

The software development approach called *Domain\-Driven Design*, or *DDD*, exists to help us more readily succeed at achieving high\-quality software model designs\. When implemented correctly, DDD helps us reach the point where *our design is exactly how the software works*\. This book is about help\- ing you correctly implement DDD\.   

领域驱动设计是一种软件开发方法，它的存在是为了帮助我们更轻松地成功实现高质量的软件模型设计。当正确实施 DDD 时，它可以帮助我们达到这样的境地：我们的设计恰好反映了软件的运行方式。本书的目的就是帮助读者正确实现DDD。

You may be completely new to DDD, you may have tried it and struggled, or you may have already succeeded with it before\. Regardless, you no doubt are reading this book because you want to improve your ability to implement DDD, and you can\. The chapter road map helps you target your specific needs\.  

您可能是初学者，对DDD一无所知；您可能曾尝试过，但遇到困难；或者您可能已经成功实施过DDD。无论您属于哪种情况，您阅读这本书的目的无疑是为了提高实施DDD的能力，而本书确实可以帮你做到。章节路线图有助于您针对自己的特定需求进行学习。

__Road Map to This Chapter__

- Discover what DDD can do for your projects and your teams as you grapple with complexity\.  <br>了解DDD如何帮助您应对项目和团队的复杂性。
- Find out how to score your project to see if it deserves the DDD investment\.
<br>了解如何评估项目是否值得进行DDD投入。
- Consider the common alternatives to DDD and why they often lead to problems\.
<br>了解DDD的常见替代方案，以及它们通常会导致的问题。
- Grasp the foundations of DDD as you learn how to take the first steps on your project\.
<br>掌握DDD的基础，学习如何在项目中迈出第一步。
- Learn how to sell DDD to your management, domain experts, and technical team members\. 
<br>了解如何向管理层、领域专家和技术团队成员推销DDD。
- Face the challenges of using DDD armed with knowledge of how to succeed\. 
<br>具备应对使用DDD时面临挑战的知识，从而从容应对。
- Look in on a team that is learning how to implement DDD\. 
<br>了解一个正在学习如何实施DDD的团队的情况。  


What should you expect from DDD? Not a heavy, dense, ceremonial process that blocks your way to progress\. Rather, expect to use the agile development techniques you probably already have come to trust\. Beyond agile, anticipate the acquisition of methods that help you gain deep insight into your business domain, with the prospect of producing testable, malleable, organized, care\- fully crafted, high\-quality software models\.  

您对DDD的期望是什么？它不是一个阻碍您前进的繁琐、密集的形式过程。相反，您可以期待使用您已经信任的敏捷开发技术。除了敏捷开发，您还将获得有助于深入了解业务领域的方法，并有望产生可测试、可塑、组织良好的、精心制作的、高质量的软件模型。

DDD gives you both the *strategic and tactical modeling tools* necessary to design high\-quality software that meets core business objectives\.  

DDD为您提供了设计高质量软件的战略性和战术性建模工具,以满足核心业务目标。