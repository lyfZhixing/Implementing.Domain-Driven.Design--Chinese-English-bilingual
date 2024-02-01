# Why You Should Do DDD

Actually, I’ve already given you some pretty good reasons why DDD makes so much practical sense\. At the risk of breaking the DRY principle \(“Don’t repeat yourself”\), I reiterate them here and also add to the earlier reasons\. Does any\- one hear an echo?

- Put domain experts and developers on a level playing field, which pro\- duces software that makes perfect sense to the business, not just the cod\- ers\. This doesn’t mean merely tolerating the opposite group\. It means becoming one cohesive, tight\-knit team\.
- That “makes sense to the business” thing means investing in the business by making software that is as close as possible to what the business lead\- ers and experts would create if they were the coders\.
- You can actually teach the business more about itself\. No domain expert, no C\-level manager, no one, ever knows every single thing about the busi\- ness\. It’s a constant discovery process that becomes more insightful over time\. With DDD, everybody learns because everybody contributes to dis\- covery discussions\.
- Centralizing knowledge is key, because with that the business is capable of ensuring that understanding the software is not locked in “tribal knowl\- edge,” available only to a select few, who are usually only the developers\.
- There are zero translations between the domain experts, the software developers, and the software\. That doesn’t mean maybe some few transla\- tions\. It means zero translations because your team develops a common, shared language that everyone on the team speaks\.
- The design is the code, and the code is the design\. The design is how it works\. Knowing the best code design comes through quick experimental models using an agile discovery process\.
- DDD provides sound software development techniques that address both strategic and tactical design\. Strategic design helps us understand what are the most important software investments to make, what existing soft\- ware assets to leverage in order to get there fastest and safest, and who must be involved\. Tactical design helps us craft the single elegant model of a solution using time\-tested, proven software building blocks\.

Like any good, high\-yielding investment, DDD has some up\-front cost of time and effort for the team\. Considering the typical challenges encountered by every software development effort will reinforce the need to invest in a sound software development approach\.

## Delivering Business Value Can Be Elusive

Developing software that delivers true business value is not the same thing as developing ordinary business software\. Software that delivers true business value aligns with the business strategic initiatives and bears solutions with clearly identifiable competitive advantage—software that is not about technol\- ogy, but about the business\.    

Business knowledge is never centralized\. Development teams have to bal\- ance and prioritize among the needs and requests of multiple stakeholders and engage with many people having diverse skill sets, all with the goal of uncov\- ering software functional and nonfunctional requirements\. After gathering all that information, how can teams be certain that any given requirement delivers true business value? In fact, what are the business values being sought, and how do you uncover them, prioritize them, and realize them?

One of the worst disconnects of a business software development effort is seen in the gap between domain experts and software developers\. Generally speaking, true domain experts are focused on delivering business value\. On the other hand, software developers are typically drawn to technology and technical solutions to business problems\. It’s not that software developers have wrong motivations; it’s just what tends to grab their attention\. Even when soft\- ware developers engage with domain experts, the collaboration is largely at a surface level, and the software that gets developed often results in a trans\- lation/mapping between how the business thinks and operates and how the software developer interprets that\. The resulting software generally does not reflect a recognizable realization of the mental model of the domain experts, or perhaps it does so only partially\. Over time this disconnect becomes costly\. The translation of domain knowledge into software is lost as developers transi\- tion to other projects or leave the company\.

A different, yet related problem is when one or more domain experts do

not agree with each other\. This tends to happen because each expert has more or less experience in the specific domain being modeled, or they are simply experts in related but different areas\. It’s also common for multiple “domain experts” to have no expertise in a given domain, where they are more of a busi\- ness analyst, yet they are expected to bring insightful direction to discussions\. When this situation goes unchecked, it results in blurred rather than crisp men\- tal models, which lead to conflicting software models\.

Worse still is when the technical approach to software development actually wrongly changes the way the business functions\. While a different scenario, it is well known that enterprise resource planning \(ERP\) software will often change the overall business operations of an organization to fit the way the ERP functions\. The total cost of owning the ERP cannot be fully calculated in terms of license and maintenance fees\. The reorganization and disruption to the business can be far more costly than either of those two tangible fac\- tors\. A similar dynamic is at play as your software development teams inter\- pret what the business needs into what the newly developed software actually does\. This can be both costly and disruptive to the business, its customers, and its partners\. Furthermore, this technical interpretation is both unnecessary and avoidable with the use of proven software development techniques\. The solu\- tion is a key investment\. 

## How DDD Helps   

DDD is an approach to developing software that focuses on these three pri\- mary aspects:

