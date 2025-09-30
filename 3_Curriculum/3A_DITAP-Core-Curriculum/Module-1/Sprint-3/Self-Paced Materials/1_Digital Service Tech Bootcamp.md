# Introduction to the Digital Service Tech Bootcamp
**Module 1 Sprint 3**

> _Average completion time: 2.5 - 3 hours_

Modern government acquisition professionals operate in a rapidly evolving digital environment. Whether you're evaluating a cloud-based platform, reviewing a data-sharing agreement, or procuring custom software development, your work increasingly intersects with key technology concepts that shape how agencies deliver public services.

This module introduces seven essential digital service topics: data, software, cloud computing, artificial intelligence, cybersecurity, accessibility, and open source software, with a focus on how these topics directly impact your role as an acquisition professional. 

| Topic | Description |
|----------|-------------|
| **Data** | Data is the foundation of digital services; it's collected, stored, and analyzed to inform decisions, measure impact, and improve government operations. Procurement supports this by sourcing tools and services for managing and protecting data. |
| **Software** | Software refers to the programs that run on computers or in the cloud to help agencies operate efficiently. Procurement plays a key role in acquiring, licensing, and maintaining the right software to meet mission needs. |
| **Cloud Services** | Cloud services allow agencies to rent computing power, storage, and tools over the internet instead of maintaining physical servers. Procurement must structure contracts to align with flexible, scalable cloud service models. |
| **Artificial Intelligence (AI)** | AI uses algorithms to analyze data, automate tasks, and generate insights that support faster, smarter decisions. Procurement may support AI initiatives by acquiring ethical, compliant AI tools and ensuring proper data use. |
| **Cybersecurity** | Cybersecurity protects government systems and data from threats like hacking or data breaches. Procurement ensures that systems and services meet security standards and include appropriate safeguards. |
| **Accessibility** | Accessibility ensures that digital services and products are usable by people with disabilities. Procurement must ensure that technology acquisitions comply with legal requirements and support inclusive design practices to serve all citizens. |
| **Open Source Software** | Open Source Software is publicly available software with source code that can be inspected, modified, and enhanced by anyone. Procurement must understand open source licensing and intellectual property to leverage its benefits while managing risks. |


You don't need to be a technical expert, but understanding the fundamentals will help you write better requirements, evaluate vendor capabilities, and ensure contracts support secure, effective, and user-centered digital services.

The lessons ahead will explain terminology, describe modern delivery models, and highlight practical implications for acquisition planning, vendor engagement, and contract oversight.

The recent overhaul of **Federal Acquisition Regulation (FAR) Parts 6 and 39** significantly impacts how acquisition professionals approach digital service procurements. These changes emphasize human-centered design, iterative development, and strategic competition considerations specific to information technology acquisitions.

**Key changes include**:

- Enhanced requirements for IT acquisition planning under FAR Part 39, including mandatory consideration of open source alternatives and Software Bills of Materials (SBOMs)
- Updated competition procedures in FAR Part 6 that recognize the unique characteristics of digital services and emerging technologies
- New emphasis on modular contracting approaches that support Agile development methodologies
- Strengthened cybersecurity baseline requirements that must be addressed in all IT acquisitions
- Requirements for accessibility compliance verification throughout the acquisition lifecycle

---

By the end of this module, you will be able to:

- Describe the differences between structured, unstructured, and semi-structured data, and explain why those distinctions matter for procurement and contract oversight.
- Identify key challenges and modernization needs related to data storage, migration, analytics, and privacy in federal systems.
- Explain the importance of Section 508 and other accessibility standards in digital services, and assess how accessibility requirements impact acquisition planning and contract oversight.
- Explain the software development lifecycle (SDLC) and modern practices like Agile, DevOps (development and operations), and Continuous Integration and Continuous Delivery (CI/CD), and recognize their relevance in acquisition strategies.
- Differentiate between proprietary and open-source software licenses, and understand the implications of software supply chain security.
- Define Artificial Intelligence (AI) and explain its strategic role in acquisition, including key considerations like algorithmic bias, data governance, and ethical use.
- Define cloud computing and distinguish between public, private, community, and hybrid cloud deployment models.
- Explain the differences between Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS), and assess what kind of cloud service model a contract may require.
- Recognize cloud-specific procurement considerations, including pricing models, shared security responsibilities, vendor lock-in risks, and Federal Risk and Authorization Management Program (FedRAMP) compliance.
- Understand the basics of cybersecurity as it applies to acquisitions, including compliance frameworks (e.g., National Institute of Standards and Technology \[NIST\]), identity and access management (IAM), vulnerability management, and Security Incident and Event Management (SIEM).
- Apply updated FAR Part 39 requirements for IT acquisition planning, including digital service delivery standards and security baseline assessments.
- Navigate FAR Part 6 competition procedures as they apply to specialized IT procurements and emerging technology acquisitions.


---

## Digital service tech topic: Data

### What is data?

Data is just information that’s been collected and stored (“recorded”). It can come in many forms—numbers in a spreadsheet, written text in emails, pictures, or even audio and video. In government contracting, examples of data include:

* Contractor performance records  
* Purchase histories  
* Budget logs  
* Emails between vendors and agencies

There are three main types:

| Data Type | Description |
|-----------|-------------|
| **Structured Data** | Organized in a way that computers can easily process, regardless of whether a human can easily read it, like Excel sheets or databases. |
| **Unstructured Data** | Organized in a way that humans can easily process, but not organized for computers to process the information, like PDF documents or social media comments. |
| **Semi-Structured Data** | Somewhere in between, like webpages, which are human readable and are tagged so that computers can easily process them, with varying levels of granularity or structure. |


Think of a contracting file that includes emails, PDFs, performance reviews, and a payment history, that’s a mix of structured and unstructured data.

**Key considerations for government systems**

As data grows in size and complexity, there are more challenges related to data storage, data transfer, and data processing:

* Old systems may slow down or fail under the weight.  
* Data must often be moved between different clouds, networks, or storage areas—which can cause delays or added costs.
* Network upgrades and smarter designs are sometimes needed to keep up with demands.  
* New data processing techniques or tradeoffs may be needed as data volumes increase.  
* Ensuring data accuracy and forward/backward compatibility for different use cases can become complex.

