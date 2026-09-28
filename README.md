# NETWORKWALKS-B083-WK4-PENETRATION-TESTING-REPORT
**Liability Disclaimer**

I have performed these activities only on systems and devices for which I had secured written authorization.
This project is conducted in a controlled environment for educational purposes only. The target has been authorised for security testing by Networkwalks. These techniques must never be applied to any system without explicit written permission from the owner.
All materials are provided strictly for educational and research purposes. Do not use any information, techniques, tools, or examples presented here to violate laws, access systems without permission, or cause harm.
The instructor, authors, and Networkwalks are not responsible for how this knowledge is used. Every action you take is your own responsibility. Misuse of these materials may result in criminal prosecution, significant fines, loss of employment, civil liability, and a permanent criminal record.
In many countries, unauthorized access to a computer system, network, application, or device is a criminal offense—even if no data is altered, stolen, or damaged. 


**Executive summary**
 
During the scheduled security assessment, a Critical-severity SQL Injection (SQLi) vulnerability was discovered on the primary application login gateway. Throughout testing, the username parameter accepted the input " admin'-- ", which resulted in successful authentication without supplying the legitimate account password. This completely bypasses the authentication mechanism, granting access to the application for non-authorized user without a valid password. This behaviour indicates that user-controlled input may be incorporated into an SQL query without adequate parameterization, potentially allowing an attacker to bypass authentication and gain unauthorized access. This flaw poses an immediate threat to data confidentiality, system integrity, and overall regulatory compliance.
