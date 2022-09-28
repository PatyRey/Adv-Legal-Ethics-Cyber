# Chapter 10

1.  **What are some typical attacks on password-based authentication? Enumerate countermeasures for each case.**
* **Offline dictionary attack**
In this type of attack, an attacker bypasses system controls and gains access to the password file. The attacker obtains the system password file and compares the password hashes against hashes of commonly used passwords. If a match is found, the attacker can gain access by using that ID/password combination. Countermeasures include controls to prevent unauthorized access to the password file, intrusion detection measures to identify a compromise, and rapid reissuance of passwords in the event that the password file is compromised.

* **Specific account attack**
This is a variation of the preceding attack type, but here the attacker uses a popular password and tries it against a wide range of user IDs. A user’s tendency is to choose a password that is easily remembered; this unfortunately makes the password easy to guess. Countermeasures include policies to inhibit the selection by users of common passwords and scanning the IP addresses of authentication requests and client cookies for submission patterns.

* **Password guessing against a single user**
Here the attacker attempts to gain knowledge about the account holder and system password policies and uses that knowledge to guess the password. Countermeasures include training in and enforcement of password policies that make passwords difficult to guess. Such policies address the secrecy, minimum length of the password, character set, prohibition against using well-known user identifiers, and length of time before the password must be changed.

* **Workstation hijacking**
Here the attacker waits until a logged-in workstation is unattended. The standard countermeasure is automatically logging the user out of the workstation after a period of inactivity. Intrusion detection schemes can be used to detect changes in user behavior.

* **Exploiting user mistakes**
This type of attack exploits users’ mistakes. A user may intentionally share a password to enable a colleague to share files, for example. Also, attackers are frequently successful in obtaining passwords by using social engineering tactics that trick the user or an account manager into revealing a password. Countermeasures include user training, intrusion detection, and simpler passwords combined with another authentication mechanism.

* **Exploiting multiple password use**
Here the attacker can harm more than one system as the user has set the same password for multiple systems. Countermeasures include a policy that forbids using the same or similar password on particular network devices.

* **Electronic monitoring**
Here the attack can snoop the network traffic to extract a password that is transmitted over a network. Simple encryption will not fix this problem because the encrypted password is, in effect, the password and can be observed and reused by an adversary.

 #
   
2.  **Describe major vulnerabilities of password file protection.**

* A hacker may be able to exploit a software vulnerability in the operating system to bypass the access control system long enough to extract the password file. Alternatively, the hacker may find a weakness in the file system or database management system that allows access to the file.

* An accident of protection or a manual slip might render the password file readable, thus compromising all the accounts.

* Some users may have accounts on other machines in other protection domains, for which they might use the same password. Thus, if the passwords could be read by anyone on one machine, a machine in another location might be compromised.

* A lack of or weakness in physical security may aid a hacker. Sometimes there is a backup to the password file on an emergency repair disk or archival disk. Access to this backup enables the attacker to read the password file. Alternatively, a user may boot from a disk running another operating system such as Linux and access the file from that operating system.

* Instead of capturing the system password file, another approach to collecting user IDs and passwords is through sniffing network traffic when a user is trying to log in to an unsecured channel.    

#

3.  **Describe the likely threats to possession-based authentication.**
    
* **Theft**
An attacker can steal a token device. If a second factor is required, such as a PIN, the attacker must also use some means to obtain or guess the PIN. If the second factor is biometric, the attacker must come up with some way of forging the biometric characteristic.

* **Duplication**
The attacker gains access to the device and clones it. Again, if a second factor is required, the attacker’s task is more formidable.

* **Eavesdropping/replaying**
The authenticator secret or authenticator output is revealed to the attacker as the subscriber is authenticating. This captured information can be used later. If there is a time-sensitive aspect to the exchange, such a nonce or the use of an OTP, this latter attack can be thwarted.

* **Replay**
If the attacker can interpose between the token device and the server, this constitutes a man-in-the-middle attack, in which the attacker assumes the role of the client to the server and the server to the client.

* **Denial of service**
The attacker makes repeated failed attempts to access the server, which may cause the server to lock out the legitimate client.

* **Host attack**
The attacker may gain sufficient control of the authentication server to enable the attacker to be authenticated to an application.


4.  **Describe criteria used in designing a biometric system.**
* **Universality** 
A very high percentage of the population should have the characteristic. For example, virtually everyone has recognizable fingerprints, but there are rare exceptions.

* **Distinctiveness**
No two people should have identical characteristics. For some otherwise acceptable characteristics, identical twins share virtually the same patterns, such as facial features and DNA, but not other features, such as fingerprints and iris patterns.

* **Permanence**
The characteristic should not change with time. For otherwise acceptable characteristics, such as facial features and signatures, periodic reenrollment of the individual may be required.

