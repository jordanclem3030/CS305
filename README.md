Artemis Financial Security Project Reflection
Client Summary

Artemis Financial is a financial services company that required improvements to the security of its web-based software application. The company wanted to ensure secure communication between clients and servers while protecting sensitive financial data from vulnerabilities and cyber threats. My task was to conduct a vulnerability assessment, identify security risks in the application, and implement secure coding practices to mitigate those risks.

The primary issue addressed was insecure communication and potential dependency vulnerabilities within the Spring-based application. The goal was to strengthen encryption, implement HTTPS, and reduce software security risks.

What I Did Well & Importance of Secure Coding

When identifying vulnerabilities, I effectively used dependency scanning tools and reviewed insecure configurations in the Spring framework. I successfully implemented secure hashing (SHA-256), configured SSL/TLS certificates, and enforced HTTPS communication.

Secure coding is important because it:

Protects sensitive financial data

Prevents data breaches and cyberattacks

Builds customer trust

Reduces legal and financial risk for companies

Software security adds value to a company by improving reliability, protecting its reputation, and ensuring regulatory compliance.

Challenging or Helpful Aspects

The most challenging part of the vulnerability assessment was understanding dependency vulnerabilities and interpreting the OWASP Dependency-Check report. Learning how to analyze CVEs (Common Vulnerabilities and Exposures) and determine their severity required careful review.

However, this was also the most helpful part because it strengthened my ability to evaluate third-party libraries and understand how external dependencies can introduce risk.

Increasing Layers of Security

I increased layers of security by:

Implementing SHA-256 hashing

Generating and configuring SSL/TLS certificates

Enforcing HTTPS communication

Running OWASP Dependency-Check to identify vulnerabilities

Refactoring code to remove insecure configurations

In the future, I would use:

OWASP Dependency-Check

Static code analysis tools

Penetration testing tools

Secure coding guidelines (OWASP Top 10)

These tools help assess vulnerabilities and determine proper mitigation strategies.

Ensuring Functionality and Security

After refactoring the code, I ensured functionality by:

Running the application and verifying successful execution

Testing checksum generation

Confirming HTTPS secure communication in the browser

Running mvn clean verify to ensure successful builds

Reviewing the dependency-check report for new vulnerabilities

This confirmed that security improvements did not break application functionality and that no new vulnerabilities were introduced.

Resources, Tools, and Practices Used

Resources and tools used in this project include:

OWASP Dependency-Check

Maven (mvn clean verify)

Java keytool for certificate generation

SHA-256 hashing

Spring framework security configuration

Secure coding best practices

These tools and practices will be valuable in future coursework and professional software development.

What I Would Show Future Employers

From this assignment, I could show:

A completed vulnerability assessment report

Secure software refactoring documentation

Implementation of HTTPS and SSL certificates

Dependency vulnerability scanning results

Evidence of secure coding and testing practices

This project demonstrates my ability to identify security risks, implement secure solutions, and verify application integrity.# CS305
