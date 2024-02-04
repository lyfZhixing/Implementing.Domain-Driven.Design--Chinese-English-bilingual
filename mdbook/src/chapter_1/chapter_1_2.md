# Why You Should Do DDD

Actually, I’ve already given you some pretty good reasons why DDD makes so much practical sense. At the risk of breaking the DRY principle (“Don’t repeat yourself”), I reiterate them here and also add to the earlier reasons. Does anyone hear an echo?   

事实上，我已经给了你一些很好的理由来解释为什么 DDD 如此实用。冒着违反 DRY 原则（"Don’t repeat yourself"）的风险，我在此重申这些原则，并对之前的理由进行补充。有人听到回声了吗？

- Put domain experts and developers on a level playing field, which produces software that makes perfect sense to the business, not just the coders. This doesn’t mean merely tolerating the opposite group. It means becoming one cohesive, tight-knit team.   

    将领域专家和开发人员置于一个公平的竞争环境中，这将产生对业务(而不仅仅是程序员)完全有意义的软件。这并不意味着仅仅容忍相反的群体。它意味着成为一个有凝聚力、紧密团结的团队。

- That “makes sense to the business” thing means investing in the business by making software that is as close as possible to what the business leaders and experts would create if they were the coders.   

    所谓 "对业务有意义"，是指通过制作尽可能接近业务领导和专家所期望制作的软件，对业务进行投资。  

- You can actually teach the business more about itself. No domain expert, no C-level manager, no one, ever knows every single thing about the business. It’s a constant discovery process that becomes more insightful over time. With DDD, everybody learns because everybody contributes to discovery discussions.   

    实际上，你可以让企业更多地了解自己。没有一个领域专家、没有一个 C 级经理、没有一个人了解企业的每一件事。这是一个不断发现的过程，随着时间的推移，这个过程会变得更有洞察力。有了 DDD，每个人都能学到东西，因为每个人都参与了发现讨论。   

- Centralizing knowledge is key, because with that the business is capable of ensuring that understanding the software is not locked in “tribal knowledge,” available only to a select few, who are usually only the developers.    

    知识的集中化是关键，因为有了知识的集中化，企业就能确保对软件的理解不会被禁锢在 "__tribal knowledge__"（部落知识） 中，只有少数人（通常只是开发人员）才能获得这些知识。  

- There are zero translations between the domain experts, the software developers, and the software. That doesn’t mean maybe some few translations. It means zero translations because your team develops a common, shared language that everyone on the team speaks.   

    领域专家、软件开发人员和软件之间的翻译为零。这并不意味着可能会有一些翻译。这意味着零翻译，因为你的团队开发出了团队中每个人都会说的通用语言。

- The design is the code, and the code is the design. The design is how it works. Knowing the best code design comes through quick experimental models using an agile discovery process.    

    设计就是代码，代码就是设计。设计就是如何运行。要想知道最佳的代码设计，就必须使用敏捷发现流程快速建立实验模型。

- DDD provides sound software development techniques that address both strategic and tactical design. Strategic design helps us understand what are the most important software investments to make, what existing software assets to leverage in order to get there fastest and safest, and who must be involved. Tactical design helps us craft the single elegant model of a solution using time-tested, proven software building blocks.   

    DDD 提供了完善的软件开发技术，既能解决战略设计问题，也能解决战术设计问题。战略设计帮助我们了解哪些是最重要的软件投资，利用哪些现有软件资产才能最快、最安全地实现目标，以及哪些人必须参与其中。战术设计可以帮助我们利用久经考验、行之有效的软件构件，为解决方案设计出一个优雅的模型。

Like any good, high-yielding investment, DDD has some up-front cost of time and effort for the team. Considering the typical challenges encountered by every software development effort will reinforce the need to invest in a sound software development approach.   

与任何高收益的良好投资一样，DDD 也需要团队付出一定的前期时间和精力成本。考虑到每项软件开发工作都会遇到的典型挑战，我们就更有必要投资于完善的软件开发方法。

## Delivering Business Value Can Be Elusive  （交付业务价值可能是难以捉摸的）

Developing software that delivers true business value is not the same thing as developing ordinary business software. Software that delivers true business value aligns with the business strategic initiatives and bears solutions with clearly identifiable competitive advantage—software that is not about technology, but about the business.      