1. DDD brings domain experts and software developers together in order to develop software that reflects the mental model of the business experts\. This does not mean that effort is spent on modeling the “real world\.” Rather, DDD delivers a model that is the most useful to the business\. Sometimes useful and realistic models happen to intersect, but to the degree that they diverge, DDD chooses useful\.

    With this aspect the efforts of domain experts and software developers are devoted to jointly developing a Ubiquitous Language of the areas of the business that they are focused on modeling\. The Ubiquitous Language is developed with full team agreement, is spoken, and is directly captured in the model of the software\. It is worth reiterating that the team is com\- posed of both domain experts and software developers\. It’s never “us and them\.” It’s always *us\. *This is a key business value that allows business know\-how to outlive the relatively short initial development efforts that deliver the first few versions of the software, and the teams that produce it\. It’s the point where the cost of developing software is a justifiable busi\- ness investment, not just a cost center\.

    This entire effort unifies domain experts who initially disagree with each other, or who simply lack core knowledge of the domain\. Further, it strengthens the close\-knit team by spreading deep domain insight among all team members, including software developers\. Consider this the hands\-on training that every company should invest in its knowledge workers\.

1. DDD addresses the strategic initiatives of the business\. While this stra\- tegic design approach naturally includes technical analysis, it is more concerned with the strategic direction of the business\. It helps define the best inter\-team organizational relationships and provides early\-warning systems for recognizing when a given relationship could cause software and even project failure\. The technical aspects of strategic design have the goal of cleanly bounding systems and business concerns, which pro\- tects each *business\-level service*\. This provides meaningful motivations for how an overall *service\-oriented architecture *or *business\-driven archi\- tecture *is achieved\.

1. DDD meets the real technical demands of the software by using tacti\- cal design modeling tools to analyze and develop the executable software deliverables\. These tactical design tools allow developers to produce soft\- ware that is a correct codification of the domain experts’ mental model, is highly testable, is less error prone \(a provable statement\), performs to service\-level agreements \(SLAs\), is scalable, and allows for distrib\- uted computing\. DDD best practices generally address a dozen or more higher\-level architectural and lower\-level software design concerns, with a focus on recognizing true business rules and data invariants, and pro\- tecting the rules from error situations\.

Using this approach to software development, you and your team can succeed in delivering true business value\.  

## Grappling with the Complexity of Your Domain

We primarily want to use DDD in the areas that are most important to the business\. You don’t invest in what can be easily replaced\. *You invest in the nontrivial, the more complex stuff, the most valuable and important stuff that promises to return the greatest dividends\.* That’s why we call such a model a __Core Domain \(2\)__\. It is these, and in second priority the *significant* __Supporting Subdomains \(2\)__, that deserve and get the biggest investment\. Rightly, then, we need to grasp what *complex* means\.

> __Use DDD to Simplify, Not to Complicate__  
Use DDD to model a complex domain in the simplest possible way\. Never use DDD to make your solution more complex\.

What qualifies as complex will differ from business to business\. Different companies have different challenges, different levels of maturity, and different software development capabilities\. So rather than determining what is *com\- plex*, it may be easier to determine what is *nontrivial*\. Thus, *your team and management will have to determine if a system you are planning to work on deserves the cost of making a DDD investment\.*

__DDD Scorecard:__ Use Table 1\.1 to determine whether your project qualifies for an investment in DDD\. If a row on the scorecard describes your project, place the corresponding number of points in the right\-hand column\. Tally all the points for your project\. If it’s 7 or higher, seriously consider using DDD\.

__Table 1\.1__ The DDD Scorecard

__*Does Your Project Score a Total of 7 Points or Higher?*__     