* **Collectability**
Obtaining and measuring the biometric feature(s) should be easy, non-intrusive, reliable, and robust, as well as cost-effective for the application.Performance—The system must meet a required level of accuracy, perform properly in the required range of environments, and be cost-effective.

* **Circumvention**
The difficulty of circumventing the system must meet a required threshold. This is particularly important in an unattended environment, where it would be easier to use such countermeasures and a fingerprint prosthetic or a photograph of a face.

* **Acceptability**
The system must have high acceptance among all classes of users. Systems that are uncomfortable to the user, appear threatening, require contact that raises hygienic issues, or are non-intuitive are unlikely to be acceptable to the general population.

#
    
5.  **What does AAL stand for? What are the levels for AAL? Please describe each level.**
**NIST SP 800-63** provides a useful way of characterizing the risk of an authentication system by using the **concept of authentication assurance level (AAL).** 
The AAL describes the degree of confidence in the registration and authentication processes. A higher level of AAL indicates that an attacker must have better capabilities and expend greater resources to successfully subvert the authentication process.

…

# Quiz

1. The attack on passwords-based authentication in which the attack can snoop the network traffic to extract a password that is transmitted over a network. This method is known as:

* Electronic Monitoring
* Exploring multiple password use
* Workstation hijacking 
* None of the above

##
`a`

##

2. Which of the following is a common attack on password-based authentication?

* Offline directory attack
* Specific account attack 
* Workstation hijack
* All of the above are common attacks on password-base

##
`d`
##

3. One of the major vulnerabilities of password file protection include an accident of protection or a manual slip to render the password file readable

* True
* False

##
`a`

##

4. Which of the following is a major vulnerability of password file protection:

* An accident of protection or  a manual slip might render the password file readable thus compromising all the accounts

* Some users may  have accounts on other machines in other protection domains, for which they might use the same password

* A lack of weakness in physical security may aid a hacker

* All of the above are major vulnerabilities of password protection

##
`d`
##

5. If the attacker can interpose between the token device and the server, this constitute a man-in-the-middle attack, in which the attacker assumes the role of the client to the server and the server to the client. This possible threat to possession-based authentication is know as:

* Eavesdropping 
* Host attack
* Theft
* Replay

##
`d`
##

6. When the attacker repeated failed attempts to access the server which may cause the server to lock out the legitimate client. This is referred to as:

* Denial of service 
* Denial of access
* Denial of data
* None of the above

##
`a`
## 

7. Obtaining and measuring the biometric feature(s) should be easy, non-intrusive, reliable, and robust, as well as cost-effective for the application. These criteria in designing a biometric system are known as:
* Collectability
* Performance
* Universality
* None of the avobe

##
`a`
##

8. Major criteria in designing a biometric system  requires no two people should have identical characteristics?
* Uniqueness
* Individuality
* Distinctiveness
* None of the above

##
`c`
##

9. The NIST SP 800-63 describes the degree of confidence in the registration and authentication processes.
* True
* False

##
`false`
##

10. The _______________________________ (AAL) describes the degree of confidence in the registration and authentication processes. A higher level of AAL indicates that an attacker must have better capabilities and expend greater resources to successfully subvert the authentication process.

* Access Assurance Level
* Authentication Access Level
* Authentication Assurance Level
* None of the above

##
`c`
##

11. The attack on password-based authentication in which the attacker uses a popular password and tries it against a wide range of user IDs, is known as:
* Offline dictionary attack
* Specific account attack (or popular password attack)
* Exploiting multiple password use
* Electronic monitoring

##
`b`
##

12. Which of the following is a major vulnerability of password file protection? 
* Instead of capturing the system password file, another approach to collecting user IDs and passwords is through sniffing network traffic when a user is trying to log in to an unsecured channel
* A lack of weakness in physical security may aid a hacker
* A hacker may be able to exploit a software vulnerability in the operating system to bypass the access control system long enough to extract password file
* None of the above are major vulnerabilities of password file protection
* All of the above are major vulnerabilities of password file protection

##
`e`
##

13. Which of the following is NOT a possible threat to possession-based authentication?
* Theft
* Replay
* Workstation hijacking
* None of the above

##
`c`
##

14. _________________________ is when the attacker gains access to the device and clones it.
* Duplication
* Cloning techniques
* Host attack
* None of the above

##
`a`
##

15. Which of the following is a major criteria in designing a biometric system in which the difficulty of circumventing the system should meet a required threshold?

* Circumvention
* Permanence
* Acceptability
* Performance

##
`a`
##

16. Which of the following is NOT a major criteria in designing a biometric system?
* Universality
* Distinctiveness
* Accessability
* Performance
* Host Attack

17. Which or the following provides a useful way of characterizing the risk of an authentication system by using the concept of authentication assurance level? 
* NDIP SP 80
* NIST SP AAL 63
* NIST SP 800-63
* NIST DP 80063

##
`c`
