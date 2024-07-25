# Overview Django development

## References
* [ ] Becoming an enterprise Django developer: Chapter 1/2

## Types of enterprise systems

Enterprise Application Software (EAS)

Types of enterprise systems: There are many different kinds of enterprise-level systems but we can consolidate them into six major categories

* **Customer Relationship Management (CRM)**: CRM systems can typically be thought of as lead management, marketing communications, sales and inventory control, retail management, and so much more. The systems can be thought of as everything but the actual selling of products and services. They can even go further to include customer support and data analytics. These systems are designed to develop better relationships with your business partners, customers and potential customers, and anyone else in the equation.
* **Enterprise Content Management (ECM)**: An ECM system can best be described as a system for people working in fields that deal with creative and other intellectual property in some kind of way. Newspapers, magazines, and other news companies today have a great deal of content that they make available to the internet on a daily basis. A Content Management System (CMS) provides a less technical and rapid way to build new pages and enter that content onto the web. Enterprise level just means you are adding more and more tools to your toolbox for your organization to use.
* **Enterprise Asset Management (EAM)**: In an EAM system, products and inventory of all kinds can be entered into a system in the same way as a CMS. This is often known as an e-commerce or shopping cart website. It's where you make your physical goods and assets available online. These systems allow the tracking of inventory, project management, and document control, such as contracts and other legal documents. These systems may even consist of physical assets, such as real estate, automobiles, and music records
* **Enterprise Resource Planning (ERP)**: An ERP system is typically thought of as a way to manage people, the employees of the company, or what is commonly known as the Human Resources (HR) department. The system can handle on-boarding and off-boarding procedures and store all personnel records. It could serve as a tool for project management, risk assessment, and record keeping. It can even serve as a knowledge base such as in the form of the Frequently Asked Questions (FAQs) area. A knowledge base is often used to point people to and have them find common questions and answers in order to reduce the workload on your staff. These can also be used for training purposes, such as generating quizzes or asking trivia questions and playing tutorials.
* **Supply Chain Management (SCM)**: SCM systems are similar to CRM and EAM systems. These are systems that manage inventory in every aspect of its development in the supply chain. These systems manage inventory on a national or even a global scale. They communicate with suppliers, connect to buyers, track packages, predict future supply orders, and may even automatically place those orders. One way to look at the difference between a CRM and SCM system is that a CRM is mostly used for sales and marketing while an SCM is mostly used for production and distribution. Both deal with products but in different ways and a large company or a conglomerate would need both.
* **Enterprise Information System (EIS)**: An EIS is a system that generally combines a CRM and SCM system to handle a wider range of business needs. An EIS may even integrate some or all of an ERP system and act as one giant central nervous system. Depending on the needs, this may consist of numerous databases and even numerous development projects all working together, comprising the brains of everything. These systems are known for storing and processing large volumes of data and connecting many different systems all together into one.

## Why Python/Django?
Django's features include the following
* Caching framework
* Data serialization
* Extensibility
* Form handling and validation
* Scalability
* Security
* Template language
* Testing framework

## Types of APIs
An API is a means for two systems to communicate with each other through what are known as endpoints or a URL.

We can categorize APIs into three main categories:
* **Open:** Open APIs are open to the public and are sometimes referred to as an external API. This typically means there are no restrictions and anyone can be granted access. Sometimes, a simple registration or API key may be required before developers can gain access but they usually have the freedom to do with it as they wish. These APIs can be open bidirectionally as well, meaning the system is open for all GET, POST, PUT, PATCH, and DELETE requests coming to and from your system.
* **Private:** Private APIs are the most secure; these APIs are locked down because they are intended to be used internally by that company or organization only. Large financial institutions or corporate retail entities may use these to manage any aspect of their internal functions. The public and any other external sources may not be granted access unless a specific need for it is warranted. Common examples are government organizations using APIs to connect to systems that keep legal records and documents. Another example could be a university granting an educational department access to student and class records.
* **Partner:** Partner APIs are commonly found in business-to-business relationships. The general public cannot gain access and permission is only granted to strategic partners who need to use your API in order to do business with you. Limitations can be defined depending on your agreements with each party. These are fairly common in the world today when business mergers occur and your team is tasked with making two external systems communicate with each other. Sometimes, you have to build a central database in between the two existing systems for various reasons, such as your business model is based on granting access to your API in order for companies to sell their goods on your platform. A common example of this is the Amazon Selling Partner API (SP-API), which is used for selling goods on the Amazon Marketplace

## Designing and planning
Every project, however big or small, needs a clear plan for what it is and how it will be built. The larger the project, the more work should be put into the beginning phase of preparing for development. It is no surprise that enterprise-level development should also require a great deal of preliminary work before actual development begins. Whether you are working for a company or are a company providing a solution to a client, you should have a clear plan of what needs to be done. There is a lot of flexibility here based on factors such as cost, lack of developers, and deadlines. Prepare as much as possible and try to stick to the timelines that are set to keep you on track to completion. Remember that too little planning could come back to haunt you later.

