# DNS with NSlookup
## DNS Enumeration with nslookupUse
 nslookup to extract A, MX, TXT, and NS records, and perform a reverse lookup for [digi.ninja](https://digi.ninja).
## Try

`A` `MX` `TXT` `NS` `PTR`
## test
- Domain binding with IPv4 address
`nslookup -type=A digi.ninja `
```
Name:   digi.ninja
Address: 5.196.105.14
```
- Identify mail servers `nslookup -type=MX digi.ninja`
```
digi.ninja      mail exchanger = 5 alt1.aspmx.l.google.com.
digi.ninja      mail exchanger = 10 alt4.aspmx.l.google.com.
digi.ninja      mail exchanger = 10 alt3.aspmx.l.google.com.
digi.ninja      mail exchanger = 1 aspmx.l.google.com.
digi.ninja      mail exchanger = 5 alt2.aspmx.l.google.com.
```
- Miscellaneous textual information `nslookup -type=TXT digi.ninja`
```
digi.ninja      text = "MS=712FB4F79EBA359697F41AB0976D6F38DF9DAE4F"
digi.ninja      text = "keybase-site-verification=RlBQzB0npOVxkoAwBYJJuWxT8xMVqLPQ1NuBwA30Dq4"
digi.ninja      text = "v=spf1 include:_spf.google.com ~all"
```
- Trusted Name Servers `nslookup -type=NS digi.ninja`
```
digi.ninja      nameserver = dns1.zoneedit.com.
digi.ninja      nameserver = dns2.zoneedit.com.
```
- Reverse - from IP to domain name `nslookup -type=PTR 14.105.196.5` 
```
Server:         192.168.1.1
Address:        192.168.1.1#53

** server can't find 5.196.105.14.in-addr.arpa: NXDOMAIN
```
❌ No PTR record

## 📚Learning Resources

nslookup Commands:

    nslookup <domain>: Basic DNS lookup
    nslookup -type=MX <domain>: Mail exchange records
    nslookup -type=NS <domain>: Name server records
    nslookup -type=TXT <domain>: Text records
    nslookup <domain> <server>: Query specific DNS server

DNS Record Types:

    A: IPv4 address record
    AAAA: IPv6 address record
    MX: Mail exchange record
    NS: Name server record
    TXT: Text record (often used for verification)
    CNAME: Canonical name (alias) record
Or the server provider (usually OVH) hasn't configured Reverse DNS for this IP address

## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)

