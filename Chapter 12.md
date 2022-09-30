# Chapter 12
    
1. **What are the key functions of network management according to ISO 7498-4?**

According to SGP, system management is divided into two areas: system configuration and system maintenance. 

The objective of system configuration is to develop and enforce consistent system configuration policies that can cope with current and protected workloads and protect systems and the information they process and store against malfunction, cyber attack, unauthorized disclosure, and loss.

The objective of system maintenance is to provide guidelines for the management of the security of systems by performing backups of essential information and software, applying a rigorous change management process, and monitoring performance against agreed service level agreements.
    
#
	
2. **What are the techniques that firewalls use to control access to a site and enforce the site's security policy? Please describe each technique.**

* **Service control**
A firewall determines the types of Internet services that can be accessed, inbound or outbound. The firewall may filter traffic on the basis of IP address, protocol, or port number; it may provide proxy software that receives and interprets each service request before passing it on; or may host the server software itself, such as a web or mail service.

* **Direction control**
A firewall determines the direction in which particular service requests may be initiated and allowed to flow through the firewall.

* **User control**
A firewall controls access to a service according to which user is attempting to access it. This feature is typically applied to users inside the firewall perimeter (local users). It may also be applied to incoming traffic from external users; the latter requires some form of secure authentication technology, such as that provided by IPsec.

* **Behavior control**
A firewall controls how particular services are used. For example, the firewall may filter email to eliminate spam, or it may enable external access to only a portion of the information on a local web server.

#

3. **What are the weaknesses of packet filters?**

* A packet filtering firewall cannot prevent attacks that employ application-specific vulnerabilities or functions as these firewalls do not examine upper-layer data. For example, if a packet filtering firewall cannot block specific application commands and if a packet filtering firewall allows a given application, all functions available within that application will be permitted.

* The logging functionality present in packet filtering firewalls is limited as these firewalls have access to limited information.

* Most packet filtering firewalls do not support advanced user authentication schemes. Once again, this limitation is mostly due to the lack of upper-layer functionality.

* Packet filtering firewalls are generally vulnerable to attacks and exploits that take advantage of problems within the TCP/IP specification and protocol stack, such as network layer address spoofing. Many packet filtering firewalls cannot detect a network packet in which the OSI Layer 3 addressing information has been altered.

* Packet filtering firewalls are susceptible to security breaches caused by improper configurations. This means it is easy to accidentally configure a packet filtering firewall to allow traffic types, sources, and destinations that should be denied based on an organization’s information security policy.

#
    
4. **What are the important characteristics of automated network device configuration management tools?**

* **Multivendor device support**
The solution should support all device types from all popular vendors.

* **Discovery capability for device addition**
The solution should have provision for discovering the devices in the network and automatically adding them, in addition to other device addition options.

* **Communication protocols**
The solution should support a wide range of protocols to establish communication with the device and transfer configuration files.

* **Secure storage**
The configuration data should be stored in encrypted form and protected against intrusion.

* **Inventory**
The solution should provide an informative inventory of the devices being managed. It should provide various details, such as serial numbers, interface details, chassis details, port configurations, IP addresses, and hardware properties of the devices.

* **Configuration operations and schedules**
The solution should provide simple, intuitive options in the GUI to carry out various configuration operations, such as configuration retrieval and viewing, editing, and uploading configurations back to the device.

* **Configuration versioning**
A version number should be associated with the configuration of each device and incremented with each change.

* **Baseline configuration**
The solution should have provision for labeling the trusted configuration version of each device as a baseline version to enable administrators to roll back configurations to the baseline version in the event of a network outage.

* **Access control**
An attribute-based or rol-based access control scheme should be used to provide security when multiple users have access to configuration tools.

* **Approval mechanism**
The security policy in an enterprise may require certain types of changes carried out by certain levels of users to be reserved for review and approval by top administrators prior to the deployment of the changes.

#

    
5. **What are the key risks associated with wireless access?**

* **Insufficient policies, training, and awareness**
Wireless security controls must include policies and user awareness training specifically for wireless access. These should include procedures regarding uses of wireless devices and an understanding of relevant risks.

* **Access constraints**
Wireless access points repeatedly send out signals to announce themselves so that users can find them to initiate connectivity. This signal transmission occurs when beacon frames containing the access points’ service set identifiers (SSIDs) are sent unencrypted. SSIDs are names or descriptions used to differentiate networks from one another. This signal transmission makes it easy for unauthorized users to learn the network name and attempt an attack or intrusion.

* **Rogue access points**
Rogue access points are APs that users install without coordinating with IT. Access controls, encryption, and authentication procedures enable IT to maintain control.

* **Traffic analysis and eavesdropping**
An eavesdropper can snoop the communication and interpret the communication. To counter this threat, it is necessary to use a strong user authentication technique and to encrypt all traffic.

* **Insufficient network performance**
Poor performance may be due to an imbalance in the use of access points, insufficient capacity planning, or a denial-of-service (DoS) attack.

* **Hacker attacks**
Hackers attempt to gain unauthorized access over wireless networks. Intrusion detection systems, antivirus software, and firewalls are mitigation

* **Physical security deficiencies**
This is in the domain of physical security. Both network devices and mobile devices should be subject to physical security policies and procedures


#

6. **How does the Standards Customer Council define the key components of a cloud service agreement (CSA)?**

* **Customer agreement**
This section describes the overall relationship between the customer and the provider. Its terms include how the customer is expected to use the service, methods of charging and paying, reasons a provider may suspend service, termination, and liability limitations.

