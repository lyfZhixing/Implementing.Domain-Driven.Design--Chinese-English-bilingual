# How to Do DDD   
Let’s back away from heavy implementation discussions for a moment to con\- sider one of the most empowering features of DDD, the Ubiquitous Language\. It’s one of the two primary pillars of DDD’s strengths, the second being the __Bounded Context \(2\)__, and one cannot properly stand without the other\.

> __Terms in a Context__  
For now think of a Bounded Context as a conceptual boundary around a whole application or finite system\. The reason for this boundary is to highlight that every use of a given domain term, phrase, or sentence—the Ubiquitous Language—inside the boundary has a specific contextual meaning\. Any use of the term outside that boundary could, and probably does, mean something different\. Chapter 2 explains Bounded Context in depth\.

## Ubiquitous Language

The Ubiquitous Language is a shared team language\. It’s shared by domain experts and developers alike\. In fact, it’s shared by everyone on the project team\. No matter your role on the team, since you are on the team you use the Ubiquitous Language of the project\.

> __So, You Think You Know What a Ubiquitous Language Is__  
*Obviously it’s the language of the business\.*  
Well, no\.  
*Surely it must be adopting industry standard terminology\.*   
No, not really\.   
*Clearly it’s the lingo used by the domain experts\.*  
Sorry, but no\.   
*The Ubiquitous Language is a shared language developed by the team—a team composed of both domain experts and software developers\.*   
That’s it\. Now you’ve got it\!  
Naturally, the domain experts have a heavy influence on the Language because they know that part of the business best and may be influenced by industry stan\- dards\. However, the Language is *more centered on how the business itself thinks and operates*\. Also, many times two or more domain experts disagree on concepts and terms, and they are actually wrong about some because they haven’t thought of every case before\. So, as the experts and developers work together to craft a model of the domain, they use discussion with both consensus and compromise to achieve the very *best Language for the project*\. The team never compromises on the quality of the Language, just on the best concepts, terms, and meanings\. Initial consensus is not the end, however\. The Language grows and changes over time as tiny and large breakthroughs are achieved, much like any other living language\.       

This is no gimmick to get developers to be on the same page as domain experts\. It’s not just a bunch of business jargon being forced on developers\. It’s a real language that is created by the whole team—domain experts, developers, business analysts, everyone involved in producing the system\. The Language may start out with terms that are the natural lingo of the domain experts, but it isn’t limited to that because the Language must grow over time\. Suffice it to say that when multiple domain experts are involved in creating the Language, they often disagree ever so slightly on the terms and meanings of what they thought were already ubiquitous\.

In Table 1\.4, we not only model the administration of flu vaccines in code, but the team must also speak the Language openly\. When the team discusses this aspect of the model, they literally speak phrases such as “Nurses adminis\- ter flu vaccines to patients in standard doses\.”

There will be some haggling and wrangling over the Language that exists in the minds of experts and what evolves from there\. It’s all part of the nat\- ural progression of developing the best Language that will matter a lot for a long time\. This happens through open discussion, looking at existing docu\- ments, business tribal knowledge that finally surfaces, as well as referencing standards, dictionaries, and thesauruses\. There’s also a point reached where we come to terms with the fact that some words and phrases just don’t aptly fit the business context as well as we once thought, and we realize that others fit it much better\.