|If Your Project \. \. \.|Points|Supporting Thoughts  | Your Score  |    
|---------|-----------|--------|  --------|
|If your application is completely data\-centric and truly qualifies for a pure CRUD solution, where every operation is basically a simple database query to Create, Read, Update, or Delete, you don’t need DDD\. Your team just needs to put a pretty face ona database table editor\. In other words, if you can trust your users to insert data directly into a table, update it, and some\- times delete it, you wouldn’t even need a user interface\. That’s not realistic, but it’s conceptually relevant\. If you could even use a simple database development tool to create a solution, don’t waste your company’s time and money on DDD\. |0|This seems like a no\-brainer, but it’s not usually that easy to determine simple versus complex\. It’s not as if every application that isn’t pure CRUD deserves the time and effort of using DDD\. So maybe we could come up with other metrics to help us draw a line between what is complex and what is not \. \. \.| |   
|If your system requires just 30 or fewer business operations, it’s probably pretty simple\. This would mean that your applica\- tion would have no more than 30 total user stories or use case flows, with each of those flows having only minimal business logic\. If you could quickly and easily develop such an applica\- tion using Ruby on Rails or Groovy and Grails and not feel the pain of lacking power and control over complexity and change, your system probably doesn’t need to use DDD\. | 1 |To be clear, I am talking about 25 to 30 single busi\- ness methods, not 25 to 30 whole service interfaces, each with multiple methods\. The latter might be complex\. |  |    
|So let’s say that somewhere in the range of 30 to 40 user stories or use case flows could be creeping toward complexity\. Your system might be getting into DDD territory\.|  2  | *Caveat emptor*: Very often complexity is not rec\- ognized soon enough\. *We software developers are really, really good at underestimating complexity and level of effort\. *Just because we might want to code up a Rails or Grails application doesn’t mean we should\. In the long run those could hurt more than help\.|  |
|Even if the application is not going to be complex now, will it grow in complexity? You may not know this for sure until real users start working with it, but there is a step in the “Sup\- porting Thoughts” column that may help uncover the true situation\.<br/><br/>Be careful here\. If there is any hint at all that the application has even moderate complexity—here’s a good time to be para\- noid—that may be sufficient indication that it will actually be more than moderately complex\. Lean toward DDD\.|  3|  Here it pays off to walk through the more complex usage scenarios with domain experts and see where it leads\. Are domain experts \. \. \.<br/>1. already asking for more complex features?If so, it’s likely an indication that the application is already or will soon become too complex to use a CRUD approach\.<br/>2. so bored with the features that they can hardly bear discussing them? It’s probably not complex\.  |  |   
|The application’s features are going to change often over a number of years, and you can’t anticipate that the kinds of changes will be simple. | 4 | DDD can help you manage the complexity of refactoring your model over time. |  |    
| You don’t understand the __Domain (2)__ because it’s new. As far as you and your team know, nobody has done this before. That most likely means it’s complex, or at least deserves due diligence with analytical scrutiny to determine the level of complexity.  | 5 | You are going to need to work with domain experts and experiment with models to get it right. You certainly also scored on one or more of the previous criteria, so use DDD |  |   

    This scoring exercise may have led your team to these conclusions:

    It’s too bad that we can’t shift gears quickly and easily when we discover we are on the wrong side of complexity, no matter if the wrong side is more or less complex than we thought.

    Sure, but that just means that we need to become much better at determining simplicity versus complexity early on in our project planning. That would save us a lot of time, expense, and trouble.

    Once we make a major architectural decision and get several use cases deep in development, we are usually stuck with it. We had better choose wisely.

If any of these observations resonates with your team, you are making good use of critical thought\.   

## Anemia and Memory Loss

Anemia can be a serious health ailment with dangerous side effects\. When the name __Anemic Domain Model __\[Fowler, Anemic\] was first coined, *it wasn’t meant to be a complimentary term*, as if to say that a domain model that is weak, without the power of inherent behavioral qualities, could possibly be a good thing\. Strangely enough, Anemic Domain Models have popped up left and right in our industry\. The trouble is that most developers seem to think this is quite normal and would not even acknowledge that a serious condition exists when employed in their systems\. It’s a real problem\.

Are you wondering if your model is feeling tired, listless, forgetful, clumsy, needing a good shot in the arm? If you’re suddenly experiencing technical hypochondria, here’s a good way to perform a self\-examination\. You’ll either put yourself at ease or confirm your worst fears\. Use the steps in Table 1\.2 to perform your checkup\.

__Table 1\.2__ Determine Your Domain Model Health History    

|    | Yes/No |     
|----| ------ |  
|Does the software you call a “domain model” have mostly public getters and setters, and no business logic or almost none at all—you know, objects that are mostly attri\- bute value holders?  |   |    
| Are the software components that frequently use your “domain model” the ones that house most of the business logic of your system, and do those heavily invoke the public getters and setters on the “domain model”? You probably call this particular client layer of the “domain model” a __Service Layer__ or __Application Layer \(4, 14\)__\. If instead this describes your user interface, answer “Yes” to this question and write a thousand times on a whiteboard that you’ll never, ever do that again\.  |    |   
|__Hint: The correct answers are either “Yes” to both questions or “No” to both questions\.__  |  |      

