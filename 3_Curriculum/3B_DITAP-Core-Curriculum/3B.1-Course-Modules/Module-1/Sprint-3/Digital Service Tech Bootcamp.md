# Module 1 Sprint 3

## Introduction to the Digital Service Tech Bootcamp

Modern government acquisition professionals operate in a rapidly evolving digital environment. Whether you're evaluating a cloud-based platform, reviewing a data-sharing agreement, or procuring custom software development, your work increasingly intersects with key technology concepts that shape how agencies deliver public services.

This module introduces five essential digital service topics—data, software, cloud computing, artificial intelligence, and cybersecurity—with a focus on how these topics directly impact your role as an acquisition professional. 

* Data is the foundation of digital services; it's collected, stored, and analyzed to inform decisions, measure impact, and improve government operations. Procurement supports this by sourcing tools and services for managing and protecting data.  
* Software refers to the programs that run on computers or in the cloud to help agencies operate efficiently. Procurement plays a key role in acquiring, licensing, and maintaining the right software to meet mission needs.  
* Cloud services allow agencies to rent computing power, storage, and tools over the internet instead of maintaining physical servers. Procurement must structure contracts to align with flexible, scalable cloud service models.  
* Artificial Intelligence (AI): AI uses algorithms to analyze data, automate tasks, and generate insights that support faster, smarter decisions. Procurement may support AI initiatives by acquiring ethical, compliant AI tools and ensuring proper data use.  
* Cybersecurity protects government systems and data from threats like hacking or data breaches. Procurement ensures that systems and services meet security standards and include appropriate safeguards.

You don't need to be a technical expert, but understanding the fundamentals will help you write better requirements, evaluate vendor capabilities, and ensure contracts support secure, effective, and user-centered digital services.

The lessons ahead will explain terminology, describe modern delivery models, and highlight practical implications for acquisition planning, vendor engagement, and contract oversight.

---

By the end of this module, you will be able to:

* Describe the differences between structured, unstructured, and semi-structured data, and explain why those distinctions matter for procurement and contract oversight.

* Identify key challenges and modernization needs related to data storage, migration, analytics, and privacy in federal systems.

* Explain the software development lifecycle (SDLC) and modern practices like Agile, DevOps (development and operations), and Continuous Integration and Continuous Delivery (CI/CD), and recognize their relevance in acquisition strategies.

* Differentiate between proprietary and open-source software licenses, and understand the implications of software supply chain security.

* Define cloud computing and distinguish between public, private, community, and hybrid cloud deployment models.

* Explain the differences between Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS), and assess what kind of cloud service model a contract may require.

* Recognize cloud-specific procurement considerations, including pricing models, shared security responsibilities, vendor lock-in risks, and Federal Risk and Authorization Management Program (FedRAMP) compliance.

* Understand the basics of cybersecurity as it applies to acquisitions, including compliance frameworks (e.g., National Institute of Standards and Technology \[NIST\]), identity and access management (IAM), vulnerability management, and Security Incident and Event Management (SIEM).

---

## Digital Service Tech Topic: Data

### What Is Data?

Data is just information that’s been collected and stored (“recorded”). It can come in many forms—numbers in a spreadsheet, written text in emails, pictures, or even audio and video. In government contracting, examples of data include:

* Contractor performance records  
* Purchase histories  
* Budget logs  
* Emails between vendors and agencies

There are three main types:

1. **Structured Data**: Organized in a way that computers can easily process, regardless of whether a human can easily read it, like Excel sheets or databases.  
2. **Unstructured Data**: Organized in a way that humans can easily process, but not organized for computers to process the information, like PDF documents or social media comments.  
3. **Semi-Structured Data**: Somewhere in between, like webpages, which are human readable and are tagged so that computers can easily process them, with varying levels of granularity or structure.

Think of a contracting file that includes emails, PDFs, performance reviews, and a payment history—that’s a mix of structured and unstructured data.

### Key Considerations for Government Systems

As data grows in size and complexity, there are more challenges related to data storage, data transfer, and data processing:

* Old systems may slow down or fail under the weight  
* Data must often be moved between different clouds, networks, or storage areas—which can cause delays or added costs  
* Network upgrades and smarter designs are sometimes needed to keep up with demands  
* New data processing techniques or tradeoffs may be needed as data volumes increase  
* Ensuring data accuracy and forward/backward compatibility for different use cases can become complex

