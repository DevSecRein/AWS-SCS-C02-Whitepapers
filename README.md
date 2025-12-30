### Summary Table

| **Whitepaper**              | **Primary Exam Domain** | **Key Takeaway for Exam**                         |
| --------------------------- | ----------------------- | ------------------------------------------------- |
| **Security Pillar**         | All Domains             | The 7 design principles & shared responsibility.  |
| **Incident Response Guide** | Threat Detection        | Automation of isolation (e.g., isolating an EC2). |
| **DDoS Resiliency**         | Infrastructure Security | WAF, Shield Advanced, & CloudFront architecture.  |
| **KMS Best Practices**      | Data Protection         | Key usage, grants, & policy evaluation logic.     |

For the AWS Certified Security - Specialty (SCS-C02) exam, there are a few specific whitepapers that are consistently cited as "must-reads" because the exam questions heavily rely on the scenarios and frameworks defined in them.

Here are the primary whitepapers recommended for this exam, categorized by their importance.

---
### 1. The "Holy Grail" (Start Here)

- **AWS Well-Architected Framework: Security Pillar**
    
    - **Why it's critical:** This is arguably the most important document for the exam. It defines the five key areas (Identity, Detection, Infrastructure Protection, Data Protection, Incident Response) that structure the entire certification. The exam often tests your ability to apply these exact design principles to a scenario.
    
    - [Link to Whitepaper](https://docs.aws.amazon.com/pdfs/wellarchitected/latest/security-pillar/wellarchitected-security-pillar.pdf)

---
### 2. Domain-Specific "Must Reads"

These papers cover specific deep-dive topics that make up a large percentage of the "scenario-based" questions.

- **AWS Security Incident Response Guide**
    
    - **Focus:** How to prepare for and respond to security incidents.
    
    - **Key Concept:** Pay attention to the "process" steps (Identification, Isolation, Recovery) and how to automate them using Lambda and EventBridge
    
    - [Link to Whitepaper](https://docs.aws.amazon.com/pdfs/whitepapers/latest/aws-security-incident-response-guide/aws-security-incident-response-guide.pdf)

- **AWS Best Practices for DDoS Resiliency**
    
    - **Focus:** Protecting applications from denial of service attacks. 
    
    - **Key Concept:** The exam loves to test the "BP" (Best Practice) reference architecture mentioned here, specifically the difference between protecting at the Edge (CloudFront/WAF) vs. the Infrastructure layer (Auto Scaling/ELB).
    
    - [Link to Whitepaper](https://docs.aws.amazon.com/pdfs/whitepapers/latest/aws-best-practices-ddos-resiliency/aws-best-practices-ddos-resiliency.pdf)
    
- **AWS Key Management Service (KMS) Best Practices**
    
    - **Focus:** Cryptography and key management.
    
    - **Key Concept:** This paper explains the nuances of Key Policies vs. IAM Policies, key rotation, and the specific cryptographic details that "Specialty" level exams require (e.g., Envelope Encryption).
    
    - [Link to Whitepaper](https://docs.aws.amazon.com/pdfs/prescriptive-guidance/latest/aws-kms-best-practices/aws-kms-best-practices.pdf)
    

---
### 3. General Security Context

- **Introduction to AWS Security:** Good for a baseline if you are just starting, but likely too basic for the Specialty level unless you need a refresher on the "Shared Responsibility Model." 

- [Link to Whitepaper](https://docs.aws.amazon.com/pdfs/whitepapers/latest/introduction-aws-security/introduction-aws-security.pdf)
