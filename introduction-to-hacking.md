Welcome hacker! The following is a short guide on the main topics within hacking. You'll find descriptions for each topic, along with common free-to-use tools.

todo: create a visual roadmap of where what topics people should learn, a recommended order that's just a guide, feel free to change it around if you like!

# Web Security

This domain focuses on finding and exploiting vulnerabilities in web applications, such as Cross-Site Scripting (XSS), SQL Injection, Broken Authentication/Authorization and more.

A great topic list to begin, take a holistic look at what each of these topics are and choose where you want to start learning!
- Cross-Site Scripting
- Path Traversal
- "IDOR" (simply changing a URL parameter, ?user=1 to ?user=2 to see if you get access!)
- Command Injection
- Authentication Bypass
- File Upload Vulnerabilities
- SQL Injection

All those beginner friendly topics do have their more advanced aspects, but they're a great place to start when it comes to web security!
We want to mention CORS, it's an important topic which has many aspects. It's important in both web development and web security.

A special mention for Port Swigger, it's the go to place for learning how to exploit every web security vulnerability!
They have free labs and a free academy to learn from! They only charge for the professional version of their industry leading BurpSuite software, and their industry recognized exam.
- [Port Swigger](https://portswigger.net/web-security/all-topics)

Beginner topics:
- [Reflective Cross-Site Scripting](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/07-Input_Validation_Testing/01-Testing_for_Reflected_Cross_Site_Scripting.html)
- [Stored Cross-Site Scripting](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/07-Input_Validation_Testing/02-Testing_for_Stored_Cross_Site_Scripting.html)
- [DOM-Based Cross-Site Scripting](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/11-Client_Side_Testing/01-Testing_for_DOM-based_Cross_Site_Scripting.html)
- [SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)

- [Full list of attacks - OWASP](https://owasp.org/www-community/attacks/)

Cheatsheets:
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/index.html)
- [Port Swigger XSS](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
- [Port Swigger SQL Injection](https://portswigger.net/web-security/sql-injection/cheat-sheet)

Recommended Burp Plugins:
- [Auth Matrix](https://portswigger.net/bappstore/30d8ee9f40c041b0bfec67441aad158e) - Great for authorization bypasses!
- [Hackvector](https://github.com/hackvertor/hackvertor) - Excellent for encoding and decoding strings into any format
- [Turbo Intruder](https://github.com/portswigger/turbo-intruder) - No rate limiting like the normal intruder tool has
- [Param Miner](https://github.com/portswigger/param-miner) - Can break your client-side browsing experience

## AUT Cyber Security Papers

At AUT, we have a number of papers that help education cyber security:
- [Information Security Technologies- COMP607](https://paperdescriptorreport.aut.ac.nz/PaperDescriptor/PaperDescriptor?courseCode=COMP607&date=2025-04-18&saveFormat=pdf)
	- A multi lecture series serving as an in-depth introduction to cryptography
	- Legal definitions of malware (basics)
- [Network Security - COMP715](https://paperdescriptorreport.aut.ac.nz/PaperDescriptor/PaperDescriptor?courseCode=COMP715&date=2026-04-25&saveFormat=pdf)
	- Configuration of Cisco routers and switches to mitigate attack vectors
	- Understanding firewalls, access control, rogue device attacks and more!
	- An introduction to detection systems
	- Learn about cryptography
	- Setup enterprise grade VPN tunnels in a lab environment
	- Mostly a sysadmin and defensive security paper, some offensive security included
- [Operating Systems - COMP604](https://paperdescriptorreport.aut.ac.nz/PaperDescriptor/PaperDescriptor?courseCode=COMP604)
	- Memory management, page tables
	- xv6 Operating System
	- User-land and kernel-land
	- Partly aids and serves as foundational knowledge for binary exploitation
- [Network and System Administration - COMP609](https://paperdescriptorreport.aut.ac.nz/PaperDescriptor/PaperDescriptor?courseCode=COMP609&date=2022-09-01&saveFormat=pdf)
	- Introduction to web security
	- Carry out an introductionary offensive security pentest on Windows 2012 and Metasploitable2 servers
	- Advise on mitigations for security vulnerabilities
	- Write a security report

Non-exhaustive list.

### Recommended Meetups

Great meetups around Auckland, a great way to network and meet new like-minded hacker friends:
- ISIG
- HackTheBox Auckland
- Howick Linux Group
- OWASP Auckland

# Website Resources

The following websites are a mixture of beginner friendly and more advanced in-depth topics of hacking:
- [https://portswigger.net/web-security](https://portswigger.net/web-security) (Web Security)
- [https://book.hacktricks.wiki/en/index.html](https://book.hacktricks.wiki/en/index.html) (Wiki of hacking knowledge)
- [https://pwn.college/welcome/welcome](https://pwn.college/welcome/welcome) (Linux, Binary Exploitation)
- [https://exploit.education/](https://exploit.education/) (Binary Exploitation)
- [https://hackthebox.com](https://hackthebox.com) (Mostly paid resources, free machines to hack)