* **Acceptable use policy**
This section prohibits activities that providers consider to be improper or outright illegal uses of their service. Conversely, the provider usually agrees not to violate the intellectual property rights of the customer.

* **Cloud service level agreements**
These agreements define a set of service level objectives. These objectives may concern availability, performance, security, and compliance/privacy. The SLA specifies thresholds and financial penalties associated with violations of these thresholds. Well-designed SLAs can significantly contribute to avoiding conflict and can facilitate the resolution of an issue before it escalates into a dispute.

* **Privacy policies**
These policies describe the different types of information collected; how that information is used, disclosed, and shared; and how the provider protects that information.

#

7. **In general, email security threats can be classified as follows:**

* **Authenticity-related threat**
This threat arises from not being able to verify authenticity. It could result in unauthorized access to an enterprises’ email system. Another threat in this category is deception, in which the purported author isn’t the actual author.

* **Integrity-related threat**
This threat could result in unauthorized modification of email content.

* **Confidentiality-related threat**
This threat could result in unauthorized disclosure of sensitive information.

* Availability-related threat—This threat could prevent end users from being able to send or receive email.

# 

8. **Some of the key threats for VoIP usage are as follows:**
* **Spam over Internet telephone (SPIT)**
Unsolicited bulk messages may be broadcast over VoIP to phones connected to the Internet. Although marketers already use voicemail for commercial messages, IP telephony makes a more effective channel because the sender can send messages in bulk instead of dialing each number separately.

* **Eavesdropping**
Interception of control packets enables an adversary to listen in on an unsecured VoIP call.

* **Theft of service**
This type of attack involves capturing access codes, allowing the adversary to get into the VoIP provider network and then use the facility.

* **Man-in-the middle attack**
This type of attack involves an adversary inserting as a relay point between two ends of a VoIP call. In addition to eavesdropping, the adversary could divert a call to a third party or generate simulated voice content to create misleading impressions or cause operational errors.

#

# Quiz

1. When a firewall controls access to a service according to which user is attempting to access it, is know as:
* User control
* Personal Control
* Service Control
* None of the above 

##
`a`
#

2. Which of the following is NOT a firewall technique to control access and enforce the site’s security?
* Personal Control
* Direction control
* All of the above
* User Control

##
`a`
##

3. Poor performance may be due to an imbalance in the use of access points, insufficient capacity planning, or a denial-of-service (DOS) attack. This is known as:
* Insufficient Network performance
* Physical security
* Traffic analysis eavesdropping
* Hacker attack

##
`a`
##

4. The attempt to gain unauthorized access over wireless networks. Intrusion detection system, antivirus software, and firewalls are mitigation techniques is known as _____________.
* Eavesdropping
* Hacker attacks
* Unauthorized attack
* None of the above

##
`b`
##

5. In general, email security threats can be classified as which of the following?
* Integrity related threat
* All of the above
* Authenticity related threat
* Confidentiality related threat

##
`b`
##

6. This threat could result in unauthorized disclosure of sensitive information:
* Integrity related threats
* Authenticity related threats
* Confidentiality related threats 
* None of the above

##
`c`
##

7. One way to protect email in which ISO 27002 advocates include protecting messages from unauthorized access, modification, or denial of service commensurate with the classification scheme adopted by the organization:
* True
* False

##
`true`
##

8. ISO 27002 advocates which of the following ways to protect emails?
* All of the above
* Protecting message from unauthorized access, modification, or denial of service commensurate with the classification scheme adopted by the organization
* Ensuring reliability and availability of the service
* Ensuring correct addressing and transportation of the message

##
`a`
##

9. This type of attack involves an adversary inserting as a relay point between two ends of a VoIP call:
* Two point attack
* None of the above
* Midpoint attack
* Man in the middle attack

##
`d`
##

10. One of the key threats for VoIP usage is:
* Spam over internet telephone (SPIT)
* Breach of security
* None of the above
* Integrity related threat

##
`a`
##

11. Which of the following are techniques to control access and enforce the site’s security policy?
* User control
* Direction control
* All of the above
* Service control

##
`c`
##

12. _______ are APs that users install without coordinating with IT. Access controls, encryption, and authentication procedures enable IT to maintain control.
* None of the above
* Access constrains
* Rogue access point
* Traffic analysis and eavesdropping

##
`c`
##

13. This threat could prevent end users from being able to send or receive emails.
* Confidentiality related threat
* Integrity related threat
* Availability related threat
* Authenticity related threat

##
`c`
##

14. A firewall controls how particular services are used. For example, the firewall may filter email to eliminate spam, or it may enable external access to only a portion of the information on a local web server. This control is known as the:
* User control
* Behavior control
* Service control
* Direction control

##
`b`
##

15. Which of the following is not a risk associated with wireless access:
* Access constraints
* Easy access to data
* Physical security deficiencies
* Hacker attacks

##
`b`
##

16. This threat could result in unauthorized modification of email content:
* Confidentiality related threat
* Authenticity related threat
* Availability related threat
* Integrity related threat

##
`d`
##

17. This type of attack involves capturing access codes, allowing the adversary to get into the VoIP provider network and then use the facility:
* Eavesdropping
* Spam over internet telephone
* Man in the middle attack
* Theft of service

##
`d`
   
18. ISO 27002 advocates which of the following ways to protect emails?
* Obtaining approval prior to using external public services such as instant messaging and social network
* Giving legal consideration, such as requirements for electronic signatures
* Using file sharing instead of sending sensitive data unencrypted over email
* All of the above

##
`d`
##




  