开发真正具有业务价值的软件与开发普通的业务软件是两码事。真正具有业务价值的软件与业务战略计划相一致，并提供具有明确竞争优势的解决方案--这些软件与技术无关，而是与业务有关。

Business knowledge is never centralized. Development teams have to balance and prioritize among the needs and requests of multiple stakeholders and engage with many people having diverse skill sets, all with the goal of uncovering software functional and nonfunctional requirements. After gathering all that information, how can teams be certain that any given requirement delivers true business value? In fact, what are the business values being sought, and how do you uncover them, prioritize them, and realize them?   

业务知识从来不是集中的。开发团队必须在多个利益相关者的需求和要求之间进行平衡和优先排序，并与拥有不同技能组合的许多人接触，所有这些都是为了发现软件的功能性和非功能性需求。在收集了所有这些信息后，团队如何才能确定哪些特定需求才能带来真正的业务价值？事实上，我们所追求的业务价值是什么，又该如何发现它们、确定它们的优先级并实现它们？

One of the worst disconnects of a business software development effort is seen in the gap between domain experts and software developers. Generally speaking, true domain experts are focused on delivering business value. On the other hand, software developers are typically drawn to technology and technical solutions to business problems. It’s not that software developers have wrong motivations; it’s just what tends to grab their attention.    Even when software developers engage with domain experts, the collaboration is largely at a surface level, and the software that gets developed often results in a translation/mapping between how the business thinks and operates and how the software developer interprets that. The resulting software generally does not reflect a recognizable realization of the mental model of the domain experts, or perhaps it does so only partially. Over time this disconnect becomes costly. The translation of domain knowledge into software is lost as developers transition to other projects or leave the company.   

业务软件开发工作中最严重的脱节之一就体现在领域专家与软件开发人员之间的差距上。一般来说，真正的领域专家专注于实现业务价值。另一方面，软件开发人员通常被技术和解决业务问题的技术方案所吸引。这并不是说软件开发人员的动机不对，而是他们的注意力往往被什么吸引住了。即使软件开发人员与领域专家合作，这种合作也主要停留在表面层次，开发出来的软件往往是业务思考和运作方式与软件开发人员理解方式之间的转换/映射。由此产生的软件通常无法反映领域专家心智模型（__mental model__）的可识别实现，或者只能部分反映。随着时间的推移，这种脱节会变得代价高昂。随着开发人员转到其他项目或离开公司，将领域知识转化为软件的工作就会丢失。

A different, yet related problem is when one or more domain experts do not agree with each other. This tends to happen because each expert has more or less experience in the specific domain being modeled, or they are simply experts in related but different areas. It’s also common for multiple “domain experts” to have no expertise in a given domain, where they are more of a business analyst, yet they are expected to bring insightful direction to discussions. When this situation goes unchecked, it results in blurred rather than crisp mental models, which lead to conflicting software models.    

一个不同但相关的问题是，当一个或多个领域的专家意见不一致时。出现这种情况的原因往往是每个专家在所建模的特定领域都有或多或少的经验，或者他们只是相关但不同领域的专家。同样常见的情况是，多个 "领域专家 "在特定领域并不具备专业知识，他们更像是业务分析师，但却被期望为讨论提供有见地的指导。如果这种情况得不到控制，就会导致心智模型（__mental model__）模糊而不是清晰，从而导致软件模型相互冲突。

Worse still is when the technical approach to software development actually wrongly changes the way the business functions. While a different scenario, it is well known that enterprise resource planning (ERP) software will often change the overall business operations of an organization to fit the way the ERP functions. The total cost of owning the ERP cannot be fully calculated in terms of license and maintenance fees. The reorganization and disruption to the business can be far more costly than either of those two tangible factors. A similar dynamic is at play as your software development teams interpret what the business needs into what the newly developed software actually does. This can be both costly and disruptive to the business, its customers, and its partners. Furthermore, this technical interpretation is both unnecessary and avoidable with the use of proven software development techniques. The solution is a key investment.   

更糟糕的是，软件开发的技术方法实际上错误地改变了企业的运作方式。虽然情况不同，但众所周知，企业资源规划（ERP）软件往往会改变组织的整体业务运作，以适应ERP的运作方式。拥有ERP系统的总成本不能完全以许可证和维护费用来计算。业务重组和中断的成本可能远远超过这两个有形因素。当软件开发团队将业务需求转化为新开发软件的实际功能时，也会发生类似的动态变化。这对企业、其客户和合作伙伴来说既昂贵又具有破坏性。 此外，通过使用成熟的软件开发技术，这种技术解释是不必要的，也是可以避免的。解决方案是一项关键投资。

