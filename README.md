# DNS-Scan Description
DNS-Scan is a simple python tool designed to find subdomains using bruteforce.

## Dependencies

* <b>Host</b>:
    ```sudo apt install host```
    
* <b>Python</b>
    ```sudo apt install python```

## Setup

```chmod +x dns_scan```

## How To Use

```./dns_scan <domain> <wordlist>```

<b>Example: </b> ```./dns_scan google.com subdomains.txt ```
The command above will scan *.google.com hosted domains.

![alt text](https://i.ibb.co/yN7krfs/running-dns-scan.png)

## Recommended Wordlist

The following repository contains a lot of useful wordlists for subdomain enumeration: https://github.com/rbsec/dnscan
