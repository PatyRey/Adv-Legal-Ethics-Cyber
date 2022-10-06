# Chapter 13

1.  **List the categories for security controls for SCRM.**

SP 800-161 organizes security controls for SCRM into the following categories:

- Access control
- Awareness and training
- Audit and accountability
- Security assessment and authorization
- Configuration management
- Contingency planning
- Identification and authentication
- Incident response
- Maintenance
- Media protection
- Physical and environmental protection
- Planning
- Program management
- Personnel security
- Provenance
- Risk assessment
- System and services acquisition
- System and communications protection
- System and information security

2.  **List and describe the three security controls of the provenance family.**

- **Provenance policy and procedures**
    This provides guidance for implementing a provenance policy.
    
- **Tracking provenance and developing a baseline**
    This provides details concerning the tracking process.
    
- **Auditing roles responsible for provenance**
    This indicates the role auditing plays in an effective provenance policy.
    

3. **List and describe the three service models of cloud computing, according to NIST.**

- **Software as a service (SaaS)**
    
- In this model, the consumer can use the provider’s applications running on a cloud infrastructure. The applications are accessible from various client devices through a thin client interface such as a web browser. Instead of obtaining desktop and server licenses for software products it uses, an enterprise obtains these functions from the cloud service. SaaS eliminates the complexity of software installation, maintenance, upgrades, and patches. Examples of services at this level are Gmail, Google’s email service, and Salesforce.com, which helps firms keep track of their customers.
    
- **Platform as a service (PaaS)**
    In this model, the consumer can deploy onto the cloud infrastructure consumer-created or acquired applications created using programming languages and tools supported by the provider. PaaS often provides middleware-style services such as database and component services for use by applications.
    
- **Infrastructure as a service (IaaS)**
    In this model, the consumer is provided with processing, storage, network, and other fundamental computing resources where the consumer is able to deploy and run software, which can include operating systems and applications. IaaS enables customers to combine basic computing services, such as number crunching and data storage, to build highly adaptable computer systems in a short period of time.
    

4.  **Describe some of the threats to cloud service users.**

- **Responsibility ambiguity**
    This arises from the fact that cloud service users consume delivered resources through service models, thereby making the customer-built IT system dependent on those services. The lack of a clear definition of responsibility among cloud service users and providers may evoke conceptual conflicts. Moreover, any contractual inconsistency of provided services could induce anomalies or incidents.
    
- **Loss of governance**
    This refers to reduction on full control of IT systems. The decision by an enterprise to migrate a part of its own IT system to a cloud infrastructure implies giving partial control to the cloud service providers. This loss of governance depends on the cloud service models. For instance, IaaS delegates only hardware and network management to the provider, while SaaS also delegates operating system, application, and service integration in order to provide a turnkey service to the cloud service user.
    
- **Loss of trust**
    It is sometimes difficult for a cloud service user to recognize the provider’s trust level due to the black-box feature of the cloud service. There is no measure to obtain and share the provider’s security level in a formalized manner.
    
- **Service provider lock-in**
    This refers to tight binding with the cloud service provider. Loss of governance could result in lack of freedom in how to replace one cloud provider with another. This could be the case if a cloud provider relies on nonstandard hypervisors or virtual machine image format and does not provide tools to convert virtual machines to a standardized format.
    
- **Insecure cloud service user access**
    As most of the resource deliveries are through remote connections, non-protected APIs (mostly management APIs and PaaS services) are among the easiest attack vectors. Attack methods such as phishing, fraud, and exploitation of software vulnerabilities may achieve results.
    
- **Lack of information/asset management**
    Because the physical assets are not hosted at the user’s premises, a cloud service user may have serious concerns about lack of information/asset management from cloud service providers, such as location of sensitive asset/information, lack of physical control for data storage, reliability of data backup (data retention issues), and disaster recovery. Furthermore, cloud service users also may have important concerns about exposure of data to foreign governments and compliance with privacy laws.
    
- **Data loss and leakage**
    This threat may be strongly related to the preceding item. However, loss of an encryption key or a privileged access code will bring serious problems to cloud service users. Accordingly, lack of cryptographic management information, such as encryption keys, authentication codes, and access privilege, will lead to sensitive damages, such as data loss and unexpected leakage to the outside.
    

5.  **List and define the key components of a cloud service agreement.**

- **Customer agreement**
    This section describes the overall relationship between the customer and the provider. Its terms include how the customer is expected to use the service, methods of charging and paying, reasons a provider may suspend service, termination, and liability limitations.
    
