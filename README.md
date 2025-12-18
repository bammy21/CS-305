# CS-305 – Software Security

## Client Summary
The client for this project was Artemis Financial, a financial services company that develops software for managing and transferring sensitive financial data. Artemis Financial required improvements to the security of their existing software application to protect customer information and ensure data integrity. The primary issue addressed in this project was identifying software security vulnerabilities and implementing secure coding practices, encryption, and verification mechanisms to mitigate potential threats.

## Software Security and Vulnerability Assessment
When assessing the client’s software for vulnerabilities, I successfully identified security risks related to dependency management, data integrity, and secure communications. Using automated tools and manual review allowed me to pinpoint outdated or vulnerable libraries and areas where additional protections were needed. Secure coding is critical because insecure software can lead to data breaches, financial loss, and reputational damage. Implementing strong security practices adds value to a company by protecting sensitive data, maintaining customer trust, and ensuring regulatory compliance.

## Challenges and Helpful Aspects
One of the more challenging aspects of the vulnerability assessment was interpreting the dependency-check reports and determining which findings represented real risks versus false positives. However, this process was also very helpful because it improved my ability to analyze security reports and make informed mitigation decisions.

## Layers of Security
I increased the layers of security by implementing SHA-256 hashing for checksum verification, generating and configuring self-signed certificates, enabling HTTPS for secure communication, and suppressing false positives in dependency scanning. In the future, I would continue to use automated vulnerability scanners, static code analysis tools, and security frameworks to assess risks and determine appropriate mitigation strategies.

## Functional and Security Testing
To ensure the software remained functional and secure, I tested the application after each refactoring step. I verified that the application built successfully, ran without errors, and produced consistent checksum results. After refactoring, I re-ran vulnerability scans to confirm that no new vulnerabilities were introduced.

## Tools and Resources Used
Throughout this project, I used several tools and practices that will be valuable in future work, including OWASP Dependency-Check, Java keytool, HTTPS configuration, SHA-256 hashing, Maven dependency management, and secure coding best practices.

## Portfolio and Employer Use
This project demonstrates my ability to perform vulnerability assessments, implement encryption and hashing, configure secure communications, and document security practices. I would show future employers this repository and report as evidence of my skills in secure software development, risk mitigation, and industry-standard security practices.
