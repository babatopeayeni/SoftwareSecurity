# Artemis Financial - Secure Software Practices

## Summary of Artemis Financial and Software Requirements  
Artemis Financial is a company focused on secure financial transactions. Their main concern was fixing vulnerabilities in their web application to protect sensitive financial data. I was tasked with assessing weaknesses and implementing security improvements.  

## Security Vulnerability Assessment  
I identified issues like hardcoded data, missing input validation, and insecure exception handling. To address them, I implemented **SHA-256 hashing** for data integrity and **AES-256 encryption** for confidentiality. Secure coding is essential to prevent **data breaches, financial loss, and reputational damage**. Strong security measures improve customer trust and regulatory compliance.  

## Challenges and Solutions in the Vulnerability Assessment  
One challenge was **input validation issues**, which could lead to **SQL injection or XSS attacks**. Implementing strict sanitization and structured error handling strengthened security. The most useful improvement was **TLS encryption**, ensuring secure communication and preventing **man-in-the-middle attacks**.  

## Enhancing Security Layers and Future Assessment Methods  
I added multiple security layers, including:  
- **Cryptographic Security**: SHA-256 for hashing and AES-256 for encryption  
- **Input Validation**: Prevents injection attacks  
- **Secure Communication**: HTTPS encryption  
- **Structured Error Handling**: Prevents exposure of sensitive data  

In future assessments, I would use tools like **OWASP Dependency-Check** and **automated static code analysis** to identify vulnerabilities.  

## Ensuring Functional and Secure Code  
After refactoring, I conducted **functional testing** to ensure security without breaking functionality. I tested:  
- **Encrypted communication (TLS/SSL)**  
- **Input validation and sanitization**  
- **Exception handling and error messages**  

Additional **penetration testing and dependency checks** confirmed no new vulnerabilities were introduced.  

## Helpful Tools and Resources  
The most useful tools were:  
- [OWASP Secure Coding Practices](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/)  
- [Java Keytool](https://docs.oracle.com/javase/9/tools/keytool.htm)  
- [OWASP Dependency-Check](https://jeremylong.github.io/DependencyCheck/dependency-check-maven/index.html)  
- **SHA-256 and AES-256 cryptographic standards**  

These tools will be valuable in future secure software development projects.  

## Showcasing Skills to Employers  
This project highlights my skills in:  
 **Vulnerability assessment and mitigation**  
 **Encryption implementation (SHA-256, AES-256)**  
 **Secure web applications and TLS encryption**  
 **Industry-standard secure coding practices**  


