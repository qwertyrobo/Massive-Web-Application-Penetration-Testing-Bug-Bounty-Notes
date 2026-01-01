## **Penetration Testing, Beginners To Expert\!**

This guide is designed for both beginners and experienced penetration testers. It covers all aspects of web application penetration testing, including foundational concepts, setting up testing environments with tools such as Burp Suite and bWAPP, and detailed methodologies for identifying and exploiting vulnerabilities, particularly those listed in the OWASP Top 10. The guide also provides practical resources such as video tutorials and links to relevant tools, making it valuable for anyone looking to improve their web application security testing and bug bounty hunting skills.

**Content List:**

  * Phase 1 - History
  * Phase 2 - Web and Server Technology
  * Phase 3 - Setting up the lab with Burp Suite and bWAPP
  * Phase 4 - Mapping the application and attack surface
  * Phase 5 - Understanding and exploiting OWASP top 10 vulnerabilities
  * Phase 6 - Session management testing
  * Phase 7 - Bypassing client-side controls
  * Phase 8 - Attacking authentication/login
  * Phase 9 - Attacking access controls (IDOR, Priv esc, hidden files and directories)
  * Phase 10 - Attacking Input validations (All injections, XSS and mics)
  * Phase 11 - Generating and testing error codes
  * Phase 12 - Weak cryptography testing
  * Phase 13 - Business logic vulnerability

-----

### **Web Application Penetration Testing**