## How DDD Helps（DDD的作用）   

DDD is an approach to developing software that focuses on these three primary aspects:   

领域驱动设计(DDD)是一种软件开发方法,着重以下三个主要方面:

1. DDD brings domain experts and software developers together in order to develop software that reflects the mental model of the business experts. This does not mean that effort is spent on modeling the “real world.” Rather, DDD delivers a model that is the most useful to the business. Sometimes useful and realistic models happen to intersect, but to the degree that they diverge, DDD chooses useful.    

    通过DDD,可以把业务领域专家和软件开发人员汇聚在一起,共同开发出可以反映业务专家心智模型（__mental model__）的软件。这不意味着会花时间建立“现实世界”的模型。相反,DDD会构建对业务最有用的模型。有时有用的模型和现实模型可能重合,但如果两者存在分歧,DDD会选择更有用的模型。DDD关注的不是现实世界本身,而是业务需要。它通过软件实现业务专家共享的 __mental model__,从而更好地支持业务需求变更。

    With this aspect the efforts of domain experts and software developers are devoted to jointly developing a Ubiquitous Language of the areas of the business that they are focused on modeling. The Ubiquitous Language is developed with full team agreement, is spoken, and is directly captured in the model of the software. It is worth reiterating that the team is composed of both domain experts and software developers. It’s never “us and them.” It’s always *us. *This is a key business value that allows business know-how to outlive the relatively short initial development efforts that deliver the first few versions of the software, and the teams that produce it. It’s the point where the cost of developing software is a justifiable business investment, not just a cost center.    

        通过这一点,业务领域专家和软件开发人员都致力于共同开发需要着手建模的业务领域的 __通用语言__ 。通用语言是在全体团队一致同意下制定的,用于日常交流,并直接记录在软件模型中。需要强调的是,团队成员包括业务领域专家和软件开发人员。他们不是“我们和他们”,而是“我们”。这是一个关键的业务价值,可以使业务知识超越最初开发软件的相对较短发展阶段和相应团队,延续下去。也就是说,开发软件不再仅仅是成本中心,而成为可以被批准的合理业务投资。通过通用语言的使用,软件可以真正映射和支持业务规则和业务变更需求,同时将业务知识深入维护和应用在软件体内,这就是DDD的关键业务价值所在。

    This entire effort unifies domain experts who initially disagree with each other, or who simply lack core knowledge of the domain. Further, it strengthens the close-knit team by spreading deep domain insight among all team members, including software developers. Consider this the hands-on training that every company should invest in its knowledge workers.

1. DDD addresses the strategic initiatives of the business. While this strategic design approach naturally includes technical analysis, it is more concerned with the strategic direction of the business. It helps define the best inter-team organizational relationships and provides early-warning systems for recognizing when a given relationship could cause software and even project failure. The technical aspects of strategic design have the goal of cleanly bounding systems and business concerns, which protects each *business-level service*. This provides meaningful motivations for how an overall *service-oriented architecture *or *business-driven architecture *is achieved.

1. DDD meets the real technical demands of the software by using tactical design modeling tools to analyze and develop the executable software deliverables. These tactical design tools allow developers to produce software that is a correct codification of the domain experts’ mental model, is highly testable, is less error prone \(a provable statement\), performs to service-level agreements \(SLAs\), is scalable, and allows for distributed computing. DDD best practices generally address a dozen or more higher-level architectural and lower-level software design concerns, with a focus on recognizing true business rules and data invariants, and protecting the rules from error situations.

Using this approach to software development, you and your team can succeed in delivering true business value.  

## Grappling with the Complexity of Your Domain

We primarily want to use DDD in the areas that are most important to the business. You don’t invest in what can be easily replaced. *You invest in the nontrivial, the more complex stuff, the most valuable and important stuff that promises to return the greatest dividends.* That’s why we call such a model a __Core Domain \(2\)__. It is these, and in second priority the *significant* __Supporting Subdomains \(2\)__, that deserve and get the biggest investment. Rightly, then, we need to grasp what *complex* means.

> __Use DDD to Simplify, Not to Complicate__  
Use DDD to model a complex domain in the simplest possible way. Never use DDD to make your solution more complex.

