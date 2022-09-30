# Chapter 11
    
1. **What are the common security threats to servers according to NIST SP 800-123?**
* Malicious entities may exploit software bugs in the server or its underlying operating system to gain unauthorized access to the server. Further, they may attack other entities after compromising a server. These attacks can be launched directly (for example, from the compromised host against an external server) or indirectly (for example, placing malicious content on the compromised server that attempts to exploit vulnerabilities in the clients of users accessing the server).

* Denial-of-service (DoS) attacks may be directed to the server or its supporting network infrastructure, denying or hindering valid users from making use of its services.

* Sensitive information on the server may be read by unauthorized individuals or changed in an unauthorized manner.

* Sensitive information transmitted unencrypted or weakly encrypted between the server and the client may be intercepted.

* Malicious entities may gain unauthorized access to resources elsewhere in the organization’s network via a successful attack on the server.

#

2. **What does virtualization mean? What benefits does it offer to an organization?**

* Virtualization is the process of creating a non-real (or virtual) representation of an entity. 

* It is a technology that provides an abstraction of the computing resources used by some software, which thus runs in a simulated environment called a virtual machine (VM). 

* Virtualization improves efficiency in the use of the physical system resources compared to what is typically seen using a single operating system instance. 

* Virtualization can also provide support for multiple distinct operating systems and associated applications on the one physical system. 

* It can be a very cost-effective solution to a firm that wants to launch its product in a short time and on a small budget.

#
    
3. **What is a hypervisor? What functions does it perform?**

A hypervisor is software that runs on top of hardware and gives services to the VMs by acting as a resource broker. It allows multiple VMs to safely coexist on a single physical server host and share that host’s resources. 

The virtualizing software provides abstraction of all physical resources (such as processor, memory, network, and storage) and thus enables multiple computing stacks, called virtual machines, to be run on a single physical host. 

Principal functions of hypervisor are as follows:

* **Execution management of VM**
This includes scheduling VMs for execution, virtual memory management to ensure VM isolation from other VMs, and context switching between various processor states. It also includes isolation of VMs to prevent conflicts in resource usage and emulation of timer and interrupt mechanisms.

* **Device emulation and access control**
This is all about emulating all network and storage (block) devices that different native drivers in VMs are expecting, mediating access to physical devices by different VMs.

* **Execution of privileged operations by hypervisor for guest VMs**
In certain cases, operations are invoked by guest operating systems, instead of being executed directly by the host hardware, and they may have to be executed by the hypervisor because of their privileged nature.

* **Management of VMs (also called VM life cycle management)**
This is about configuring guest VMs and controlling VM states (for example, start, pause, stop).

* **Administration of hypervisor platform and hypervisor software**
This involves setting parameters for user interactions with the hypervisor host as well as hypervisor software.

#

4. **What does SLA stand for, and what does it mean? What are some common SLAs encountered in an IT organization?**

A service level agreement (SLA) is a contract between a service provider and its internal or external customers that documents what services the provider will furnish and defines the performance standards the provider is obligated to meet.

SLAs are output based, with the sole purpose of specifically defining what service the customer will receive.

Companies that establish SLAs include IT service providers, managed service providers, and cloud computing service providers. 

Three important types of SLAs are as follows:

* **Network provider SLA**
A network SLA is a contract between a network provider and a customer that defines specific aspects of the service that is to be provided.

* **Computer security incident team SLA** 
A computer security incident response team (CSIRT) SLA typically describes the response to an incident, preventive actions to stop such incidents, and steps takes to beef up security of the system.

* **Cloud service provider SLA**
An SLA for a cloud service provider should include security guarantees such as data confidentiality, integrity guarantees, and availability guarantees for cloud services and data.

#

5. **How can organization ensure effective backup?**
* Backups of all records and software must be retained such that computer operating systems and applications are fully recoverable. The frequency of backups is determined by the volatility of data; the retention period for backup copies is determined by the criticality of the data. At a minimum, backup copies must be retained for 30 days.

* Tri level or, better, N level redundancy must be maintained at the server level.At a minimum, one fully recoverable version of all data must be stored in a secure offsite location. An offsite location may be in a secure space in a separate building or with an approved offsite storage vendor.

* Derived data should be backed up only if restoration is more efficient than re-creation in the event of failure.

* All data information accessed from workstations, laptops, or other portable devices should be stored on networked file server drives to allow for backup. Data located directly on workstations, laptops, or other portable devices should be backed up to networked file server drives.

* Required backup documentation includes identification of all critical data, programs, documentation, and support items that would be necessary to perform essential tasks during a recovery period. Documentation of the restoration process must include procedures for the recovery from single-system or application failures, as well as for a total data center disaster scenario, if applicable.

* Backup and recovery documentation must be reviewed and updated regularly to account for new technology, business changes, and migration of applications to alternative platforms.

* Recovery procedures must be tested on an annual basis.

#

6. **List useful guidelines for developing a change management strategy.**

* **Communication** Adequate advance notice should be given, especially if a response is expected and a proper response matrix with contact details is known.

* **Maintenance window** A maintenance window is a defined period of time during which maintenance, such as patching software or upgrading hardware components, can be performed. Clearly defining a regular maintenance window can be advantageous as it provides a time when users should expect service disruptions 

