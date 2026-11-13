# NETWORKWALKS--WEEK2
In Week 2 of my Cybersecurity & Ethical Hacking internship, I got hands-on practice with footprinting, reconnaissance, and network scanning.

For footprinting, I used six Kali Linux tools to gather information about a target domain. WHOIS gave me domain registration details, WhatWeb showed which technologies the site runs on, and Nslookup resolved domain names. Curl let me inspect HTTP headers, Wafw00f detected whether a WAF was in place, and DNSRecon pulled additional DNS records.

For network scanning, I used Zenmap to map my local network configuration and find active hosts. I also recorded IP and MAC addresses and built a network topology from what I found.

My biggest takeaways:

	•	Information gathering matters. Before ever attempting an exploit, you can learn a lot just from public information and network responses.
	•	Documentation matters. A good report explains what was done, what was found, what it means, what risk it creates, and how to reduce that risk.
	•	Authorization matters most. Reconnaissance and scanning must stay within an approved scope. Everything I did was part of the assigned educational lab.