What qualifies as complex will differ from business to business. Different companies have different challenges, different levels of maturity, and different software development capabilities. So rather than determining what is *complex*, it may be easier to determine what is *nontrivial*. Thus, *your team and management will have to determine if a system you are planning to work on deserves the cost of making a DDD investment.*

__DDD Scorecard:__ Use Table 1.1 to determine whether your project qualifies for an investment in DDD. If a row on the scorecard describes your project, place the corresponding number of points in the right-hand column. Tally all the points for your project. If it’s 7 or higher, seriously consider using DDD.

__Table 1.1__ The DDD Scorecard

__*Does Your Project Score a Total of 7 Points or Higher?*__     

|If Your Project . . .|Points|Supporting Thoughts  | Your Score  |    
|---------|-----------|--------|  --------|
|If your application is completely data-centric and truly qualifies for a pure CRUD solution, where every operation is basically a simple database query to Create, Read, Update, or Delete, you don’t need DDD. Your team just needs to put a pretty face ona database table editor. In other words, if you can trust your users to insert data directly into a table, update it, and sometimes delete it, you wouldn’t even need a user interface. That’s not realistic, but it’s conceptually relevant. If you could even use a simple database development tool to create a solution, don’t waste your company’s time and money on DDD. |0|This seems like a no-brainer, but it’s not usually that easy to determine simple versus complex. It’s not as if every application that isn’t pure CRUD deserves the time and effort of using DDD. So maybe we could come up with other metrics to help us draw a line between what is complex and what is not . . .| |   
|If your system requires just 30 or fewer business operations, it’s probably pretty simple. This would mean that your application would have no more than 30 total user stories or use case flows, with each of those flows having only minimal business logic. If you could quickly and easily develop such an application using Ruby on Rails or Groovy and Grails and not feel the pain of lacking power and control over complexity and change, your system probably doesn’t need to use DDD. | 1 |To be clear, I am talking about 25 to 30 single business methods, not 25 to 30 whole service interfaces, each with multiple methods. The latter might be complex. |  |    
|So let’s say that somewhere in the range of 30 to 40 user stories or use case flows could be creeping toward complexity. Your system might be getting into DDD territory.|  2  | *Caveat emptor*: Very often complexity is not recognized soon enough. *We software developers are really, really good at underestimating complexity and level of effort. *Just because we might want to code up a Rails or Grails application doesn’t mean we should. In the long run those could hurt more than help.|  |
|Even if the application is not going to be complex now, will it grow in complexity? You may not know this for sure until real users start working with it, but there is a step in the “Supporting Thoughts” column that may help uncover the true situation.<br/><br/>Be careful here. If there is any hint at all that the application has even moderate complexity—here’s a good time to be paranoid—that may be sufficient indication that it will actually be more than moderately complex. Lean toward DDD.|  3|  Here it pays off to walk through the more complex usage scenarios with domain experts and see where it leads. Are domain experts . . .<br/>1. already asking for more complex features?If so, it’s likely an indication that the application is already or will soon become too complex to use a CRUD approach.<br/>2. so bored with the features that they can hardly bear discussing them? It’s probably not complex.  |  |   
|The application’s features are going to change often over a number of years, and you can’t anticipate that the kinds of changes will be simple. | 4 | DDD can help you manage the complexity of refactoring your model over time. |  |    
| You don’t understand the __Domain (2)__ because it’s new. As far as you and your team know, nobody has done this before. That most likely means it’s complex, or at least deserves due diligence with analytical scrutiny to determine the level of complexity.  | 5 | You are going to need to work with domain experts and experiment with models to get it right. You certainly also scored on one or more of the previous criteria, so use DDD |  |   

    This scoring exercise may have led your team to these conclusions:

    It’s too bad that we can’t shift gears quickly and easily when we discover we are on the wrong side of complexity, no matter if the wrong side is more or less complex than we thought.

    Sure, but that just means that we need to become much better at determining simplicity versus complexity early on in our project planning. That would save us a lot of time, expense, and trouble.

    Once we make a major architectural decision and get several use cases deep in development, we are usually stuck with it. We had better choose wisely.

If any of these observations resonates with your team, you are making good use of critical thought.   

## Anemia and Memory Loss