* **Change committee**
The change committee reviews change requests and determine whether the changes should be made. In addition, it may determine that certain changes to the proposed plan for implementing the change must be made in order for it to be acceptable.

* **Critical changes**
There must be provision to accommodate critical changes that are needed to be rushed into production, creating an unscheduled change.

* **Plan the change** All aspects associated with the change (who what, when, and so on) must be carefully planned.

* **Document change requests** 
A change request form provides detailed information about the change and is appropriate for changes affecting data classified as confidential (highest, most sensitive) where protection is required by law and where the asset risk is high and involves information that provides access to resources, physical or virtual.

* **Test the change**
The change should be tested prior to implementation.

* **Execute the change** 
The change should be properly executed.

* **Keep a record of the change**
A log or other record of all changes should be kept to supplement the change request document.

# 

# Quiz

1. Which of the following is NOT a common security threat mentioned in NIST SP 800-123:
* Sensitive information transmitted unencrypted or weakly encrypted between server and the client
* Malicious entities may gain unauthorized access to resources elsewhere in the organization’s network via a successful attack on the server.
* Both of the above are common security threats
* Neither of the above are common security threats

##
`c`
##

2. One common security threat mentioned in the NIST SP 800-123 include that sensitive information transmitted unencrypted or weakly encrypted between the server and the client may be intercepted 
* True
* False

##
`True`
##

3. Which of the following is NOT a principal function of hypervisor?
*  Execution management of VMs
*  Device emulation and access control
*  Data security of VMs
* VM life cycle management

##
`c`
##

4. This is about configuring guest VMs and controlling VM states
*  Execution management of VMs
*  Administration of hypervisor platform and hypervisor software of VM
*  Management of VMs (VM life cycle management)
*  Execution of privileged operations by hypervisor for guest VMs

##
`c`
##

5. ________________________ is a contract between a network provider and a customer that defines specific aspects of the service that is to be provided
* Network provider SLA
*  Computer security incident team SLA
*  Cloud service provider SLA
*  None of the above

##
`a`
##

6. Which of the following is an important type of SLA? 
* All of the above are important types of SLA´s
* Network provider SLA
*  Computer security incident team SLA
*  Cloud service provider SLA

##
`a`
##

7. An organization can ensure effective backup by using which of the following policies?
* Backups of all records and software must be retained such that computer operating systems and applications are fully recoverable.
* All data information accessed from workstations, laptops, or other portable devices should be stored on networked fi le server drives to allow for backup
* Backup and recovery documentation must be reviewed and updated regularly
* All of the above are effective polices

##
`d`
##

8. An organization can ensure effective backup by following which of the following policy?
* Adequate advance notice should be given
* Required backup documentation includes identification of all criterial data, programs, documentation, and support items that would be necessary to perform essential tasks during recovery period
* A maintenance window is a defined period of time during which maintenance, can be performed
* All aspects associated with the change must be carefully planned

##
`b`
##

9. Which of the following are NOT some useful guidelines for developing a change management strategy?
* Cold site, direct attached storage and device emulation and access control
* Critical change, plan the change and document the change
*  Communication, maintenance window, change committee
* Test the change, execute the change, keep a record of the change

##
`a`
##

10. Which of the following are some useful guidelines for developing a change management strategy?
* Communication
* Maintenance window
* Change committee
* All of the above

##
`d`
##

11. Which of the following is a common security threat meantioned in NIST SP 800-123?
* Sensitive information on the server may be read by unauthorized individuals or changed in an unauthorized manner.
* Denial-of-service (DoS) attacks may be directed to the server or its supporting network infrastructure, denying or hindering valid users from making use of its services.
* Malicious entities may exploiy software bugs in the server or its underlying operating system to gain unauthorized access to the server.
* All of the above

##
`d`
##

12. A(an) __________________ is a software that runs on top of hardware and gives services to the VMs by acting as a resource broker. It allows multiple VMs to safely coexist on a single physical server host and share that host's resources.
* VM software broker
* Hypervisor
* Resource library
* None of the above

##
`b`
##

13. This is all about emulating all netwok and storage (block) devices that different native drivers in VMs are expecting, mediating access to physical devices by different VMs.
* Device emulation and access control
* Emulation and access management
* Emulation and access of VMs
* None of the above

##
`a`
##

14. A(an) __________________ is a contract between a service provider and its internal or external customers that documents what services the provider will furnish and defines the performance standards the provider is obligated to meet.
* Service management agreement
* Standard level agreement
* Service level agreement
* None of the above

##
`c`
##

15. Which of the following is an effective backup policy an organization can ensure?
* Recovery procedures must be tested on an annual basis.
* At minimum, one fully recoverable version of all data must be stored in a secure offsite location
* Tri-level or better, N level redundancy must be maintained at the server level 
* All of the above

##
`d`
##

16. Adequate advance notice should be given, especially if a response is expected and a proper response matrix with contact details is known. This guideline for developing a change management strategy is known as:
* Communication
* Intercommunication
* Announcements
* None of the above

##
`a`
##

17. The change should be tested prior to implementation. This guideline for developing a change management strategy is known as:
* Critical change
* Plan the change
* Test the change
* Execute the change

##
`c`
##
