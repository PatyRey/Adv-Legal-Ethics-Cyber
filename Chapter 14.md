# Chapter 14

1. **Security architecture is a unified security design that addresses the necessities and potential risks**
    involved in a certain scenario or environment. Describe the key characteristics.

* It consists of a transparent and coherent overview of models, principles, starting points, and conditions that give a concrete interpretation of the information security policy, usually without speaking in terms of specific solutions.

* It reduces a complex problem into models, principles and subproblems that can be understood.

* The models and principles show where to take which type of measures, when the principles are applicable, and how the principles connect with other principles.

# 

2. **Describe the good malware software capabilities.**

SP 800-83 indicates that good malware software has the following capabilities:

* It must scan critical host components, such as startup files and boot records.

* It must watch real-time activities. Good anti-malware software should be configured to perform real-time scans of each file as it is downloaded, opened, or executed, which is known as on-access scanning.

* It must monitor common applications, such as email, instant messaging software, email clients, and Internet browsers. Good anti-malware software monitors activity involving the applications most likely to be used to infect hosts or spread malware to other hosts.

* It must scan each file for known malware. Anti-malware software on hosts should be configured to scan all hard drives regularly to identify any file system infections and, optionally, depending on organization security needs, to scan removable media inserted into the host before allowing its use.

* It must be capable of identifying common types of malware as well as attacker tools.

* It must be capable of disinfecting and quarantining files. Disinfecting files refers to removing malware from within a file, and quarantining files means storing files containing malware in isolation for future disinfection or examination.

#
3. **Describe some of the best practices for avoiding common security mistakes with IAM( identify management application).**

* Proactively train staff to spot warning signs of phishing attacks and social engineering.
* Patch promptly to guard against attacks.
* Sensibly encrypt data.
* Deploy multifactor authentication judiciously.
* Implement least-privilege access controls by giving access to systems only when it is needed.
* Implement controls and monitoring tools to access privileged systems and data.
* Protect your mobile and cloud applications.
* Stop breaches that start on endpoints by granting access to apps and infrastructure from trusted and secured endpoints.
* Implement portals for accessing the web as SaaS applications using single sign-on (SSO).

# 

4. **Describe some of the common ways to recognize sensitive data in real time.**

* **Rule-based**
Regular expressions, keywords, and other basic pattern-matching techniques are best suited for basic structured data, such as credit card numbers and Social Security numbers. This technique efficiently identifies data blocks, files, database records, and so on that contain easily recognized sensitive data.

* **Database fingerprinting**
This technique searches for exact matches to data loaded from a database, which can include multiple-field combinations, such as name, credit card number, and CVV number.

* **Exact file matching**
This technique involves computing the hash value of a file and monitoring for any files that match that exact fingerprint. This is easy to implement and can be used to check whether a file has been accidentally stored or transmitted in an unauthorized manner.

* **Partial document matching**
This technique looks for a partial match on a protected document. It involves the use of multiple hashes on portions of the document, such that if a portion of the document is extracted and filed elsewhere or pasted into an email, it can be detected.

#

5. **Describe the ingredient of symmetric encryption.**

* Plaintext—This refers to the original message or data block that is fed into the algorithm as input.

* Encryption algorithm—This performs various substitutions and transformations on the plaintext.

* Secret key—This is one of the main inputs to the encryption algorithm. The exact substitutions and transformations performed by the algorithm depend on the key.

* Ciphertext—This refers to the scrambled message produced as output. It depends on the plaintext and the secret key. For a given data block, two different keys produce two different ciphertexts.

* Decryption algorithm—This is the inverse of the encryption algorithm: It uses the ciphertext and the secret key and produces the original plaintext.


***
# Quiz

1. Security architecture is a unified security design that addresses the necessities and potential risks involved in a certain scenario or environment. Its key characteristics are as follows:
  * It consists of a transparent and coherent overview of models, principles, starting points, and conditions that give a concrete interpretation of the information security policy, usually without speaking in terms of specific solutions.
  * It reduces a complex problem into models, principles and subproblems that can be understood.
  * The models and principles show where to take which type of measures, when the principles are applicable, and how the principles connect with other principles.
  * All of the above

##
`a `
##

2. Which of the following is NOT a key characteristic of a security architecture

* It consists of a transparent and coherent overview of models, principles, starting points, and conditions that give a concrete interpretation of the information security policy, usually without speaking in terms of specific solutions.
 * It reduces a complex problem into models, principles and subproblems that can be understood.
 * It must be capable of identifying common types of malware as well as attacker tools
 * All of the above
##
`c `
##

3. Which of the following is NOT a good malware software capability of SP 800-83

*  It must be capable of identifying common types of malware as well as attacker tools
* It must be capable of disinfecting and quarantining files. Disinfecting files refers to removing malware from within a file
* It must scan critical host components, such as startup files and boot records
* All of the above are capabilities

##
`d `
##

4. One of the capabilities SP 800-83 indicates that good malware software has is that it must monitor common applications, such as email, instant messaging software, email clients and internet browsers

 * True
 * False

##
`a`
##

5. Which of the following is one of the best practices for avoiding common security mistakes with IAM?
*  Patch promptly to guard against attacks.
* Sensibly encrypt data.
*  Deploy multi factor authentication judiciously.
* All of the above

##
`d `
##

6. Which of the following is NOT one of the best practices for avoiding common security mistakes with IAM?
* Implement portals for accessing the web as SaaS applications using single sign-on (SSO)
* Proactively train staff to spot warning signs of phishing attacks and social engineering
*  Patch promptly to guard against attacks
*  Search exact matches to data loaded from a database

##
`d `
##

7. This technique searches for exact matches to data loaded from a database, which can include multiple-field combinations, such as name, credit card number, and CVV number. This method is known as:
 * Exact data match
 * Exact file matching
 * Database fingerprinting
 * None of the above

##
`c `
##

8. This technique involves computing the hash value of a file and monitoring for any files that match that exact fingerprint. This is easy to implement and can be used to check whether a file has been accidentally stored or transmitted in an unauthorized manner. This method is known as:
 * Data matching
 * Exact file matching
 * Partial document matching
 * None of the above

##
`b `
##

9. This is one of the main inputs to the encryption algorithm. The exact substitutions and transformations performed by the algorithm depend on it.
*  Decryption algorithm
 * Secret key
 * Plaintext
 * None of the above

##
`b `
##

10. Symmetric encryption has which of the following ingredients?
  * Plaintext
  * Secret key
  * Decryption algorithm
  * All of the above

##
`a `
##