Anemia can be a serious health ailment with dangerous side effects. When the name __Anemic Domain Model __\[Fowler, Anemic\] was first coined, *it wasn’t meant to be a complimentary term*, as if to say that a domain model that is weak, without the power of inherent behavioral qualities, could possibly be a good thing. Strangely enough, Anemic Domain Models have popped up left and right in our industry. The trouble is that most developers seem to think this is quite normal and would not even acknowledge that a serious condition exists when employed in their systems. It’s a real problem.

Are you wondering if your model is feeling tired, listless, forgetful, clumsy, needing a good shot in the arm? If you’re suddenly experiencing technical hypochondria, here’s a good way to perform a self-examination. You’ll either put yourself at ease or confirm your worst fears. Use the steps in Table 1.2 to perform your checkup.

__Table 1.2__ Determine Your Domain Model Health History    

|    | Yes/No |     
|----| ------ |  
|Does the software you call a “domain model” have mostly public getters and setters, and no business logic or almost none at all—you know, objects that are mostly attribute value holders?  |   |    
| Are the software components that frequently use your “domain model” the ones that house most of the business logic of your system, and do those heavily invoke the public getters and setters on the “domain model”? You probably call this particular client layer of the “domain model” a __Service Layer__ or __Application Layer \(4, 14\)__. If instead this describes your user interface, answer “Yes” to this question and write a thousand times on a whiteboard that you’ll never, ever do that again.  |    |   
|__Hint: The correct answers are either “Yes” to both questions or “No” to both questions.__  |  |      

<br>

    How did you do?

    If you answered “No” to both questions, your domain is doing well.

    If you answered “Yes” to both questions, your “domain model” is very, very ill. It’s anemic. The good news is that you can get help for it by reading on.

    If you answered “Yes” to one question and “No” to the other question, you are either in denial or suffering from delusions or another neurological issue that could be caused by anemia. What should you do if you have conflicting answers? Go straight back to the first question and run the selfexamination once again. Take your time, but remember that your answer to both questions must be an emphatic “Yes!”

As \[Fowler, Anemic\] says, an Anemic Domain Model is a bad thing because you pay most of the high cost of developing a domain model, but you get little or none of the benefit. For example, because of the object-relational impedance mismatch, developers of such a “domain model” spend a lot of time and effort mapping objects to and from the persistence store. That’s a high price to pay while getting little or no benefit in return. I’ll add that what you have is not a domain model at all, but just a data model projected from a relational model \(or other database\) into objects. It’s an impostor that may actually be closer to the definition of __Active Record __\[Fowler, P of EAA\]. You can probably simplify your architecture by not being pretentious and just admit that you are really using a form of __Transaction Script __\[Fowler, P of EAA\].   

__Reasons Why Anemia Happens__

So if an Anemic Domain Model is the sickly outcome of a poorly executed design effort, why do so many use it while thinking that their model is experiencing fine health? Certainly it does reflect a procedural programming mentality, but I don’t think that’s the primary reason. A good portion of our industry is made up of sample code followers, which isn’t bad as long as the samples are quality ones. Often, however, sample code is purposely focused on demonstrating some concept or application programming interface \(API\) feature in the simplest possible way, without concern for good design principles. Yet oversimplified sample code, which usually demonstrates with a lot of getters and setters, is copied every day without a second thought about design.

There is another, older influence. The ancient history of Microsoft’s Visual Basic had much to do with where we are today. I’m not saying that Visual Basic was a bad language and integrated development environment \(IDE\), because it’s always been a highly productive environment and in some ways influenced the industry for the good. Of course, some may have avoided its direct influence altogether, but Visual Basic indirectly caught up with just about every software developer eventually. Just note the timeline shown in Table 1.3.    

__Table 1.3__ The Timeline from Behavior Rich to Infamous Anemia    

|1980s   |  1991 |  1992-1995 | 1996 | 1997 | 1998- |   
|--------| ------| ---------- | -----| ---- | ----- |   
|Objects make an impact due to Smalltalk and C++ |  Visual Basic properties and property sheets  | Visual tools and IDEs become prolific | Java JDK 1.0 released | JavaBean specification | Explosion of reflection-based tools for Java and .NET platforms based on properties |   

What I am talking about is the influence of properties and property sheets, both backed by property getters and setters that were made so popular by the original Visual Basic forms designer. All you had to do was place a few custom control instances on a form, fill out their property sheets, and *voilà\!* You had a fully functioning Windows application. It took just a few minutes to do that compared to the few days required to program a similar application directly against the Windows API using C.

