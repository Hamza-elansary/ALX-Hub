# Zone Transfer Attack
Attempt a DNS zone transfer for example.com. Only ns1.example.com is vulnerable. Use dig or nslookup to try an AXFR.
## Hint 
First find the nameservers with dig example.com NS, then try zone transfers on each nameserver.
## test
- Get the NS for the [digi.ninja](https://digi.ninja) website
```
└─$ dig +short digi.ninja NS
;; Warning: Client COOKIE mismatch
dns1.zoneedit.com.
dns2.zoneedit.com.
```
- Zone Transfer Attempts
```
└─$ dig @dns1.zoneedit.com digi.ninja

; <<>> DiG 9.20.15-2-Debian <<>> @dns1.zoneedit.com digi.ninja
; (2 servers found)
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 12843
;; flags: qr aa rd; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 1
;; WARNING: recursion requested but not available

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 1232
; COOKIE: a2535ebf9529e239010000006983bfa9f7ee3c41e50bdeb6 (good)
;; QUESTION SECTION:
;digi.ninja.                    IN      A

;; ANSWER SECTION:
digi.ninja.             10800   IN      A       5.196.105.14

;; Query time: 108 msec
;; SERVER: 165.22.116.248#53(dns1.zoneedit.com) (UDP)
;; WHEN: Wed Feb 04 23:52:41 SAST 2026
;; MSG SIZE  rcvd: 83
```
## 📚Learning Resources

Zone Transfer Commands:

    dig @<nameserver> <domain> AXFR: Zone transfer with dig
    nslookup -type=AXFR <domain> <nameserver>: Zone transfer with nslookup
    dig <domain> NS: Find nameservers
    nslookup -type=NS <domain>: Find nameservers

Zone Transfer Security:

    Zone transfers reveal all DNS records for a domain
    Misconfigured DNS servers may allow unauthorized zone transfers
    This can expose internal network structure and subdomains
    Modern DNS servers should restrict zone transfers to authorized servers
    Always test multiple nameservers as configurations may vary

## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)

