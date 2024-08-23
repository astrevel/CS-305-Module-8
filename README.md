# CS-305 Module 8

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client, Artemis Financial, is a company specializing in financial planning and insurance services. Artemis Financial wanted my assistance to address concerns around securely storing private data and ensuring secure communications for uploading and downloading data.



## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

What I believe that I excelled at when assisting Artemis Financial with their goal, was identifying a wide range of security issues, from hard-coded credentials and input validation flaws to outdated libraries with known vulnerabilities. Throughout this project for Artemis Financial, I have found that secure coding to be crucial as it protects sensitive financial data, maintains client trust, and ensures compliance with regulations. By prioritizing software security, we're not just preventing potential breaches and financial losses, but also adding value to the company by enhancing its reputation, providing a competitive edge in the market, and creating long-term client relationships built on trust and reliability. This focus on security is a huge investment for Artemis Financial's overall stability and future growth.



## What about the process of working through the vulnerability assessment did you find challenging or helpful? 

One of the challenges that I faced was implementing the SHA-256 hash algorithm. This experience was a bit frustrating, but was most certainly valuable, as it reinforced my commitment to secure coding practices and helped challenge myself to become a better developer.



## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

My security enhancement approach began with running dependency checks, followed by source code analysis for errors. I then implemented TLS and encryption. In a real-world scenario, I'd follow a similar process but seek a more refined list of false positives for dependency checks.



## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities? 

To ensure the software’s functionality, I first eliminated all code errors that were present in the Eclipse editor. Next, I ran the server and verified that it had the correct output on localhost. I confirmed HTTPS access using the self-signed certificate. Finally, at post-refactoring, I conducted another dependency check, comparing results with the initial scan, and re-examined my code for any new errors.



## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks? 

What I found to be very helpful was not only to be able to generate dependency reports, as I plan to implement this process into other projects, but the process of creating SSL certificates. I found it to be particularly useful and believe it will be valuable for testing secure communications in future website development projects.



## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer? 

The assignment that I would showcase to future employers would be the Artemis Financial vulnerability report, as I believe it shows proof of my competency, and overall commitment to writing, secure code, along with how to overcome such vulnerabilities in a code base, to ensure that whatever software that I contribute to will not be compromised due to poor decisions that can made during the Software Development Life Cycle (SDLC).