Developers should be given as much information as possible to help them understand what they are building. If your developers are not provided with enough documentation, blueprints, and other materials, then they will be left to make assumptions on their own, assumptions that later on are found in the testing and Quality Assurance (QA) phases of development as bugs in your application. When this happens, you may discover that a particular feature needs to be rebuilt, requiring major foundational changes that will take a great deal of time to refactor. If we think about something other than programming for a moment, such as building a house, we all know a foundation needs to be built before a team can frame the house. In turn, that foundation needs to be completed before a team can build the roof, wire up the electrics, install plumbing, and so on. You can't start building a roof without a frame, and you can't build a frame without a foundation to put it on.

### Requirements gathering
Gathering requirements is important to help document the build process and to allow both parties, the developer and the owner of the software, to reference it at any time during development. This ability is essential in order to ensure things stay on track until completion and are also completed on time. There should be an initial brainstorming phase to get a feel for the scope of the project. One good trick is to have all the stakeholders get together and debate the needs of the system, while you record any key points raised during the debate and include them in your requirements findings. You should always start by asking questions, and you should ask alternate questions for different sets of people. After you have spoken to stakeholders, move on to directors, project managers, developers, and employees, known as end users. Interview as many different types of users as possible. For extremely large entities, you could create a questionnaire, distribute that questionnaire to a number of users, and then come to a conclusion based on the results.

Research and discovery:
* Do you have business-specific requirements?
* Why do you need a new system?
* What does your current system prevent you from doing; are there any bottlenecks?
* What new features would you like to add; do you need any improvements?
* What old features would you like to keep or remove?
* Who will you interact with in the system; what types of users and roles?
* Will you need reporting, email messaging, or any other kind of notification system?
* Will the system connect with any third-party or partner systems in any way?
* What kind of traffic or load on the server are we predicting?
* When does this new system need to be operational?
* What kind of budget have you allocated toward completing this project?
* Will data need to be migrated from the old system to the new system?
* How will development be divided up among the development team members?
* What skills does the development team have; what are the team's strengths and weaknesses?
* How should the User Interface (UI) flow work; should it be multipage or single page?

Decision making

### Visualization and interpretation
There are many different diagram types in the Unified Modeling Language (UML):
* **Activity diagram:** A class diagram is used to illustrate the different classes or components of a system and how they relate to each other. A class is best known as a group of objects with shared or similar roles within your system. Similar to an Entity Relationship Diagram (ERD), class diagrams depict the objects that would be tables in a database, the interactions that could take place, and any other main elements of your system. This diagram is usually structured in a way where the top compartment is the class name, the middle compartment contains all the attributes, also known as the fields, and the bottom compartment shows any functions or actions that could take place.
* Class diagram
* Communication diagram
* Component diagram
* Composite diagram
* **Deployment diagram:** A deployment diagram is used for high-level planning. This is how developers will collaborate and code will be updated between different environments. Network engineers will use the diagram to map out physical nodes that will be used within their configuration. Developers will use it to have a better understanding of how code will update between different environments and where they may need to push or pull that code to and from when updates need to be made. The primary components of a deployment diagram include artifacts, devices, and nodes:
  * An artifact is a digital asset, such as a file or an executable script of some kind.
  * A device is a node that represents a computational resource, such as the application server or the domain server
  * A node is a physical entity that executes a component, subsystem, or process. Nodes can comprise a physical hardware component or a virtual, cloud-based component.
* **Entity relationship diagram:** An ERD visualizes the relationships between objects within your system. It's best used for mapping how different tables are linked within a database and is sometimes called an entity relationship model after modeling relationships in a database. These are used by your backend to help create the structure of the database and what fields should be included. On the other hand, these can be created by accessing existing databases to help map the current structure of a system and help you to see how best to rebuild it. It's like accessing blueprints of an existing building. Auto-generating these can mean they are so accurate that they even tell you about renovations done to that building after those initial blueprints were first drafted.
* **Flowchart:** Flowcharts represent the flow of data within the system. They provide a step-by-step approach to solving a particular problem or task. These diagrams are used by developers to gain an understanding of what rules apply when writing code. Rules can include logic such as data validation scenarios before proceeding to the next step. Flowcharts can be simple to fairly complex, and often provide decisions the user can make along the way. T
* Interaction diagram
* Object diagram
* Package diagram
* Profile diagram
* Sequence diagram
* **State diagram:** A state diagram shows the behavior of objects within a system. The diagram shows possible conditions or states that something can be in at any given time, such as depicting whether a user is either logged in or logged out; an order is either received, processing, or out for delivery, or an order is fulfilled or returned. These are great for showing a particular shift in behavior versus decisions that can be made. They may even depict certain triggers that cause a state to change as an operation moves through its life cycle toward completion
* Timing diagram
* **Use case diagram:** A use case diagram represents the behavior of a user and the system. These are fairly similar to a flowchart but often focus on the bigger picture. These are used by teams such as the creative department, stakeholders, project managers, and directors, to help understand the concept of what this particular flow or use case will do.

## Hosting and deployment
## Development tools
## Starting a project
## Creating a virtual environment
## Project configuration
## Using basic database settings
## Preparing PostgreSQL for Heroku