Learn more about data analysis by visiting [this page](https://www.coursera.org/articles/data-analysis-tools). 

These are some of the key challenges that are driving agency modernization efforts today, and are likely to come across your desk as an acquisition professional. 

Modern systems need to move data across clouds, networks, and apps. That creates bottlenecks unless you’ve planned for it.

Old databases weren’t built for the amount of data we use today. That’s like trying to run modern apps on a flip phone— the hardware would struggle to work correctly.

You may want to change data or delete it over time, but there may be practical or legal reasons not to. (E.g., System for Award Management (SAM.gov) “Federal Procurement Reports” from 2007… useful? Not really. But should it be *deleted?* Probably not.) 

As a contracting officer, you will likely encounter a variety of “buzz words”/topics related to data in your work, here are a few that are particularly relevant today: 

* **Data modernization**: The process of updating and transforming data systems, infrastructure and practices to modern, cloud-based formats to enhance accessibility, security and business intelligence.   
* **Data migration**: The process of transferring data from one storage system or computing environment to another.   
* **Data analytics**: The process of collecting, transforming, and organizing data in order to draw conclusions, make predictions, and drive informed decision making.   
* **Data Lake**: A data lake is a centralized repository designed to store, process, and secure large amounts of structured, semistructured, and unstructured data. It can store data in its native format and process any variety of it, ignoring size limits.  
* **ETL (Extract, Transform, Load)**:  A data integration process that combines, cleans, and organizes data from multiple sources into a single, consistent dataset for storage in a data warehouse or other target system.   
* **Data Provenance**: The historical record of data that details data’s origins by capturing its metadata as it moves through various processes and transformations. Data provenance is primarily concerned with authenticity, providing details such as who created the data, the history of modifications, and who made those changes.


### Open Data

Open Data is information that anyone can access, use, and share. In the context of government, this has two dimensions: 

1. The ability for someone to *access* the data  
2. The legal right for the user to use the data

Generally, Open Data also refers to non-sensitive public information made available in data *formats* that are easy to use, reuse, and republish.

Many government entities, from local to federal to international, provide data sets to data.gov and/or operate their own open data websites so that information generated may be shared and utilized by the public. There are many open data sets, ranging from government operations data (e.g., Federal Procurement Data System (FPDS)) to data “products” (e.g., Census survey data tables).

Outside of government, open data can also refer to a movement to provide open access and use of the massive amounts of projects and data being developed every day in commerce, science, and technology in order to promote progress and innovation, and improve the accountability of both private and public institutions.

Why It Matters to Procurement Officers:

1. **Licensing**: Procurements that potentially involve open data require consideration of the relative intellectual property / data rights.  
2. **Privacy**: Open data can—in some cases—implicate privacy concerns, particularly when combined with other open data sets. Understanding how data is published and ensuring that contracts have adequate remedies for privacy violations is important for contracting officers.  
3. **Efficiency**: Understanding how open data can be used to improve data publication and use can reduce duplication of effort and allow for more efficient use of government and non-government data.

### Data Privacy

Data Privacy means protecting personal or sensitive information so that only people who are supposed to see it can access it. This includes things like social security numbers, health records, or confidential contract data.

Why It Matters to Procurement Officers:

1. **Legal Compliance**: You must follow privacy laws like the Privacy Act of 1974 and agency-specific policies to protect personal information collected during procurement processes.  
2. **Risk Management**: Mishandling private data could lead to security breaches, legal penalties, and loss of public trust.  
3. **Contract Integrity**: Some procurement data may contain sensitive vendor information. Protecting this data ensures fair competition and integrity of the procurement process.

For example, if your office is collecting contractor tax IDs or employee background checks, that data must be stored and shared securely to prevent unauthorized access.

### What Contracting Officers Should Keep in Mind:

* Understand what data your systems hold and how it’s organized.  
* Ask vendors how they handle data—especially if Artificial Intelligence (AI) or analytics are part of the service.  
* Support modernization efforts that improve how data is stored and accessed across departments.

As a contracting officer, you are both a data user and a data steward. You should know:

* What data can and should be **shared openly** (e.g., awarded contracts).  
* What data must be **protected** (e.g., personally identifiable information or confidential business information).  
* The **laws and best practices** that guide both.

---
## Digital Service Tech Topic: Software

### What is software?

Software refers to the instructions, data, or programs that enable computers and digital systems to perform specific tasks. Informally, software tells computer hardware how to do something useful with data. It includes human-readable instructions, known as source code, and machine-readable instructions compiled for the computer to execute.

>CO note: It may be necessary to clarify whether the government can access the source code or compiled software. Access to source code may be required under FAR clauses like 52.227-14 (Rights in Data), or via specific IP clauses negotiated in contracts—especially for custom software. Agencies can specify unlimited, government purpose, or restricted rights in deliverables, depending on mission needs.

### How is software developed?

Understanding how software is developed helps procurement professionals recognize what they're buying, how to evaluate progress, and what kinds of contract structures best support successful delivery. This section introduces the software development lifecycle, modern methodologies like Agile, the roles involved, and key concepts such as the software supply chain.

The Software Development Lifecycle (SDLC) is the process organizations use to plan, design, develop, maintain, and eventually retire software systems. Approaches to SDLC range from traditional "waterfall" methods, where each phase is completed sequentially, to more modern, iterative approaches like Agile. Agile methodology focuses on building and delivering functional software in small, manageable increments. Different Agile approaches include Scrum, where teams work in short, time-boxed sprints, and Kanban, which emphasizes continuous delivery with strict limits on work in progress to maintain flow.

A central principle of modern software development is the importance of iteration, prototyping, and feedback loops—testing ideas early, learning from users, and continuously improving. For example, the U.S. Digital Service and VA used Agile and iterative development to improve the VA.gov website, releasing updates in small increments based on honest user feedback. They also leveraged open-source libraries and maintained a Software Bill of Materials (SBOM) to track components and ensure security compliance. OMB Memo M-22-18 and NIST’s Secure Software Development Framework (SSDF) now require SBOMs and secure development attestations from software vendors—making SBOMs a federal policy expectation in many software contracts.

Instead of building everything from scratch, developers commonly use packages and libraries—prewritten code modules created by others—to speed up development and improve reliability. However, this practice introduces potential security, licensing, and maintenance risks. As a result, tools like SBOMs are becoming essential, helping organizations manage their software supply chain more effectively.

### How is software delivered?

Software can be delivered in several ways, depending on user needs, organizational infrastructure, and security considerations. One standard method is running software locally, where it is installed directly on a user's device, such as a laptop or desktop, and does not require a constant internet connection. For example, tools like Microsoft Excel can be installed and run entirely on a user’s local machine without an internet connection. 

In more controlled environments, software may be hosted on-premises, meaning it runs on servers that an organization owns and maintains, often in physical data centers. For instance, the Department of Energy (DOE) operates sensitive, high-performance computing systems in dedicated, on-premises data centers to meet strict security and performance requirements. 

Increasingly, software is delivered as a service, hosted on third-party cloud infrastructure ("other people’s servers") and accessed over the internet. This includes models such as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). 

Finally, software can be delivered as an app and downloaded via app stores to user devices. These apps often rely on cloud services to provide real-time data, updates, and functionality while offering a convenient user interface on mobile or desktop platforms.

### How is software updated?

Modern software isn’t built once and left alone—it’s regularly updated to fix bugs, add new features, and improve security. To manage this, software teams use practices that help them make changes quickly and safely.

