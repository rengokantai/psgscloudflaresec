#### psgscloudflaresec
#####2 setting up a new site
######change name servers
go do DNS provider, change to cloudflare server name  
######5testing the configuration
```
nslookup y.me
```
open chrome
```
chrome://net-internals/#dns
```

#####3
######7
use full certificate  
strict certificate->do not use
######8 forcing HTTPS with a page title(redirect HTTPS)
Add a new rule  
```
/*
```
then it is 301 request to HTTPS
######9 HTTP strict transport security (HSTS)
```
Strict-Transport-Security: max-age=111111; includeSubDomains;preload
```
307 status code. Internal redirect  
test:goto ssllabs.com
#####4
######3 setting the security level

