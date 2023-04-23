# Java-SoftwareSecurity-ArtemisFinancial
This is a school project in Java programming addressing software security methods such as Maven Dependency check, Self-signed certificates, using secure hash algorithms and ciphers, 
or creating websites with secure protocols.


# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Financial company Artemis Financial hired me as their leading security developer. My job was to test their security features and enhance them to be on par with today's requirements.
After doing an initial check, I discovered multiple areas of insufficient security. The company was lacking safety against cyberattacks such as harmful code injection, 
DoS, sensitive information was not secured properly and attackers were able to access it, old versions of their software, etc. They asked me to improve the security features
and develop code that is strong against harmful efforts.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
What I did well was a thorough security check with explanations of all the vulnerabilities and giving the company a deep and comprehensive look into how is their data vulnerable to attacks.
Then I proceeded to upgrade their security features to prevent hackers from getting access to their databases, websites, and information about the users and themselves. Security is an important aspect
of the well-being of a successful company. If the attack is not defended they can lose their business and go bankrupt or end up in court. 

#What part of the vulnerability assessment was challenging or helpful to you?
Setting up the Maven Dependency Check was initially a challenge and also understanding what it means was hard. After familiarizing myself with how things work and how to interpret
the reports, I was able to comprehensively explain what is wrong with the Artemis Financial security team and the owners of the company.
A challenge was the time that it took to research all of the software and interpret all of the issues the company's code had. Afterward, more research was conducted to
eliminate vulnerabilities and develop code that would be on par with security standards and would not create more issues with security.

#How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I started with the code review. There I noticed some common mistakes like making the account balance variable public, so it was accessible by unauthorized users. 
Then I used Maven Dependency check, tried to understand the issues, and eliminate them if possible. In this step, false positive vulnerabilities had to be considered and a suppression file
was created to eliminate issues that were not a threat. The next step was to use a hash algorithm and cipher to secure the information transferred between the company and users through the Internet.
This was a helpful security feature because it improved the safety of sensitive data. Last, a self-signed certificate was added to the system to further secure the communication between the API and the Internet.

#How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
First, I went over the code and looked for any issues before running it. I ran the Maven Dependency check to see what the issues are before making any changes. After updating and refactoring their code, 
I started testing it to see if it is working. When I was sure it is working as intended, I ran a new Maven Dependency check to see if I introduced new vulnerabilities that need to be addressed.
There were no new vulnerabilities and I could proceed with updating the cipher and algorithms to secure the information transferred through the API call. Lastly, I created a self-signed certificate.
That confirmed that the protocols are secure and up to date, changing the website from HTTP (not secure) to HTTPS (secure).

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The primary resource that I will use in the future is the Maven Dependency check. I learned a lot about software security and it helped me to understand how vulnerabilities need to be addressed and dealt with 
before any issue happens. Another tool that was helpful to learn is what cipher algorithms exist and how they are used as well as certificates such as self-signed or CA. 
In my current work, I encountered some of these features and it gave me a better insight into how they work and how to use them in the future.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
To my future employer, I can show both of the projects that I developed. The first one shows how comprehensively I can understand the vulnerabilities, I can research them in great detail, and
it also shows that I am capable of using the vulnerability tools such as Maven Dependency Check. The second project also uses these skills described before and adds important skills and knowledge that I gained 
in this class. I learned how cipher algorithms work and I can use them to secure the data of my future employer. I know how to create self-signed certificates and add them to the code base to improve
the security of the system. And I can create thorough reports on the issues found and on the work that I did to remediate those issues.
