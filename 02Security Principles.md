# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

## CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element | Description | Example |
|----------|--------------|----------|
| Confidentiality | Ensures data is accessible only to authorized users. | Encrypting files, using passwords, access control lists. |
| Integrity | Ensures data is accurate, consistent, and not tampered with. | Using hashing, digital signatures, checksums. |
| Availability | Ensures systems and data are available when needed. | Redundant servers, backups, DDoS protection. |




<img width="227" height="222" alt="download" src="https://github.com/user-attachments/assets/14d07673-ea4a-4690-b50b-ab9315c4ffe4" />


## Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).



 ## Examples
Confidentiality Violation:* Unauthorized access to customer data (e.g., Facebook-Cambridge Analytica case).
- Integrity Violation: Tampered medical data in hospitals leading to misdiagnosis.
- Availability Violation: DDoS attack on banking websites preventing service access.

# Risk, Privacy, and Accountability
# Risk
- Definition: Probability of a threat exploiting a vulnerability to cause harm.

## Components:
- Threat -> something that can cause damage.
- Vulnerability -> weakness that can be exploited.
- Impact -> damage if threat is realized

## Formula:
- Risk = Threat x Vulnerability x Impact


## Example: 
Threat: Phishing 
Vulnerability: Employee lack of awareness 
Impact: Credential theft, financial loss 



![download](https://github.com/user-attachments/assets/9b018435-f7dc-48b6-b652-5ed1b309f0d4)



# Privacy 
- Protecting personel and sensitive information of individuals. 
- Governed by laws like GDPR, DPDP Act (India), HIPAA


 ![images](https://github.com/user-attachments/assets/dd33f7d4-4337-4223-b952-ef9cdc9eca56)


## Key Practices:
- Data minimization 
- Informed consent 
- Data anonymization
  
Example: A healthcare app must not share user health data without consent.

# Accountability
Ensuring every action in an IT system can be traced back to an individual.
## Achieved through:
- Logging & auditing
- User access tracking
- Non-repudiation mechanisms
  
Example: Audit logs in firewalls to trace malicious user actions. 


## Real-world Case Studies

| Case                  | Description                                          | Violated Principle 
|-----------------------|------------------------------------------------------|--------------------
| WannaCry (2017)       | Ransomware disabled hospital systems worldwide       | Availability             
| Equifax Breach (2017) | Personal data of 143M users leaked                   | Confidentiality & Integrity    
| Twitter Hack (2020)   | Insider access to admin tools                        | Confidentiality & Accountability


