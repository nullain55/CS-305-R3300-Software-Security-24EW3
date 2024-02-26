3-1 Project One Submission
Artemis Financials is committed to secure communications, safeguarding proprietary information, and compliance with data protection laws. 
The vulnerability assessment includes identifying external threats and considering modernization, such as updating open-source dependencies and staying current with web technologies.
The four areas identified in the security assessment are Input Validation, API, Cryptography, and Client/Server architecture.
The manual review of the Project One Code Base identified several issues. The GreetingController.java file needs proper input validation for the “name” string. 
The pom.xml file includes dependencies but does not directly handle data protection. The code base lacks an API, resulting in a loss of data integrity. 
No cryptography was reviewed, and the files did not contain any type of data encryption. The DocData.java file had good code quality but contained no error handling.
Several dependencies were identified as having flaws or needing upgrades. 
These include hibernate-validator-6.0.18.Final.jar, jackson-databind-2.10.2.jar, logback-core-1.2.3.jar, snakeyaml-1.25.jar, spring-boot-2.2.4.RELEASE.jar, and spring-web-5.2.3.RELEASE.jar.
Mitigation Plan
Based on the findings from the manual review and static testing report, Global Rain has developed a comprehensive mitigation plan for Project One:

Address lack of proper input validation for the "name" parameter.
Prevent malicious data entry and address username/password vulnerabilities.
Upgrade Apache Server to address vulnerabilities in jackson-databind.
Integrate secure coding practices and error handling.
Properly sanitize code for certificate validation to prevent exploitation of vulnerabilities.
Configure Spring Boot application to use HTTPS for secure communication.
Develop a detailed migration plan with steps, responsible parties, timelines, and verification mechanisms for each identified vulnerability.
