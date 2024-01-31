# Can I DDD

You can implement DDD if you have

- A passion for creating excellent software every day, and the tenacity to achieve that goal
- The eagerness to learn and improve, and the fortitude to admit you need to
- The aptitude to understand software patterns and how to properly apply them
- The skill and patience to explore design alternatives using proven agile methods
- The courage to challenge the status quo
- The desire and ability to pay attention to details, to experiment and discover
- A drive to seek ways to code smarter and better

I’m not going to tell you that there isn’t a learning curve\. To put it bluntly, the learning curve can be steep\. Yet, this book has been put together to help flatten the curve as much as possible\. My goal is to help you and your team implement DDD with the greatest potential for success\.

DDD isn’t first and foremost about technology\. In its most central principles, DDD is about discussion, listening, understanding, discovery, and business value, all in an effort to centralize knowledge\. If you are capable of *understanding the business* in which your company works, you can at a minimum participate in the software model discovery process to produce a __Ubiquitous Language__\. Sure, you’re going to have to learn more about the business, lots more\. Still, you are on your way to succeeding with DDD already because you can comprehend the concepts of your business, you revel in developing great software, and that gives you the proper footing to take DDD all the way\.  

Won’t having years, even a decade or two, of software development expe\- rience help? It might\. Nevertheless, software development experience doesn’t give you the ability to listen and learn from *domain experts*, the people who know the most about some high\-priority area of the business\. You are at a greater advantage if you can engage with those who seldom, if ever, express themselves using technical lingo\. You’re going to have to listen and listen care\- fully\. You’re going to have to respect their viewpoint and trust that they know a lot more than you do\.   

> __There Are Big Advantages to Engaging with Domain Experts__  
You are at a greater advantage if you can engage with those who seldom, if ever, express themselves using technical lingo\. Just as you are going to learn from them, there is a high probability that they are also going to learn from you\.

What you may like best about DDD is that the domain experts are also going to *have to listen to you*\. You are on the team just as they are\. As strange as it may seem, the domain experts don’t know everything about their business, and they are also going to learn more about it\. Just as you are going to learn from them, there is a high probability that they are also going to learn from you\. Your questions about what they know will most likely also uncover what they don’t know\. You’ll be directly involved in helping everyone on the team discover a deeper understanding of the business, *even shaping the business*\.

It’s great when a team learns and grows together\. If you give it a chance, DDD makes that possible\.

> __But We Don’t *Have* Domain Experts__   
A domain expert is not one by job title\. These are the people who know the line of business you are working in really well\. They probably have a lot of background in the business domain, and they might be product designers or even your salespeople\. Look past the job title\. The people you are looking for know more about what you are working on than anyone else, and for sure way more than you know\. *Find them\. Listen\. Learn\. Design in code\.*   

So far we’re off to a pretty reassuring start\. Still, I am also not going to tell you that technical ability isn’t important, that somehow you can get by without it\. You will have to grasp some advanced software *domain modeling *concepts\. Even so, it doesn’t necessarily mean you are going to be in over your head\. If you have abilities somewhere between grasping *Head First Design Patterns *\[Freeman et al\.\] and grokking the original *Design Patterns *\[Gamma et al\.\] text, or even more advanced patterns, you stand a really good chance of succeeding with DDD\. You can bank on this: I’m going to do everything I can to make that happen by lowering the bar, no matter what your level of experience\.   

> __What’s a Domain Model?__   
It’s a software model of the very specific business domain you are working in\. Often it’s implemented as an object model, where those objects have both data and behav\- ior with literal and accurate business meaning\.  
Creating a unique, carefully crafted domain model at the heart of a core, strate\- gic application or subsystem is essential to practicing DDD\. With DDD your domain models will tend to be smallish, very focused\. Using DDD, you never try to model the whole business enterprise with a single, large domain model\. Phew, that’s good\!

Consider the following perspectives of the people who can benefit from DDD\. I know you fit in here somewhere:

- __*Newbie, junior developer*: __“I’m young, with fresh ideas, I’ve got pent\-up energy to code, and I’m going to have an impact\. What’s got me miffed is one of the projects I sprint on\. I didn’t expect that my first gig off campus would mean shoveling data back and forth using lots of almost identical yet redundant ‘objects\.’ Why is this architecture so complex if that’s all that’s happening? What’s up with *that*? The code breaks a lot when I try to change it\. Does anyone actually understand what it’s supposed to do? Now there are some complex new features I have to add\. I regularly slap an *adapter *around legacy classes to shield me from the goo\. *No joy*\. I’m sure there’s something I can do besides code and debug all day and night just to finish iterations\. Whatever that is, I’m going to track it down and own it\. I heard some of the others talking about DDD\. *It sounds like Gang of Four, but tuned for the domain model\.* Nice\.”

