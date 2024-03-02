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



8-1 Journal: Portfolio Submission
Summary
Artemis Financial, a consulting firm specializing in personalized financial planning, engaged Global Rain to conduct a comprehensive vulnerability assessment of their web-based software application.
Software Security Excellence
By conducting manual reviews and static testing, it was identified critical areas such as input validation, API security, cryptography, and client/server communication. 
Challenges 
Ensuring thorough coverage of all potential vulnerabilities while considering Artemis Financial's specific security requirements. 
Increasing Layers of Security
implementing proper input validation, upgrading outdated dependencies, enhancing error handling, and enforcing HTTPS communication
Functionality and Security
Regular assessments, code reviews, and proactive measures help maintain a secure and functional software application.
Resources 
utilized industry-standard tools such as static code analysis tools, dependency scanners, and vulnerability databases.
Showcase Work
well-documented vulnerability assessment report, highlight my testing practices, emphasize security expertise, and showcase my commitment to quality and collaboration. 
