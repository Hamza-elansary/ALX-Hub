# Subfinder
Learn to use subfinder for fast subdomain discovery. This tool uses passive techniques to find subdomains without directly querying the target.
## Objective
Use subfinder to discover subdomains for [digi.ninja](https://digi.ninja).
## Try
subfinder -d example.com or subfinder -d example.com -all

## test
- Basic Subfinder usage `subfinder -d digi.ninja `
```
└─$ subfinder -d digi.ninja 

               __    _____           __         
   _______  __/ /_  / __(_)___  ____/ /__  _____
  / ___/ / / / __ \/ /_/ / __ \/ __  / _ \/ ___/
 (__  ) /_/ / /_/ / __/ / / / / /_/ /  __/ /    
/____/\__,_/_.___/_/ /_/_/ /_/\__,_/\___/_/

                projectdiscovery.io

[INF] Current subfinder version v2.12.0 (latest)
[INF] Loading provider config from /home/bat/.config/subfinder/provider-config.yaml
[INF] Enumerating subdomains for digi.ninja
005936cf.poison.digi.ninja
161f0401.poison.digi.ninja
22903bd2.poison.digi.ninja
html5server.digi.ninja
0ea7273a.poison.digi.ninja
16ecd080.poison.digi.ninja
1d187ce7.poison.digi.ninja
alertlab.digi.ninja
collab1.digi.ninja
crackedflask.digi.ninja
dvwa.digi.ninja
html5.digi.ninja
1e2e130a.poison.digi.ninja
1e41a041.poison.digi.ninja
authlab.digi.ninja
splitxsslab.digi.ninja
dns0.zoneedit.com.digi.ninja
10895081.poison.digi.ninja
14eff7c8.poison.digi.ninja
17f7fa1f.poison.digi.ninja
collab.digi.ninja
robin.digi.ninja
055728bc.poison.digi.ninja
05d0a592.poison.digi.ninja
0c5f3945.poison.digi.ninja
cors-client.digi.ninja
07a1f15c.poison.digi.ninja
16d10b3f.poison.digi.ninja
1c91724d.poison.digi.ninja
22cc8df0.poison.digi.ninja
fronted.digi.ninja
secret.digi.ninja
04fe7086.poison.digi.ninja
098e8b4b.poison.digi.ninja
1c7e3cc2.poison.digi.ninja
graphqlab.digi.ninja
poison.digi.ninja
299a2a60.poison.digi.ninja
053e9be7.poison.digi.ninja
hb2.digi.ninja
nsztm1.digi.ninja
nsztm2.digi.ninja
svg.digi.ninja
ws.digi.ninja
00bf72f7.poison.digi.ninja
10856cc9.poison.digi.ninja
189aa7ba.poison.digi.ninja
1c5e7ce4.poison.digi.ninja
wss.digi.ninja
dd681807.poison.digi.ninja
198f3c79.poison.digi.ninja
1e27cf31.poison.digi.ninja
www.digi.ninja
043ba7cf.poison.digi.ninja
cors-server.digi.ninja
frontme.digi.ninja
ip.digi.ninja
10bda1bb.poison.digi.ninja
191c56d9.poison.digi.ninja
vulndap.digi.ninja
0b4294ba.poison.digi.ninja
0eb8baea.poison.digi.ninja
1c01bc88.poison.digi.ninja
4681435e.poison.digi.ninja
0066742f.poison.digi.ninja
0a29c51a.poison.digi.ninja
[INF] Found 66 subdomains for digi.ninja in 19 seconds 490 milliseconds
```
- All sources with detailed output `subfinder -d digi.ninja -all`
```
└─$ subfinder -d digi.ninja -all

               __    _____           __         
   _______  __/ /_  / __(_)___  ____/ /__  _____
  / ___/ / / / __ \/ /_/ / __ \/ __  / _ \/ ___/
 (__  ) /_/ / /_/ / __/ / / / / /_/ /  __/ /    
/____/\__,_/_.___/_/ /_/_/ /_/\__,_/\___/_/

                projectdiscovery.io

[INF] Current subfinder version v2.12.0 (latest)
[INF] Loading provider config from /home/bat/.config/subfinder/provider-config.yaml
[INF] Enumerating subdomains for digi.ninja
fronted.digi.ninja
ws.digi.ninja
1e41a041.poison.digi.ninja
dns0.zoneedit.com.digi.ninja
67cee597.poison.digi.ninja
465ef97c.poison.digi.ninja
a0e21476.poison.digi.ninja
d550b9c7.poison.digi.ninja
graphqlab.digi.ninja
0eb8baea.poison.digi.ninja
1c7e3cc2.poison.digi.ninja
1d187ce7.poison.digi.ninja
aadfec94.poison.digi.ninja
f7495fab.poison.digi.ninja
hb2.digi.ninja
splitxsslab.digi.ninja
16d10b3f.poison.digi.ninja
alertlabserver.digi.ninja
3d40bbcb.poison.digi.ninja
8f04b2b1.poison.digi.ninja
cors-client.digi.ninja
10895081.poison.digi.ninja
189aa7ba.poison.digi.ninja
dd681807.poison.digi.ninja
00bf72f7.poison.digi.ninja
07a1f15c.poison.digi.ninja
161f0401.poison.digi.ninja
16ecd080.poison.digi.ninja
1e27cf31.poison.digi.ninja
22903bd2.poison.digi.ninja
5a7224fa.poison.digi.ninja
poison.digi.ninja
04fe7086.poison.digi.ninja
a0918761.poison.digi.ninja
affc80e7.poison.digi.ninja
authlab.digi.ninja
ip.digi.ninja
vulndap.digi.ninja
10856cc9.poison.digi.ninja
299a2a60.poison.digi.ninja
collab1.digi.ninja
collab.digi.ninja
frontme.digi.ninja
html5server.digi.ninja
www.digi.ninja
191c56d9.poison.digi.ninja
cd119a18.poison.digi.ninja
0066742f.poison.digi.ninja
053e9be7.poison.digi.ninja
1c91724d.poison.digi.ninja
61cae5be.poison.digi.ninja
927a256d.poison.digi.ninja
b5110a7e.poison.digi.ninja
dvwa.digi.ninja
html5.digi.ninja
secret.digi.ninja
wss.digi.ninja
005936cf.poison.digi.ninja
14eff7c8.poison.digi.ninja
nsztml.digi.ninja
hb1.digi.ninja
robin.digi.ninja
2e47d53c.poison.digi.ninja
7b2b5c96.poison.digi.ninja
ba43b410.poison.digi.ninja
c56f2d5d.poison.digi.ninja
f71d8127.poison.digi.ninja
9ef328b0.poison.digi.ninja
9898156d.poison.digi.ninja
1c5e7ce4.poison.digi.ninja
nstzm1.digi.ninja
47fc800a.poison.digi.ninja
7d9df267.poison.digi.ninja
3bf47d0b.poison.digi.ninja
198f3c79.poison.digi.ninja
crackedflask.digi.ninja
nsztm1.digi.ninja
svg.digi.ninja
055728bc.poison.digi.ninja
4681435e.poison.digi.ninja
alertlab.digi.ninja
05d0a592.poison.digi.ninja
098e8b4b.poison.digi.ninja
0a29c51a.poison.digi.ninja
0b4294ba.poison.digi.ninja
0ea7273a.poison.digi.ninja
1c01bc88.poison.digi.ninja
1e2e130a.poison.digi.ninja
cors-server.digi.ninja
nsztm2.digi.ninja
043ba7cf.poison.digi.ninja
0c5f3945.poison.digi.ninja
10bda1bb.poison.digi.ninja
17f7fa1f.poison.digi.ninja
22cc8df0.poison.digi.ninja
5ce945f4.poison.digi.ninja
6010bcdc.poison.digi.ninja
4eed71a9.poison.digi.ninja
[INF] Found 98 subdomains for digi.ninja in 30 seconds 1 millisecond
```

## 📚 Learning Resources

    subfinder: Show usage and available options
    subfinder -d <domain>: Basic subdomain enumeration
    subfinder -d <domain> -o <file>: Save results to file
    subfinder -d <domain> -s <sources>: Use specific sources
    subfinder -d <domain> -all: Use all available sources
    subfinder -d <domain> -silent: Silent output mode
    subfinder -d <domain> -v: Verbose output mode
    subfinder -d <domain> -t <N>: Set number of threads
    subfinder uses passive techniques for stealth reconnaissance
    Multiple sources provide comprehensive subdomain coverage
    Silent mode is useful for scripting and automation
    Verbose mode shows source attribution for each subdomain
    Thread adjustment can optimize performance

## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)

