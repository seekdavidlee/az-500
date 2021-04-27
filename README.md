# 1.0 Introduction
This is my study notes for AZ 500. As we know, the Azure Platform is constantly being updated, which means that the Azure exams are also constantly updated. As such, it is important to check if my notes are still applicable to you. For your reference, I am using the updated exam list from March 23, 2021 and my notes are up-to-date as of April 2021. You will find that the way that works for me when studying is to reference videos from experts and it may be different for everyone. Anyone, feel free to reference for your own study! Good luck and enjoy!

<br />

## 1.1 The Exam
| Description | Weight | Notes |
| --- | --- | -- |
| Manage identity and access | 30-35% | AAD/ Identity/ Application Access/ Access Control |
| Implement platform protection | 15-20% | Network/ Compute Security |
| Manage security operations | 25-30% | Monitor/ Sentinel / Security Center / Policies |
| Secure data and applications | 20-25% | Storage/ Database/ Key Vault |

<br />

## 1.2 Quiz
This is an excellent way to gauge if you are prepared for the exam. I would suggest the best time to go through the quizes is when you have gone through all the materials. The credit for these quizes goes to Pete Zerger who prepared these. Note that some answers may be incorrect as things have changed. For example, Azure Key Vault data plane now supports RBAC in addition to access policies.

* Microsoft AZ-500 Practice Quiz #1 (video self-assessment): https://www.youtube.com/watch?v=XAgb-4FfPes
* Microsoft AZ-500 Practice Quiz #2 (video self-assessment): https://www.youtube.com/watch?v=jOBaVXVwXLc
* Microsoft AZ-500 Practice Quiz #3 (video self-assessment): https://www.youtube.com/watch?v=j79qRN9cNA0
* Microsoft AZ-500 Practice Quiz #4 (video self-assessment): https://www.youtube.com/watch?v=CqPGpfdETSM

<br />

## 1.3 References
| Description | Link |
| --- | --- |
| Microsoft Learnings - Lab | https://microsoftlearning.github.io/AZ500-AzureSecurityTechnologies/  |
| Another study guide by Mike Grimes  | https://aka.ms/AZ-500 |
| Linked in Videos | https://www.linkedin.com/learning/paths/microsoft-exam-az-500-microsoft-azure-security-technologies |
| Official Exam Reference | https://learning.oreilly.com/library/view/exam-ref-az-500/9780136789000 |

<br />

# 2.0 Manage Identity and Access
* Mark Grimes Module 1: https://www.youtube.com/watch?v=ps9EcICGHJ0
* Pete Zerger: https://www.youtube.com/watch?v=jdsBolMxhiw
* John Savill, Azure Master Class Part 2 - Identity: https://www.youtube.com/watch?v=Jd3IzN9x2as

## 2.1 Manage Azure Active Directory identities
* John Savill, Azure AD Administrative Units Overview: https://www.youtube.com/watch?v=1-x86jJuK7c
* Review decision tree: https://docs.microsoft.com/en-us/azure/active-directory/hybrid/choose-ad-authn#decision-tree

## 2.2 Configure secure access by using Azure AD
* How to roll out conditional access | Azure Active Directory: https://www.youtube.com/watch?v=0_Fze7Zpyvc
* How to deploy conditional access | Azure Active Directory: https://www.youtube.com/watch?v=c_izIRNJNuk
* John Savill, Azure Security Center and Azure Sentinel Overview (AZ-500): https://www.youtube.com/watch?v=rE-qgIgDCq8
* John Savill, Azure AD Privileged Identity Management (PIM) - AZ-500, SC-300 Deep Dive Topic: https://www.youtube.com/watch?v=gccgIkR8_a0
* Link to register for MFA: https://aka.ms/MFASetup

### Conditional Access
* P1 License OR Enterprise Mobility + Security E3 
* Exclude action overrides an include in policy i.e. If User or User Group is in both Include and Exclude list, the User or Group will be excluded from Policy

### Identity Protection
* P2 License OR Enterprise Mobility + Security (EMS) E5
* Detect + remediate identity-based risks
* Investigate risk
* Export risk data to third party

### Identity Governance - Privileged Identity Management (PIM)
* P2 License OR Enterprise Mobility + Security (EMS) E5
* Entitlement - Just-in-time, time bound access to Azure AD and Azure resources + Approval process
* MFA, justification to activate, and notifications when activated
* Access Review
* Audit history

## 2.3 Manage application access
* Pete Zerger, Azure AD App Registration in Plain English (Exam Prep FAQs): https://www.youtube.com/watch?v=YWvl0cIilyA
* John Savill, Azure AD App Registrations, Enterprise Apps and Service Principals: https://www.youtube.com/watch?v=WVNvoiA_ktw

### OAuth 2.0
* Third-party app access web-hosted resources on behalf of a user
* Permisson: Principle of least privilege, asking for only the permissions they need for their applications to function
* These types of permission sets are called scopes

| Delegated | Application |
| --- | --- |
| User MUST be signed in | User is NOT signed in  |
| User or Admin consent  | Only Admin consent |
| Effective permissions is what user is allowed, and what user has allowed by consent  | Effective permissions of your app are the full level of privileges implied by the permission |

<br />

### 2.4 Manage access control
* Adam Marczak, AZ-900 Episode 28 | Azure Role-based Access Control (RBAC): https://www.youtube.com/watch?v=4v7ffXxOnwU

<br />

# 3.0 Implement Platform Protection
* Mark Grimes Module 2: https://www.youtube.com/watch?v=huoQReklaRM
* Pete Zerger: https://www.youtube.com/watch?v=Ax8iTC8oZY8

<br />

## 3.1 Implement advanced network security
* John Savill, Azure Master Class Part 6 - Networking: https://www.youtube.com/watch?v=K8ePZdLfU7M
* Adam Marczak, AZ-900 Episode 23 | Azure Firewall - https://www.youtube.com/watch?v=VIEaz869njk
* Azure Academy, Azure Networking - #13 - Azure Front Door - https://www.youtube.com/watch?v=6PK88DDU3K4&t=872s

<br />

## 3.2 Configure advanced security for compute

<br />

# 4.0 Manage Security Operations
* Mark Grimes Module 3: https://www.youtube.com/watch?v=NUfMtd12KQE
* Pete Zerger: https://www.youtube.com/watch?v=qfSSKFL9rNg
* John Savill, Azure Master Class Part 9 - Monitoring and Security: https://www.youtube.com/watch?v=hTS8jXEX_88

<br />

## 4.1 Monitor security by using Azure Monitor

<br />

## 4.2 Monitor security by using Azure Security Center

<br />

## 4.3 Monitor security by using Azure Sentinel

<br />

## 4.4 Configure security policies

<br />

# 5.0 Secure Data and Applications
* Mark Grimes Module 4: https://www.youtube.com/watch?v=AfQV4gB2ldM
* Pete Zerger: https://www.youtube.com/watch?v=nwTTL7Oi2-k
* John Savill, Azure Master Class Part 8 - Application Services: https://www.youtube.com/watch?v=_E73_SQN8ZU

<br />

## 5.1 Configure security for storage
* John Savill, Azure Master Class Part 5 - Storage: https://www.youtube.com/watch?v=ZNuzmUKt6IE&list=PLlVtbbG169nGccbp8VSpAozu3w9xSQJoY&index=6
<br />

## 5.2 Configure security for databases

<br />

## 5.3 Configure and manage Key Vault
* John Savill, Azure Key Vault Deep Dive (AZ-500): https://www.youtube.com/watch?v=kP7KpfToMkg&t=2s

