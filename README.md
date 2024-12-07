# Controls and Compliance Checklist

## Controls Assessment Checklist

Select “yes” or “no” to answer the question: **Does Botium Toys currently have this control in place?**

| Control | Yes | No |
|---------|-----|----|
| Least Privilege |   | x  |
| Disaster recovery plans |   | x  |
| Password policies |   |x  |
| Separation of duties |   | x  |
| Firewall |  x |   |
| Intrusion detection system (IDS) |   |  x |
| Backups |   |x   |
| Antivirus software | x  |   |
| Manual monitoring, maintenance, and intervention for legacy systems |   | x  |
| Encryption |   | x  |
| Password management system |   | x  |
| Locks (offices, storefront, warehouse) | x  |   |
| Closed-circuit television (CCTV) surveillance | x  |   |
| Fire detection/prevention (fire alarm, sprinkler system, etc.) | x  |   |

## Compliance Checklist

Select “yes” or “no” to answer the question: **Does Botium Toys currently adhere to this compliance best practice?**

### Payment Card Industry Data Security Standard (PCI DSS)

| Best practice | Yes | No |
|----------------|-----|----|
| Only authorized users have access to customers’ credit card information. |   | x  |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |   | x  |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. |   |  x |
| Adopt secure password management policies. |   | x  |

### General Data Protection Regulation (GDPR)

| Best practice | Yes | No |
|----------------|-----|----|
| E.U. customers’ data is kept private/secured. |   | x  |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | x  |   |
| Ensure data is properly classified and inventoried. |   | x  |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | x  |   |

### System and Organizations Controls (SOC type 1, SOC type 2) 

| Best practice | Yes | No |
|----------------|-----|----|
| User access policies are established. |   |  x |
| Sensitive data (PII/SPII) is confidential/private. |   |  x |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. | x |   |
| Data is available to individuals authorized to access it. |   |  x |

## Recommendations

Given the scope, goals, risk assessment, and the detailed controls and compliance checklist provided, here are tailored recommendations for Botium Toys to address their security posture:

### Critical Security Controls:

- **Implement Least Privilege and Separation of Duties**: 
  - Establish role-based access controls where employees have access only to the information and systems necessary for their job roles. This reduces the risk of insider threats and unauthorized data access.

- **Data Encryption**:
  - Enforce encryption for all customer credit card data during storage, processing, and transmission to ensure confidentiality and comply with PCI DSS.

- **Disaster Recovery and Data Backups**:
  - Develop disaster recovery plans and schedule regular, secure backups. This should include both on-site and off-site storage to protect against data loss from various catastrophic events.

- **Intrusion Detection System (IDS)**:
  - Install an IDS to complement the existing firewall, providing an additional layer of security to detect and respond to potential intrusions or anomalies in network traffic.

- **Password Management System**:
  - Implement a sophisticated password management system that enforces strong password policies, including complexity, length, and regular updates, to mitigate risks from password-related vulnerabilities.

- **Legacy System Management**:
  - Create a formal schedule for monitoring, maintenance, and possibly upgrading or replacing legacy systems to minimize vulnerabilities and ensure they are not a weak link in the security chain.

### Compliance Recommendations:

- **PCI DSS Compliance**:
  - Ensure that only authorized personnel have access to credit card information. This might involve user authentication, access logs, and periodic access reviews.
  - Implement comprehensive encryption for all cardholder data touchpoints. This includes databases, transmission channels, and any portable device used for payment processing.

- **GDPR Compliance**:
  - Enhance data classification and inventory processes. This will aid in better management and protection of E.U. customers' data, ensuring it is kept private and secure.
  - Continue enforcing the 72-hour breach notification policy, and expand training to ensure all staff are aware of GDPR requirements.

- **SOC Compliance**:
  - Establish and document user access policies to ensure that only authorized users can access sensitive data.
  - Improve measures that guarantee confidentiality and privacy of sensitive data (PII/SPII), possibly through enhanced encryption, secure disposal practices, and data minimization.

### Additional Recommendations:

- **Employee Training and Awareness**:
  - Regular security training for employees to understand the importance of security practices, particularly around data handling, access rights, and incident response.

- **Regular Audits and Vulnerability Assessments**:
  - Conduct regular security audits and penetration testing to identify new vulnerabilities, ensure ongoing compliance, and validate the effectiveness of security measures.

- **Physical Security Enhancements (if needed)**:
  - While physical security measures are in place, consider implementing time-controlled safes for highly sensitive documents or hardware, and review the effectiveness of current surveillance and locking systems.

- **Incident Response Plan**:
  - Develop or refine an incident response plan that includes roles, responsibilities, communication strategies, and recovery steps, ensuring rapid response to any security incidents.

These recommendations should be presented in a stakeholder meeting where the IT manager can outline the current risks, the proposed controls, and the expected outcomes in terms of risk reduction and compliance enhancement. Emphasize the business benefits like customer trust, regulatory compliance, and operational continuity alongside the technical improvements.
