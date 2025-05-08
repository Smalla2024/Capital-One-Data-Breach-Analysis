# Capital-One-Data-Breach-Analysis
This project offers an in-depth case study of the 2019 Capital One data breach, one of the most significant cybersecurity incidents in U.S. banking history. The analysis covers the technical breakdown, attack timeline, regulatory and legal aftermath, and preventative strategies that could have mitigated or prevented the breach.

# Key Components
- Attack Vector and Technical Breakdown:
Analysis of the SSRF (Server-Side Request Forgery) vulnerability used to access AWS EC2 metadata and retrieve credentials, which were then used to access S3 buckets.

- Security Misconfigurations:
Examination of Capital One’s cloud configuration flaws, including inadequate firewall rules, IAM (Identity and Access Management) policies, and lack of real-time alerting for unusual data access.

- Legal and Regulatory Consequences:
Overview of the $80 million fine imposed by the U.S. Treasury’s OCC, the class action lawsuits, and compliance failures with GLBA, FCRA, and PCI DSS standards.

- Lessons Learned and Recommendations:
A set of best practices that organizations can adopt to avoid similar breaches, such as:

a. Implementing Web Application Firewalls (WAF)
b. Enforcing principle of least privilege
c. Continuous audit logging and monitoring
d.Regular penetration testing and cloud security assessments

# References and Standards
- NIST Cybersecurity Framework (CSF)
- OWASP Cloud Security Guidelines
- AWS Well-Architected Framework – Security Pillar.
