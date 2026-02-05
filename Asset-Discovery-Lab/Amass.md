# Amass - Advanced Subdomain Enumeration 
Learn to use amass for comprehensive subdomain enumeration and intelligence gathering. Amass is a powerful tool that combines passive and active reconnaissance techniques.

## Objective
 Use amass to enumerate subdomains for example.com using different techniques.
## Hint
Start with amass enum -d example.com for basic enumeration.
Try amass intel -d example.com for intelligence gathering.
Use amass enum -h to see all available options

## test
`amass enum -d example.com`
```
pentester@kali-linux:~$ amass enum -d example.com
[INFO] Configuration loaded from: /root/.config/amass/config.ini
[INFO] Starting enumeration of example.com
[INFO] Found: www.example.com
[INFO] Found: mail.example.com
[INFO] Found: ftp.example.com
[INFO] Found: blog.example.com
[INFO] Found: api.example.com
[INFO] Found: admin.example.com
[INFO] Found: dev.example.com
[INFO] Found: staging.example.com
[INFO] Found: test.example.com
[INFO] Found: support.example.com
[INFO] Found: ns1.example.com
[INFO] Found: ns2.example.com
```
`amass intel -d example.com`
```
pentester@kali-linux:~$ amass intel -d example.com
[INFO] Configuration loaded from: /root/.config/amass/config.ini
[INFO] Starting intelligence gathering for example.com
[INFO] ASN: 12345 - Example Corp
[INFO] CIDR: 192.168.1.0/24
[INFO] Found related domain: example.org
[INFO] Found related domain: example.net
[INFO] Found related domain: examplecorp.com
[INFO] Intelligence gathering finished
```
`amass enum -h`
```
pentester@kali-linux:~$ amass enum -h
Usage: amass enum [flags]

Flags:
  -active                 Enable active recon methods
  -brute                  Enable brute force subdomain enumeration
  -d, --domain strings    Domain names separated by commas (can be used multiple times)
  -exclude-sources string Sources to exclude from enumeration
  -include-sources string Sources to include in enumeration 
```
- 🎉 Challenge Complete! You successfully used amass for subdomain enumeration.
## 📚 Learning ResourcesAmass 
Commands:

    amass enum -d <domain>: Basic subdomain enumeration
    amass enum -d <domain> -passive: Passive enumeration only
    amass enum -d <domain> -active: Active enumeration with DNS queries
    amass enum -d <domain> -brute: Include brute force techniques
    amass intel -d <domain>: Intelligence gathering and ASN discovery
    amass enum -d <domain> -o <file>: Save results to file

Amass Features:

    Combines multiple data sources for comprehensive enumeration
    Supports both passive and active reconnaissance techniques
    Can perform DNS brute forcing and zone transfers
    Provides intelligence gathering capabilities
    Maintains a graph database of discovered assets
    Supports API integrations with various security services

## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)


