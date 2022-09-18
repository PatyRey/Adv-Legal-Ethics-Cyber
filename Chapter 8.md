# Chapter 8

1. What tasks are part of the initiation phase?

* **Strategy** This task involves ensuring that the system release is fully aligned to all master stratefy and intent

* **Research** This task involve determining opportunities and solution options that meet requirements

* **Feasibility** This task involves ensuring that if the overall strategy ia acceptable to management, then the team takes the next steo to ecamine the viability of the system in terms of economic 

* **Planning** This taks inclides activities such as detailing what will actually go into the systems release (for example, new features and break-fixes) 

* **Requirement** This task is primarily focused on developing the requirements specification of what needs to be accounted for in downstream design and implementation activities


#

2. What are some of the testing types that are deployed during the development /acquisition phase?

* **Integration testing** This type of testing takes as scope all interfaces of the system (to the other entities). Here all data and technology connections are tested for specific system moving through the SDLC (Software Development Life Cycle) and all its upstream dependencies (use layers) and all its downstreams system targets (service layers) 

* **User acceptance testing** This takes as scope the entire system and tests system fucntions that end users will be able to execute while operating in the final production environment

#

3. What is the pilot run strategy in the changeover step of the implementation /assessment phase?
The changeover is implemented by running the new system with data from one or more of the previous periods for the whole system or part of it. The results are compared with the old system results and the old system is replaced if and only if the result prove better. It is less expensive and risky than the parallel run approach

#

4. Explain DevOps as a method of software development and deployment.
The DevOps methodology rest  on the joint effort of all participants- including business unit managers, developers, operation staff, security staff, and end user groups - in creating a product or system collaborating from the beginnig. DevOps can be defined as the best practive of operations and development engineers participating toguether in the entire service life cycle, from design through the development process ro active production support. THe techniques can range from using source control to debugging to testing and to participating in an Agile development process

#

5. **What are the typical stages in the life cycle of an application/system? Please describe them.**

* **Development**
Developers build and deploy code in a test enviriment, and the development team test the application at the most basic level. The application must meet certain criteria for advancement to the next phase

* **System integration testing**
The application is tested to ensure that it works with existing applications and systems. The application must meet the criteria of this enviroment before it can move to the next phase

*  **User acceptance testing**
The application is tested to ensure that it provides the required features for end users. This enviroment is usially production-like. The application must pass these requirements to move to the next phase 

*  **Production**
The application is made available to users. Feedback is capture by monitoring the applicaiton's availability and functionality. Any updates or patches are introduced in the development enviroment to repeat this cycle

#

6. **What are the four phases of the DevOps reference architecture?**

* **Plan and measurement**
THis activity focuses on business units and their planning process. The planning process relates business needs to the outcomes of the development process. This activity can start with small limited proportions of the overall plan, identifying outcomes and resources needed to develop the required sodtware

* **Develop and test**
This activity focuses on the collaborative development, continuous integration of the new code, and continuous testing of the systems. It focuses on catching the synergies of the development and testing teams. 

* **Release and deploy**
THis activity provides a continuous delivery pipeline that automates deployment to test and production enviroments using variety of tools. Releases are managed centrally in a collaborative environment thatleverages automation. Deployment and middleware configurations are automated and then matures to a self-service model that gives individual developers, teams, testers and deployment managers the capability to continueously build, provision, deploy, test and promote

* **Monitor and optimized**
This activity includes the practice of continuous monitoring, customer feedback, and optimization to monitor how applications are performing, allowing business to adapt their requirements as needed

# 
7. DevOps rests on two key foundations. Name them.
The two key foundations are **collaboration** and **automation**. Collaboration begins with management policy to encourage and require the various actors in the software development and deployment process to work toguether. Automation consists of tools that support collaboration and are designed to automate as much as posible this cycle process

#

8. Explain the term control gates from SDLC (Software Development Life Cycle) point of view.
Control gates are decision points at the end of each phase when the system needs be evaluated and management needs to determine whether the project should continue as is, change directions, or be discontinued. Typical examples of control gates are performance review, code review, and financial feasibility analysis.

#

9. **What are the key security considerations through the SDLC (Software Development Life Cycle)?**

