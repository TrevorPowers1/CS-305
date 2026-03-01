Artemis Financial is a financial planning company, and they needed to improve the security of their web app that handled clients’ sensitive information on their investments, savings, and insurance plans. The primary issue was the insecure communication and verification of the data. I solved this problem by using HTTPS to enable secure communication and SHA-256 to perform the verification of the data.

Some things I did well: 
During the vulnerability assessment, I was good at identifying the locations where the data could be transmitted securely, and then I implemented the security improvements to the code. Secure coding is vital to prevent applications from exposing sensitive information to attackers, which could harm the company’s trust and reputation. Secure coding also helps to build trust with the users of the software, which is vital to the long-term stability of the business.

What was the most difficult problem to implement? 
Setting up the SSL certificate and keystore to allow the application to run on HTTPS was the most challenging task, but it was also useful to me because I gained experience on the actual application and debugging of the application.

What additional security layers did I implement?
I implemented additional security layers to the application by enabling the HTTPS communication, using SHA-256 to perform the verification of the data, and using OWASP Dependency-Check to perform the vulnerability assessment of the application. To ensure that the application was still functioning and secure after the modifications, I executed the program, the test of the hash endpoint using HTTPS, and the results of the Dependency-Check tool to ensure that there were no new vulnerabilities introduced to the application.

What tools and techniques did I use?
I used tools and techniques like Maven, Spring Boot, Java’s MessageDigest to perform the hashing, and OWASP Dependency-Check to perform the vulnerability assessment of the application. This project will be useful to me in the future if I want to present it to my potential employers to show them my ability to identify vulnerabilities, perform secure coding, and test the application to ensure that it is functioning properly and securely.
