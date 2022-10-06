# Chapter 15
    
1. **List and describe the five key steps involved in vulnerability management.**

A technical vulnerability is a hardware, software, or firmware weakness or design deficiency that leaves an information system open to assault, harm, or unauthorized exploitation, either externally or internally, thereby resulting in unacceptable risk of information compromise, information alteration, or service denial. 

Five key steps are involved in vulnerability management:

* **Plan vulnerability management**
This first step in managing technical vulnerabilities involves many things, such as integration with asset inventory, establishment of clear authority to review vulnerabilities, proper risk and process integration, and integration of vulnerabilities with the application/system life cycle.

* **Discover known vulnerabilities**
This involves monitoring sources of information about known vulnerabilities to hardware, software, and network equipment.

* **Scan for vulnerabilities**
Apart from regular monitoring, enterprises should regularly scan software, systems, and networks for vulnerabilities and proactively address those that are found.

* **Log and report**
After the vulnerability scan, the results should be logged to verify the activity of the regular vulnerability scanning tools.

* **Remediate vulnerabilities**
The enterprise should deploy automated patch management tools and software update tools for operating system and software/applications on all systems for which such tools are available and safe. As a good practice, patches should be applied to all systems.

# 

2. **What are some of the technical tools used to prevent delivery?**

* **Antivirus software (AVS)**
AVS is a program that monitors a computer or network to identify all major types of malware and prevent or contain malware incidents. Continuously running AVS can identify, trap, and destroy incoming known viruses. If a virus is detected, the AVS can be configured to trigger a scan of the rest of the IT infrastructure for indicators of compromise associated with this outbreak.

* **Firewall**
A firewall can block delivery attempts from known or suspected hostile sources.

* **Web application firewall (WAF)**
A WAF is a firewall that monitors, filters, or blocks data packets as they travel to and from a web application.

* **Intrusion prevention system (IPS)**
An IPS is a system that can detect an intrusive activity and can also attempt to stop the activity, ideally before it reaches its targets. This is similar to an intrusion detection system but is proactive in attempting to block the intrusion

#

3. **List the objectives for security incident management.**

* Information security events are detected and dealt with efficiently. This involves deciding when they should be classified as information security incidents.

* Identified information security incidents are assessed and responded to in the most appropriate and efficient manner.

* The adverse effects of information security incidents on the organization and its operations are minimized by appropriate controls as part of incident response.

* A link with relevant elements from crisis management and business continuity management through an escalation process is established.

* Information security vulnerabilities are assessed and dealt with appropriately to prevent or reduce incidents.

* Lessons are learned quickly from information security incidents, vulnerabilities, and their management. This feedback mechanism is intended to increase the chances of preventing future information security incidents from occurring, improve the implementation and use of information security controls, and improve the overall information security incident management plan.

#

4. **List and describe the classifications of security incidents.**
* **Emergency**—Severe impact. These are incidents that:
	1. Act on especially important information systems and
	2. Result in especially serious business loss or
	3. Lead to especially important social impact

* **Critical**—Medium impact. These are incidents that:
	1. Act on especially important information systems or important information systems and
	2. Result in serious business loss or
	3. Lead to important social impact

* **Warning**—Low impact. These are incidents that:
 	1. Act on especially important information systems or ordinary information systems and
 	2. Result in considerable business loss or
 	3. Lead to considerable social impact
 
 * **Information**—No impact. These are incidents that:
 	1. Act on ordinary information systems and
 	2. Result in minor business loss or no business loss or
 	3. Lead to minor social impact or no social impact

#

5. **What are the typical phases in a digital forensics process?**
* **Preparation**
This refers to the planning and policy-making activities related to forensic investigation. SP 800-86 recommends the following considerations:
	1. Organizations should ensure that their policies contain clear statements addressing all major forensic considerations, such as contacting law enforcement, performing monitoring, and conducting regular reviews of forensic policies and procedures.
	2. Organizations should create and maintain procedures and guidelines for performing forensic tasks, based on the organization’s policies and all applicable laws and regulations.
	3. Organizations should ensure that their policies and procedures support the reasonable and appropriate use of forensic tools. Organizations should ensure that their IT professionals are prepared to participate in forensic activities.