* **Secure concept of operations**
There should be an operations or business continuity documents for secure development that contains a contingency plan for the code repository as well as documents as both are predominant work products of software and system development and should be preserved in the event of interruption to the development enviroment

* **Standard and process**
These play a role of a guide and help decide and document appropiate security process for the assurance level required by the system

* **Security training for development team**
Additional security training may be needed for key developers to understand the current threats and potential exploitation of their products as well as training for secure design and coding techniques, based on the prevaling standards and needs

* **Quality management**
This include planning, assurance, and control that are keys to ensuring minimal defects in and proper execution of the information system. 
*  **Secure enviroment**
The development enviroment  - including workstation, servers, network devices, and code repositories - needs to meet the organization's security requirements. **A secure development enviroment is a prerequisete for developing secure software and systems  

*  **Secure code practices and repository**
These should be religiously follow. Special attention should be placed on code repositories, with emphasis on systems thar support distributed code contribution with check-in/check-out functionality. 

#

10. **What are some of the control gates at the development/acquisition phase?**

* **Architecture/design review**
Here you do review of the security architecture and design that evaluates its integration with other systems and the overall enterprise architecture

* **Performance review**
Here you evaluate whether the system meets the docuemnted expectation of the owner and whether the system behaves in a predictable manner if it is subjected to improper use

* **Functional test review**
Here you ensure that functional requirements are sufficiently detailed and are testable after deployment

* **Risk management review**
Here your review the risk management decisiones made up to that point and their impact on the systems or its security controls

* **Mid-project status and finantial review**
Here you determines if there have been changes in the planned level of effort and evaluate the effect on cost and benefits


#

11. What are the key activities for the disposal phase?
* Create disposal/transition plan
* Ensure information protection
* Sanitize media
* Dispose of hardware and software
* Close system


#

12.**What are the best practices for managing the SDLC according to the International Foundation for Information Technology?**

* **Ownership**
Assign full, unambiguous accountability for system development management to key individuals, committees, or departments

* **Inventory**
Religiously maintain a central database of all items related to the management of system development, including requirements, deliverables and the status of control gates

* **Terminology**
Be consistent in the use of standard terminology for the various aspects of system development

* **Data centralization**
Mantain code data - that is data that is required by or is useful for stakeholders involved in system development in a central repository

* **Metrics**
ENsure that management discuss and agree on a set of performancemetric thatcan be defined tracked and analyzed to assess progress in systemdevelopment

*  **Standards and best practices**
Follow to maximus extend possible, industry standards and best practices for system development. This helps interoperability and legal compliance

*  **Transparency**
Strive to make any and all system development mangement data transparent to all other appropiate stakeholders, at minimum and often to the entire enterprise

#

13. According to the International Foundation for Information Technology, what are some key environments associated with system development?
* Research
* Developer work space
* Centralized build
* Integration testing
* User acceptance testing
* Production

***
# Quiz

1. When the application is tested to ensure that it provides the required features for end users, it si know as:
**User Aceptance testing**

2. When applications is tested to ensure that it works with existing application and system is also know as:
**System integration testing**

3. In the ________ and _______ phase the focus in on the collaborative development, continuous integration of new code, and continue resting of the system:
**Developing and testing**

4. All of the following are phases of the DevOps reference architectures EXCEPT for:
* Plan and measure
* Develop and test
* Implement and improve
* All of the above are phases of the DevOps reference architecture

`c`

5. All of the following are key security considerations that exist throughout the SDLC except:
* Security enviroment
* Quality management
* Standard and Processes
* Security testing

`d`

6.  All of the following are key security considerations that exit throughout the SDLC except:
* Secure code practices abd repositories
* Standards and processes
* Secure environment
* All of the above are key security consideration

`d`

7. Which of the following is NOT a control gate at the development/acquisition phase:
* Risk management review
* Performance review
* Functional test review
* All of the above are control gates

8. In which control gate do you evaluate whether if the system meets the documented expectation of the owner and whether the system behaves in a predictable manner if it is subjected to improper use:
**Performance Review**

9. In which best practice for managing SDLC do you strive to make any and all system managenment data clear to all other  appropiate stakeholders?
**Tranparency**

10.  Which of the following is a best practice for managing SDLC according to the international Foundation for Informaiton Technology:
**Inventory**





