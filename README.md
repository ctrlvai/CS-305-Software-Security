# CS 305 Portfolio Reflection: Artemis Financial

## Project Overview

The client for this project was Artemis Financial, a company that develops individualized financial plans for its customers. Artemis Financial wanted to improve the security of its web application and protect sensitive customer information during data transmission. The primary requirement was to implement secure communication mechanisms, including checksum verification and HTTPS encryption, to help ensure the integrity and confidentiality of client data.

## Software Security Assessment

One aspect of this project that I completed successfully was identifying security vulnerabilities and implementing solutions to address them. Through vulnerability analysis and dependency scanning, I gained experience evaluating security risks within an application. Coding securely is important because software vulnerabilities can expose sensitive information, damage a company's reputation, and create financial and legal risks. Software security adds value to an organization by helping protect customer data, maintain trust, and reduce the likelihood of security incidents.

## Challenges and Lessons Learned

One of the most challenging parts of the project was understanding how different security components work together. Learning how to configure HTTPS, generate certificates, implement cryptographic hashing, and perform dependency analysis required careful testing and troubleshooting. At the same time, these activities were helpful because they provided practical experience with real-world security tools and techniques commonly used in software development.

## Security Improvements

To increase the application's security, I implemented SHA-256 checksum verification, generated a self-signed SSL certificate, enabled HTTPS communication, and performed dependency analysis using OWASP Dependency-Check. In the future, I would continue using vulnerability scanning tools, dependency analysis tools, code reviews, and security testing frameworks to assess risks and determine appropriate mitigation strategies.

## Testing and Validation

To verify that the application remained functional and secure after refactoring, I performed both manual and automated testing. I confirmed that the application successfully generated SHA-256 checksums and established secure HTTPS connections. After making security-related changes, I ran OWASP Dependency-Check to identify potential vulnerabilities and verify that the modifications did not introduce new security issues.

## Resources and Tools

Several resources and tools were valuable throughout this project. Spring Boot provided the application framework, Java Keytool was used to generate SSL certificates, SHA-256 was used for checksum verification, and OWASP Dependency-Check was used to perform static security testing. These tools and practices will continue to be useful in future software development and security-related projects.

## Portfolio Artifact

The artifact included in this repository is the Artemis Financial Practices for Secure Software Report. This artifact demonstrates my ability to assess software security requirements, implement cryptographic hashing, configure HTTPS communication, generate SSL certificates, perform vulnerability testing, and document secure software development practices. Future employers can use this project as evidence of my understanding of software security concepts and secure coding techniques.