<br>

    How did you do?

    If you answered “No” to both questions, your domain is doing well.

    If you answered “Yes” to both questions, your “domain model” is very, very ill. It’s anemic. The good news is that you can get help for it by reading on.

    If you answered “Yes” to one question and “No” to the other question, you are either in denial or suffering from delusions or another neurological issue that could be caused by anemia. What should you do if you have conflicting answers? Go straight back to the first question and run the selfexamination once again. Take your time, but remember that your answer to both questions must be an emphatic “Yes!”

As \[Fowler, Anemic\] says, an Anemic Domain Model is a bad thing because you pay most of the high cost of developing a domain model, but you get little or none of the benefit\. For example, because of the object\-relational impedance mismatch, developers of such a “domain model” spend a lot of time and effort mapping objects to and from the persistence store\. That’s a high price to pay while getting little or no benefit in return\. I’ll add that what you have is not a domain model at all, but just a data model projected from a relational model \(or other database\) into objects\. It’s an impostor that may actually be closer to the definition of __Active Record __\[Fowler, P of EAA\]\. You can probably simplify your architecture by not being pretentious and just admit that you are really using a form of __Transaction Script __\[Fowler, P of EAA\]\.   

__Reasons Why Anemia Happens__

So if an Anemic Domain Model is the sickly outcome of a poorly executed design effort, why do so many use it while thinking that their model is experi\- encing fine health? Certainly it does reflect a procedural programming mental\- ity, but I don’t think that’s the primary reason\. A good portion of our industry is made up of sample code followers, which isn’t bad as long as the samples are quality ones\. Often, however, sample code is purposely focused on demon\- strating some concept or application programming interface \(API\) feature in the simplest possible way, without concern for good design principles\. Yet oversimplified sample code, which usually demonstrates with a lot of getters and setters, is copied every day without a second thought about design\.

There is another, older influence\. The ancient history of Microsoft’s Visual Basic had much to do with where we are today\. I’m not saying that Visual Basic was a bad language and integrated development environment \(IDE\), because it’s always been a highly productive environment and in some ways influenced the industry for the good\. Of course, some may have avoided its direct influ\- ence altogether, but Visual Basic indirectly caught up with just about every software developer eventually\. Just note the timeline shown in Table 1\.3\.    

__Table 1\.3__ The Timeline from Behavior Rich to Infamous Anemia    

|1980s   |  1991 |  1992-1995 | 1996 | 1997 | 1998- |   
|--------| ------| ---------- | -----| ---- | ----- |   
|Objects make an impact due to Smalltalk and C++ |  Visual Basic properties and property sheets  | Visual tools and IDEs become prolific | Java JDK 1.0 released | JavaBean specification | Explosion of reflection-based tools for Java and .NET platforms based on properties |   

What I am talking about is the influence of properties and property sheets, both backed by property getters and setters that were made so popular by the original Visual Basic forms designer\. All you had to do was place a few custom control instances on a form, fill out their property sheets, and *voilà\!* You had a fully functioning Windows application\. It took just a few minutes to do that compared to the few days required to program a similar application directly against the Windows API using C\.

So what does all that have to do with Anemic Domain Models? *The Java\- Bean standard was originally specified to assist in the creation of visual pro\- gramming tools for Java*\. Its motivation was to bring the Microsoft ActiveX capabilities to the Java platform\. It offered the hope of creating a market full of third\-party custom controls of various kinds, just like Visual Basic’s\. Soon almost every framework and library jumped on the JavaBean bandwagon\. This included  much  of  the  Java  SDK/JDK  as  well  as  libraries  such  as  the  popular Hibernate\. Specific to our DDD concerns, *Hibernate was introduced to persist domain models\.* The trend continued as the \.NET platform reached us\.

Interestingly, any domain model that was persisted using Hibernate in the early days had to expose public getters and setters for every persistent sim\- ple attribute and complex association in every domain object\. This meant that even if you wanted to design your POJO \(Plain Old Java Object\) with a behav\- ior\-rich interface, you had to expose your internals publicly so that Hibernate could persist and reconstitute your domain objects\. Sure, you could do things to hide the public JavaBean interface, but by and large most developers didn’t bother or even understand why they should have\.


> __Should I Be Concerned about Using Object\-Relational Mappers with DDD?__  
The preceding critique of Hibernate is from a historical perspective\. For quite a while now Hibernate has supported the use of hidden getters and setters, and even direct field access\. I demonstrate in later chapters how to avoid anemia in your mod\- els when using Hibernate and other persistence mechanisms\. So, don’t sweat it\.   

Most, if not all, of the Web frameworks also function solely on the JavaBean standard\. If you want your Java objects to be able to populate your Web pages, the Java objects had better support the JavaBean specification\. If you want your HTML forms to populate a Java object when submitted to the server side, your Java form object had better support the JavaBean specification\.

