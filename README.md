# Botium-toys-security-audit
Internal Security Audit for Botium Toys - NIST CSF Implementation and Compliance Checklist.
# Contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Audit Goals](#audit-goals)
4. [Audit Workflow](#workflow)
5. [Assets, Controls & Compliance Checklist](#checklist)  
6. [Stakeholder Memorandum](#stakeholder-memo)
7. [Conclusion](#conclusion)

-------

# 1. Introduction <a name="introduction">

An internal security audit assessment conducted on Botium Toys, a fictitious toy company, as part of my cybersecurity portfolio. It was a part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course .

The objective is to conduct an audit of Botium Toys' cybersecurity program. This audit should ensure that the company's current business practices are in line with industry standards and best practices. The purpose of the audit is to identify and recommend mitigations for vulnerabilities classified as "high risk" and to develop a comprehensive strategy to enhance the organization's security posture. The audit team is responsible for documenting their findings, outlining remediation plans, and effectively communicating these to stakeholders.

# 2. Scenario  <a name="scenario">

This scenario is based on a fictional company:

Botium Toys, a small U.S. business that develops and sells toys, operates from a single physical location serving as their main office, storefront, and warehouse. Despite their modest physical presence, their online market has significantly expanded, drawing customers from both the U.S. and abroad. This growth has placed substantial pressure on their IT department to support and secure their expanding online operations. The IT manager, concerned about maintaining compliance and business continuity amid this growth, has decided to conduct an internal IT audit to identify and address potential risks, threats, and vulnerabilities to the company's critical assets.

To ensure comprehensive security and compliance, the IT manager is implementing the **National Institute of Standards and Technology Cybersecurity Framework** (NIST CSF). This involves defining the audit's scope and goals, cataloging the assets managed by the IT department, and completing a risk assessment. The audit aims to provide a detailed overview of the risks and potential fines the company could face due to its current security posture. Additionally, it seeks to ensure compliance with regulations related to online payments and conducting business in the European Union (E.U.).

# 3. Audit Goals <a name="audit-goals">

The goals of this internal Security audit are:<br>
• Align current business practices with industry standards and best practices in cybersecurity.<br>
• Identify and prioritize high-risk vulnerabilities within the company's systems and infrastructure.<br>
• Provide comprehensive mitigation recommendations to address identified vulnerabilities.<br>
• Develop detailed remediation plans outlining steps to implement necessary security measures.<br>
• Communicate findings, remediation plans, and recommendations effectively with stakeholders.<br>

# 4. Audit Workflow <a name="workflow">
The internal security audit workflow is divided into two main parts, each with its own set of steps:
### Part 1:
1. **Analysis**: This involves reviewing the audit scope, goals, and the results of the risk assessment to understand the objectives of the audit.
2. **Audit Execution**:
   - **Controls Assessment**: Evaluate the existing controls in place, identify which ones need implementation, and prioritize them based on urgency.
   - **Compliance Checklist**: Complete a checklist outlining selected compliance regulations and standards, and provide explanations for their importance.
### Part 2:
1. **Review and Analysis**: Examine the findings and deliverables from Part 1, Step #2, taking note of any significant discoveries.
2. **Communication**: Summarize the audit findings and recommendations concisely and clearly for stakeholders, ensuring effective communication of the audit's outcomes.

# 5. Assets, Controls & Compliance Checklist  <a name="checklist">

Current Assets 
--------------

Assets managed by the IT Department include:

● On-premises equipment for in-office business needs.<br>
● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.<br>
● Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse.<br>
● Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management.<br>
● Internet access<br>
● Internal network<br>
● Data retention and storage<br>
● Legacy system maintenance: end-of-life systems that require human
monitoring

Controls 
--------------

### Administrative/Managerial Controls
| Control Name | Control type | Explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- | --- |
| Least Privilege | Preventative | Limiting access to only what employees need, reduces the chance of unauthorized access to sensitive information, making the company more secure. | X | High |
| Disaster recovery plans | Corrective | Ensures business continuity by making plans that outline what to do if something goes wrong, like a cyber attack or a natural disaster, ensuring the company can quickly recover and minimize damage. | X | High |
| Password policies | Preventative | Setting rules for strong passwords helps prevent unauthorized access by making it harder for hackers to guess or crack passwords through brute force or dictionary attack techniques. | X | High |
| Access control policies | Preventative | Policies that determine who can access what information or systems, preventing unauthorized users from getting into sensitive areas. | X | High |
| Account management policies | Preventative | These policies ensure that employee accounts are created, modified, and removed properly, reducing the risk of outdated or unused accounts being exploited. | X | High |
| Separation of duties | Preventative | By dividing tasks among different employees, it prevents any one person from having too much control, reducing the risk of fraud or errors going undetected. | X | High |

### Technical Controls 
| Control Name | Control type | Explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- | --- |
| Firewall | Preventative| Firewalls **are already in place** to block unwanted/malicious traffic from entering organization's internal network. | NA | NA |
| Intrusion Detection System (IDS) | Detective | Allows Security teams to identify potential intrusions (e.g., DoS Attacks). | X | High |
| Encryption | Deterrent | Makes confidential information/data more secure by making it unreadable (e.g., payment transactions) | X | High |
| Backups | Corrective | Supports business continuity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management | Preventative | Establishing a system for storing passwords securely and accessing them quickly when needed | X | High |
| Antivirus (AV) software | Preventative | **Already in place.** Detects potential threats & quarantine unknown files | NA | NA |
| Manual monitoring, maintenance, and intervention | Preventative | Required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |

### Physical/Operational Controls
| Control Name | Control type | Explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- | --- |
| Time-controlled safe | Deterrent | Utilized to restrict access to valuable assets within specific timeframes, bolstering security measures by limiting exposure to potential threats. May help to reduce attack surface/impact from physical threats. | X | Medium |
| Closed-circuit television (CCTV) surveillance | Preventative/detective | **Already in place.** Offers continuous monitoring of premises through video recording, serving as a deterrent as well as preventative/detective to unauthorized activities and aiding in post-incident investigations. | NA | NA |
| Locking cabinets (for network gear) | Preventative | Provides physical protection to critical network infrastructure components, safeguarding against unauthorized access and tampering. | X | High |
| Signage indicating alarm service provider | Deterrent | Acts as a visible deterrent and informs potential intruders of the security measures in place, deterring unauthorized access and enhancing overall security awareness. | X | Low |
| Locks | Deterrent/Preventative | **Already in place.** Essential physical security measures that prevent unauthorized entry to restricted areas, safeguarding assets and maintaining confidentiality. | NA | NA |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative | **Already in place.** Detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | NA | NA |
