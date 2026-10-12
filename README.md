[assets, threats, and vulnerablities.md](https://github.com/user-attachments/files/33345531/assets.threats.and.vulnerablities.md)# assets-threats-and-vulnerabilities-notes
Personal notes created while learning assets, threats, and vulnerabilities as part of my cybersecurity journey.

# Purpose
This repository documents my learning progress and serves as a reference for reviewing concepts I've studied.

#note
[Upl# Security Planning, Assets, Threats, and Vulnerabilities

## 1. Security Planning

Security planning is the process of creating rules, procedures, and strategies to protect an organization's assets and information from security risks.

**Examples:**

* Creating security policies.
* Planning incident response procedures.
* Preparing backup and disaster recovery plans.

## 2. Assets

An asset is anything valuable to an organization that needs protection.

**Examples:**

* Data and confidential information.
* Computers and servers.
* Networks and software.
* Employees and intellectual property.

## 3. Threats

A threat is any circumstance or event that could harm an asset or negatively affect an organization.

**Examples:**

* Malware and ransomware attacks.
* Phishing emails.
* Insider threats from employees or contractors.
* Natural disasters, such as floods or fires.

## 4. Vulnerabilities

A vulnerability is a weakness in a system, application, network, or process that a threat could exploit.

**Examples:**

* Weak passwords.
* Outdated software.
* Misconfigured security settings.
* Unpatched software vulnerabilities.

## 5. How They Relate

* **Asset:** What needs protection.
* **Threat:** What could cause harm.
* **Vulnerability:** A weakness that could be exploited.
* **Risk:** The possibility and potential impact of harm occurring.

**Example:**

An organization's customer database is an asset. A cybercriminal is a potential threat. An unpatched database server is a vulnerability. If the criminal exploits that weakness to steal customer information, the organization experiences a security incident.

## 6. Security Planning and Risk Reduction

Organizations can reduce risk by identifying valuable assets, assessing threats and vulnerabilities, applying security controls, updating software, and regularly reviewing their security plans.

## ***risk factors***
- [ ] **threats**
- [ ] **vulnerabilities**

## threats
**there are usually 2 types of threats**
- [ ] **intentional threats**
- [ ] **unintentional threats**

## ***intentional threats***
**intentional threats are like a malicious hacker gets acces to important documents and data that can potentialy lead an breach or maay harm the organization**

## ***unintentional threats***
 **unintentional threats are like an employee from an organization may hold the door way to help an malicious person gaain access to any confidential data**

 ***key take aways***
 **an unintentional or an intentional threat both can cause minimum to massive dmg to an organization**
**______________________________________________________________________________________________________________**

## ***asset inventory***
**an catalog of assets that needs to be protected**

## ***asset classification***
**aan hierarchy for assets that needs to be more secure then others as if they gggets exploited they will do more damage**
## for example
**we keep our wallet more then our shoes cuz if the shoes gets exploited or stolen we will not suffer from severe damage while if the wallet does then it will be aaa headache to find a car to home**

## ***levels of asset classifications***
- [ ] **public**
- [ ] **internal only**
- [ ] **confidential**
- [ ] **restricted**
## data
**information that is translated processed or stored by a computer**

## ***states of data***
- [ ] **in use**
- [ ] **in transit**
- [ ] **at rest**

##  **data in use**
**data being accessed by one or more users**

## ***data in transit***
**data traveling from one point  ot another**

## ***data at rest***
**data not currently being accessd**

## ***information security(InfoSec)***
**the practice of keeping data in all states away from unauthorized users**


##  ***note :*** risks are usually divied in categories such as damage , disclosure , loss of information

## ***security plans*** 
 **a security plan is a document that describes how an organization protects its assets indentifies pontential threats and vulnerablities**

## ***elements of a security plan***
 - [ ] **policies**
 - [ ] **standards**
 - [ ] **procedures**
## policy
**a set of rules taht reduces risk and protects information**

## standards
**references that informahow to set policies**

## procedures
**step by step instruction to perform a specific security task**

## ***The NIST Cybersecurity Framework***
 ## ***Compliance***
 **the process of adheringg to internal standards external regulation**

 ## ***Regulations***
 **Rules set by a government or other authority tto controll the way something is done**

 ## ***The NIST Cybersecurity Framework(CSF)***
 **A voluntry framework that consists of standards guidelines and best practices to manage cybersecurity risk**


 ## ***five functions of NIST CSF core***
 - [x] **identify**
 - [x] **protect**
 - [x] **detect**
 - [x] **respond**
 - [x] **recover**


 ## note: NIST was orginally released in 2014 
 
 ## CSFA COMPONENTS
 - [ ] **core**
 - [ ] **tiers**
 - [ ] **profiles**

## security controlls
**safe guards designed to reduce specific security risks**

## types of security controlls
- [ ] **technical**
- [ ] **operational**
- [ ] **managerial**

 ***technical***
 **techincal includes the mini technologies like encryption authentication etc**

 ## operational ##
 **operatioal controlls relate to maintainning data daily environtment**

 ## information privacy 
 **the protction of unauthorized access and distribution of data**

 ## principle of least privilege
 **the concept of granting oonly the minimal access aand authorization required to coomplete a task or function**

##   Data owner
**the persoon that decides who can access edit use or destroy their information**

##  data custodian
 **anyone or anything thaat responsible for the safe handling transport and storage of information**

## Data steward 
**the person or group that maintains and implements data governance  policies**

 ## tip : 
 **paasswords play an important role when implementing the principle of least privilege. even if user aaccounts aare assigned            appropriately,an insecure passsword can compromise ur systems**

 ## Auditing account privileges
 **there are 3 commonn approaches to auditing user accounts:**
1. **usage accounts**
2. **privilege audits**
3. **account change audits**

## most directory services can be conofigured to alert system aadministraatoss of suspicious activity

## The data life cycle
**in general dataa lifecycle has 5 stages:**
1. **collect**
2. **store**
3. **use**
4. **archive**
5. **destroy**

## Types of Sensitive Information

- **PHI (Protected Health Information):** Identifiable information about a person's health, medical history, or healthcare.  
  *Example:* A patient's medical record linked to their name.

- **PII (Personally Identifiable Information):** Information that can identify a specific person, directly or when combined with other data.  
  *Example:* Full name, national ID number, or email address.

- **SPII (Sensitive Personally Identifiable Information):** Highly sensitive personal information that could cause serious harm if exposed or misused.  
  *Example:* Passwords, financial account credentials, or sensitive government identification data.

  General Data Protection Regulation (GDPR)

Payment Card Industry Data Security Standard (PCI DSS)

Health Insurance Portability and Accountability Act (HIPAA)

## Cryptography
**the process of transforming information into form that unintended readers cant understand**

## Algorithm
**a set of rules used that solve a problem**

## Cipher
**An algorithm that encrypts information**

## Cryptographic key
**A mechanism that decrypts ciphertext**

## Brute force attack
**A trial and error process of discovering private information**

## public key infrastructure (PKI)
**An encryption framework that secures the exchange of information online**

## (PKI) is a 2 step process : 1 exchange of encrypted information

## exchange of encrypted information
**may include asymmetric encryption or symmetric encryption**

## Note: encryption are usually 2 types one is asymmetric and another is symmetric encryption

## Types of Encryption

**1. Symmetric Encryption**
**Uses the same secret key to encrypt and decrypt data. It is fast and suitable for encrypting large amounts of data.**

**2. Asymmetric Encryption**
**Uses a pair of keys: a public key and a private key. It supports secure communication and digital signatures.**

**Key Difference:** **Symmetric encryption uses one shared secret key, while asymmetric encryption uses a pair of related keys.**

## Hash function an algorithm that produces a code that cant be decrypted

## Non - repudiation
**The concept that the authenticity of information cant be denied**


## Hash Functions

A hash function converts data into a fixed-length hash value used to verify data integrity.

**SHA (Secure Hash Algorithm):**
- **SHA-1:** **160-bit hash; no longer secure against collisions.**
- **SHA-224:** **224-bit hash.**
- **SHA-256:** **256-bit hash; widely used.**
- **SHA-384:** **384-bit hash.**
- **SHA-512:** **512-bit hash.**

**Key Points:**
- **The same input produces the same hash.**
- **A small change in input produces a different hash.**
- **Hashing is one-way and is not encryption.**
- **Hash functions help detect unauthorized data modifications.**

oading assets, threats, and vulnerablities.md…]()

