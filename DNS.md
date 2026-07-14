# 🌍 Domain Name System (DNS)

## Overview

The Domain Name System (DNS) is often called the **phonebook of the Internet**. It translates human-readable domain names into IP addresses so that computers can communicate with each other.

For example, instead of remembering an IP address like **142.250.190.78**, we simply type **www.google.com**.

---

## How DNS Works

When you enter a website address in your browser:

1. The browser sends a DNS request.
2. The DNS server searches for the IP address.
3. The correct IP address is returned.
4. The browser connects to the web server.
5. The requested website is displayed.

---

## Common DNS Record Types

| Record  | Purpose                                   |
|---------|---------                                 |
| A       | Maps a domain name to an IPv4 address    |
| AAAA    | Maps a domain name to an IPv6 address    |
| CNAME   | Points one domain to another domain      |
| MX      | Specifies the mail server for a domain   |
| NS      | Identifies the authoritative name server |

---

## Why DNS is Important

- Makes websites easy to access.
- Eliminates the need to remember IP addresses.
- Enables communication between users and web servers.
- Plays a key role in Internet browsing.

---

## DNS in Cyber Security

DNS is frequently monitored during security investigations because attackers may use it for:

- DNS Spoofing
- DNS Cache Poisoning
- Malware communication
- Phishing attacks

Security analysts also use DNS logs to identify suspicious network activity.

---

## Quick Facts

- DNS uses **Port 53**.
- It works with both **TCP** and **UDP** protocols.
- Every website relies on DNS before a connection is established.

---

## Summary

DNS is a fundamental networking service that converts domain names into IP addresses. A strong understanding of DNS is essential for networking, system administration, and cyber security.