#### **Phase 1 - History**

  * **History of the Internet** - [https://www.youtube.com/watch?v=VPToE8vwKew](https://www.youtube.com/watch?v=VPToE8vwKew)
  * **How the Internet Works in 5 Minutes** - [https://www.youtube.com/watch?v=sMHzfigUxz4](https://www.youtube.com/watch?v=sMHzfigUxz4)

#### **Phase 2 - Web and Server Technology**

  * **Basic concepts of web applications, how they work and the HTTP protocol** - [https://www.youtube.com/watch?v=qcALGDn0zpk](https://www.youtube.com/watch?v=qcALGDn0zpk)
  * **HTML Crash Course For Absolute Beginners** - [https://www.youtube.com/watch?v=salY\_Sm6mv4](https://www.youtube.com/watch?v=salY_Sm6mv4)
  * **Difference between static and dynamic website** - [https://www.youtube.com/watch?v=0QT06AFAbdc](https://www.youtube.com/watch?v=0QT06AFAbdc)
  * **HTTP Request Methods & Headers Explained** - [https://www.youtube.com/watch?v=8q5mc1AEtYo](https://www.youtube.com/watch?v=8q5mc1AEtYo)
  * **REST API concepts and examples** - [https://www.youtube.com/watch?v=-mN3VyJuCjM](https://www.youtube.com/watch?v=-mN3VyJuCjM)
  * **What is a cookie?** - [https://www.youtube.com/watch?v=yoE9-tNvhRs](https://www.youtube.com/watch?v=yoE9-tNvhRs)
  * **HTTP Status codes** - [https://www.youtube.com/watch?v=qmpUfWN7hh4](https://www.youtube.com/watch?v=qmpUfWN7hh4)
  * **What Is an HTTP Proxy?** - [https://www.youtube.com/watch?v=j9-Y0KWVJ1k](https://www.youtube.com/watch?v=j9-Y0KWVJ1k)
  * **HTTP Cookies and Sessions** - [https://www.youtube.com/watch?v=zHBpJA5XfDk](https://www.youtube.com/watch?v=zHBpJA5XfDk)
  * **HTTP basic and digest authentication** - [https://www.baeldung.com/cs/digest-vs-basic-authentication](https://www.baeldung.com/cs/digest-vs-basic-authentication)
  * **What is a Server?** - [https://www.youtube.com/watch?v=BPVcsOKfd34](https://www.youtube.com/watch?v=BPVcsOKfd34)
  * **Client-Server Model** - [https://www.youtube.com/watch?v=B8azMzrluHE](https://www.youtube.com/watch?v=B8azMzrluHE)
  * **Characters, Symbols and the Unicode Miracle** - [https://www.youtube.com/watch?v=MijmeoH9LT4](https://www.youtube.com/watch?v=MijmeoH9LT4)
  * **Encoding Basics** - [https://www.youtube.com/watch?v=8ue8febDDKU](https://www.youtube.com/watch?v=8ue8febDDKU)

#### **Phase 3 - Setting up the lab with BurpSuite and bWAPP**

  * **Setup lab with bWAPP (2024)** - [https://www.youtube.com/watch?v=cQhE0aBfreU](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DcQhE0aBfreU)
  * **Getting Started with Burp Suite (PortSwigger Official)** - [https://www.youtube.com/watch?v=S9i\_15D2VvY](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DS9i_15D2VvY)
  * **Configure Firefox with Burp Suite and Install Certificate** - [https://www.youtube.com/watch?v=JexC1-eeg-c](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DJexC1-eeg-c)
  * **Mapping and Scoping a Website with Burp Suite** - [https://www.youtube.com/watch?v=Pr-212A0A4E](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DPr-212A0A4E)
  * **Spidering and Crawling with Burp Suite** - [https://www.youtube.com/watch?v=tAqj6h5a-k8](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DtAqj6h5a-k8)
  * **Active and Passive Scanning** - [https://www.youtube.com/watch?v=vVuxa-5n\_1M](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DvVuxa-5n_1M)
  * **Burp Suite Intruder: A Full Tutorial** - [https://www.youtube.com/watch?v=1pGZ5dw-23k](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D1pGZ5dw-23k)
  * **Burp Suite Intruder Attack Types Explained** - [https://www.youtube.com/watch?v=4zjg6ZST5vU](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D4zjg6ZST5vU)
  * **Burp Suite Repeater Tutorial** - [https://www.youtube.com/watch?v=L9iK2aPmNsM](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DL9iK2aPmNsM)
  * **Burp Suite Sequencer Explained** - [https://www.youtube.com/watch?v=qbtD5I6m90A](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DqbtD5I6m90A)
  * **Burp Suite Decoder Tutorial** - [https://www.youtube.com/watch?v=LqZ6Yh-a2Pk](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DLqZ6Yh-a2Pk)
  * **Burp Suite Comparer Tutorial** - [https://www.youtube.com/watch?v=D0s8yf8aWPE](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DD0s8yf8aWPE)

#### **Phase 4 - Mapping the application and attack surface**

  * **Mapping application using robots.txt** - [https://www.youtube.com/watch?v=W9udg2iM\_RA](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DW9udg2iM_RA)
  * **Find Hidden Directories And Files With GoBuster** - [https://www.youtube.com/watch?v=40n5p-0I2iA](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D40n5p-0I2iA)
  * **Discover hidden directories and files with Burp Intruder** - [https://www.youtube.com/watch?v=4Fz9mJeMNkI](https://www.youtube.com/watch?v=4Fz9mJeMNkI)
  * **Identify application entry points** - [https://www.youtube.com/watch?v=IgJWPZ2OKO8](https://www.youtube.com/watch?v=IgJWPZ2OKO8)
  * **Identify client and server technology (Wappalyzer & WhatWeb)** - [https://www.youtube.com/watch?v=B8jN\_iWjtyM](https://www.youtube.com/watch?v=B8jN_iWjtyM)
  * **Identify server technology using banner grabbing (telnet)** - [https://www.youtube.com/watch?v=O67M-U2UOAg](https://www.youtube.com/watch?v=O67M-U2UOAg)
  * **Pentesting with Google Dorks (Google Hacking)** - [https://www.youtube.com/watch?v=NmdrKFwAw9U](https://www.youtube.com/watch?v=NmdrKFwAw9U)
  * **Use Nmap for fingerprinting web server** - [https://www.youtube.com/watch?v=VQV-y\_-AN80](https://www.youtube.com/watch?v=VQV-y_-AN80)
  * **Review web servers' metafiles for information leakage** - [https://www.youtube.com/watch?v=sds3Zotf\_ZY](https://www.youtube.com/watch?v=sds3Zotf_ZY)
  * **Web Application Enumeration** - [https://www.youtube.com/watch?v=vX-qn6V\_y-Q](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DvX-qn6V_y-Q)
  * **Map execution path through application** - [https://www.youtube.com/watch?v=0I0NPiyo9UI](https://www.youtube.com/watch?v=0I0NPiyo9UI)
  * **Fingerprint web application frameworks** - [https://www.youtube.com/watch?v=ASzG0kBoE4c](https://www.youtube.com/watch?v=ASzG0kBoE4c)

#### **Phase 5 - Understanding and exploiting OWASP top 10 vulnerabilities**

  * **OWASP Top 10 2021 Explained (Full Course)** - [https://www.youtube.com/watch?v=1I-b--I4j4U](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D1I-b--I4j4U)
  * **A01:2021 - Broken Access Control** - [https://www.youtube.com/watch?v=P38at6Tp8Ms](https://www.youtube.com/watch?v=P38at6Tp8Ms)
  * **A02:2021 - Cryptographic Failures** - [https://www.youtube.com/watch?v=2RKbacrkUBU](https://www.youtube.com/watch?v=2RKbacrkUBU)
  * **A03:2021 - Injection (SQL Injection)** - [https://www.youtube.com/watch?v=rWHvp7rUka8](https://www.youtube.com/watch?v=rWHvp7rUka8)
  * **A04:2021 - Insecure Design** - [https://www.youtube.com/watch?v=QJexYmJ-d5A](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DQJexYmJ-d5A)
  * **A05:2021 - Security Misconfiguration** - [https://www.youtube.com/watch?v=JuGSUMtKTPU](https://www.youtube.com/watch?v=JuGSUMtKTPU)
  * **A06:2021 - Vulnerable and Outdated Components** - [https://www.youtube.com/watch?v=IGsNYVDKRV0](https://www.youtube.com/watch?v=IGsNYVDKRV0)
  * **A07:2021 - Identification and Authentication Failures** - [https://www.youtube.com/watch?v=mruO75ONWy8](https://www.youtube.com/watch?v=mruO75ONWy8)
  * **A08:2021 - Software and Data Integrity Failures (Insecure Deserialization)** - [https://www.youtube.com/watch?v=nkTBwbnfesQ](https://www.youtube.com/watch?v=nkTBwbnfesQ)
  * **A09:2021 - Security Logging and Monitoring Failures** - [https://www.youtube.com/watch?v=IFF3tkUOF5E](https://www.youtube.com/watch?v=IFF3tkUOF5E)
  * **A10:2021 - Server-Side Request Forgery (SSRF)** - [https://www.youtube.com/watch?v=52-g7x1i-8Y](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D52-g7x1i-8Y)

#### **Phase 6 - Session management testing**

  * **Bypass authentication using cookie manipulation** - [https://www.youtube.com/watch?v=mEbmturLljU](https://www.youtube.com/watch?v=mEbmturLljU)
  * **Cookie Security Via HttpOnly and Secure Flag - OWASP** - [https://www.youtube.com/watch?v=3aKA4RkAg78](https://www.youtube.com/watch?v=3aKA4RkAg78)
  * **What is Session Fixation? (PortSwigger)** - [https://www.youtube.com/watch?v=YpFRx0a4kX8](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DYpFRx0a4kX8)
  * **What is Cross-Site Request Forgery (CSRF)? (PortSwigger)** - [https://www.youtube.com/watch?v=m0EHlfTgGUU](https://www.youtube.com/watch?v=m0EHlfTgGUU)
  * **Admin bypass using session hijacking** - [https://www.youtube.com/watch?v=1wp1o-1TfAc](https://www.youtube.com/watch?v=1wp1o-1TfAc)

#### **Phase 7 - Bypassing client-side controls**

  * **What are hidden form fields in HTML?** - [https://www.youtube.com/watch?v=orUoGsgaYAE](https://www.youtube.com/watch?v=orUoGsgaYAE)
  * **Bypassing hidden form fields using Burp Suite** - [https://www.youtube.com/watch?v=xahvJyUFTfM](https://www.youtube.com/watch?v=xahvJyUFTfM)
  * **Changing price on eCommerce website using parameter tampering** - [https://www.youtube.com/watch?v=A-ccNpP06Zg](https://www.youtube.com/watch?v=A-ccNpP06Zg)
  * **Hacking Websites with Cookie Tampering** - [https://www.youtube.com/watch?v=NgKXm0lBecc](https://www.youtube.com/watch?v=NgKXm0lBecc)
  * **Understanding the Referer header** - [https://www.youtube.com/watch?v=GkQnBa3C7WI](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DGkQnBa3C7WI)
  * **What is Cross-Origin Resource Sharing (CORS)?** - [https://www.youtube.com/watch?v=Ka8vG5miErk](https://www.youtube.com/watch?v=Ka8vG5miErk)
  * **What are Security Headers?** - [https://www.youtube.com/watch?v=TNlcoYLIGFk](https://www.youtube.com/watch?v=TNlcoYLIGFk)

#### **Phase 8 - Attacking authentication/login**

  * **Brute-force login panel with Burp Suite Intruder** - [https://www.youtube.com/watch?v=25cazx5D\_vw](https://www.youtube.com/watch?v=25cazx5D_vw)
  * **Username enumeration** - [https://www.youtube.com/watch?v=WCO7LnSlskE](https://www.youtube.com/watch?v=WCO7LnSlskE)
  * **Authentication over insecure HTTP protocol (Wireshark)** - [https://www.youtube.com/watch?v=ueSG7TUqoxk](https://www.youtube.com/watch?v=ueSG7TUqoxk)
  * **Forgot password vulnerability** - [https://www.youtube.com/watch?v=FEUidWWnZwU](https://www.youtube.com/watch?v=FEUidWWnZwU)
  * **Login page autocomplete feature enabled vulnerability** - [https://www.youtube.com/watch?v=XNjUfwDmHGc](https://www.youtube.com/watch?v=XNjUfwDmHGc)
  * **Testing for Weak password policy (OTG-AUTHN-007)** - [https://www.owasp.org/index.php/Testing\_for\_Weak\_password\_policy(OTG-AUTHN-007](https://www.google.com/search?q=https://www.owasp.org/index.php/Testing_for_Weak_password_policy\(OTG-AUTHN-007\))
  * **Test for credentials transport over an encrypted channel** - [https://www.youtube.com/watch?v=21\_IYz4npRs](https://www.youtube.com/watch?v=21_IYz4npRs)
  * **Testing browser cache weaknesses** - [https://www.youtube.com/watch?v=2T\_Xz3Humdc](https://www.youtube.com/watch?v=2T_Xz3Humdc)
  * **Bypassing login panel using SQL Injection** - [https://www.youtube.com/watch?v=TSqXkkOt6oM](https://www.youtube.com/watch?v=TSqXkkOt6oM)

#### **Phase 9 - Attacking access controls (IDOR, Priv esc, hidden files and directories)**

  * **Finding admin panels** - [https://www.youtube.com/watch?v=r1k2lgvK3s0](https://www.youtube.com/watch?v=r1k2lgvK3s0)
  * **Finding Hidden Webpages With Dirbuster / Gobuster** - [https://www.youtube.com/watch?v=--nu9Jq07gA](https://www.youtube.com/watch?v=--nu9Jq07gA)
  * **What is IDOR (Insecure Direct Object Reference)?** - [https://www.youtube.com/watch?v=gci4R9Vkulc](https://www.youtube.com/watch?v=gci4R9Vkulc)
  * **Zomato IDOR bug bounty walkthrough** - [https://www.youtube.com/watch?v=tCJBLG5Mayo](https://www.youtube.com/watch?v=tCJBLG5Mayo)
  * **What is privilege escalation?** - [https://www.youtube.com/watch?v=80RzLSrczmc](https://www.youtube.com/watch?v=80RzLSrczmc)
  * **Privilege escalation example** - [https://www.youtube.com/watch?v=g3lv\_\_87cWM](https://www.youtube.com/watch?v=g3lv__87cWM)

#### **Phase 10 - Attacking Input validations (All injections, XSS and mics)**

##### **HTTP verb tampering**

  * **Introduction HTTP verb tampering** - [https://www.youtube.com/watch?v=Wl0PrIeAnhs](https://www.youtube.com/watch?v=Wl0PrIeAnhs)
  * **HTTP verb tampering demo** - [https://www.youtube.com/watch?v=bZlkuiUkQzE](https://www.youtube.com/watch?v=bZlkuiUkQzE)

##### **HTTP parameter pollution**

  * **Introduction HTTP parameter pollution** - [https://www.youtube.com/watch?v=Tosp-JyWVS4](https://www.youtube.com/watch?v=Tosp-JyWVS4)
  * **HTTP parameter pollution demo** - [https://www.youtube.com/watch?v=QVZBl8yxVX0](https://www.youtube.com/watch?v=QVZBl8yxVX0)

##### **XSS - Cross site scripting**

  * **What is XSS? (PortSwigger)** - [https://www.youtube.com/watch?v=cbmBDiR6WaY](https://www.youtube.com/watch?v=cbmBDiR6WaY)
  * **Reflected XSS Demo** - [https://www.youtube.com/watch?v=r79ozjCL7DA](https://www.youtube.com/watch?v=r79ozjCL7DA)
  * **Stored XSS Demo** - [https://www.youtube.com/watch?v=oHIl\_pCahsQ](https://www.youtube.com/watch?v=oHIl_pCahsQ)
  * **DOM Based XSS Explained** - [https://www.youtube.com/watch?v=SHmQ3sQFeLE](https://www.youtube.com/watch?v=SHmQ3sQFeLE)
  * **XSS Filter Evasion Cheat Sheet** - [https://owasp.org/www-community/xss-filter-evasion-cheatsheet](https://owasp.org/www-community/xss-filter-evasion-cheatsheet)

##### **SQL injection**

  * **SQL Injection Master Course (Complete Series)** - [https://www.youtube.com/watch?v=243tripa-pI\&list=PLk\_nB42gPc\_c\_r2a-sY2y5sIIZ3nYa-hO](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D243tripa-pI%26list%3DPLk_nB42gPc_c_r2a-sY2y5sIIZ3nYa-hO)

##### **NoSQL injection**

  * **Introduction to NoSQL injection** - [https://www.youtube.com/watch?v=h0h37-Dwd\_A](https://www.youtube.com/watch?v=h0h37-Dwd_A)
  * **Attacking NoSQL databases** - [https://www.youtube.com/watch?v=lcO1BTNh8r8](https://www.youtube.com/watch?v=lcO1BTNh8r8)

##### **XPath and XML injection**

  * **What is XPath Injection?** - [https://www.youtube.com/watch?v=L2k3223i-w8](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DL2k3223i-w8)
  * **What is XML External Entity (XXE) Injection? (PortSwigger)** - [https://www.youtube.com/watch?v=g2ey7ry8\_CQ](https://www.youtube.com/watch?v=g2ey7ry8_CQ)
  * **XXE Demo** - [https://www.youtube.com/watch?v=3B8QhyrEXlU](https://www.youtube.com/watch?v=3B8QhyrEXlU)

##### **LDAP injection**

  * **Introduction and Practical Demo** - [https://www.youtube.com/watch?v=-TXFlg7S9ks](https://www.youtube.com/watch?v=-TXFlg7S9ks)

##### **OS command injection**

  * **What is OS Command Injection? (PortSwigger)** - [https://www.youtube.com/watch?v=v\_R0p3n\_5I8](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3Dv_R0p3n_5I8)
  * **OS command injection demo in bWAPP** - [https://www.youtube.com/watch?v=qLIkGJrMY9k](https://www.youtube.com/watch?v=qLIkGJrMY9k)

##### **File Inclusion (LFI/RFI)**

  * **Local File Inclusion (LFI) Explained** - [https://www.youtube.com/watch?v=kcojXEwolIs](https://www.youtube.com/watch?v=kcojXEwolIs)
  * **Remote File Inclusion (RFI) Explained** - [https://www.youtube.com/watch?v=MZjORTEwpaw](https://www.youtube.com/watch?v=MZjORTEwpaw)

##### **HTTP splitting/smuggling**

  * **What is HTTP Request Smuggling? (PortSwigger)** - [https://www.youtube.com/watch?v=bVaZWHrfiPw](https://www.youtube.com/watch?v=bVaZWHrfiPw)
  * **HTTP Request Smuggling Demo** - [https://www.youtube.com/watch?v=mOf4H1aLiiE](https://www.youtube.com/watch?v=mOf4H1aLiiE)

#### **Phase 11 - Generating and testing error codes**

  * **Forcing Error Messages with Burp Intruder** - [https://www.youtube.com/watch?v=LDF6OkcvBzM](https://www.youtube.com/watch?v=LDF6OkcvBzM)

#### **Phase 12 - Weak cryptography testing**

  * **SSL/TLS weak configuration explained** - [https://www.youtube.com/watch?v=Rp3iZUvXWlM](https://www.youtube.com/watch?v=Rp3iZUvXWlM)
  * **Testing for Weak SSL/TLS Ciphers with Nmap** - [https://www.youtube.com/watch?v=slbwCMHqCkc](https://www.youtube.com/watch?v=slbwCMHqCkc)
  * **Test SSL/TLS security with Qualys SSL Labs** - [https://www.youtube.com/watch?v=Na8KxqmETnw](https://www.youtube.com/watch?v=Na8KxqmETnw)
  * **Sensitive information sent via unencrypted channels** - [https://www.youtube.com/watch?v=21\_IYz4npRs](https://www.youtube.com/watch?v=21_IYz4npRs)

#### **Phase 13 - Business logic vulnerability**

  * **What is a business logic flaw?** - [https://www.youtube.com/watch?v=ICbvQzva6lE](https://www.youtube.com/watch?v=ICbvQzva6lE)
  * **How To Identify Business Logic Flaws** - [https://www.youtube.com/watch?v=FJcgfLM4SAY](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DFJcgfLM4SAY)
  * **Business Logic Flaws: Attacker Mindset** - [https://www.youtube.com/watch?v=Svxh9KSTL3Y](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DSvxh9KSTL3Y)
  * **Business Logic Exploits: Data Leakage** - [https://www.youtube.com/watch?v=qe0bEvguvbs](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3Dqe0bEvguvbs)
  * **Demo 1 - Excessive trust in the client** - [https://www.youtube.com/watch?v=yV7O-QRyOao](https://www.youtube.com/watch?v=yV7O-QRyOao)
  * **Demo 2 - Insecure Password Reset** - [https://www.youtube.com/watch?v=A8V\_58QZPMs](https://www.youtube.com/watch?v=A8V_58QZPMs)
  * **Demo 3 - Logic Flaw Bug Bounty Example** - [https://www.youtube.com/watch?v=1pvrEKAFJyk](https://www.youtube.com/watch?v=1pvrEKAFJyk)
  * **HackerOne Report - Logic flaw on password reset** - [https://hackerone.com/reports/145745](https://hackerone.com/reports/145745)
  * **HackerOne Report - Business Logic Flaw allows adding credits** - [https://hackerone.com/reports/430854](https://hackerone.com/reports/430854)

-----

ENJOY & HAPPY LEARNING\! ♥

### Follow me on LinkedIn: www.linkedin.com/in/akmalshaik