So what does all that have to do with Anemic Domain Models? *The JavaBean standard was originally specified to assist in the creation of visual programming tools for Java*. Its motivation was to bring the Microsoft ActiveX capabilities to the Java platform. It offered the hope of creating a market full of third-party custom controls of various kinds, just like Visual Basic’s. Soon almost every framework and library jumped on the JavaBean bandwagon. This included  much  of  the  Java  SDK/JDK  as  well  as  libraries  such  as  the  popular Hibernate. Specific to our DDD concerns, *Hibernate was introduced to persist domain models.* The trend continued as the .NET platform reached us.

Interestingly, any domain model that was persisted using Hibernate in the early days had to expose public getters and setters for every persistent simple attribute and complex association in every domain object. This meant that even if you wanted to design your POJO \(Plain Old Java Object\) with a behavior-rich interface, you had to expose your internals publicly so that Hibernate could persist and reconstitute your domain objects. Sure, you could do things to hide the public JavaBean interface, but by and large most developers didn’t bother or even understand why they should have.


> __Should I Be Concerned about Using Object-Relational Mappers with DDD?__  
The preceding critique of Hibernate is from a historical perspective. For quite a while now Hibernate has supported the use of hidden getters and setters, and even direct field access. I demonstrate in later chapters how to avoid anemia in your models when using Hibernate and other persistence mechanisms. So, don’t sweat it.   

Most, if not all, of the Web frameworks also function solely on the JavaBean standard. If you want your Java objects to be able to populate your Web pages, the Java objects had better support the JavaBean specification. If you want your HTML forms to populate a Java object when submitted to the server side, your Java form object had better support the JavaBean specification.

Just about every framework on the market today requires, and therefore promotes, the use of public properties on simple objects. Most developers can’t help but be influenced by all the anemic classes all over their enterprises. Admit it. You’ve been bitten by it, haven’t you? As a result, we have a situation that might be best labeled *anemia everywhere*.   

## Look at What Anemia Does to Your Model

All right, so let’s say we can agree that this is both true and vexing to us. What does *anemia everywhere* have to do with *memory loss* ? When you are reading through the client code of an Anemic Domain Model \(for example, the impostor __Application Service \(4, 14\)__, à la Transaction Script\), what do we usually see? Here’s a rudimentary example:   
```java
    @Transactional
    public void saveCustomer(
            String customerId,
            String customerFirstName, String customerLastName,
            String streetAddress1, String streetAddress2,
            String city, String stateOrProvince,
            String postalCode, String country,
            String homePhone, String mobilePhone,
            String primaryEmailAddress, String secondaryEmailAddress) {
        Customer customer = customerDao.readCustomer(customerId);
        if (customer == null) {
            customer = new Customer();
            customer.setCustomerId(customerId);
        }
        customer.setCustomerFirstName(customerFirstName);
        customer.setCustomerLastName(customerLastName);
        customer.setStreetAddress1(streetAddress1);
        customer.setStreetAddress2(streetAddress2);
        customer.setCity(city);
        customer.setStateOrProvince(stateOrProvince);
        customer.setPostalCode(postalCode);
        customer.setCountry(country);
        customer.setHomePhone(homePhone);
        customer.setMobilePhone(mobilePhone);
        customer.setPrimaryEmailAddress(primaryEmailAddress);
        customer.setSecondaryEmailAddress (secondaryEmailAddress);
        customerDao.saveCustomer(customer);
    }
```
> __Example Purposely Kept Simple__  
Admittedly, this example is not from a very interesting domain, but it does help us examine a less-than-ideal design and determine how we can refactor it to a much better one. Let’s be clear that this exercise is not leading us to a cooler way to save data. It’s about crafting a software model that adds value to your business, even though this example may not seem valuable.

What did this code just do? Actually it’s pretty versatile code. It saves a Customer no matter whether it is new or preexisting. It saves a Customer no matter whether the last name changed or the person moved to a new home. It saves a Customer no matter whether the person got a new home phone number or discontinued home phone service, or whether he or she got a mobile phone for the first time, or both. It even saves a Customer who switched from using Juno to using Gmail instead, or who changed jobs and now has a new work e-mail address. Wow, this is an awesome method\!

