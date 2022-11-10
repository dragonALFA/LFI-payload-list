What is local file inclusion (LFI)?
LFI is a web vulnerability caused by mistakes made by a programmer of a website or web application. If an LFI vulnerability exists in a website or web application, an attacker can include malicious files that are later run by this website or web application.

How common is LFI?
Luckily, LFI is not a very common vulnerability. According to the latest Acunetix Web Application Vulnerability Report, it is present on average in 1% of web applications.

How dangerous is LFI?
LFI can be dangerous, especially if combined with other vulnerabilities – for example, if the attacker is able to upload malicious files to the server. Even if the attacker cannot upload files, they can use the LFI vulnerability together with a directory traversal vulnerability to access sensitive information.

How to detect LFI?
The most efficient way to detect LFI is by using an automated vulnerability scanner. You can of course detect such vulnerabilities through manual penetration testing but it takes a lot more time and resources.

How to avoid LFI?
To avoid LFI and many other vulnerabilities, never trust user input. If you need to include local files in your website or web application code, use a whitelist of allowed file names and locations. Make sure that none of these files can be replaced by the attacker using file upload functions.
