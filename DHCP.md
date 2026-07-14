# 📡 Dynamic Host Configuration Protocol (DHCP)

## What is DHCP?

DHCP (Dynamic Host Configuration Protocol) is a network protocol that automatically assigns IP addresses and other network settings to devices connected to a network.

Without DHCP, network administrators would have to manually configure every device, which becomes difficult in large networks.

---

## Information Provided by DHCP

A DHCP server can automatically assign:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server Address

---

## How DHCP Works

When a device joins a network, the following process takes place:

1. The device sends a DHCP Discover message.
2. The DHCP server responds with a DHCP Offer.
3. The device requests the offered IP address.
4. The server confirms the request and assigns the IP address.

This process is commonly known as the **DORA** process:

- Discover
- Offer
- Request
- Acknowledge

---

## Advantages of DHCP

- Automatically assigns IP addresses.
- Reduces manual configuration.
- Prevents IP address conflicts.
- Saves time in managing large networks.

---

## Cyber Security Relevance

DHCP is an important network service, but it can also be abused by attackers. For example, a rogue DHCP server may assign incorrect network settings and redirect users to malicious systems. Because of this, network administrators monitor DHCP activity and secure their network infrastructure.

---

## Quick Notes

- DHCP uses **UDP**.
- Server Port: **67**
- Client Port: **68**
- Commonly used in homes, offices, schools, and enterprise networks.

---

## Summary

DHCP simplifies network management by automatically assigning IP addresses and other network settings to devices. It is one of the essential services used in modern computer networks.
