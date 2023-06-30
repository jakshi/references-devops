# Intro

* According to RFC5737 - The blocks 192.0.2.0/24 (TEST-NET-1), 198.51.100.0/24 (TEST-NET-2), and 203.0.113.0/24 (TEST-NET-3) are provided for use in documentation.
* let's say we have some domain that need to be redirected to another domain.
* We add it to cloudflare and add a pager rule for redirect.
* But we need to add a DNS records to enable redirect mode on them
* What IP addresses we should assign to those `@` and `www` DNS records?
* For example: `192.0.2.1`
* This IP address of course will never be used because we will redirect everything to the other domain.
* And as nobody route this IP address it's safe to have in values even if redirect would break for some reason.

# References

* https://datatracker.ietf.org/doc/rfc5737/
