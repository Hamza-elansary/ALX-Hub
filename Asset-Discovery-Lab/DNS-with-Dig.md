# DNS with Dig
Learn to use dig to enumerate A, MX, TXT, and NS records for domain reconnaissance.
## Objective
Use dig to query different DNS record types for [digi.ninja](https://digi.ninja/).
## Try
 dig digi.ninja, dig digi.ninja MX, dig digi.ninja TXT, or dig digi.ninja NS
## test
- IPv4 addresses
`dig  +short digi.ninja`
```
└─$ dig  +short digi.ninja  
5.196.105.14
```
- Mail servers
`dig +short digi.ninja MX`
```
└─$ dig +short digi.ninja MX                  
5 alt1.aspmx.l.google.com.
10 alt4.aspmx.l.google.com.
10 alt3.aspmx.l.google.com.
1 aspmx.l.google.com.
5 alt2.aspmx.l.google.com.
```
- TXT records (SPF, DKIM, etc.)
`dig +short digi.ninja TXT`
```
└─$ dig +short digi.ninja TXT
"MS=712FB4F79EBA359697F41AB0976D6F38DF9DAE4F"
"keybase-site-verification=RlBQzB0npOVxkoAwBYJJuWxT8xMVqLPQ1NuBwA30Dq4"
"v=spf1 include:_spf.google.com ~all"
```

- Name servers
`dig  digi.ninja NS`
```
digi.ninja.             3599    IN      NS      dns1.zoneedit.com.
digi.ninja.             3599    IN      NS      dns2.zoneedit.com.## About Me
```
## 📚 Learning Resources
    dig: Show usage and available options
    dig <domain>: Query A records (default)
    dig <domain> MX: Query mail exchange records
    dig <domain> TXT: Query text records (SPF, DKIM, etc.)
    dig <domain> NS: Query name server records
    dig @<server> <domain>: Query specific DNS server
    DNS enumeration reveals infrastructure and security configurations
    Different record types provide different intelligence about the target
    Using specific DNS servers can bypass filtering or get different results

## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)