Gotcha covered\.

-  __*Midlevel developer* :__ “Over the past few months I’ve been included on the new system\. It’s my turn to make a difference\. I get it, but what I’m missing are profound insights when I’m meeting with the senior develop\- ers\. Sometimes things seem whacked, but I’m not sure why\. I’m going to help change the way things are done around here\. I know that throwing technology at a problem only takes you so far, and that’s basically not far enough\. What I need is *a sound software development technique* that’s going to help me become a wise and experienced software practitioner\. One of the senior architects, the new guy, made a pitch for something called DDD\. I’m listening\.”

You’re sounding senior already\. Read on\. Your forward\-thinking attitude will be rewarded\.

- __*Senior developer, architect* :__ “I’ve used DDD on a few projects, but not since landing this new position\. I like the power of the *tactical patterns*, but there’s a lot more I could apply, with *strategic design *being one\. What I found most insightful when reading \[Evans\] was the Ubiquitous Lan\- guage\. *That’s powerful stuff*\. I’ve had discussions with a number of my teammates and management, trying to influence DDD’s adoption here\. One of the new kids and a few of the midlevel and senior members are jazzed about the prospects\. Management isn’t so excited\. I recently joined this company, and although I was brought in to lead, it seems that the organization is less interested in disruptive advancements than I thought\. Whatever\. I’m not giving up\. With other developers psyched about it, *I know we can make it happen*\. The payoffs are going to be much greater than anticipated\. We’ll draw the pure business people—the domain experts—closer to our technical teams, and *we’ll actually invest in our solutions*, not just grunt them out iteration after iteration\.”

    Now *that’s* what a leader does\. This book has lots of guidance that shows how to succeed with *strategic design*\.

- __*Domain expert* :__ “I’ve been involved in specifying the IT solutions to our business challenges for a long time now\. Maybe it’s too much to expect, but I wish the developers understood better what we do here\. They’re always talking down to us like we’re stupid\. What they don’t understand is, if it wasn’t for us there wouldn’t be jobs here for them to mess around with computers\. The developers always have some strange way of talking about what our software does\. If we talk about A, they say it’s really called B\. *It’s like we have to have some sort of dictionary and road map on hand every time we try to communicate what we need*\. If we don’t let them have their way by calling B what we know is A, they don’t coop\- erate\. We waste so much time in this mode\. *Why can’t the software just work the way the real experts think about the business?*”

    You’ve got that right\. One of the biggest problems is the false need for translation between business people and techies\. This chapter is for you\. As you’re going to see, *DDD puts you and developers on level ground*\.    

    And, surprise\! You’ve got some developers already leaning your way\. Help them here\.

- __*Manager* :__ “We are shipping software\. It’s not always with the greatest result, and changes seem to take longer than they should\. The developers keep talking about some domain something\-or\-another\. I’m not sure we need to get high centered on yet another technique or methodology, like it’s some kind of silver bullet\. I’ve heard all that a thousand times before\. We try, the fad dies, and we are right back to the same\-old same\-old\. I keep saying that we need to stay the course and stop dreaming, but the<a id="Why You Should Do DDD"></a> <a id="_bookmark21"></a>team keeps hounding me\. They’ve worked hard, so I owe them a listen\. *They are smart people and they all deserve a chance to improve things* before they get torqued and move on\. I could allow them some time to learn and adjust if I can get backing from upper management\. I think I could get that approval if I can convince my boss of the team’s claims of *achieving critical software investment and a centralization of business knowledge* \. Truth is, it will make my job easier if *I can do something to inspire trust and cooperation between my teams and business experts*\. Anyway, that’s what I am hearing I can do\.”

    Good manager\!

Whoever you are, here’s an important heads\-up\. To succeed with DDD *you are going to have to learn something*, and actually a lot of somethings\. That shouldn’t be a big deal, though\. You are smart and you have to learn all the time\. Yet we all face this challenge:

> Personally I’m always ready to learn, although I do not always like being taught\.   
&nbsp;&nbsp;&nbsp;  — Sir Winston Churchill

That’s where this book comes in\. I’ve tried to make the teaching as pleas\- ant as possible while delivering the vital understanding you need to implement DDD with success\.

Your question, though, is: “Why should I do DDD?” That’s fair\.