Or is it? Actually, we have no idea under what business situations this saveCustomer\(\) method is used—not exactly, anyway. Why was this method created in the first place? Does anyone remember its original intent, and all the motivations for changing it to support a wide variety of business goals? Those memories were quite likely lost only a few weeks or months after the method was created and then modified. And it gets even worse. You don’t believe me? Look at the next version of this same method:   
```java
    @Transactional
    public void saveCustomer(
            String customerId,
            String customerFirstName, String customerLastName,
            String streetAddress1, String streetAddress2,
            String city, String stateOrProvince,
            String postalCode, String country,
            String homePhone, String mobilePhone,
            String primaryEmailAddress, String secondaryEmailAddress) {
        Customer customer = customerDao.readCustomer(customerId);
        if (customer == null) {
            customer = new Customer();
            customer.setCustomerId(customerId);
        }
        if (customerFirstName != null) {
            customer.setCustomerFirstName(customerFirstName);
        }
        if (customerLastName != null) {
            customer.setCustomerLastName(customerLastName);
        }
        if (streetAddress1 != null) {
            customer.setStreetAddress1(streetAddress1);
        }
        if (streetAddress2 != null) {
            customer.setStreetAddress2(streetAddress2);
        }
        if (city != null) {
            customer.setCity(city);
        }
        if (stateOrProvince != null) {
            customer.setStateOrProvince(stateOrProvince);
        }
        if (postalCode != null) {
            customer.setPostalCode(postalCode);
        }
        if (country != null) {
            customer.setCountry(country);
        }
        if (homePhone != null) {
            customer.setHomePhone(homePhone);
        }
        if (mobilePhone != null) {
            customer.setMobilePhone(mobilePhone);
        }
        if (primaryEmailAddress != null) {
            customer.setPrimaryEmailAddress(primaryEmailAddress);
        }
        if (secondaryEmailAddress != null) {
            customer.setSecondaryEmailAddress (secondaryEmailAddress);
        }
        customerDao.saveCustomer(customer);
    }
```  

I have to note here that this example isn’t as bad as it gets. Many times the data-mapping code becomes quite complex, and a lot of business logic gets tucked away in it. I’m sparing you the worst in this example, but you’ve probably seen it for yourself.

Now each of the parameters other than the customerId is optional. We can now use this method to save a Customer under at least a dozen business situations, and more\! But is that really a good thing? How could we actually test this method to ensure that it doesn’t save a Customer under the wrong situations?

Without going into extensive detail, this method could function incorrectly in more ways than it could correctly. Perhaps there are database constraints that prevent a completely invalid state from being persisted, but now you have to look at the database to be sure. Almost certainly it will take you some time to mentally map between Java attributes and column names. Once you’ve figured out that part, you find that the database constraints are missing or incomplete.

You could look at the possibly many clients \(not counting those added after the user interface was completed to manage automatic remote clients\) and compare source revisions to gain some insight into why it is implemented the way it is right now. As you search for answers, you learn that nobody can explain why this one method works the way it does, or how many correct uses there are. It could take several hours or days to understand it on your own.     

<img src = "../img/image39.png" align = "right" width = "300">    

__Cowboy Logic:__     
AJ: “That fella’s so confused, he doesn’t know if he’s sackin’ potatoes or rollerskatin’ in a buffalo herd.”
<br><br><br><br><br><br><br><br><br>

Domain experts can’t help here because they would have to be programmers to understand the code. Even if a domain expert or two knew enough about programming or could at least read the code, they would probably be at least equally at a loss as a developer regarding all that code is meant to support. With all these concerns in mind, do we dare change this code in any way, and if so, how?

There are at least three big problems here:

1. There is little intention revealed by the saveCustomer\(\) interface.
2. The implementation of saveCustomer\(\) itself adds hidden complexity.
3. The Customer “domain object” isn’t really an object at all. It’s really just a dumb data holder.

Let’s call this unenviable situation *anemia-induced memory loss*. It happens all the time on projects that produce this kind of implicit, completely subjective code “design.”   


> __Hold On a Minute\!__   
At this point some of you may be thinking, “Our designs never really leave the whiteboard. We just draw some structure, and once agreement on that is reached, we are set free to implement. Scary.”   
If so, try not to distinguish design from implementation. Remember that when practicing DDD, *the design is the code and the code is the design*. In other words, whiteboard diagrams aren’t the design, just a way to discuss the challenges of the model.    
Stay tuned, as you’ll learn how to take ideas off the whiteboard and make them work for you.

By now you should be worried about this kind of code and how you can create a better design. The good news is that you can succeed in producing an explicit, carefully crafted design in your code.
