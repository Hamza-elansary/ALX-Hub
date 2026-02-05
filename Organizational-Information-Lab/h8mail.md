# h8mail
Learn to use h8mail for email OSINT and password breach hunting. This tool helps discover email addresses and check for password breaches.

## Objective
Use h8mail to discover email addresses and check for password breaches for example.com.

## Try 
 `h8mail -t example.com` or `h8mail -t admin@example.com`
- h8mail -t admin@example.com

```
pentester@kali-linux:~$ h8mail -t admin@example.com
[+] h8mail v2.5.6 - Email OSINT & Password breach hunting
[+] Target: admin@example.com
[+] Starting breach analysis...

[+] Email: admin@example.com
[+] Checking password breaches...
[+] Found in 3 data breaches:
  - LinkedIn (2012)
  - Adobe (2013)
  - Collection #1 (2019)

[+] Associated passwords:
  - password123
  - admin2021
  - welcome123

[+] Analysis completed
[+] Total breaches: 3
[+] Passwords found: 3
```
🎉 Challenge Complete! You discovered email addresses and subdomains using theHarvester.

## 📚 Learning Resources
    h8mail: Show usage and available options
    h8mail -t <domain>: Email enumeration for domain
    h8mail -t <email>: Check specific email for breaches
    h8mail -t <target> -o <file>: Save results to file
    h8mail -t <target> -j: Output in JSON format
    h8mail -t <target> -v: Verbose output
    h8mail -t <target> -q: Quiet mode
    h8mail combines email discovery with breach checking
    Password breaches reveal compromised credentials
    Email enumeration helps with social engineering
    JSON output facilitates integration with other tools
    Always respect privacy and legal boundaries
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)