One common practice is **Continuous Integration and Continuous Delivery (CI/CD).** This means developers regularly add their code to a shared system, where automated tools check the code and prepare it for release. These tools also run tests to ensure the changes don’t break anything. As a result, working software can be updated more frequently and with greater reliability.

Developers use a **version control system**, the most common one being Git, to keep track of changes. It helps teams see who made what change, roll back to earlier versions if needed, and collaborate on the same code without overwriting each other’s work. Platforms like GitHub and GitLab build on Git to make this process easier.

Testing is critical to updating software. **Automated testing tools** check for problems every time a change is made. These tests can include basic functionality, how different parts of the system interact, how the software handles heavy use, and whether it meets security standards. Even though many tests are automated, some types of testing—like checking for accessibility or ease of use—still need a human touch.

Before updates reach the end users, the software usually moves through several **environments.** These might include a development environment (where the code is written), a testing environment (where changes are checked), a staging environment (which mimics the live system), and finally, the production environment (used by real users). This process helps catch any issues before the update goes live.

Teams also use techniques like **canary testing** and **feature flags** to manage risk. Canary testing means rolling out a new software version to a small group of users first. If it works well, the update is released more broadly. Feature flags allow developers to turn specific features on or off without changing the code. This helps teams test features gradually or run A/B tests to compare performance.

#### Why updates matter—and how they stay safe

Frequent updates help agencies respond quickly to user needs and changing requirements. But they also come with tradeoffs. Updates can introduce new problems or confuse users if not communicated well. That’s why finding the right balance between moving fast and keeping systems stable is essential.

Security is another key reason software needs regular updates. Updates often include patches for known vulnerabilities and help systems comply with federal security policies, like FedRAMP or NIST standards. Agencies should plan for ongoing updates as part of the delivery process, not as an afterthought.

#### How teams monitor and respond to problems

After software is deployed, teams don’t just walk away—they monitor its performance in real time. They use monitoring tools to track uptime, response time, and error rates. Standard tools include Datadog, Prometheus, and AWS CloudWatch. These insights help teams decide when to update or improve the system.

If something goes wrong, teams rely on incident response plans. These plans include steps for rolling back bad updates, recovering data, and communicating with stakeholders. Having clear procedures in place helps minimize downtime and protects user trust.

### Considerations around supply chain and licensing

When buying or managing software, it's essential to understand what’s behind the hood. Most modern software isn’t built from scratch—it’s assembled from many parts, including third-party libraries, open-source tools, proprietary code, and deployment tools. This collection of components is often referred to as the **software supply chain.**

If agencies or vendors don’t track these components correctly, it can lead to hidden vulnerabilities, licensing conflicts, or even security breaches. For example, the **SolarWinds cyberattack**—a significant event that affected several federal agencies—exploited weaknesses in the software build process. This incident showed how risky it can be when dependencies and tools aren't properly managed or monitored.

One way to manage this risk is through a **Software Bill of Materials (SBOM)**. An SBOM is like a parts list for software—it shows all the libraries, packages, and tools that make up a system. Many federal agencies now require vendor SBOMs because they help track vulnerabilities and support a faster response when issues arise. This requirement is reinforced by OMB M-22-18 and NIST SSDF guidance.

Contracting officers and acquisition professionals should also ask vendors about **risk management practices.** Are they scanning for vulnerabilities? Do they patch or replace risky components? Do they follow secure development practices? These questions are essential to ensure that the software delivered is safe and dependable.

Licensing is another key consideration. Software licenses set the rules for how software can be used, shared, or changed. There are two main types: **proprietary licenses** and **open-source licenses.**

**Proprietary licenses** usually come with restrictions and fees. Agencies don’t get access to the source code and must rely on the vendor for support and updates. Common examples include Microsoft Office or Salesforce. In contrast, **open-source licenses** generally allow for more flexibility. They let agencies use, change, and distribute software freely, though some licenses require that changes be shared publicly. For instance, the Apache 2.0 license is relatively permissive, while the GNU General Public License (GPL) has stricter conditions.

These licensing choices affect more than legal compliance—they impact cost, flexibility, and long-term strategy. While open-source tools may reduce licensing costs, they still require investment in support and integration. Open-source software can be customized, while proprietary tools may be more complex to adapt. Failure to follow the terms of a license, especially with open-source software, can lead to contract issues or legal trouble.

Finally, agencies should consider the risk of **vendor lock-in,** when switching providers becomes difficult or expensive. This can happen if the vendor uses proprietary formats, doesn’t allow access to data, or doesn’t follow open standards. When reviewing a procurement, it’s worth asking: Does the software use open standards? Will we be able to access and export our data? Could another vendor take over if needed? APIs and modularity can help avoid lock-in, and they support DevSecOps, interoperability, and zero-trust architecture. APIs should follow open standards (e.g., OpenAPI) and be well-documented, often as required deliverables in contracts.

By considering these factors, 1102s can make better-informed decisions that reduce risk, support flexibility, and help agencies maintain control over their software assets.

### Service design and delivery standards (21st Century IDEA & USDS Playbook)

Modern software isn’t just about code—it’s about delivering effective services that meet user needs, comply with the law, and adapt over time. The 21st Century Integrated Digital Experience Act (IDEA) and the U.S. Digital Services Playbook set specific expectations for how software supporting government services should be designed and delivered.

Contracting officers should understand these frameworks to write solicitations that support human-centered, standards-compliant digital service delivery. Section 280 of the FY2023 NDAA also promotes modular contracting and HCD in acquisition planning—making it easier for agencies to build flexible, responsive digital tools.

When federal agencies build or buy digital services, focusing on the people who will use them is critical. This approach is called **Human-Centered Design (HCD).** It means engaging with users throughout the development process—not just at the beginning or the end—to ensure the product meets their needs. Human-centered design focuses on the needs, behaviors, and feedback of end users of a product or service. Consider making user research a contract deliverable, including usability testing, accessibility audits, and multiple feedback loops to validate success.

