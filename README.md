# SoftwareSecurity  
<ins>Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</ins>  
Artemis Financial is a financial consulation agency that would like to utilize a more secure web platform for their customers.  They want their customer data to be encrypted and the website housing their customer data to used secure hyptertext transfer protocol.  Only authenticated and authorized users should be allowed access to the data as well.  
<ins>What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?</ins>  
When I searched vulnerabilities within Artemis Financial's software, I eliminitated areas where injection attacks may pose a threat as well as updated their dependency check version so it will be easier to identify new vulnerabilities.  A self-signed certificate and authentication was added to secure web access as well.  It is important to code securely because data leaks and downtime cause loss of money for a company.  Software security adds the time spent dealing with crisis management back to the labor bank because you are no longer struggling to mitigate issues when you identify vulnerabilities ahead of time.  
<ins>What part of the vulnerability assessment was challenging or helpful to you?</ins>  
The part of the vulnerability assessment that was most challenging for me was understanding when to suppress dependency vulnerabilities because of false positives or no known plan of action. This is something I think will take more time for me to get a grasp on when to suppress and when to take action.  
<ins>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</ins>  
To increase layers of security, I added a self-signed certificate to improve transport layer.  I added authentication and authorization to improve the session layer.  I removed injection attack areas of concern to improve the application layer.  
<ins>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</ins>  
To verify the security and functionality of the application, I thoroughly read through the code base and added authentication, encryption, authorization, a signed certificate, and updated dependency checks.  Once the changes were made, I ran the application to verify proper functionality.  After all modifications and tests were made, I completed another maven dependency check to see if any new vulnerabilities were added.  
<ins>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?</ins>  
I used maven dependency checks and SNHU step-by-step guides to work through all the best coding practices.  Making sure that no vulnerabilities are included in the code base and following the vunerability assessment process flow diagram will help me in future application builds so that I keep any development I'm involved in secure.  
<ins>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?</ins>  
I may show future employers the report I have uploaded to show that I have a competent grasp on application security and will not continually introduce new vulnerabilities into the company software.