Just about every framework on the market today requires, and therefore promotes, the use of public properties on simple objects\. Most developers can’t help but be influenced by all the anemic classes all over their enterprises\. Admit it\. You’ve been bitten by it, haven’t you? As a result, we have a situation that might be best labeled *anemia everywhere*\.   

## Look at What Anemia Does to Your Model

All right, so let’s say we can agree that this is both true and vexing to us\. What does *anemia everywhere* have to do with *memory loss* ? When you are reading through the client code of an Anemic Domain Model \(for example, the impos\- tor __Application Service \(4, 14\)__, à la Transaction Script\), what do we usually see? Here’s a rudimentary example:   
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
Admittedly, this example is not from a very interesting domain, but it does help us examine a less\-than\-ideal design and determine how we can refactor it to a much better one\. Let’s be clear that this exercise is not leading us to a cooler way to save data\. It’s about crafting a software model that adds value to your business, even though this example may not seem valuable\.

What did this code just do? Actually it’s pretty versatile code\. It saves a Customer no matter whether it is new or preexisting\. It saves a Customer no matter whether the last name changed or the person moved to a new home\. It saves a Customer no matter whether the person got a new home phone number or discontinued home phone service, or whether he or she got a mobile phone for the first time, or both\. It even saves a Customer who switched from using Juno to using Gmail instead, or who changed jobs and now has a new work e\-mail address\. Wow, this is an awesome method\!

Or is it? Actually, we have no idea under what business situations this saveCustomer\(\) method is used—not exactly, anyway\. Why was this method created in the first place? Does anyone remember its original intent, and all the motivations for changing it to support a wide variety of business goals? Those memories were quite likely lost only a few weeks or months after the method was created and then modified\. And it gets even worse\. You don’t believe me? Look at the next version of this same method:   
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

I have to note here that this example isn’t as bad as it gets\. Many times the data\-mapping code becomes quite complex, and a lot of business logic gets tucked away in it\. I’m sparing you the worst in this example, but you’ve proba\- bly seen it for yourself\.

Now each of the parameters other than the customerId is optional\. We can now use this method to save a Customer under at least a dozen business situations, and more\! But is that really a good thing? How could we actually test this method to ensure that it doesn’t save a Customer under the wrong situations?

Without going into extensive detail, this method could function incorrectly in more ways than it could correctly\. Perhaps there are database constraints that prevent a completely invalid state from being persisted, but now you have to look at the database to be sure\. Almost certainly it will take you some time to mentally map between Java attributes and column names\. Once you’ve figured out that part, you find that the database constraints are missing or incomplete\.

You could look at the possibly many clients \(not counting those added after the user interface was completed to manage automatic remote clients\) and com\- pare source revisions to gain some insight into why it is implemented the way it is right now\. As you search for answers, you learn that nobody can explain why this one method works the way it does, or how many correct uses there are\. It could take several hours or days to understand it on your own\.     

<img src = "../img/image39.png" align = "right" width = "300">    

__Cowboy Logic:__     
AJ: “That fella’s so confused, he doesn’t know if he’s sackin’ potatoes or rollerskatin’ in a buffalo herd\.”
<br><br><br><br><br><br><br><br><br>

Domain experts can’t help here because they would have to be programmers to understand the code\. Even if a domain expert or two knew enough about programming or could at least read the code, they would probably be at least equally at a loss as a developer regarding all that code is meant to support\. With all these concerns in mind, do we dare change this code in any way, and if so, how?

There are at least three big problems here:

1. There is little intention revealed by the saveCustomer\(\) interface\.
2. The implementation of saveCustomer\(\) itself adds hidden complexity\.
3. The Customer “domain object” isn’t really an object at all\. It’s really just a dumb data holder\.

Let’s call this unenviable situation *anemia\-induced memory loss*\. It happens all the time on projects that produce this kind of implicit, completely subjective code “design\.”   


> __Hold On a Minute\!__   
At this point some of you may be thinking, “Our designs never really leave the whiteboard\. We just draw some structure, and once agreement on that is reached, we are set free to implement\. Scary\.”   
If so, try not to distinguish design from implementation\. Remember that when practicing DDD, *the design is the code and the code is the design*\. In other words, whiteboard diagrams aren’t the design, just a way to discuss the challenges of the model\.    
Stay tuned, as you’ll learn how to take ideas off the whiteboard and make them work for you\.

By now you should be worried about this kind of code and how you can create a better design\. The good news is that you can succeed in producing an explicit, carefully crafted design in your code\.