* **Identification**
This phase is initiated when there is a request for a forensic analysis. This phase involves understanding the purpose of the request and the scope of the investigation, such as type of case, subjects involved, and system involved. The identification phase determines where the data of interest are stored and what data can be recovered and retrieved.

* **Collection**
When the location or locations of data are identified, the forensic process ensures that the data are collected in a manner that preserves the integrity of the evidence.

* **Preservation**
Several actions comprise the preservation of data process, including the following:
	1. Creating a log that documents when, from where, how, and by whom data were collected
	2. Storing the data in a secure fashion to prevent tampering or contamination
	3. Logging each access to the data made for forensic analysis

* **Analysis**
Examples of analysis tasks include:
	1. Checking for changes to the system such as new programs, files, services, and users
	2. Looking at running processes and open ports for anomalous behavior
	3. Checking for Trojan horse programs and toolkits
	4. Checking for other malware
	5. Looking for illegal content
	6. Looking for indicators of compromise
	7. Determining the who, when, where, what, and how details of a security incident

* **Reporting**
This phase involves publishing a report resulting from a forensic investigation. SP 800-86 lists the following factors that affect reporting for any type of investigation.
	1. **Alternative explanations:**
	The available information may not provide a definitive explanation of the cause and nature of an incident. The analyst should present the best possible conclusions and highlight alternative explanations.
	2. **Audience consideration:**
	An incident requiring law enforcement involvement requires highly detailed reports of all information gathered and can also require copies of all evidentiary data obtained. A system administrator might want to see network traffic and related statistics in great detail. Senior management might simply want a high-level overview of what happened, such as a simplified visual representation of how the attack occurred and what should be done to prevent similar incidents.
	5. **Actionable information:**
	Reporting also includes identifying actionable information gained from data that allows an analyst to collect new sources of information. For example, a list of contacts may be developed from the data that can lead to additional information about an incident or a crime. Also, information that is obtained might help prevent future events, such as learning about a backdoor on a system that is to be used for future attacks, a crime that is being planned, a worm scheduled to start spreading at a certain time, or a vulnerability that could be exploited.
	
	
#
# Quiz

1. A technical ____________________________ could be a hardware, software, or firmware weakness or design deficiency that leaves an information system open to assault, harm, or unauthorized exploitation, either externally or internally, thereby resulting in an unacceptable risk of information compromise, information alteration, or service denial. 
* Error
* Data mismanagement
* Vulnerability
* None of the above

##
`c`
##

2. Which of the following is NOT a key step are involved in vulnerability management?
 * Scan for vulnerabilities
 * Remove known vulnerabilities
 * Remediate vulnerabilities
 * Discover known vulnerabilities

##
`b`
##

3. A (an) ______________________________ is a system that can detect an intrusive activity and can also attempt to stop the activity, ideally before it reaches its targets.
*  Antivirus software
*  Web application firewall
*  Intrusion prevention system
* None of the above

##
`c`
##

4. A(an)  _____________________ is a firewall that monitors, filters, or blocks data packets as they travel to and from a web application.
*  Web application firewall
*  Antivirus software
*  Intrusion prevention system
*  None of the above

##
`a`
##

5. ISO 27035-1 lists which of the following objectives for security incident management?
* Information security events are detected and dealt with efficiently. This involves deciding when they should be classified as information security incidents.
* Identified information security incidents are assessed and responded to in the most appropriate and efficient manner.
* The adverse effects of information security incidents on the organization and its operations are minimized by appropriate controls as part of incident response.

*  All of the above

##
`d`
##

6. One of the following objectives for security incident management is to patch discovered vulnerabilities to prevent damage
*  True
*  False

##
`false`
##

7. ISO 27035 classifies security incidents in which of the following ways?
 * Emergency
 * Critical
 * Warning
 * All of the above

##
`d`
##

8. Which of the following classification of security incidents has medium impact?
*  Warning
*  Critical
*  Emergency
*  None of the above

##
`b`
##

9. Typical phases in a digital forensics process include which of the following?
*  Preparation
*  Identification
*  Collection
*  All of the above

##
`d`
##

10. This phase is initiated when there is a request for forensic analysis. This phase involves understanding the purpose of the request and the scope of the investigation, such as the type of case, subjects involved, and system involved.
 * Identification
 * Evaluation
 * Reporting
 * None of the above

##
`a`
##
