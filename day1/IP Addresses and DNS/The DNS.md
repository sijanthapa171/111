# DNS (Domain Name System)

## Internet's Phone Book
DNS translates human-friendly domain names (like google.com) into IP addresses (like 192.168.1.1).

## What is DNS?
A hierarchical and distributed system that helps computers find each other on the internet.

## How DNS Works (Short)
1. Browser requests domain IP.
2. Resolver starts lookup.
3. Root server → points to TLD.
4. TLD server → points to domain server.
5. Authoritative server → gives IP.
6. Resolver caches result.
7. Browser connects to server.

## DNS Hierarchy
- Root
- TLD (.com, .org, etc.)
- Second-level domain (example.com)
- Subdomain ([www.example.com](http://www.example.com))

![](dns.png)

## Common DNS Records

- A → IPv4 address
- AAAA → IPv6 address
- CNAME → Alias
- MX → Mail server
- TXT → Text info
- NS → Name server