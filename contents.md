# <a id="Contents"></a><a id="_bookmark0"></a>Contents

## [Chapter 1  Getting Started with DDD](#_bookmark13)   
- [Can I DDD](#bookmark15)

- [Why You Should Do DDD](#bookmark21)

- [How to Do DDD ](#_bookmark31)

- [The Business Value of Using DDD](#bookmark38)

    1. [The Organization Gains a Useful Model of Its Domain](#bookmark40)
    2. [A Refined, Precise Definition and Understanding of the Business Is Developed](#_bookmark41)

    3. [Domain Experts Contribute to Software Design](#_bookmark42)
    4. [A Better User Experience Is Gained](#_bookmark44)
    5. [Clean Boundaries Are Placed around Pure Models](#_bookmark45)
    6. [Enterprise Architecture Is Better Organized](#_bookmark46)
    7. [Agile, Iterative, Continuous Modeling Is Used](#_bookmark48)
    8. [New Tools, Both Strategic and Tactical, Are Employed](#_bookmark49)

- [The Challenges of Applying DDD](#_bookmark50)

- [Fiction, with Bucketfuls of Reality](#_bookmark60)

- [Wrap\-Up](#_bookmark64)

## [Chapter 2  Domains, Subdomains, and Bounded Contexts](#_bookmark66)

- [Big Picture](#_bookmark68)

    1. [Subdomains and Bounded Contexts at Work](#_bookmark70)

    2. [Focus on the Core Domain](#_bookmark76)

- [Why Strategic Design Is So Incredibly Essential](#_bookmark80)

- [Real\-World Domains and Subdomains](#_bookmark85)

- [Making Sense of Bounded Contexts](#_bookmark91)

    1. [Room for More than the Model](#_bookmark97)

    2. [Size of Bounded Contexts](#_bookmark100)

    3. [Aligning with Technical Components](#_bookmark103)

- [Sample Contexts](#_bookmark106)

    1. [Collaboration Context](#_bookmark108)

    2. [Identity and Access Context](#_bookmark115)

    3. [Agile Project Management Context](#_bookmark118)

- [Wrap\-Up](#_bookmark121)

## [Chapter 3 Context Maps](#_bookmark123)

- [Why Context Maps Are So Essential](#_bookmark125)

    1. [Drawing Context Maps](#_bookmark128)

    2. [Projects and Organizational Relationships](#_bookmark131)

    3. [Mapping the Three Contexts](#_bookmark135)

- [Wrap\-Up](#_bookmark150)

## [Chapter 4 Architecture](#_bookmark152)

- [Interviewing the Successful CIO](#_bookmark155)

- [Layers](#_bookmark160)

    1. [Dependency Inversion Principle](#_bookmark165)

- [Hexagonal or Ports and Adapters](#_bookmark168)

- [Service\-Oriented](#_bookmark174)

- [Representational State Transfer—REST](#_bookmark179)

    1. [REST as an Architectural Style](#_bookmark180)

    1. [Key Aspects of a RESTful HTTP Server](#_bookmark182)

    1. [Key Aspects of a RESTful HTTP Client](#_bookmark184)

    1. [REST and DDD](#_bookmark186)

    1. [Why REST?](#_bookmark188)


- [Command\-Query Responsibility Segregation, or CQRS](#_bookmark190)

    1. [Examining Areas of CQRS](#_bookmark192)

    1. [Dealing with an Eventually Consistent Query Model](#_bookmark200)

- [Event\-Driven Architecture](#_bookmark202)

    1. [Pipes and Filters](#_bookmark204)

    1. [Long\-Running Processes, aka Sagas](#_bookmark210)

    1. [Event Sourcing](#_bookmark216)

- [Data Fabric and Grid\-Based Distributed Computing](#_bookmark221)

    1. [Data Replication](#_bookmark223)

    1. [Event\-Driven Fabrics and Domain Events](#_bookmark225)

    1. [Continuous Queries](#_bookmark226)

    1. [Distributed Processing](#_bookmark228)

- [Wrap\-Up](#_bookmark231)

## [Chapter 5 Entities](#_bookmark233)

- [Why We Use Entities](#_bookmark235)

- [Unique Identity](#_bookmark237)

    1. [User Provides Identity](#_bookmark239)

    1. [Application Generates Identity](#_bookmark241)

    1. [Persistence Mechanism Generates Identity](#_bookmark246)

    1. [Another Bounded Context Assigns Identity](#_bookmark250)

    1. [When the Timing of Identity Generation Matters](#_bookmark252)

    1. [Surrogate Identity](#_bookmark254)

    1. [Identity Stability](#_bookmark257)

- [Discovering Entities and Their Intrinsic Characteristics](#_bookmark259)

    1. [Uncovering Entities and Properties](#_bookmark261)

    1. [Digging for Essential Behavior](#_bookmark266)

    1. [Roles and Responsibilities](#_bookmark272)

    1. [Construction](#_bookmark277)

    1. [Validation](#_bookmark279)

    1. [Change Tracking](#_bookmark286)

- [Wrap\-Up](#_bookmark287)

## [Chapter 6 Value Objects](#_bookmark290)

- [Value Characteristics](#_bookmark293)

    1. [Measures, Quantifies, or Describes](#_bookmark295)

    1. [Immutable](#_bookmark296)

    1. [Conceptual Whole](#_bookmark298)

    1. [Replaceability](#_bookmark302)

    1. [Value Equality](#_bookmark305)

    1. [Side\-Effect\-Free Behavior](#_bookmark307)

- [Integrate with Minimalism](#_bookmark311)

- [Standard Types Expressed as Values](#_bookmark314)

- [Testing Value Objects](#_bookmark320)

- [Implementation](#_bookmark325)

- [Persisting Value Objects](#_bookmark331)

    1. [Reject Undue Influence of Data Model Leakage](#_bookmark333)

    1. [ORM and Single Value Objects](#_bookmark335)

    1. [ORM and Many Values Serialized into a Single Column](#_bookmark338)

    1. [ORM and Many Values Backed by a Database Entity](#_bookmark340)

    1. [ORM and Many Values Backed by a Join Table](#_bookmark343)

    1. [ORM and Enum\-as\-State Objects](#_bookmark345)

- [Wrap\-Up](#_bookmark348)

## [Chapter 7 Services](#_bookmark350)

- [What a Domain Service Is \(but First, What It Is Not\)](#_bookmark353)

- [Make Sure You Need a Service](#_bookmark356)

- [Modeling a Service in the Domain](#_bookmark361)

    1. [Is Separated Interface a Necessity?](#_bookmark364)

    1. [A Calculation Process](#_bookmark368)

    1. [Transformation Services](#_bookmark372)

    1. [Using a Mini\-Layer of Domain Services](#_bookmark373)

- [Testing Services](#_bookmark374)

- [Wrap\-Up](#_bookmark376)

## [Chapter 8 Domain Events](#_bookmark378)

- [The When and Why of Domain Events](#_bookmark380)

- [Modeling Events](#_bookmark384)

    1. [With Aggregate Characteristics](#_bookmark390)

    1. [Identity](#_bookmark391)

- [Publishing Events from the Domain Model](#_bookmark394)

    1. [Publisher](#_bookmark395)

    1. [Subscribers](#_bookmark398)

- [Spreading the News to Remote Bounded Contexts](#_bookmark400)

    1. [Messaging Infrastructure Consistency](#_bookmark402)

    1. [Autonomous Services and Systems](#_bookmark404)

    1. [Latency Tolerances](#_bookmark406)

- [Event Store](#_bookmark409)

- [Architectural Styles for Forwarding Stored Events](#_bookmark412)

    1. [Publishing Notifications as RESTful Resources](#_bookmark413)

    1. [Publishing Notifications through Messaging Middleware](#_bookmark418)

- [Implementation](#_bookmark420)

    1. [Publishing the NotificationLog](#_bookmark422)

    1. [Publishing Message\-Based Notifications](#_bookmark426)

- [Wrap\-Up](#_bookmark433)

## [Chapter 9 Modules](#_bookmark434)

- [Designing with Modules](#_bookmark436)

- [Basic Module Naming Conventions](#_bookmark440)

- [Module Naming Conventions for the Model](#_bookmark441)

- [Modules of the Agile Project Management Context](#_bookmark445)

- [Modules in Other Layers](#_bookmark448)

- [Module before Bounded Context](#_bookmark451)

- [Wrap\-Up](#_bookmark452)

## [Chapter 10 Aggregates](#_bookmark453)

- [Using Aggregates in the Scrum Core Domain](#_bookmark455)

    1. [First Attempt: Large\-Cluster Aggregate](#_bookmark457)

    1. [Second Attempt: Multiple Aggregates](#_bookmark461)

- [Rule: Model True Invariants in Consistency Boundaries](#_bookmark464)

- [Rule: Design Small Aggregates](#_bookmark467)

    1. [Don’t Trust Every Use Case](#_bookmark470)

- [Rule: Reference Other Aggregates by Identity](#_bookmark473)

    1. [Making Aggregates Work Together through Identity](#_bookmark474)

    1. [References](#_bookmark474)

    1. [Model Navigation](#_bookmark476)

    1. [Scalability and Distribution](#_bookmark479)

- [Rule: Use Eventual Consistency Outside the Boundary](#_bookmark481)

    1. [Ask Whose Job It Is](#_bookmark484)

- [Reasons to Break the Rules](#_bookmark485)

    1. [Reason One: User Interface Convenience](#_bookmark487)

    1. [Reason Two: Lack of Technical Mechanisms](#_bookmark488)

    1. [Reason Three: Global Transactions](#_bookmark491)

    1. [Reason Four: Query Performance](#_bookmark492)

    1. [Adhering to the Rules](#_bookmark493)

- [Gaining Insight through Discovery](#_bookmark494)

    1. [Rethinking the Design, Again](#_bookmark496)

    1. [Estimating Aggregate Cost](#_bookmark498)

    1. [Common Usage Scenarios](#_bookmark500)

    1. [Memory Consumption](#_bookmark503)

    1. [Exploring Another Alternative Design](#_bookmark505)

    1. [Implementing Eventual Consistency](#_bookmark507)

    1. [Is It the Team Member’s Job?](#_bookmark509)

    1. [Time for Decisions](#_bookmark512)

- [Implementation](#_bookmark513)

    1. [Create a Root Entity with Unique Identity](#_bookmark514)

    1. [Favor Value Object Parts](#_bookmark517)

    1. [Using Law of Demeter and Tell, Don’t Ask](#_bookmark519)

    1. [Optimistic Concurrency](#_bookmark522)

    1. [Avoid Dependency Injection](#_bookmark525)

- [Wrap\-Up](#_bookmark527)

## [Chapter 11 Factories](#_bookmark529)

- [Factories in the Domain Model](#_bookmark531)

- [Factory Method on Aggregate Root](#_bookmark533)

    1. [Creating CalendarEntry Instances](#_bookmark535)

    1. [Creating Discussion Instances](#_bookmark538)

- [Factory on Service](#_bookmark539)

- [Wrap\-Up](#_bookmark543)

## [Chapter 12 Repositories](#_bookmark545)

- [Collection\-Oriented Repositories](#_bookmark548)

    1. [Hibernate Implementation](#_bookmark553)

    1. [Considerations for a TopLink Implementation](#_bookmark560)

- [Persistence\-Oriented Repositories](#_bookmark563)

    1. [Coherence Implementation](#_bookmark565)

    1. [MongoDB Implementation](#_bookmark571)

- [Additional Behavior](#_bookmark574)

- [Managing Transactions](#_bookmark577)

    1. [A Warning](#_bookmark582)

- [Type Hierarchies](#_bookmark583)

- [Repository versus Data Access Object](#_bookmark587)

- [Testing Repositories](#_bookmark589)

    1. [Testing with In\-Memory Implementations](#_bookmark591)

- [Wrap\-Up](#_bookmark594)

## [Chapter 13 Integrating Bounded Contexts](#_bookmark596)

- [Integration Basics](#_bookmark598)

    1. [Distributed Systems Are Fundamentally Different](#_bookmark600)

    1. [Exchanging Information across System Boundaries](#_bookmark602)

- [Integration Using RESTful Resources](#_bookmark607)

    1. [Implementing the RESTful Resource](#_bookmark610)

    1. [Implementing the REST Client Using an Anticorruption](#_bookmark614)

        a. [Layer](#_bookmark614)  

- [Integration Using Messaging](#_bookmark620)

    1. [Staying Informed about Product Owners and Team](#_bookmark622)

        a. [Members](#_bookmark622)

    1. [Can You Handle the Responsibility?](#_bookmark626)

    1. [Long\-Running Processes, and Avoiding Responsibility](#_bookmark629)

    1. [Process State Machines and Time\-out Trackers](#_bookmark635)

    1. [Designing a More Sophisticated Process](#_bookmark639)

    1. [When Messaging or Your System Is Unavailable](#_bookmark640)

- [Wrap\-Up](#_bookmark642)

## [Chapter 14 Application](#_bookmark644)

- [User Interface](#_bookmark648)

    1. [Rendering Domain Objects](#_bookmark650)

    1. [Render Data Transfer Object from Aggregate Instances](#_bookmark652)

    1. [Use a Mediator to Publish Aggregate Internal State](#_bookmark653)

    1. [Render Aggregate Instances from a Domain Payload Object](#_bookmark655)

    1. [State Representations of Aggregate Instances](#_bookmark658)

    1. [Use Case Optimal Repository Queries](#_bookmark659)

    1. [Dealing with Multiple, Disparate Clients](#_bookmark661)

    1. [Rendition Adapters and Handling User Edits](#_bookmark663)

- [Application Services](#_bookmark666)

    1. [Sample Application Service](#_bookmark668)

    1. [Decoupled Service Output](#_bookmark675)

- [Composing Multiple Bounded Contexts](#_bookmark678)

- [Infrastructure](#_bookmark681)

- [Enterprise Component Containers](#_bookmark683)

- [Wrap\-Up](#_bookmark685)

## [Appendix A Aggregates and Event Sourcing: A\+ES](#_bookmark687)

- [Inside an Application Service](#_bookmark690)

- [Command Handlers](#_bookmark699)

- [Lambda Syntax](#_bookmark704)

- [Concurrency Control](#_bookmark706)

- [Structural Freedom with A\+ES](#_bookmark707)

- [Performance](#_bookmark709)

- [Implementing an Event Store](#_bookmark712)

- [Relational Persistence](#_bookmark716)

- [BLOB Persistence](#_bookmark718)

- [Focused Aggregates](#_bookmark721)

- [Read Model Projections](#_bookmark723)

- [Use with Aggregate Design](#_bookmark725)

- [Events Enrichment](#_bookmark727)

- [Supporting Tools and Patterns](#_bookmark729)

    1. [Event Serializers](#_bookmark730)

    1. [Event Immutability](#_bookmark732)

    1. [Value Objects](#_bookmark734)

- [Contract Generation](#_bookmark737)

- [Unit Testing and Specifications](#_bookmark739)

- [Event Sourcing in Functional Languages](#_bookmark741)

## [Bibliography](#_bookmark743)

## [Index](#_bookmark744)