>Learn more about data analysis by visiting [15 Data Analysis Tools and When to Use Them](https://www.coursera.org/articles/data-analysis-tools). 

These are some of the key challenges that are driving agency modernization efforts today, and are likely to come across your desk as an acquisition professional. 

* Modern systems need to move data across clouds, networks, and apps. That creates bottlenecks unless you’ve planned for it.
* Old databases weren’t built for the amount of data we use today. That’s like trying to run modern apps on a flip phone— the hardware would struggle to work correctly.
* You may want to change data or delete it over time, but there may be practical or legal reasons not to. (E.g., System for Award Management (SAM.gov) “Federal Procurement Reports” from 2007… useful? Not really. But should it be *deleted?* Probably not.) 

As a contracting officer, you will likely encounter a variety of “buzz words”/topics related to data in your work, here are a few that are particularly relevant today: 

* **Data modernization**: The process of updating and transforming data systems, infrastructure and practices to modern, cloud-based formats to enhance accessibility, security and business intelligence.   
* **Data migration**: The process of transferring data from one storage system or computing environment to another.  
* **Data analytics**: The process of collecting, transforming, and organizing data in order to draw conclusions, make predictions, and drive informed decision making.   
* **Data Lake**: A data lake is a centralized repository designed to store, process, and secure large amounts of structured, semistructured, and unstructured data. It can store data in its native format and process any variety of it, ignoring size limits.  
* **ETL (Extract, Transform, Load)**: A data integration process that combines, cleans, and organizes data from multiple sources into a single, consistent dataset for storage in a data warehouse or other target system.   
* **Data Provenance**: The historical record of data that details data’s origins by capturing its metadata as it moves through various processes and transformations. Data provenance is primarily concerned with authenticity, providing details such as who created the data, the history of modifications, and who made those changes.

### Open data

Open data is information that anyone can access, use, and share. In the context of government, this has two dimensions: 

1. The ability for someone to *access* the data  
2. The legal right for the user to use the data

Generally, Open data also refers to non-sensitive public information made available in data *formats* that are easy to use, reuse, and republish.

Many government entities, from local to federal to international, provide data sets to data.gov and/or operate their own open data websites so that information generated may be shared and utilized by the public. There are many open data sets, ranging from government operations data (e.g., Federal Procurement Data System (FPDS)) to data “products” (e.g., Census survey data tables).

Outside of government, open data can also refer to a movement to provide open access and use of the massive amounts of projects and data being developed every day in commerce, science, and technology in order to promote progress and innovation, and improve the accountability of both private and public institutions.

**Why it matters to procurement officers:**

1. **Licensing**: Procurements that potentially involve open data require consideration of the relative intellectual property / data rights.  
2. **Privacy**: Open data can, in some cases, implicate privacy concerns, particularly when combined with other open data sets. Understanding how data is published and ensuring that contracts have adequate remedies for privacy violations is important for contracting officers.  
3. **Efficiency**: Understanding how open data can be used to improve data publication and use can reduce duplication of effort and allow for more efficient use of government and non-government data.

### Data privacy

Data privacy means protecting personal or sensitive information so that only people who are supposed to see it can access it. This includes things like social security numbers, health records, or confidential contract data.

| Topic | Key Points |
|-------|------------|
| **Why it matters** | - **Legal compliance:** Follow privacy laws like the Privacy Act of 1974 and agency-specific policies to protect personal information collected during procurement.<br>- **Risk management:** Mishandling private data can lead to security breaches, legal penalties, and loss of public trust.<br>- **Contract integrity:** Some procurement data may contain sensitive vendor information; protecting it ensures fair competition and integrity of the process.<br>- **Example:** Contractor tax IDs or employee background checks must be stored and shared securely to prevent unauthorized access. |
| **What to keep in mind** | - Understand what data your systems hold and how it’s organized.<br>- Ask vendors how they handle data, especially if AI or analytics are part of the service.<br>- Support modernization efforts that improve how data is stored and accessed across departments.<br>- As a contracting officer, you are both a data user and a data steward. <br>Know:<br>  - What data can and should be shared openly (e.g., awarded contracts).<br>  - What data must be protected (e.g., PII or confidential business info).<br>  - The laws and best practices that guide both. |

---

## Digital service tech topic: Software

### What is software?

Software refers to the instructions, data, or programs that enable computers and digital systems to perform specific tasks. Informally, software tells computer hardware how to do something useful with data. It includes human-readable instructions, known as source code, and machine-readable instructions compiled for the computer to execute.

>Note for contracting officers: It may be necessary to clarify whether the government can access the source code or compiled software. Access to source code may be required under FAR clauses like 52.227-14 (Rights in Data), or via specific IP clauses negotiated in contracts—especially for custom software. Agencies can specify unlimited, government purpose, or restricted rights in deliverables, depending on mission needs.

### How is software developed?

Understanding how software is developed helps procurement professionals recognize what they're buying, how to evaluate progress, and what kinds of contract structures best support successful delivery. This section introduces the software development lifecycle, modern methodologies like Agile, the roles involved, and key concepts such as the software supply chain.

The **Software Development Lifecycle (SDLC)** is the process organizations use to plan, design, develop, maintain, and eventually retire software systems. Approaches to SDLC range from traditional "waterfall" methods, where each phase is completed sequentially, to more modern, iterative approaches like Agile. Agile methodology focuses on building and delivering functional software in small, manageable increments. Different Agile approaches include Scrum, where teams work in short, time-boxed sprints, and Kanban, which emphasizes continuous delivery with strict limits on work in progress to maintain flow.

A central principle of modern software development is the importance of iteration, prototyping, and feedback loops, testing ideas early, learning from users, and continuously improving. For example, the U.S. Digital Service and VA used Agile and iterative development to improve the VA.gov website, releasing updates in small increments based on honest user feedback. They also leveraged open-source libraries and maintained a Software Bill of Materials (SBOM) to track components and ensure security compliance. OMB Memo M-22-18 and NIST’s Secure Software Development Framework (SSDF) now require SBOMs and secure development attestations from software vendors, making SBOMs a federal policy expectation in many software contracts.

Instead of building everything from scratch, developers commonly use packages and libraries, prewritten code modules created by others, to speed up development and improve reliability. However, this practice introduces potential security, licensing, and maintenance risks. As a result, tools like SBOMs are becoming essential, helping organizations manage their software supply chain more effectively.

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

### Why updates matter—and how they stay safe

Frequent updates help agencies respond quickly to user needs and changing requirements. But they also come with tradeoffs. Updates can introduce new problems or confuse users if not communicated well. That’s why finding the right balance between moving fast and keeping systems stable is essential.

Security is another key reason software needs regular updates. Updates often include patches for known vulnerabilities and help systems comply with federal security policies, like FedRAMP or NIST standards. Agencies should plan for ongoing updates as part of the delivery process, not as an afterthought.

### How teams monitor and respond to problems

After software is deployed, teams don’t just walk away; they monitor its performance in real time. They use monitoring tools to track uptime, response time, and error rates. Standard tools include Datadog, Prometheus, and AWS CloudWatch. These insights help teams decide when to update or improve the system.

If something goes wrong, teams rely on incident response plans. These plans include steps for rolling back bad updates, recovering data, and communicating with stakeholders. Having clear procedures in place helps minimize downtime and protects user trust.

### Considerations around supply chain and licensing

When buying or managing software, it's essential to understand what’s behind the hood. Most modern software isn’t built from scratch, it’s assembled from many parts, including third-party libraries, open-source tools, proprietary code, and deployment tools. This collection of components is often referred to as the **software supply chain.**

If agencies or vendors don’t track these components correctly, it can lead to hidden vulnerabilities, licensing conflicts, or even security breaches. For example, the **SolarWinds cyberattack**, a significant event that affected several federal agencies, exploited weaknesses in the software build process. This incident showed how risky it can be when dependencies and tools aren't properly managed or monitored.

One way to manage this risk is through a **Software Bill of Materials (SBOM)**. An SBOM is like a parts list for software, it shows all the libraries, packages, and tools that make up a system. Many federal agencies now require vendor SBOMs because they help track vulnerabilities and support a faster response when issues arise. This requirement is reinforced by OMB M-22-18 and NIST SSDF guidance.

Contracting officers and acquisition professionals should also ask vendors about **risk management practices.** Are they scanning for vulnerabilities? Do they patch or replace risky components? Do they follow secure development practices? These questions are essential to ensure that the software delivered is safe and dependable.

Licensing is another key consideration. Software licenses set the rules for how software can be used, shared, or changed. There are two main types: **proprietary licenses** and **open-source licenses.**

**Proprietary licenses** usually come with restrictions and fees. Agencies don’t get access to the source code and must rely on the vendor for support and updates. Common examples include Microsoft Office or Salesforce. In contrast, **open-source licenses** generally allow for more flexibility. They let agencies use, change, and distribute software freely, though some licenses require that changes be shared publicly. For instance, the Apache 2.0 license is relatively permissive, while the GNU General Public License (GPL) has stricter conditions.

These licensing choices affect more than legal compliance; they impact cost, flexibility, and long-term strategy. While open-source tools may reduce licensing costs, they still require investment in support and integration. Open-source software can be customized, while proprietary tools may be more complex to adapt. Failure to follow the terms of a license, especially with open-source software, can lead to contract issues or legal trouble.

Finally, agencies should consider the risk of **vendor lock-in,** when switching providers becomes difficult or expensive. This can happen if the vendor uses proprietary formats, doesn’t allow access to data, or doesn’t follow open standards. When reviewing a procurement, it’s worth asking: Does the software use open standards? Will we be able to access and export our data? Could another vendor take over if needed? APIs and modularity can help avoid lock-in, and they support DevSecOps, interoperability, and zero-trust architecture. APIs should follow open standards (e.g., OpenAPI) and be well-documented, often as required deliverables in contracts.

By considering these factors, 1102s can make better-informed decisions that reduce risk, support flexibility, and help agencies maintain control over their software assets.

### Service design and delivery standards (21st Century IDEA & USDS Playbook)

Modern software isn’t just about code, it’s about delivering effective services that meet user needs, comply with the law, and adapt over time. The 21st Century Integrated Digital Experience Act (IDEA) and the U.S. Digital Services Playbook set specific expectations for how software supporting government services should be designed and delivered.

Contracting officers should understand these frameworks to write solicitations that support human-centered, standards-compliant digital service delivery. Section 280 of the FY2023 NDAA also promotes modular contracting and HCD in acquisition planning, making it easier for agencies to build flexible, responsive digital tools.

When federal agencies build or buy digital services, focusing on the people who will use them is critical. This approach is called **Human-Centered Design (HCD).** It means engaging with users throughout the development process, not just at the beginning or the end, to ensure the product meets their needs. Human-centered design focuses on the needs, behaviors, and feedback of end users of a product or service. Consider making user research a contract deliverable, including usability testing, accessibility audits, and multiple feedback loops to validate success.

HCD places special emphasis on **accessibility, usability, and continuous feedback.** Digital tools should be easy for everyone, including people with disabilities. That’s where **Section 508 compliance** comes in, requiring things like screen reader compatibility, keyboard navigation, and appropriate color contrast. But accessibility alone isn’t enough—systems should be usable and continually improved based on real-world feedback. Agencies can achieve this by building in regular user testing, collecting performance data, and listening to feedback.

Contracting officers can help by shaping procurements to support these practices. Instead of static, one-time requirements, solicitations should encourage **iterative research and design.** This might mean asking vendors to include user researchers and designers on their teams or to plan for multiple testing and feedback cycles as part of their delivery.

**Modular development** and **API-driven architecture** are other key strategies for building flexible, user-friendly systems. Modular development breaks large systems into smaller, usable parts that can be delivered and improved over time, rather than waiting years for a final product. Meanwhile, **APIs** (Application Programming Interfaces) allow different systems to talk to each other. This makes integrating commercial tools, in-house software, and legacy systems easier, while avoiding vendor lock-in. These strategies align with modern cloud and DevSecOps practices, and support faster, more secure delivery.

Strong **performance and usability standards** are also essential. Systems should respond quickly, handle expected workloads, and navigate easily. Agencies may track things like the number of transactions a system handles each day or how long it takes for a page to load (e.g., 95% of responses under 500 milliseconds).

Finally, **continuous improvement** should be part of any technology investment. This means monitoring systems for performance and problems, collecting data on how users interact with the service, and using that data to guide future updates. Combining **quantitative** **analytics** (like page views or error rates) with **qualitative research** (like interviews and surveys) gives a fuller picture of how well a system works and how to improve it.

By prioritizing user needs, accessibility, and flexibility, agencies can deliver effective and inclusive digital tools. Acquisition professionals play a key role in this process.

---

## Digital service tech topic: Cloud

### Basics

Cloud computing offers a flexible and efficient way for federal agencies to manage their IT needs. Rather than relying entirely on traditional data centers, agencies can turn to a wide range of cloud services provided by various vendors. There isn’t just one “cloud” - cloud computing refers to a model of accessing shared computing resources like storage, servers, and applications over the internet. 

According to the National Institute of Standards and Technology (NIST), a true cloud service must offer five key features: 

1. On-demand self-service  
2. Broad network access  
3. Resource pooling  
4. Rapid elasticity  
5. Measured service

These characteristics allow agencies to access computing resources when they need them, from almost anywhere, and scale usage up or down depending on demand, all while tracking and managing usage.

![Diagram illustrating the 5 essential characteristics of cloud computing: On-Demand Self-Service, Broad Network Access, Resource Pooling, Rapid Elasticity, and Measured Service, all stemming from a central cloud icon.](https://raw.githubusercontent.com/usds/ditap-curriculum-update/e0c2ace59ae43fb910dbddc0fbfb2c4c45093908/3_Curriculum/3B_DITAP-Core-Curriculum/Module-1/Module-1-Media/5_essentials_cloud.png) 

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

It’s also important to understand that security and management responsibilities are shared in cloud environments. In traditional data centers, the agency is responsible for every aspect of IT security and maintenance. In cloud environments, some responsibilities, such as physical security or infrastructure updates, fall to the cloud vendor, while others remain with the agency. This division varies by cloud vendor and by service type, so contracting officers should pay close attention to the terms and service models when evaluating proposals or monitoring vendor performance.

### Considerations

Cloud computing is fundamentally different from traditional data center operations, and applying old practices to cloud environments can lead to inefficiencies and unnecessary costs. Cloud services are purchased and managed differently, requiring agencies to train staff in cloud-native practices. Fortunately, major cloud vendors offer training to help agencies manage usage and costs effectively. Without this knowledge, agencies risk overspending and misconfiguring services.

Security concerns often deter cloud adoption, but cloud platforms are generally secure when implemented correctly. Most breaches result from human error, not cloud vulnerabilities. Agencies should follow their security policies and use best practices like strong identity and access management (IAM), vulnerability management, and Security Incident and Event Management (SIEM) tools. They should also work directly with vendors to ensure cloud-specific security configurations.

Not all cloud vendors are the same, each has strengths and weaknesses. Agencies can use one as a primary provider and others as backups, as long as systems are built for flexibility and resilience. Vendor lock-in is less of a risk in the cloud than in traditional IT, and thoughtful architecture can simplify migration between platforms.

Using Federal Risk and Authorization Management Program (FedRAMP), authorized services can streamline security approvals and ensure compliance with federal standards. Lastly, agencies must ensure that cloud solutions follow vendor-recommended best practices for architecture, deployment, and emerging technologies like AI/ML. Poor implementations by contractors using outdated approaches often result in high costs and technical debt. Getting it right from the start helps ensure secure, efficient, and scalable cloud operations.

**Why understanding cloud computing is critical for government contracting officers**

| Topic | Key Points |
|-------|------------|
| **1. Cloud procurement is fundamentally different** | - Cloud services are dynamic; agencies buy elastic, scalable services, not fixed assets.<br>- Service catalogs change frequently; contracts should allow access to new services without renegotiation.<br>- Payment models use pay-as-you-go rather than upfront capital expenditures.<br>- Oversight requires adapting to a shared responsibility model between agency and vendor.<br>- Ignoring this can lead to wasteful spending, unfulfilled mission needs, higher security risks, and vendor performance issues. |
| **2. Risk management, security responsibilities and governance shift** | - Some responsibilities remain with the agency; others are handled by the cloud provider.<br>- Governance should include agency leaders in cloud services, software engineering, cybersecurity, program management, finance, and CORs.<br>- Best practices: understand cost/utilization, review trend reports monthly, ensure compliance with vendor recommended best practices.<br>- Contracting officers must account for responsibility division, select FedRAMP-authorized services, and include cloud-specific security clauses (IAM, vulnerability management, incident response).<br>- Ignoring these shifts can create security and compliance gaps. |
| **3. Cost control in the cloud is about skills, not just pricing** | - Cloud costs fluctuate with usage; providers may reduce prices over time.<br>- Poor management leads to unexpected overruns.<br>- Agencies should have access to training and professional services.<br>- Contract pricing should allow dynamic pricing adjustments and protect against rate increases.<br>- Performance metrics should include effective cloud resource management.<br>- Neglecting cost management can create unsustainable contracts difficult to justify to auditors. |
| **4. Vendor selection and cloud architecture need strategic thinking** | - Not all providers are the same; some specialize in AI/ML, IoT, or scalability.<br>- Choose the right provider or mix to ensure mission success.<br>- Architect for flexibility to reduce lock-in and facilitate future migrations.<br>- Encourage broad and flexible access in contracts.<br>- Common pitfalls: IaaS-only contracts, missing professional services or integrated marketplaces, restricted access leading to shadow IT, splitting spend across divisions reducing volume discounts.<br>- Include pre-solicitation architecture planning and multi/hybrid-cloud strategies. |
| **5. Training is not optional** | - Cloud vendors provide robust training.<br>- Agencies may skip training without proper contracting, leading to mismanagement, inefficiencies, security incidents, or mission failure.<br>- Contracts should require certifications or training milestones.<br>- Embed cloud operation best practices into performance expectations. |


**Bottom line for contracting officers**

If you don't adapt your acquisition strategies for cloud, your agency risks financial waste, security breaches, failed missions, and poor technology outcomes.

By understanding the cloud's unique characteristics and adjusting procurement approaches accordingly, contracting officers become key enablers of efficient, secure, and future-proof government operations.

---

## Digital service tech topic: Artificial intelligence

### What is artificial intelligence?

Artificial Intelligence (AI) refers to computer systems designed to perform tasks that typically require human intelligence. These tasks include learning, problem-solving, decision-making, understanding language, and recognizing images and speech.

In government procurement, AI may be used in:

* Chatbots that help citizens navigate government websites  
* Tools that automatically classify or summarize procurement documents  
* Systems that detect potential fraud or patterns in spending  
* Applications that assist in analyzing large amounts of market research data

Just like automation helped streamline paper-based processes, AI helps automate cognitive tasks, making decisions faster and often more accurately.

### Types of AI

There are different types of AI you might hear about:

- **Rule-based systems**: Follow clearly defined “if-this-then-that” instructions. Think of it as a very advanced flowchart.
- **Machine Learning (ML)**: A type of AI that learns patterns from data and improves over time without being explicitly programmed. For example, if you feed it thousands of past solicitations, it might learn to predict which vendors are most likely to submit bids.
- **Natural Language Processing (NLP)**: Allows machines to understand and process human language. For instance, it can summarize a long acquisition strategy or analyze sentiment in contractor feedback.
- **Generative AI (like ChatGPT)**: Creates new content (like text or images) based on patterns learned from existing data. It might help draft performance work statements, justifications, or market research summaries.

### Key considerations for government systems

Bringing AI into government systems requires careful consideration of several challenges:

* **Transparency**: Can the AI explain how it reached a decision? This is important for accountability and legal defensibility.
* **Bias**: If AI systems are trained on biased data, they can perpetuate or amplify those biases. Procurement teams must ask about training data and fairness.
* **Security and privacy**: AI may process sensitive data, so it must comply with data protection laws and agency security standards.
* **Change management**: AI may impact workflows or job responsibilities. Agencies must prepare for this shift with proper communication and training.
* **Vendor Oversight**: If an AI-enabled solution is being procured, COs should ask how models are trained, tested, and updated.

### Common AI terms you may encounter

- **Model training**: The process of feeding an AI system significant amounts of data to learn how to perform a task.
- **Algorithm**: A set of rules or instructions the AI follows to make decisions or predictions.
- **Inference**: When the AI applies what it has learned to new data, e.g., recommending vendors or flagging anomalies.
- **Explainability**: The degree to which a human can understand why an AI system made a specific decision. Necessary for audits and legal review.
- **Human-in-the-loop**: A setup where an AI system supports human decision-making rather than replacing it outright.

| Topic | Details |
|-------|---------|
| **Why it matters to procurement officers** | - **Market research:** AI tools can help summarize vendor capabilities or detect patterns in procurement history, making the early stages of procurement more efficient.<br>- **Performance monitoring:** AI can quickly analyze contractor performance data to flag trends or anomalies.<br>- **Drafting support:** Generative AI tools may help create first drafts of solicitation language or evaluation criteria, but humans must always review these drafts.<br>- **Risk management:** Using AI in procurement systems introduces new risks, bias, transparency, and compliance that COs must account for in contracts and performance oversight.<br>- **Evaluation criteria:** When procuring AI solutions, COs should ensure that solicitations require vendors to describe data sources, bias mitigation strategies, and how their models can be audited or explained. |
| **What contracting officers should keep in mind** | - **Ask questions:** If AI is mentioned in a proposal, ask vendors how it works, how it was trained, and how it will be monitored.<br>- **Understand the use case:** Not all tasks need AI, be skeptical of buzzwords, and ensure a clear benefit.<br>- **Balance innovation with oversight:** AI may be new, but government procurement still requires precise requirements, measurable outcomes, and accountability.<br>- **Support responsible use:** Like with data, you are a steward of responsible AI use. Advocate for ethical practices and transparency in the tools your agency adopts.<br>- **Post-award monitoring and model drift:** Even if the AI works at the time of contract award, there is a chance that the AI model doesn’t match changing behaviors. Ensuring that AIs are updated to keep up with changing needs is essential. |

---

## Digital service tech topic: Cybersecurity

### Why is cybersecurity important?

Cybersecurity is essential to digital service delivery. Every federal digital product, from public websites to mission-critical systems, relies on the ability to protect sensitive information, preserve system integrity, and ensure continuity of operations. As federal agencies modernize IT infrastructure and expand services across cloud, mobile, and AI platforms, the attack surface expands, making cybersecurity a shared responsibility across procurement, program, and technical roles.

Contracting Officers (COs) and Contracting Officer’s Representatives (CORs) are uniquely positioned to shape the cybersecurity posture of federal digital services by enforcing precise security requirements during acquisition planning, contract development, vendor evaluation, and post-award oversight.

Understanding key concepts like security compliance, identity and access management (IAM), vulnerability management, and security incident and event management (SIEM) is foundational to aligning acquisitions with agency cybersecurity goals and legal mandates.

### Cybersecurity in the current federal procurement context

Several federal initiatives define how agencies must secure digital systems and software:

* [Executive Order 14028](https://www.gsa.gov/technology/government-it-initiatives/cybersecurity/executive-order-14028) mandates using secure software development practices and Zero Trust architectures.
* [OMB M-22-09](https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf) outlines a federal Zero Trust strategy to modernize access control, network segmentation, and device visibility.
* [OMB M-22-18](https://www.whitehouse.gov/wp-content/uploads/2022/09/M-22-18.pdf) provides software supply chain security guidance, including secure development attestations.
* [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) and [NIST SP 800-218 (SSDF)](https://csrc.nist.gov/publications/detail/sp/800-218/final) provide frameworks for implementing security and privacy controls in systems and software.

### Four key areas of cybersecurity for digital services

| Category | Details |
|----------|---------|
| Security Compliance | All federal digital systems must meet agency-defined security standards. These standards are typically based on federal frameworks such as [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final), [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework), and potentially industry-specific standards (e.g., FISMA, HIPAA, FedRAMP). <br><br> **CO/COR role:** Understand which frameworks apply to a given acquisition and confirm that the system’s design and implementation can meet compliance expectations. <br><br> **Technical advisory:** The technical and security teams are responsible for advising whether full compliance is feasible. If not, acceptable exceptions may be allowed through documented compensating controls, subject to the discretion of the agency’s Office of the Chief Information Security Officer (OCISO). |
| Identity and Access Management (IAM) | All federal digital services must integrate with the agency’s Identity and Access Management (IAM) systems. IAM ensures that only authorized users can access protected systems and data. <br><br> **CO/COR role:** Confirm that the digital system can be integrated with the agency’s approved IAM platform. <br><br> **Integration requirement:** Vendors should be asked to demonstrate technical compatibility with the agency’s IAM approach as part of their response or during early planning. |
| Vulnerability Management | Every digital system has security vulnerabilities. The goal of vulnerability management is not just patching, it is the comprehensive identification, analysis, remediation, and reporting of vulnerabilities across a digital service's lifecycle. <br><br> **CO/COR role:** Ensure the vendor or technical team has tools, training, and processes to manage vulnerabilities to agency-defined standards. <br><br> **Key activities:** Vulnerability management includes continuous monitoring, security scanning, patching (where applicable), exception tracking, compliance reporting, and incident response coordination. <br><br> **Note:** Patching is a tool, not a solution. Not all vulnerabilities can be addressed with patches, and some require configuration changes, compensating controls, or architectural adjustments. |
| Security Incident and Event Management (SIEM) | SIEM systems detect, analyze, and respond to security events automatically. Agencies rely on centralized SIEM platforms to maintain situational awareness and act quickly on emerging threats. <br><br> **CO/COR role:** Verify that any procured system can fully integrate with the agency’s existing SIEM platform (e.g., Splunk, Elastic, Microsoft Sentinel). <br><br> **Orphaned tools:** If a system cannot be integrated into the existing SIEM infrastructure, the operational overhead for separate monitoring is high and introduces risk. |


### Conclusion

Cybersecurity is not an afterthought, it must be designed into digital services from the start. Contracting officers and CORs must be able to ask the right questions and ensure security compliance, IAM integration, vulnerability management practices, and SIEM readiness are built into the acquisition process.

Through innovative, security-conscious procurement, COs help ensure that government services are trustworthy, resilient, and aligned with federal cybersecurity mandates.

---

## Digital service tech topic: Accessibility

### Why digital accessibility matters

Digital accessibility is fundamental to inclusivity and equality in the modern world. As our lives become increasingly intertwined with technology, it’s imperative that everyone has access to digital spaces, including people with disabilities. When websites, applications, and digital content are not designed with accessibility in mind, they create significant barriers for people with disabilities, effectively excluding them from vital opportunities and information. To ensure that digital spaces are available to everyone, U.S. government agencies are required by law to make technology accessible. 

### Types of disabilities

1 in 4 adults in the United States have some type of disability. People with disabilities are a diverse group and two people with the same disability may even be impacted differently. Disabilities can also be permanent, temporary, or situational. 

| Type of Disability | Permanent Disability | Temporary Disability | Situational Disability |
| ----- | ----- | ----- | ----- |
| **Hearing** | Hearing loss | Ear infection | Being in a loud space, such as a restaurant |
| **Motor** | Arthritis | Broken arm | A new parent holding a baby |
| **Cognitive** | Autism | Concussion or mild head injury | Having a stressful day |
| **Visual** | Blindness | Cataracts | A driver becoming distracted |

Disabilities can make it difficult to interact with digital spaces. Some people use assistive technology tools to help them perform tasks on websites or applications. 

| Type of Disability | Limitation Examples | Accessibility Issues | Assistive Technology |
| ----- | ----- | ----- | ----- |
| **Hearing** | Auditory <br>Hard of hearing <br>Hearing loss | Audio content without captioning <br>Media player with no volume controls <br>Headings not following logical structure | Amplified telephones <br>Alert systems with lights <br>Auto-captioning |
| **Motor** | Quadriplegic <br>Parkinson's disease <br>Arthritis | Controls not working as expected <br>Difficulty with navigation and findability | Speech-to-text<br> Touchpad <br>Eye gaze<br> Brainwave |
| **Cognitive** | Speech impairments <br>Autism<br> Dyslexia and dyscalculia | Difficulty with navigation and findability <br>Remembering previous steps <br>Controls not working as expected | Text to speech <br>Noise cancelling headphones <br>Reader mode |
| **Visual** | Blindness <br>Glaucoma <br>Cataracts <br>Color blindness | Area of content not accessible via screen readers <br>Headings not following logical structure <br>Low color contrast | Screen readers<br> Screen magnifiers |

### Why accessibility matters in federal procurement

In the context of federal procurement, accessibility means making sure that all digital products and services acquired by the government are accessible to both employees and the public, regardless of ability. Federal laws and regulations, such as [Section 508](https://www.access-board.gov/ict/), establish clear responsibilities for procurement teams as part of a broader government-wide effort to build more inclusive digital services. These efforts benefit not only people with disabilities but also seniors, veterans, and anyone facing situational limitations, such as working outdoors or experiencing temporary impairments.

### Digital accessibility is the law

Federal law requires all U.S. government agencies to make their electronic and information technology accessible to people with disabilities. This is established in [Section 508 of the Rehabilitation Act of 1973](https://www.section508.gov/manage/laws-and-policies/), which eliminates barriers to the use of technology, creates new opportunities for people with disabilities, and encourages the development of technologies that help achieve these goals.

In a major update to the standards in 2017, Section 508 now aligns with the [Web Content Accessibility Guidelines (WCAG) 2.0 AA](https://www.w3.org/WAI/standards-guidelines/wcag/), providing a clear and globally recognized benchmark for digital accessibility. It is worth noting that the technical standard for state and local governments’ web content and mobile apps is now WCAG 2.1 AA.

### How to measure accessibility

Federal agencies commonly evaluate information and communication technology (ICT) products for accessibility using an Accessibility Conformance Report (ACR). An ACR is a document that measures how well ICT products comply with Section 508 Standards. During procurement, vendors are encouraged to create an ACR to show how an ICT meets the specific accessibility requirements that are being requested. The most well known ACR is the [Voluntary Product Accessibility Template (VPAT).](https://www.section508.gov/buy/understand-claims/)

### How to procure accessible products and services 

Accessibility should be embedded throughout the acquisition lifecycle. The earlier accessibility is considered in a project's lifespan, the more robust and less expensive it will be to implement. The [Office of Management and Budget Memo M-24-08](https://bidenwhitehouse.archives.gov/omb/management/ofcio/m-24-08-strengthening-digital-accessibility-and-the-management-of-section-508-of-the-rehabilitation-act/) states that buyers need to appropriately articulate requirements for digital accessibility and obtain suitable evidence that the supplier understands and is capable of meeting those requirements.

Government buyers must also perform a technical evaluation and validate vendor documentation of Section 508 conformance for ICT products under consideration prior to purchase, and after purchase, as appropriate, if the ICT product changes or is updated. This helps ensure accessibility is delivered throughout the project lifespan. 

Contracting teams need to develop a plan for risk assessments and documentation of buying, developing, maintaining, and using ICT products that do not meet the [Access Board’s technical standards](https://www.access-board.gov/ict/).

| Phase | How to Incorporate Accessibility |
| ----- | ----- |
| **Creation** | Determine accessibility requirements |
| **Market research** | Consult your accessibility SME to help evaluate ACRs |
| **Solicitation** | Include accessibility criteria in evaluation factors. Reference Section 508 and WCAG |
| **Proposal review** | Evaluate vendors’ testing plans, ACRs, and experience. Inquire about the prospective vendors' processes for incorporating accessibility into their work |
| **Post-Award oversight** | Require validation testing, periodic ACR updates, and inclusive user testing |

### When no accessible options are available

Although Section 508 states that ICT must be accessible, sometimes an accessible option doesn’t exist. In that case, Section 508 guidelines state that the agency should procure the ICT that best meets accessibility standards. 

[E202.7 Best Meets](https://www.access-board.gov/ict/#E202.7) section states “Where ICT conforming to one or more requirements in the Revised 508 Standards is not commercially available, the agency shall procure the ICT that best meets the Revised 508 Standards consistent with the agency’s business needs.” This needs to be clearly documented, to avoid having the procurement challenged by another vendor. 

### Common misunderstandings 

| Myth | Clarification |
| ----- | ----- |
| “A product with an ACR is accessible.” | ACRs are vendor attestations. Test with real users or assistive tech to confirm. |
| “Accessibility is a one-time checkbox.” | Software updates often break accessibility. Contracts should require ongoing validation. |
| “Section 508 doesn’t apply to this procurement.” | Rarely true. There are some exceptions, but they should be very rare and need to be well documented. |
| “Accessibility only helps people with permanent disabilities.” | It benefits everyone. Think: aging users, situational limitations, temporary injuries. |

### Your role

Accessibility isn’t just a compliance requirement; it’s a core part of delivering high-quality, inclusive digital services. As a procurement professional, you play a critical role in ensuring that the products and services acquired by your agency are usable by all people, including those with disabilities. By embedding accessibility into every phase of the acquisition lifecycle, from market research to post-award oversight, your actions help agencies meet legal obligations, reduce long-term risk, and serve the public equitably. Use the tools, templates, and SME support available to make accessibility a built-in expectation.

### Resources and tools

| Resource | Purpose |
| ----- | ----- |
| [ACREditor](https://acreditor.section508.gov/) | Review or generate ACRs |
| [Accessibility Roles and Responsibilities Mapping (ARRM)](https://www.w3.org/WAI/planning/arrm/) | Provides guidance on which roles you can assign responsibilities for accessibility |
| [Accessibility Requirements Tool (ART)](https://www.section508.gov/art) | Define and document accessibility needs during procurement |
| [Accessibility Insights](https://www.google.com/url?q=https://accessibilityinsights.io/&sa=D&source=docs&ust=1754424299274526&usg=AOvVaw1mOO_qLyputqNzV5Aw1893) | A simple browser plugin that works like a spellcheck for accessibility |
| [Disability:INclusive Workplaces](https://disabilityin.org/procurement-toolkit/) [Accessible Technology Procurement Toolkit](https://disabilityin.org/procurement-toolkit/) | Accessible procurement toolkit built for and by the private sector |
| [Section 508](https://www.section508.gov/) | Learn more about Section 508 policies, assessments, and tools |
| [Sample Contracting Language](https://github.com/usds/ditap-curriculum-update/blob/3291fb288be82ec8510a70d68e0156fd7c1f1490/3_Curriculum/3B_DITAP-Core-Curriculum/Module-1/Module-1-Media/sample-contracting-language.md) | Contracting language for accessible procurement and ICT |
| [WGAC 2.2 Understanding Docs](https://www.w3.org/WAI/WCAG22/Understanding/) | Provides detailed explanations for WCAG guidelines and success criteria |

---

## Digital service tech topic: Open source software

### Understanding open source software

Open source software (OSS) is a type of software whose source code is legally available for anyone to view, modify, and distribute. This means users can see how the software works and make changes to their copy of it. To ensure the software remains open, its use and distribution are governed by various open source licenses. These licenses (MIT, BSD, GPL, AGPL, etc.) often define how the updated code must be shared with others, typically requiring that it also be made freely available. A community of developers maintains and improves OSS using collaborative tools to manage changes and address issues like bugs and feature requests. Today, OSS is fundamental to almost all modern digital services, providing benefits like cost reduction, increased innovation, and enhanced security.

Procurement officers need to understand how OSS fits within federal procurement regulations, how to evaluate its viability, and how to structure solicitations to make the best use of OSS. Government security increasingly requires a Software Bill of Materials (SBOM), which is a comprehensive list of all the software components, dependencies, and metadata associated with an application. For both open source and proprietary tools it is a key building block in software security and supply chain risk management. 

### Open source software is used everywhere

If you’ve used the internet, you’ve used OSS. It has become an essential part of modern digital services, with its uses and influence growing rapidly. In fact, the vast majority of commercial codebases [contain open source](https://www.blackduck.com/content/dam/black-duck/en-us/reports/rep-ossra.pdf), and four out of five Fortune 500 companies use OSS for mission-critical functions. A more practical example is that an open source project called [Curl that runs in the world’s top 47 car brands](https://ostechnix.com/curl-runs-in-top-car-brands/). This widespread adoption is projected to continue its high growth rate for the foreseeable future.

### Examples of open source in action

Many of the technologies you interact with daily are built on OSS. 

* The Android operating system, which powers billions of mobile devices, is open source. Its operating system is based on a modified version of the Linux kernel.  
* Streaming services like Netflix rely on open source technologies to deliver content efficiently. Netflix streams over 170 million gigabytes of data every day using FreeBSD. This includes the majority of the web-based technology used to interact with their site and the databases where they store data.  
* The Linux operating system is the foundation for countless servers, supercomputers, and embedded devices around the world. First released as an open source product 30 years ago, it’s the basis of Android OS, Apple iOS, and macOS. It’s also used in security cameras, smartwatches and voice assistants like Alexa. 

**GitHub**

GitHub is a key player in the open source ecosystem, serving as the world's largest repository for software development. It's more than just a place to store code; it's a collaborative platform for version control, bug tracking, managing feature requests, and creating documentation. The reach of GitHub is immense, with users spanning from individual developers to major organizations. Its user base includes 67 national governments, [164 US federal agencies](https://government.github.com/community/), 52 US state and territory governments, almost [20,000 USA businesses](https://theirstack.com/en/technology/github/us) and over [25 million software developers in the USA alone](https://innovationgraph.github.com/global-metrics/developers), highlighting just how integral open source has become to both public and private sectors. In 2018, GitHub was purchased by Microsoft for $7.5 billion, and has continued to define what is expected in modern software development. 

### Why open source software matters in federal procurement

OSS is used in nearly every modern government digital service and is a significant factor in federal procurement because it offers a wide range of benefits that are distinct from traditional proprietary software. If acquisition professionals understand how to evaluate and procure it responsibly, OSS can reduce costs, increase innovation, and support long-term vendor independence.

### Federal laws and policies

Federal agencies operate under specific guidelines that support the use of OSS. The [Federal Acquisition Regulation (FAR)](https://www.acquisition.gov/) gives agencies a procurement advantage by classifying OSS as commercial off-the-shelf (COTS) software, which allows agencies to buy, adopt, or integrate OSS without lengthy procurement processes. This framework is further supported by the [Federal Source Code Policy (OMB M-16-21)](https://digital.gov/resources/requirements-for-achieving-efficiency-transparency-and-innovation-through-reusable-and-open-source-software/), which encourages agencies to reuse existing custom-developed code and release new custom code as OSS.

Building on these policies, the [SHARE IT Act (Public Law 118-187)](https://dsacms.github.io/share-it-act-lp/) mandates that agencies share their custom-developed source code with each other. This legislation is a key part of a broader effort to reduce redundant development and procurement costs across the government. Together, these laws and policies create a clear and supportive environment for federal agencies to leverage the benefits of OSS.

### Security of open source software 

All software, including OSS, faces increasing security risks due to advances in hacking tools and techniques. However, open source often has a distinct advantage: a robust community of developers dedicated to its security. Unlike proprietary software, where security audits are limited to a single company's internal team, OSS code can be inspected and tested by anyone. This collaborative approach allows for vulnerabilities to be identified and fixed much more rapidly than legacy approaches, often within days of discovery.

#### Mitigating security risks

Properly maintained OSS is just as secure as, and often more secure than, its proprietary counterparts. If it were less secure, organizations wouldn't be able to tolerate the risk, and it wouldn't be able to compete in the market. Securing OSS involves following the **same best practices as securing proprietary software**. This includes:

* Adhering to standards for protecting confidentiality, integrity and availability  
* Data remains encrypted at rest and in transit in accordance with its designated classification  
* Using standard user authentication tools to control access  
* Applying regular updates, especially for critical vulnerabilities  
* Periodically auditing activity within the application

### Government initiatives 

The U.S. government is actively involved in strengthening the security of OSS. Several federal agencies contribute to the [Open Source Security Foundation](https://openssf.org/), a collaborative effort to improve security for both open source and private developers. As an example, the Department of Defense’s [Platform One](https://p1.dso.mil/) is heavily leveraging open source to improve security and overcome common barriers. Their [Iron Bank](https://p1.dso.mil/ironbank) project distributes pre-configured, containerized versions of OSS which speeds up the process of getting the required [Authorization to Operate (ATO)](https://csrc.nist.gov/glossary/term/authorization_to_operate). This process ensures that no new vulnerabilities are introduced when the software is reused. These are just a few of the many government-led initiatives which enhance overall security and reduce costs through the use of open source software.

### The cost of "free" open source software

While the initial cost of OSS is often free, its implementation and maintenance are not. When OSS is acquired, the software itself is without charge, but the associated services carry a cost. This model shifts the financial burden from licensing fees to expenses for support and development. These costs are market-driven and can include customization, ongoing monitoring, hosting, support, training, and updates.

### Avoiding vendor lock-in

Vendor lock-in is a risk with any software, but with OSS it is considerably reduced. Vendors should be motivated to provide better value for the client, without making clients dependent on their specific offerings. It is critical that government agencies retain control of their data and ensure it remains portable to other platforms, if necessary. If a project is using OSS, it should be straightforward to move data to a new host and continue using the software. It is always wise to keep a list of alternate vendors and their services, even simply to be aware of changes in the market. It also ensures you have a clear plan for migration if the need arises.

### How to procure open source software

Navigating federal procurement with OSS requires a clear understanding of its unique characteristics and how they fit within the acquisition lifecycle. Using OSS should be considered early, before a decision is made about what software criteria to solicit for.

The first step is to thoroughly understand the specific need the procurement is trying to meet and the goals the solution must achieve. This involves a comprehensive analysis of costs and available features. Due diligence is crucial, including a comparison of OSS solutions with proprietary offerings and seeking advice from other agencies that have successfully adopted open source.

| Phase | Procurement Considerations |
| ----- | ----- |
| **Market Research** | Explore OSS solutions and evaluate the health of their communities and licensing models. |
| **Solicitation** | Avoid overly prescriptive requirements that might exclude OSS. Instead, allow for OSS solutions where viable and include specific evaluation criteria to assess their sustainability and support model. |
| **Proposal Review** | Check the vendor's implementation plan to ensure that all software licenses are compatible with your agency's needs. Confirm they contribute to the open-source community and are not simply users. |
| **Post-Award Oversight** | Continuously track software maintenance and compliance. If a product with an OSS license was selected, ensure that the software will remain OSS beyond the length of the contract. |

#### Do your due diligence

Make sure you’re asking the right questions and learning about the OSS solution.

* Compare a proprietary product with an Open Source option.   
* Consult the advice of others who have pivoted to Open Source.  
* Carefully vet requirements before selecting a solution.   
* Don’t forget about migration costs.  
* Include compliance as a recurring cost.
* Consider independently sponsoring open source projects used.

### Resources and tools

| Resource | Purpose |
| ----- | ----- |
| [CHAOSS Community](https://chaoss.community/) | Organizations with open source program offices exploring improved open source governance practices. |
| [Digital Public Goods Registry](https://www.digitalpublicgoods.net/registry) | Registry of digital solutions recognized as a Digital Public Good (DPG). DPG are a list of pre-approved software applications which have been vetted to ensure they meet generic government needs. |
| [How to Write an RFP for Open Source Solutions](https://www.drupal.org/association/blog/how-to-write-an-rfp-for-open-source-solutions-featuring-drupal-certified-partners) | A guide for crafting a Drupal RFP that prioritizes OSS contributions. |
| [Open Source Initiative Licenses](https://opensource.org/licenses) | Licenses that comply with the Open Source Definition, meaning they allow software to be freely used, modified, and shared. |
| [Open Source Procurement Checklist](https://github.com/usds/ditap-curriculum-update/blob/95198b65bbf6cd698ad649f590d7d8f287635bba/3_Curriculum/3B_DITAP-Core-Curriculum/Module-1/Module-1-Media/open_source_procurement_checklist.md) | A guide to help procurement officers evaluate OSS solutions during digital government acquisitions. |
| [Open Source Procurement FAQ](https://github.com/usds/ditap-curriculum-update/blob/95198b65bbf6cd698ad649f590d7d8f287635bba/3_Curriculum/3B_DITAP-Core-Curriculum/Module-1/Module-1-Media/open_source_procurement_faq.md) | FAQ addressing common concerns procurement officers may encounter when evaluating or acquiring OSS as part of digital government projects. |