HCD places special emphasis on **accessibility, usability, and continuous feedback.** Digital tools should be easy for everyone, including people with disabilities. That’s where **Section 508 compliance** comes in, requiring things like screen reader compatibility, keyboard navigation, and appropriate color contrast. But accessibility alone isn’t enough—systems should be usable and continually improved based on real-world feedback. Agencies can achieve this by building in regular user testing, collecting performance data, and listening to feedback.

Contracting officers can help by shaping procurements to support these practices. Instead of static, one-time requirements, solicitations should encourage **iterative research and design.** This might mean asking vendors to include user researchers and designers on their teams or to plan for multiple testing and feedback cycles as part of their delivery.

**Modular development** and **API-driven architecture** are other key strategies for building flexible, user-friendly systems. Modular development breaks large systems into smaller, usable parts that can be delivered and improved over time, rather than waiting years for a final product. Meanwhile, **APIs** (Application Programming Interfaces) allow different systems to talk to each other. This makes integrating commercial tools, in-house software, and legacy systems easier, while avoiding vendor lock-in. These strategies align with modern cloud and DevSecOps practices, and support faster, more secure delivery.

Strong **performance and usability standards** are also essential. Systems should respond quickly, handle expected workloads, and navigate easily. Agencies may track things like the number of transactions a system handles each day or how long it takes for a page to load (e.g., 95% of responses under 500 milliseconds).

Finally, **continuous improvement** should be part of any technology investment. This means monitoring systems for performance and problems, collecting data on how users interact with the service, and using that data to guide future updates. Combining **quantitative** **analytics** (like page views or error rates) with **qualitative research** (like interviews and surveys) gives a fuller picture of how well a system works and how to improve it.

By prioritizing user needs, accessibility, and flexibility, agencies can deliver effective and inclusive digital tools. Acquisition professionals play a key role in this process.


---

## Digital Service Tech Topic: Cloud

### Basics

Cloud computing offers a flexible and efficient way for federal agencies to manage their IT needs. Rather than relying entirely on traditional data centers, agencies can turn to a wide range of cloud services provided by various vendors. There isn’t just one “cloud”—cloud computing refers to a model of accessing shared computing resources like storage, servers, and applications over the internet. 

According to the National Institute of Standards and Technology (NIST), a true cloud service must offer five key features: 

1. On-demand self-service  
2. Broad network access  
3. Resource pooling  
4. Rapid elasticity  
5. Measured service

These characteristics allow agencies to access computing resources when they need them, from almost anywhere, and scale usage up or down depending on demand—all while tracking and managing usage.

