# Enum.py
A tool to enumerate network services
----------------------------------------

The tool parses output from Nmap, identifies open services and performs enumeration on those services.

The execution is parallel, so you can pass multiple IP addresses as parameters and it'll scan them in parallel.

Ideal for CTF situations and even for OSCP.


### Usage:
```python enum.py <ip addresses separated by spaces>```
