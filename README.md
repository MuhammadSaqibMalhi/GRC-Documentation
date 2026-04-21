## Overview

This repository demonstrates a practical implementation of an Information Security Management System (ISMS) aligned with ISO/IEC 27001.

## Business Scenario

This ISMS is designed for a small-to-medium enterprise operating in theindustry, e.g., financial services / mining contractor, handling sensitive operational and customer data.
The organisation relies on cloud-based systems, employee endpoints, and internal networks to support business operations. Due to regulatory and operational requirements, the organisation must ensure the confidentiality, integrity, and availability of its information assets.

This scenario is used to demonstrate how security policies, controls, and risk management practices can be applied in a real-world business context.

---

# Risk Assessment

## Risk Assessment Approach

This ISMS uses a structured, risk-based approach aligned with ISO/IEC 27001 to identify, assess, and treat information security risks.

The process includes:
- Identifying critical assets within the organisation
- Identifying threats and vulnerabilities affecting those assets
- Assessing risk based on likelihood and impact
- Prioritising risks for treatment
- Mapping risks to appropriate security controls (ISO 27001, NIST CSF, CIS Controls)

---

## Risk Rating Methodology

Risk is evaluated using a qualitative approach:

- **Impact:** Low / Medium / High  
- **Likelihood:** Low / Medium / High  
- **Risk Level:** Determined based on the combination of impact and likelihood  

---

## Sample Risk Register

| Asset                     | Threat              | Vulnerability                             | Impact      | Likelihood | Risk Level | Controls                 |
| ------------------------- | ------------------- | ----------------------------------------- | ----------- | ---------- | ---------- | ------------------------ |
| Customer Data (Cloud CRM) | Unauthorized Access | No MFA, weak access control               | High        | Medium     | High       | ISO A.9, CIS Control 6   |
| Employee Endpoints        | Malware/Ransomware  | Unpatched systems, no endpoint protection | High        | High       | High       | ISO A.12, CIS Control 10 |
| Email System              | Phishing            | Lack of user awareness                    | Medium-High | High       | High       | ISO A.7, CIS Control 14  |
| Internal Files            | Data Leakage        | No data classification or DLP             | Medium      | Medium     | Medium     | ISO A.8, CIS Control 3   |
| Network Access            | Unauthorized Access | Weak passwords, no segmentation           | High        | Medium     | High       | ISO A.13, CIS Control 12 |


---

## Control Mapping

Identified risks are treated by implementing controls aligned with:

- **ISO/IEC 27001 Annex A**
- **NIST Cybersecurity Framework (CSF)**
- **CIS Critical Security Controls**

This approach ensures alignment between compliance requirements and practical risk reduction.

---

## Continuous Improvement

The risk assessment process is reviewed periodically to:
- Reflect changes in the threat landscape  
- Incorporate new assets or systems  
- Improve control effectiveness  

## ISMS Documentation

The following policies and procedures have been developed to support the ISMS and address identified risks:

### Access Control
- Access Control Policy  
- Password Policy  

### Asset Management
- Inventory of Assets  
- Information Classification Policy  

### Acceptable Use & User Responsibilities
- Acceptable Use Policy  
- Confidentiality Statement  
- Statement of Acceptance of ISMS Documents  

### Mobile & Remote Work
- Bring Your Own Device (BYOD) Policy  
- Mobile Device and Teleworking Policy  

### Operations Security
- Backup Policy  
- Change Management Policy  
- Operating Procedures for ICT  

### Cryptography
- Policy on the Use of Cryptographic Controls  

### Physical & Environmental Security
- Clear Desk and Clear Screen Policy  
- Secure Areas Procedures  
- Disposal and Destruction Policy  

### Communications Security
- Information Transfer Policy  

### Secure Development
- Secure Development Policy  
- Security Requirements Specification  

### Supplier Security
- Supplier Security Policy  
- Security Clauses for Third Parties  

### Incident Management & Business Continuity
- Incident Management Procedure  
- Incident Log  
- Disaster Recovery Plan  

The below policies are designed to mitigate identified risks and are aligned with ISO/IEC 27001 Annex A controls.

