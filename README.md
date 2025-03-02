# CS-305-Software-Security

•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

As a developer for Global Rain, the first part of our job is to understand our clients’ wants and needs to properly service them. The client, Artemis Financial, specializes in consulting with its customers to develop individualized financial plans. The financial plans may include savings, retirement needs, investments and insurance. Some of the primary aspects regarding Artemis’ software requirements include high levels of security due to the risk of compromising customer financial and personal information. Also, power and memory are also important elements, as this software must support high traffic and communication between systems and their many individual parts. Artemis wishes that we at Global Rain analyze their web-based financial system to identify any security vulnerabilities and generate findings that can then be deployed to mitigate these risks while maintaining company integrity and user experience. 

•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

When the analysis was completed and appropriate vulnerabilities were discovered, we generated findings in conjunction with potential solutions and presented this information to Artemis in an easily accessible and understandable format. We need to effectively convey the importance of coding securely. Without security, the foundation of the company’s trust is compromised. When a customer opts to use the Artemis software, they need to know that their sensitive information is safe and inaccessible to someone with malintent. The customer demands Artemis, and by extension Global Rain, does everything within it’s capabilities to maintain security. For the development team, Artemis is not responsible for the source code, therefore they trust us with security as the customer trusts them. 

•	Which part of the vulnerability assessment was challenging or helpful to you?

I found it easy to relate to Artemis and analyze their needs and wants as I have been employed in the banking/financial industry for five years. When looking through the requirements that Artemis described to the development team, it was helpful for me to use my prior knowledge to view the full picture and scope, which affected how I suggested solutions. 

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

One of the ways we increase layers of security is by adding input validation and APIs. We want to be sure that when the customer inputs data, this input is verified to ensure it matches the expected criteria before being passed through the rest of the system. This simple verification can significantly reduce major attacks by cutting off attacks at the input level. In the future, the Maven dependency check will serve very beneficial in identifying layers of vulnerability. This check is also handy, as you can continue to improve upon the code, re-run the Maven check, and see how the updates have affected security in real time. This results in quick turn-around time between identification, planning and execution of solutions. 

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

As mentioned above, the Maven dependency check was utilized to identify vulnerabilities. This served as beneficial as we could make alterations to the code, rerun the check and see any improvements. This check could be run as many times as we wanted until we felt comfortable with the security level. Or if we are not making the progress we desire, or if we find significant vulnerabilities, we can discuss whether we need to alter our overall system such as potentially changing operating systems. 

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

A resource I found helpful was the list of algorithm ciphers. This will come in handy in the future as the use of algorithm ciphers will be crucial in security and encryption of the code. Furthermore, this semester gave me a new perspective on coding. Until now, I have only thought about function without a regard for security. In future classes, I will consciously consider the security elements when designing how I want the application to run. 

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I mentioned this aspect above; however, I think it is important to stress the aspect of running a vulnerability check, identifying vulnerabilities, planning for correction, executing this plan, and rerunning the check to analyze the performance of your solutions. This should be positively received from a potential employer, as not only do they see you completing due diligence, but also, they can see a respect for ensuring things are completed properly, and most importantly securely. 
