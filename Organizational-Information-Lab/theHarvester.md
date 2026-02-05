# theHarvester
Learn to use theHarvester to discover email addresses and subdomains from various sources.

## Objective
Use theHarvester to gather email addresses and subdomains for example.com.

## Try 
 `theHarvester -d example.com -b all` or `theHarvester -d example.com -b google`
- theHarvester -d example.com -b all

```
pentester@kali-linux:~$ theHarvester -d example.com -b all
[*] Target: example.com
[*] Searching Bing.
[*] Searching BingAPI.
[*] Searching Bufferoverun.
[*] Searching Censys.
[*] Searching Certspotter.
[*] Searching Crtsh.
[*] Searching Dnsdumpster.
[*] Searching Duckduckgo.
[*] Searching Fullhunt.
[*] Searching Github.
[*] Searching Google.
[*] Searching Hackertarget.
[*] Searching Hunter.
[*] Searching Intelx.
[*] Searching Linkedin.
[*] Searching Linkedin2.
[*] Searching Netcraft.
[*] Searching Otx.
[*] Searching PTRarchive.
[*] Searching Securitytrails.
[*] Searching Shodan.
[*] Searching Threatcrowd.
[*] Searching Threatminer.
[*] Searching Trello.
[*] Searching Twitter.
[*] Searching Urlscan.
[*] Searching Virustotal.
[*] Searching Yahoo.

[*] No IPs found.

[*] Emails found: 5
admin@example.com
contact@example.com
info@example.com
support@example.com
webmaster@example.com

[*] Hosts found: 8
www.example.com
mail.example.com
ftp.example.com
blog.example.com
api.example.com
admin.example.com
dev.example.com
staging.example.com
```
🎉 Challenge Complete! You discovered email addresses and subdomains using theHarvester.

## 📚 Learning Resources
    theHarvester -d <domain> -b all: Search all sources
    theHarvester -d <domain> -b google: Search Google only
    theHarvester -d <domain> -b linkedin: Search LinkedIn for employees
    Email addresses are valuable for social engineering and password attacks
    Subdomains reveal additional attack surface
    Always verify discovered information before using it
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)



