# CS 305 Portfolio Reflection

## Artemis Financial

Artemis Financial is a financial consulting company that works with customers and their financial information. The company wanted to improve the security of its software application and make sure sensitive information was protected. My job was to review the application for security vulnerabilities and make changes that would improve the security of the software.

## What I Did Well

I think I did well identifying security vulnerabilities and finding ways to improve the security of the application. One important part of the project was looking at the software dependencies and checking them for known vulnerabilities. I also learned that secure coding is important because applications can contain sensitive customer and company information. Security helps protect this information from unauthorized access, data breaches, and other attacks. Having secure software can also help a company maintain the trust of its customers.

## Challenges During the Vulnerability Assessment

One of the more challenging parts of the vulnerability assessment was understanding the results from the dependency-check tools. There can be many warnings and vulnerabilities listed, so I had to determine which ones were important and understand what they meant. At the same time, this was helpful because it gave me experience using security tools that developers can use to find vulnerabilities in software.

## Increasing the Layers of Security

I increased the layers of security by using secure communication, hashing, certificates, and dependency checking. I used SHA-256 for integrity verification and SSL/TLS to provide secure communication through HTTPS. In the future, I would use tools such as OWASP Dependency-Check and vulnerability databases to identify known security problems. I would also review the code and determine the risk of each vulnerability before deciding which mitigation technique would be best.

## Making Sure the Application Was Functional and Secure

After making changes to the application, I tested it to make sure it continued to run correctly. I verified that the Spring Boot server started correctly and that the hash endpoint returned the expected SHA-256 checksum. I also ran OWASP Dependency-Check again after refactoring the code. This helped me check that my changes did not introduce additional vulnerable third-party dependencies.

## Resources, Tools, and Coding Practices

Some of the resources and tools I used included Maven, OWASP Dependency-Check, Java, Spring Boot, SHA-256, certificates, and SSL/TLS. I also learned the importance of reviewing dependencies and testing an application after making security changes. These tools and practices will be useful in future programming assignments and software development projects.

## What I Can Show Future Employers

I could show future employers my Artemis Financial secure software project as an example of what I learned in this course. The project demonstrates that I can review software for vulnerabilities, use security tools, refactor an application to improve its security, and test the application afterward. It also shows that I understand why secure coding should be included throughout the software development process.
