# CS305-Software-Security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
  - Artemis Financial is in a company that builds individual financial plans for retirement and financial growth. It needs a modern web application with security precautions for checksums and encrypting large financial archieves. It wants to allow for secure file uploading and encrypting data after being stored. Thats why they recruited the help of Global Rain, which will assist in building a modern secure web application.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  - I think my biggest strenbgth was implemeniting the dependency check and buildinmg the hash functions. This will allow the company to encypt files on both sides of communication and compare the two hashed messages to ensure nothing has been altered. It also allows for having a quick report that will reveal potential vulnerabilities in third party tools, and shows you how to fix the issue

Which part of the vulnerability assessment was challenging or helpful to you?
  - The hardest part that I don't think I did correctly was making the website capatable with https and building the certificates and keys. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  - I found ways of developing security techniques that protect from man in the middle attacks, and prevent altered files/messeages. I also, implemented a dependency check tool that will analyze third party vulnerabilities in the application, I implemented a AES encryption key for archive files, and implemented a secure protocol certificate for the website.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  - Testing frequently in between changes to make sure that the code is performing correctly. It also prevents too many changes being made before testing the application which can make testing for difficult to identify potential bugs.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  - Learning how to implement keys and certificates is very useful for future web applications. Using dependency tools can be added in some format to various applications. Lastly, learning how to implemenet encryption and hashing techniques helps me understand what the encryption methods are used for and how they should be implemented.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  - That I have a broad understanding of these tools, which gives me a great potential master them more quickily. I think that's the most important part of each college course. I can't become a security expert in 8 weeks but I can learn how to further improve my security skills. It allows me to have great starting points that I can use to imrove these sklills.