[6.1 Bring_Your_Own_Device_BYOD_Policy-200618-052247.docx](https://github.com/user-attachments/files/22869533/6.1.Bring_Your_Own_Device_BYOD_Policy-200618-052247.docx)

[6.2 Mobile_Device_and_Teleworking_Policy-200618-052346.docx](https://github.com/user-attachments/files/22869545/6.2.Mobile_Device_and_Teleworking_Policy-200618-052346.docx)

[7.1 Confidentiality_Statement-200618-053301.docx](https://github.com/user-attachments/files/22869546/7.1.Confidentiality_Statement-200618-053301.docx)

[7.2 Statement_of_Acceptance_of_ISMS_Documents-200618-053301.docx](https://github.com/user-attachments/files/22869547/7.2.Statement_of_Acceptance_of_ISMS_Documents-200618-053301.docx)

[8.1 Acceptable_Use_Policy-200618-055138.docx](https://github.com/user-attachments/files/22869548/8.1.Acceptable_Use_Policy-200618-055138.docx)

[8.2 Information_Classification_Policy-200618-055138.docx](https://github.com/user-attachments/files/22869549/8.2.Information_Classification_Policy-200618-055138.docx)

[8.3 Inventory_of_Assets-200618-055138.xlsx](https://github.com/user-attachments/files/22869550/8.3.Inventory_of_Assets-200618-055138.xlsx)

[9.1 Access_Control_Policy-200618-060356.docx](https://github.com/user-attachments/files/22869555/9.1.Access_Control_Policy-200618-060356.docx)

[9.2 Password_Policy-200618-060356.docx](https://github.com/user-attachments/files/22869556/9.2.Password_Policy-200618-060356.docx)

[10 Policy_on_the_Use_of_Cryptographic_Controls-200618-062831.docx](https://github.com/user-attachments/files/22869557/10.Policy_on_the_Use_of_Cryptographic_Controls-200618-062831.docx)

[11. 2 Disposal_and_Destruction_Policy-200618-065012.docx](https://github.com/user-attachments/files/22869558/11.2.Disposal_and_Destruction_Policy-200618-065012.docx)

[11. 3 Procedures_for_Working_in_Secure_Areas-200618-065012.docx](https://github.com/user-attachments/files/22869559/11.3.Procedures_for_Working_in_Secure_Areas-200618-065012.docx)

[11.1 Clear_Desk_and_Clear_Screen_Policy-200618-065012.docx](https://github.com/user-attachments/files/22869560/11.1.Clear_Desk_and_Clear_Screen_Policy-200618-065012.docx)

[12.1 Operating_Procedures_for_Information_and_Communication_Technology-200618-070842 (1).docx](https://github.com/user-attachments/files/22869561/12.1.Operating_Procedures_for_Information_and_Communication_Technology-200618-070842.1.docx)

[12.2 Backup_Policy-200618-070842.docx](https://github.com/user-attachments/files/22869562/12.2.Backup_Policy-200618-070842.docx)

[12.3 Change_Management_Policy-200618-070842.docx](https://github.com/user-attachments/files/22869563/12.3.Change_Management_Policy-200618-070842.docx)

[13 Information_Transfer_Policy-200618-112829.docx](https://github.com/user-attachments/files/22869564/13.Information_Transfer_Policy-200618-112829.docx)

[14.1 Appendix_Security_Requirements_Specification-200618-113811.docx](https://github.com/user-attachments/files/22869566/14.1.Appendix_Security_Requirements_Specification-200618-113811.docx)

[14.2 Secure_Development_Policy-200618-113811.docx](https://github.com/user-attachments/files/22869567/14.2.Secure_Development_Policy-200618-113811.docx)

[15.1 Appendix_Security_Clauses_for_Clients_Suppliers_and_Partners-200618-114953.docx](https://github.com/user-attachments/files/22869568/15.1.Appendix_Security_Clauses_for_Clients_Suppliers_and_Partners-200618-114953.docx)

[15.2 Supplier_Security_Policy-200618-114953.docx](https://github.com/user-attachments/files/22869569/15.2.Supplier_Security_Policy-200618-114953.docx)

[16.1 Appendix_Incident_Log-200618-120450.docx](https://github.com/user-attachments/files/22869570/16.1.Appendix_Incident_Log-200618-120450.docx)

[16.2 Incident_Management_Procedure-200618-120450.docx](https://github.com/user-attachments/files/22869572/16.2.Incident_Management_Procedure-200618-120450.docx)

[17 Disaster_Recovery_Plan_27001-200618-121503.docx](https://github.com/user-attachments/files/22869573/17.Disaster_Recovery_Plan_27001-200618-121503.docx)

## Key Skills Demonstrated

- ISMS design and documentation  
- Risk assessment and control selection  
- ISO/IEC 27001 Annex A control mapping  
- Policy and procedure development  
- Information security compliance and governance  
- Continuous improvement cycle (PDCA model)

---

## Certification

**ISO/IEC 27001 Implementation – PECB Certified**  
Currently also preparing for **ISACA Certified Information Systems Auditor (CISA)** certification.

---

## Contact

**Muhammad Saqib Malhi**  
📧 Email: saqib.malhi3@outlook.com  
🌐 LinkedIn: www.linkedin.com/in/saqib-malhi-957a8598
💻 GitHub: https://github.com/MuhammadSaqibMalhi

