# Malicious-JavaScript-study
Malicious JavaScript study


Step 1:
Build HTTP request(Not HTTPS request)

Method:
XMLHttpRequest object / fetch() function.
fetch() function returns a promise
then() methods to handle the response.
catch() methods to handle any errors that may occur.

Why is it important
	-communicate with web servers
	-retrieve data from internet

Why not HTTPS?
HTTP stand for Hypertext Transfer Protocol, HTTPS stand for  Hypertext Transfer Protocol Secure, a secure version of HTTP. It has added adds encryption and authentication to the data being transmitted over the web.
A HTTPS connection can ensure the privacy and security of their users' data, and protect against malicious attacks and data breaches. (for further information google encryption and authentication.)
...A HTTP connection is less secure than HTTP.

What could it possible damage security?
While a HTTP request built, the code/ program could potentially be used to communicate with remote server or exfiltrate data from the system.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 2:
Code the Script to auto-store in temporary location on system once it's run.

Method:
Get temp path? tmpdir()
Create a temp file? createTempFile()

The major limitations of local storage are:
-Insecure data.
-Synchronous operations.
-Limited storage capacity.

Why?
It could allow it to evade the antivirus software's detection.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 3:
Move, copy or spread itself to different location.

Method:
Move: 	ActiveXObject
	GetFile()
	Move()
	
Copy:	copyFile()

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 4:
access the data of the system.

How do it access the data without permission?
It don't need to. It could exploits vulnerabilities of the system.

How?
Vulnerabilities, bugs, weakness. They could be search on the internet, there always some people did not patch it's system or update it's OS.

Privilege escalation. escalate it's own privileges to gain access data.

Fake Error Message, such as phishing. Trick users to granting permissions or provide access to data. There's many people overtrust unknown software.

How to avoid them in lowest effort?
Keep the OS up-to-date, patch the system. Set the account you usually use into NOT administrative privileges. 0 trust strategy, don't trust any software.