- **Acceptable use policy**
    This section prohibits activities that providers consider to be improper or outright illegal uses of their service. Conversely, the provider usually agrees not to violate the intellectual property rights of the customer.
    
- **Cloud service level agreements**
    These agreements define a set of service level objectives. These objectives may concern availability, performance, security, and compliance/privacy. The SLA specifies thresholds and financial penalties associated with violations of these thresholds. Well-designed SLAs can significantly contribute to avoiding conflict and can facilitate the resolution of an issue before it escalates into a dispute.
    
- **Privacy policies**
    These policies describe the different types of information collected; how that information is used, disclosed, and shared; and how the provider protects that information.
    

* * *

# Quiz

1.  SP 800-161 organizes security controls for SCRM (Supply chain risk management) into which of the following categories

- Awareness and training
- Audit and accountability
- Configuration management
- All of the above

##
`d`
##

2.  SP 800-161 organizes security controls for SCRM (Supply chain risk management) into which of the following categories

- Access control
- Maintenance
- Risk assessment
- All of the above
##
`d`
##

3.  The security controls of the provenance family that provides guidance for implementing a provenance policy.

- Provenance policy and procedures
- Tracking provenance and developing a baseline
- Auditing roles responsible for provenance
- None of the above
##
`a`
##

4.  The security controls of the provenance family that indicates the role auditing plays in an effective provenance policy.

- Provenance policy and procedures
- Tracking provenance and developing a baseline
- Auditing roles responsible for provenance
- None of the above

##
`c`
##

5.  In this model, the consumer can use the provider’s applications running on a cloud infrastructure. The applications are accessible from various client devices through a thin client interface such as a web browser.

- Platform as a service
- Infrastructure as a service
- Software as a service
- None of the above

##
`c`
##

6.  In this model, the consumer can deploy onto the cloud infrastructure consumer-created or acquired applications created using programming languages and tools supported by the provider.

- Platform as a service
- Infrastructure as a service
- Software as a service
- None of the above

##
`a`
##

7.  This arises from the fact that cloud service users consume delivered resources through service models, thereby making the customer-built IT system dependent on those services.

- Service provider lock-in
- Responsibility ambiguity
- Loss of governance
- None of the above

##
`b`
##

8.  Some of the threats to cloud service users are:

- Loss of trust
- Loss of governance
- Responsibility ambiguity
- All of the above

##
`d`
##

9.  These policies describe the different types of information collected; how that information is used, disclosed, and shared; and how the provider protects that information.

- Information policies
- Privacy policies
- Security policies
- Data policies

##
`b`
##

10. This section prohibits activities that providers consider to be improper or outright illegal uses of their service. Conversely, the provider usually agrees not to violate the intellectual property rights of the customer.

- Compliance policy
- Acceptable use policy
- User policy
- Service policy

##
`b`
##

11. Which of the followings is NOT a category that SP 800-161 organizes security controls for SCRM into?

- System and information security
- System and communications protection
- System and data acquisition
- System and services acquisition

##
`c`
##

12. Which of the following is NOT a category that SP 800-161 organizes security controls for SCRM into?

- Incident response
- Contingency planning
- Rapid Elasticity
- Media protection
- Physical and environmental protection

##
`c`
##

13. The security controls of the provenance family that provides details concerning the tracking process.

- Provenance policy and procedures
- Tracking provenance and developing a baseline
- Auditing roles responsible for provenance
- None of the above

##
`b`
##

14. In this model, the consumer is provided with processing, storage, network, and other fundamental computing resources where the consumer is able to deploy and run software, which can include operating systems and applications.

- Platform as a service
- Infrastructure as a service
- Software as a service
- None of the above

##
`b`
##

15. Which of the following is NOT a threat to cloud service users?

- Security breach
- Responsibility ambiguity
- Insecure cloud service user access
- Lack of information/asset management

##
`a`
##

16. These agreements define a set of service level objectives. These objectives may concern availability, performance, security, and compliance/privacy.

- Cloud service level agreements
- Customer agreement
- Policy agreement
- None of the above

##
`a`
##

17. Which of the following is NOT a key component of cloud services according to the Standards Customer Council?

- Customer agreement
- Acceptable use policy
- Increase governance
- Privacy policies

##
`c`
##

18. This refers to a reduction in full control of IT systems. The decision by an enterprise to migrate a part of its own IT system to a cloud infrastructure implies giving partial control to the cloud service providers

- Responsibility ambiguity
- Service provider lock-in
- Loss of trust
- None of the above

##
`d` the right answer is loss of governance