# Controls and compliance checklist

To complete the controls assessment checklist, refer to the information provided in the [scope, goals, and risk assessment report](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc). For more details about each control, including the type and purpose, refer to the [control categories](https://docs.google.com/document/d/1btezuy_bMKWoK8pd97ZuzdWB9y6au_zfkrpkfVf8ktI/template/preview) document.

Then, select “yes” or “no” to answer the question: *Does Botium Toys currently have this control in place?* 

**Controls assessment checklist**

|   Yes |     No | Control |
| :---- | :---- | :---- |
|  |  | Least Privilege |
|  |  | Disaster recovery plans |
|  |  | Password policies |
|  |  | Separation of duties |
|  |  | Firewall |
|  |  | Intrusion detection system (IDS) |
|  |  | Backups |
|  |  | Antivirus software |
|  |  | Manual monitoring, maintenance, and intervention for legacy systems |
|  |  | Encryption |
|  |  | Password management system |
|  |  | Locks (offices, storefront, warehouse) |
|  |  | Closed-circuit television (CCTV) surveillance |
|  |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) |

---

To complete the compliance checklist, refer to the information provided in the [scope, goals, and risk assessment report](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview). For more details about each compliance regulation, review the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) reading.

Then, select “yes” or “no” to answer the question: *Does Botium Toys currently adhere to this compliance best practice?*

**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice |
| :---- | :---- | :---- |
|  |  | Only authorized users have access to customers’ credit card information.  |
|  |  | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|  |  | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |
|  |  | Adopt secure password management policies. |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice |
| :---- | :---- | :---- |
|  |  | E.U. customers’ data is kept private/secured. |
|  |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|  |  | Ensure data is properly classified and inventoried. |
|  |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice |
| :---- | :---- | :---- |
|  |  | User access policies are established. |
|  |  | Sensitive data (PII/SPII) is confidential/private. |
|  |  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|  |  | Data is available to individuals authorized to access it. |

---

This section is *optional* and can be used to provide a summary of recommendations to the IT manager regarding which controls and/or compliance best practices Botium Toys needs to implement, based on the risk posed if not implemented in a timely manner.

**Recommendations (optional):** In this section, provide recommendations, related to controls and/or compliance needs, that your IT manager could communicate to stakeholders to reduce risks to assets and improve Botium Toys’ security posture.

**My Recommendations:**

1) **Separation of Duties**

According to the list of classified assets, the organization can begin to separate duties of employees based on their experience and technical understanding of the asset. This provides an oversight of knowing which employee has access and is responsible for the asset. 

2) **Identity and Access Management**

Based on the separation of duties, the organization can safely identify, authenticate and authorize the correct personnel with the minimal amount of privilege to access assets. Following the concept of least privilege, allowing employees just enough access to assets to perform and complete their daily functions. 

Having a centralized password management system could also resolve issues of when employees forget their passwords, it is easier for the Security or IT department to handle such cases. It also allows the department that manages password security to implement stronger password requirements across the organization ensuring that all employees follow the standard.

3) **Asset Security** 

Adopting a defence in depth concept, layers of security can be added to ensure compliance with Payment Card Industry Data Security Standard (PCI DSS). Layers such as ensuring only authorized employees whose daily function requires access to customer’s payment information, by setting specific rules and folder permissions. 

Layer 2, encrypting the files containing customer’s PII/SPII, and changing the passwords regularly. This mitigates the risk of brute force password attacks as well as maintaining confidentiality of all customer related data.

Layer 3, ensure proper password policies are in place. Passwords should be a layer of defence but not the only layer, coupled with Multi Factor Authentication such as One Time Passwords, an authenticator app, and/or biometrics. 

Layer 4, ensure that all data is backed up and following the best practices of data backup management is to adopt the 3-2-1. Having 3 copies in total, the original and operational, a copy stored in a cloud to mitigate risks of inaccessibility in urgent scenarios and an offsite back-up to mitigate risk of fire, water or power shortage etc..

These layers help ensure that the company is in compliance with PCI DSS. Maintaining confidentiality and integrity. This will affect the accessibility in terms of speed as there are layers of authentication to ensure the employee accessing the data is authorized to do so. The company should also look into other disaster recovery plans to ensure business continuity.

4) **Communications and Network Security**

Deploying an Intrusion Detection System(IDS). Deploying and IDS will provide security teams an advantage to be aware of the presence of a threat actor. This allows security teams to respond efficiently against a threat actor who is trying to access the company’s network. The IDS could provide alerts to all employees depending on the level of risk and departments the threat affects. 

**Summary**

All in all, the company’s security risk score is 8 out of 10\. This indicates that the company has a significant amount of exposure to risks, threats and vulnerabilities. The recommendations above are recommended in order to assist the company in reaching its security goals of being in compliance with various legal requirements and standards.

Botium Toys should perform regular, rhythmic maintenance and system analysis of legacy systems to minimise the possibility of risks and threats. To also cover the physical aspect of security, it is highly recommended to implement a Fire detection/prevention plan such as having smoke and fire alarms, sprinkler systems in strategic places that are likely to be fire hazards and most importantly a fire evacuation plan to ensure the safety of everyone.

