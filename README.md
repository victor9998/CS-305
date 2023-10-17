# CS-305
- Item 1 Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address? <br />
    - Sub Item 1Artemis Financial is a consulting company that wanted to protect their client’s information by using a checksum. Since they handle customers’ money, security is a top priority. It is important that the software is always up to date and that all vulnerabilities are found and fixed. <br />
What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?<br />
It's important to code securely because software security adds an extra layer of protection to a company's overall wellbeing. It's also important to make security a top priority early in the software development lifecycle to prevent future vulnerabilities. Hackers are constantly looking for information to steal; therefore, secure coding and testing is very important. I feel I did very well at finding and documenting the vulnerabilities that were crucial. <br />
What part of the vulnerability assessment was challenging or helpful to you?<br />
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?<br />
I increased layers of security for Artemis Financial by creating a checksum using SHA-256, which generates a hash so that the information is more secure. Throughout the project I was able to find and use a great tool called Snyk. Snyk looks through the code and lists any vulnerabilities found in the code, it also tells you how to go about fixing the issue. I will definitely keep using Snyk and dependency check maven in the future to find vulnerabilities in my code. <br />
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?<br />
I made sure that the code was functional by deploying the checksum hash and the user data. Prior to refactoring the code, I ran a dependency check on the code and screenshot the current vulnerabilities in the code. After I refactored the code, I reran the dependency check and received the same number of vulnerabilities. This showed me that no new vulnerabilities were introduced.<br />
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
A few resources I believe will be beneficial in future projects are Snyk, maven dependency check, cipher algorithms, and also the vulnerability process flow diagram. <br />
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?<br />
From this assignment I might show future employers my ability to complete security reports and also my ability to create certificates and cipher algorithms.