![Diagram illustrating the 5 essential characteristics of cloud computing: On-Demand Self-Service, Broad Network Access, Resource Pooling, Rapid Elasticity, and Measured Service, all stemming from a central cloud icon.](https://github.com/kristenjernigan/kj-liatest/blob/f0fd8784f6f47867fcb0a56b1646925ca7e9ac4d/Media/Module%201/5%20essentials%20cloud.png) 

https://cic.gsa.gov/basics/cloud-basics

Cloud computing can be deployed in several different ways: 

* **Public clouds** are managed by a third-party provider and serve multiple customers.   
* **Private clouds** are dedicated to a single agency or organization.   
* **Community clouds** are shared between agencies with similar requirements.   
* **Hybrid clouds** combine two or more of these types, allowing for greater flexibility and control.

Cloud services also come in different models, depending on what level of service the agency needs: 

* **Software as a Service (SaaS)** delivers ready-to-use applications over the internet.   
* **Platform as a Service (PaaS)** provides a platform for developers to build and deploy applications without managing the underlying hardware.   
* **Infrastructure as a Service (IaaS)** offers raw computing resources such as servers and storage, which agencies can configure and control as needed. 

These service types are often used together depending on the agency’s goals.

One of the key benefits of cloud computing is its pricing and scalability model. In a traditional data center setup, agencies must estimate and purchase all the computing power or storage they might need in advance. This often results in underused resources when traffic is low and insufficient capacity when traffic is high. With cloud computing, agencies only pay for what they use, and they can increase or decrease capacity as needed.

It’s also important to understand that security and management responsibilities are shared in cloud environments. In traditional data centers, the agency is responsible for every aspect of IT security and maintenance. In cloud environments, some responsibilities—such as physical security or infrastructure updates—fall to the cloud vendor, while others remain with the agency. This division varies by cloud vendor and by service type, so contracting officers should pay close attention to the terms and service models when evaluating proposals or monitoring vendor performance.

### Considerations

Cloud computing is fundamentally different from traditional data center operations, and applying old practices to cloud environments can lead to inefficiencies and unnecessary costs. Cloud services are purchased and managed differently, requiring agencies to train staff in cloud-native practices. Fortunately, major cloud vendors offer training to help agencies manage usage and costs effectively. Without this knowledge, agencies risk overspending and misconfiguring services.

Security concerns often deter cloud adoption, but cloud platforms are generally secure when implemented correctly. Most breaches result from human error—not cloud vulnerabilities. Agencies should follow their security policies and use best practices like strong identity and access management (IAM), vulnerability management, and Security Incident and Event Management (SIEM) tools. They should also work directly with vendors to ensure cloud-specific security configurations.

Not all cloud vendors are the same—each has strengths and weaknesses. Agencies can use one as a primary provider and others as backups, as long as systems are built for flexibility and resilience. Vendor lock-in is less of a risk in the cloud than in traditional IT, and thoughtful architecture can simplify migration between platforms.

Using Federal Risk and Authorization Management Program (FedRAMP)-authorized services can streamline security approvals and ensure compliance with federal standards. Lastly, agencies must ensure that cloud solutions follow vendor-recommended best practices for architecture, deployment, and emerging technologies like AI/ML. Poor implementations by contractors using outdated approaches often result in high costs and technical debt. Getting it right from the start helps ensure secure, efficient, and scalable cloud operations.

### Why Understanding Cloud Computing Is Critical for Government Contracting Officers

#### 1\. Cloud Procurement is Fundamentally Different

Contracting for cloud services is not like buying traditional IT hardware or managing a data center:

* Cloud services are dynamic — agencies buy elastic, scalable services, not fixed assets.  
* Service catalogs change and grow frequently – agencies should ensure they have access to new and emerging services without having to renegotiate or pursue contract modifications.    
* Payment models differ — cloud uses "pay-as-you-go" structures rather than upfront capital expenditures.  
* Management expectations change — agencies must adapt their oversight to a shared responsibility model between the cloud vendor and agency.

If contracting officers apply traditional procurement models to cloud, it can lead to:

* Wasteful spending  
* Unfulfilled mission needs  
* Higher security risks  
* Vendor performance issues

Understanding the *unique nature* of cloud services ensures contracts are structured to drive efficiency, flexibility, and accountability.

#### 2\. Risk Management, Security Responsibilities and Governance Shift

In a traditional data center, the government manages everything. In cloud computing:

* Some responsibilities are retained by the agency; others are managed by the cloud service provider  
* Governance of agency implementation and usage of the cloud is important. Agency governance should include accountable agency leaders in cloud services; systems and software engineering; cyber security; program management; agency finance; and of course, the contract’s Contracting Officer Representative (COR). Best practices for governance include:  
  * This group should work with each cloud vendor to understand the basics of effective cloud cost and utilization management  
  * The group should review trend-level reports monthly on cloud cost and utilization, and receive input from technical and business teams on the trends.   
  * The group should ensure that all major cloud architecture, software deployment, data management, automation, and AI/ML tooling comply with the cloud vendor’s recommended best practices

Contracting officers must also be aware of:

* The division of responsibilities between the agency and provider when writing requirements, SLAs, and performance metrics  
* The importance of selecting FedRamp-authorized services to meet federal security standards more easily  
* Building appropriate clauses around cloud-specific security issues like Identity and Access Management (IAM), vulnerability management, and incident response

Ignoring these shifts can leave dangerous gaps in security and compliance.

#### 3\. Cost Control in the Cloud is About Skills, Not Just Pricing

Unlike traditional fixed-cost contracts:

* Cloud costs can fluctuate monthly based on usage, and cloud providers may reduce commercial prices on specific cloud services over time  
* Poor cloud management leads to unexpected cost overruns

Contracting officers should ensure:

* Agencies have access to vendor training, and to professional services to assist with cloud implementation from skilled and experienced providers  
* Contract pricing approaches enable the agency to take advantage of dynamic pricing, particularly when cloud providers reduce prices in their commercial catalog, and don’t lock in rates that prevent the ability to do so, while also ensuring the agency is protected from any potential rate increases  
* Performance metrics include effective cloud resource management

Failing to address cloud cost management upfront can tie agencies into contracts that are unsustainable or difficult to justify to auditors and oversight bodies.

#### 4\. Vendor Selection and Cloud Architecture Need Strategic Thinking

Not all cloud providers are the same. Some specialize in certain capabilities (e.g., Artificial Intelligence/Machine Learning, Internet of Things, scalability. Contracting Officers selecting a vendor should consider:

* Choosing the right provider — or mix of providers — affects mission success  
* Architecting for flexibility — reduces lock-in and facilitates future migrations  
* Ensuring broad access \- agencies are increasingly utilizing enterprise approaches to buy and manage cloud services

Contracting officers should encourage:

* Evaluations based on specific agency needs, and the creation of contracts that allow broad and flexible access to cloud services and adjacent capabilities. Common pitfalls include:  
  * A federal agency entering a cloud contract for Infrastructure as a Service (“IaaS”), but quickly discovering the agency also needs Platform and Software as a Service (“PaaS”, “SaaS”) requiring difficult and time consuming modification.   
  * Buying all of the cloud services themselves, but not including cloud vendor professional services and/or integrated 3rd party software “marketplaces.”   
  * Buying cloud but restricting its use to only a specific program or part of an agency. This typically leads to “shadow IT” because other programs or divisions require cloud and can’t access it through the contract. Many agencies have problems with “shadow IT” and competing factions because multiple cloud procurement contracts are in place, causing organizational friction and inefficiency. Additionally, agencies may not get the full volume discounts possible from cloud vendors if they split the spend across multiple agency divisions.  
* Architecture planning as part of pre-solicitation activities  
* Inclusion of multi-cloud or hybrid-cloud strategies when appropriate

These practices help protect agency investments and maximize flexibility and resilience.

#### 5\. Training Is Not Optional

Cloud vendors offer robust training resources. Yet without proper contracting:

* Agencies may skip training  
* Agency or contract personnel may mismanage cloud operations, leading to inefficiencies, security incidents, or mission failure

Contracting officers must build training access into contracts and verify that:

* Personnel certifications or training milestones are clearly required  
* Cloud operation best practices are embedded in performance expectations

## Bottom Line for Contracting Officers

If you don't adapt your acquisition strategies for cloud, your agency risks financial waste, security breaches, failed missions, and poor technology outcomes.

By understanding the cloud's unique characteristics and adjusting procurement approaches accordingly, contracting officers become key enablers of efficient, secure, and future-proof government operations.

---
## Digital Service Tech Topic: Artificial Intelligence

### What is Artificial Intelligence?

Artificial Intelligence (AI) refers to computer systems designed to perform tasks that typically require human intelligence. These tasks include learning, problem-solving, decision-making, understanding language, and recognizing images and speech.

In government procurement, AI may be used in:

* Chatbots that help citizens navigate government websites  
* Tools that automatically classify or summarize procurement documents  
* Systems that detect potential fraud or patterns in spending  
* Applications that assist in analyzing large amounts of market research data

Just like automation helped streamline paper-based processes, AI helps automate cognitive tasks, making decisions faster and often more accurately.

### Types of AI

There are different types of AI you might hear about:

**Rule-Based Systems**: Follow clearly defined “if-this-then-that” instructions. Think of it as a very advanced flowchart.

**Machine Learning (ML)**: A type of AI that learns patterns from data and improves over time without being explicitly programmed. For example, if you feed it thousands of past solicitations, it might learn to predict which vendors are most likely to submit bids.

**Natural Language Processing (NLP)**: Allows machines to understand and process human language. For instance, it can summarize a long acquisition strategy or analyze sentiment in contractor feedback.

**Generative AI (like ChatGPT)**: Creates new content (like text or images) based on patterns learned from existing data. It might help draft performance work statements, justifications, or market research summaries.

### Key considerations for government systems

Bringing AI into government systems requires careful consideration of several challenges:

* **Transparency**: Can the AI explain how it reached a decision? This is important for accountability and legal defensibility.

* **Bias**: If AI systems are trained on biased data, they can perpetuate or amplify those biases. Procurement teams must ask about training data and fairness.

* **Security and Privacy**: AI may process sensitive data, so it must comply with data protection laws and agency security standards.

* **Change Management**: AI may impact workflows or job responsibilities. Agencies must prepare for this shift with proper communication and training.

* **Vendor Oversight**: If an AI-enabled solution is being procured, COs should ask how models are trained, tested, and updated.

### Common AI terms you may encounter

**Model training**: The process of feeding an AI system significant amounts of data to learn how to perform a task.

**Algorithm**: A set of rules or instructions the AI follows to make decisions or predictions.

**Inference**: When the AI applies what it has learned to new data, e.g., recommending vendors or flagging anomalies.

**Explainability**: The degree to which a human can understand why an AI system made a specific decision. Necessary for audits and legal review.

**Human-in-the-loop**: A setup where an AI system supports human decision-making rather than replacing it outright.

### Why it matters to procurement officers

**Market research**: AI tools can help summarize vendor capabilities or detect patterns in procurement history, making the early stages of procurement more efficient.

**Performance monitoring**: AI can quickly analyze contractor performance data to flag trends or anomalies.

**Drafting support**: Generative AI tools may help create first drafts of solicitation language or evaluation criteria, but humans must always review these drafts.

**Risk management**: Using AI in procurement systems introduces new risks—bias, transparency, and compliance—that COs must account for in contracts and performance oversight.

**Evaluation criteria**: When procuring AI solutions, COs should ensure that solicitations require vendors to describe data sources, bias mitigation strategies, and how their models can be audited or explained.

### What Contracting Officers Should Keep in Mind

* **Ask questions**: If AI is mentioned in a proposal, ask vendors how it works, how it was trained, and how it will be monitored.

* **Understand the use case**: Not all tasks need AI—be skeptical of buzzwords and ensure a clear benefit.

* **Balance innovation with oversight**: AI may be new, but government procurement still requires precise requirements, measurable outcomes, and accountability.

* **Support responsible use**: Like with data, you are a steward of responsible AI use. Advocate for ethical practices and transparency in the tools your agency adopts.

* **Post-award monitoring and model drift**: Even if the AI works at the time of contract award, there is a chance that the AI model doesn’t match changing behaviors. Ensuring that AIs are updated to keep up with changing needs is essential.


---
## Digital Service Tech Topic: Cybersecurity

### Why is cybersecurity important?

Cybersecurity is essential to digital service delivery. Every federal digital product—from public websites to mission-critical systems—relies on the ability to protect sensitive information, preserve system integrity, and ensure continuity of operations. As federal agencies modernize IT infrastructure and expand services across cloud, mobile, and AI platforms, the attack surface expands, making cybersecurity a shared responsibility across procurement, program, and technical roles.

Contracting Officers (COs) and Contracting Officer’s Representatives (CORs) are uniquely positioned to shape the cybersecurity posture of federal digital services by enforcing precise security requirements during acquisition planning, contract development, vendor evaluation, and post-award oversight.

Understanding key concepts like security compliance, identity and access management (IAM), vulnerability management, and security incident and event management (SIEM) is foundational to aligning acquisitions with agency cybersecurity goals and legal mandates.

### Cybersecurity in the current federal procurement context:

Several federal initiatives define how agencies must secure digital systems and software:

* [Executive Order 14028](https://www.gsa.gov/technology/government-it-initiatives/cybersecurity/executive-order-14028) mandates using secure software development practices and Zero Trust architectures.

* [OMB M-22-09](https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf) outlines a federal Zero Trust strategy to modernize access control, network segmentation, and device visibility.

* [OMB M-22-18](https://www.whitehouse.gov/wp-content/uploads/2022/09/M-22-18.pdf) provides software supply chain security guidance, including secure development attestations.

* [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) and [NIST SP 800-218 (SSDF)](https://csrc.nist.gov/publications/detail/sp/800-218/final) provide frameworks for implementing security and privacy controls in systems and software.

### Four key areas of cybersecurity for digital services

**1\. Security compliance**

All federal digital systems must meet agency-defined security standards. These standards are typically based on federal frameworks such as [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final), [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework), and potentially industry-specific standards (e.g., FISMA, HIPAA, FedRAMP).

* **CO/COR role**: Understand which frameworks apply to a given acquisition and confirm that the system’s design and implementation can meet compliance expectations.

* **Technical advisory**: The technical and security teams are responsible for advising whether full compliance is feasible. If not, acceptable exceptions may be allowed through documented **compensating controls**, subject to the discretion of the agency’s Office of the Chief Information Security Officer (OCISO).

**2\. Identity and Access Management (IAM)**

All federal digital services must integrate with the agency’s Identity and Access Management systems. IAM ensures that only authorized users can access protected systems and data.

* **CO/COR role**: Confirm that the digital system can be integrated with the agency’s approved IAM platform

* **Integration requirement**: Vendors should be asked to demonstrate technical compatibility with the agency’s IAM approach as part of their response or during early planning.

**3\. Vulnerability management**

Every digital system has security vulnerabilities. The goal of vulnerability management is not just patching—it is the comprehensive identification, analysis, remediation, and reporting of vulnerabilities across a digital service's lifecycle.

* **CO/COR role**: Ensure the vendor or technical team has tools, training, and processes to manage vulnerabilities to agency-defined standards.

* **Key activities**: Vulnerability management includes continuous monitoring, security scanning, patching (where applicable), exception tracking, compliance reporting, and incident response coordination.

**Note**: Patching is a tool, not a solution. Not all vulnerabilities can be addressed with patches, and some require configuration changes, compensating controls, or architectural adjustments.

**4\. Security Incident and Event Management (SIEM)**

SIEM systems detect, analyze, and respond to security events automatically. Agencies rely on centralized SIEM platforms to maintain situational awareness and act quickly on emerging threats.

* **CO/COR role**: Verify that any procured system can fully integrate with the agency’s existing SIEM platform (e.g., Splunk, Elastic, Microsoft Sentinel).

* **Orphaned tools**: If a system cannot be integrated into the existing SIEM infrastructure, the operational overhead for separate monitoring is high and introduces risk.

### Conclusion

Cybersecurity is not an afterthought—it must be designed into digital services from the start. Contracting officers and CORs must be able to ask the right questions and ensure security compliance, IAM integration, vulnerability management practices, and SIEM readiness are built into the acquisition process.

Through innovative, security-conscious procurement, COs help ensure that government services are trustworthy, resilient, and aligned with federal cybersecurity mandates.

---

## Digital Service Tech Topic: Accessibility

**Why Accessibility Matters in Federal Procurement**

Accessibility ensures that digital services are usable by everyone, including individuals with disabilities. In the context of federal procurement, this means making sure that all digital products and services acquired by the government are accessible to both employees and the public, regardless of ability. Federal laws and regulations, such as Section 508, establish clear responsibilities for procurement teams as part of a broader government-wide effort to build more inclusive digital services. These efforts benefit not only people with disabilities but also seniors, veterans, and anyone facing situational limitations, such as working outdoors or experiencing temporary impairments.

---

After completing this module, you will be able to:

* Recognize the essential concepts of accessibility in digital services procurement.  
* Identify common misunderstandings about accessibility and how to address them.  
* Recognize the importance of ongoing accessibility maintenance throughout a project's lifecycle.  
* Use federal tools and templates to improve accessibility outcomes in your procurements

---

### Must-Know Concepts

* Seek assistance from your agency’s accessibility subject-matter expert to help evaluate proposals and Accessibility Conformance Reports (ACRs).   
* Before awarding a contract, inquire about the prospective vendors' processes for incorporating accessibility into their work.   
* Accessibility, like security, must be maintained throughout the entire lifespan of the project. The contracting team must ensure this aspect of the contract is delivered throughout the project lifespan.   
* Ensure contracts incorporate user feedback by effectively using accessibility statements and conducting user research that includes people with disabilities.  
* Use the Accessibility Conformance Report (ACR) available through [Section508.gov](http://Section508.gov), and whenever possible, request an OpenACR via [acreditor.section508.gov](http://acreditor.section508.gov).   
  * Additionally, leverage the [Accessibility Requirements Tool (ART)](https://www.section508.gov/art) to help define and document accessibility needs during procurement.

---

### Common Misunderstandings 

| Myth | Clarification |
| ----- | ----- |
| “A product with an ACR is accessible.” | ACRs are vendor attestations. Test with real users or assistive tech to confirm. |
| “Accessibility is a one-time checkbox.” | Software updates can break accessibility. Contracts should require ongoing validation. |
| “Section 508 doesn’t apply to this procurement.” | Rarely true. Most acquisitions fall under the **“**Best Meets Criteria” and require documented reasoning. |
| “Accessibility only helps people with permanent disabilities.” | It benefits everyone. Think: aging users, situational limitations, temporary injuries. |

---

### Where Does Accessibility Show Up?

Accessibility should be embedded throughout the acquisition lifecycle. The earlier accessibility is considered in a project's lifespan, the more robust and less expensive it will be to implement.  Use the [ARRM framework](https://www.w3.org/WAI/planning/arrm/) to assign accessibility responsibilities across roles early in the project.

| Phase | How to Incorporate Accessibility |
| ----- | ----- |
| **Market Research** | Consult your accessibility SME. Use the [ART Tool](https://www.section508.gov/art). |
| **Solicitation** | Include accessibility criteria in evaluation factors. Reference Section 508 and WCAG. |
| **Proposal Review** | Evaluate vendors’ testing plans, ACRs, and experience. |
| **Post-Award Oversight** | Require validation testing, periodic ACR updates, and inclusive user testing. |

---

### Key Laws, Standards, or Frameworks

* **Section 508**:   
  * [Laws and Policies](https://www.section508.gov/manage/laws-and-policies)    
  * [Assessment Guidance](https://www.section508.gov/manage/section-508-assessment)  
  * [Buy Accessible Products and Services](https://www.section508.gov/buy/)   
  * [Tools](https://www.section508.gov/tools/)  
* **WCAG 2.2**: [Understanding Guidelines](https://www.w3.org/WAI/WCAG22/Understanding/)

---

### Tools & Templates

| Tool | Purpose |
| ----- | ----- |
| [Accessibility Requirements Tool (ART)](https://www.section508.gov/art) | Helps define Section 508 requirements by product type |
| [ACREditor](https://acreditor.section508.gov/) | Review or generate ACRs |
| [CivicActions Accessibility Playbook](https://accessibility.civicactions.com/playbook/checklists) | Includes practical checklists |
| [Accessibility Insights](https://accessibilityinsights.io/) | Testing tools for dev teams |
| [Open Requirements Library \- Accessibility](https://github.com/CivicActions/open-practice/blob/main/open-requirements-library/accessibility.md) | Sample accessibility requirements language for solicitations |
| [Sample Contracting Language on Accessible Procurement and ICT](https://docs.google.com/document/d/1wnBNyk0AuYmLWG4G6vTXXYSpH3E_G4lsqXv2dcJiVxI/edit?usp=sharing) | Sample contracting language |
| [Disability:INclusive Workplaces](https://disabilityin.org/procurement-toolkit/) [Accessible Technology Procurement Toolkit](https://disabilityin.org/procurement-toolkit/) | Accessible procurement toolkit |
| [CivicActions Accessibility](https://accessibility.civicactions.com/) | Comprehensive accessibility playbook |

---

### Final Takeaway

Accessibility isn’t just a compliance requirement; it’s a core part of delivering high-quality, inclusive digital services. As a procurement professional, you play a critical role in ensuring that the products and services acquired by your agency are usable by all people, including those with disabilities. By embedding accessibility into every phase of the acquisition lifecycle, from market research to post-award oversight, your actions help agencies meet legal obligations, reduce long-term risk, and serve the public equitably. Use the tools, templates, and SME support available to make accessibility a built-in expectation \- not an afterthought.

---

## Digital Service Tech Topic: Open Source Software

**Why Open Source Software Matters to Procurement Professionals**

**Open source software (OSS)** is used in nearly every modern government digital service. It can reduce costs, increase innovation, and support long-term vendor independence but only if acquisition professionals understand how to evaluate and procure it responsibly.

This module introduces procurement officers to the principles, risks, and opportunities of open source software in digital government. It covers legal foundations, evaluation practices, and OSS's role in long-term service delivery and transparency.

---

By the end of this module, you will be able to:

* Recognize how open source software fits within federal procurement.

* Identify common myths and misunderstandings around OSS in government.

* Explain how open source software fits into Commercial Off-the-Shelf (COTS) procurement

---

### Must-Know Concepts

Here are **5 must-know insights** about open source and how it fits into digital service acquisition:

1. The vast majority of all software includes some open source software.   
2. Community health for open source software is as important as understanding if a company is economically viable.   
3. Several existing pieces of legislation advocate for open source software approaches, such as the SHARE IT Act.   
4. Governments should contribute back to the open source software communities they rely on (through vendors).   
5. Strategic use of open source software can reduce costs and increase innovation for your agency. 

---

### Common Misunderstandings

| Myth | Clarification |
| ----- | ----- |
| “Open source is less secure.” | Security depends on implementation and maintenance. Developing software in the open encourages a better culture of security, quicker identification of vulnerabilities, and a stronger culture of transparency and accountability. |
| “OSS can't be supported by vendors.” | Many vendors specialize in OSS support, and some of the biggest government projects already depend on it. |
| “If it’s on GitHub, I can use it without review.” | Licensing and provenance still matter. There are many different licenses on GitHub, not all of which are compatible. |
| “OSS means no maintenance cost.” | OSS has lifecycle costs too. Any software that isn't maintained is a security risk. |

---

### Why OSS Shifts Power Back to Government

* **Open source reduces vendor lock-in:** Because the code is openly available and licensed for reuse, agencies can switch vendors, build internal capacity, or share development across teams—putting control back in the hands of the buyer. 

* **Open source encourages better vendor performance:** When vendors compete on service—not on code ownership—they're more likely to deliver quality, responsiveness, and value over time, knowing the customer can walk away and take the software with them. 

* **Open source improves security responsiveness:** Bugs and vulnerabilities are typically identified and resolved within days, thanks to the transparency and collaborative nature of public scrutiny. In contrast, proprietary vendors may delay fixes or limit disclosure to protect market interests.

### How Open Source Shows Up in the Acquisition Lifecycle

It should appear early, before a decision is made about the software to be considered.

| Phase | Procurement Considerations |
| ----- | ----- |
| **Market Research** | Explore OSS solutions and evaluate community health/licensing. |
| **RFI/RFP** | Avoid over-prescription. Allow OSS solutions where viable. Include evaluation criteria for OSS viability. |
| **Source Selection** | Assess support model, license compatibility, and ability to contribute improvements. |
| **Post-Award** | Track maintenance and compliance. Consider OSS contributions through the vendor. |

---

### Key Laws, Standards, or Frameworks

* **Federal Acquisition Regulation (FAR):** OSS is considered commercial off-the-shelf (COTS) software under the FAR. This gives OSS a procurement advantage, allowing agencies to buy, adopt, or integrate OSS without lengthy procurement processes.   
* [**Federal Source Code Policy \- OMB M-16-21**](https://digital.gov/resources/requirements-for-achieving-efficiency-transparency-and-innovation-through-reusable-and-open-source-software/)   
* [**SHARE IT Act**](https://dsacms.github.io/share-it-act-lp/)**:** Source Code Harmonization And Reuse in Information Technology Act, December 23, 2024 — Public Law 118--187 

### Tools & Resources

| Topic | Resource |
| ----- | ----- |
| Licensing | [Open Source Initiative Licenses](https://opensource.org/licenses) |
| Evaluation | [Open Source Procurement Checklist](https://docs.google.com/document/d/1gaju308kDPHOgbC8XCUbeOg6szIqxP-Bnv-NnwRka8A/edit) |
| Comparison | [Open Source Software vs Proprietary Software](https://docs.google.com/document/d/1o3rJSa1KhfC9QcliQ9RwgZsoHPJM54XzFmRLzrA8DnQ/edit?usp=sharing) |
| FAQ | [Open Source Procurement FAQ](https://docs.google.com/document/d/12FGu9gbZcIyyWYjEJm3K707kqZHK3_bs2IT1oU08J5Y/edit?usp=sharing) |

---

### Further Resources

* [Open Source Initiative (OSI) Approved Licenses](https://opensource.org/licenses)

* [Digital Public Goods Registry](https://www.digitalpublicgoods.net/registry)  
     
* [FAR Guidance](https://www.acquisition.gov/) (being updated)

* [CHAOSS Community](https://chaoss.community/)

* [How to Write an RFP for Open Source Solutions: Featuring Drupal Certified Partners](https://www.drupal.org/association/blog/how-to-write-an-rfp-for-open-source-solutions-featuring-drupal-certified-partners)

---

### Final Takeaway

Open source software isn’t “free” in the sense of being without cost; it’s software designed for openness, collaboration, and reuse. When used thoughtfully, OSS empowers agencies, reduces risk, and supports scalable, transparent government services.











