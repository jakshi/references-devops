# IPv6

* [ENG] How does IPv6 subnetting work and how does it differ from IPv4 subnetting? https://serverfault.com/questions/426183/how-does-ipv6-subnetting-work-and-how-does-it-differ-from-ipv4-subnetting

# nf_conntrack: table full error

* [ENG] http://pc-freak.net/blog/resolving-nf_conntrack-table-full-dropping-packet-flood-message-in-dmesg-linux-kernel-log/

# TCP queues

* [ENG] http://engineering.chartbeat.com/2014/01/02/part-1-lessons-learned-tuning-tcp-and-nginx-in-ec2/
* [ENG] http://veithen.github.io/2014/01/01/how-tcp-backlog-works-in-linux.html

# What is the network address (x.x.x.0) used for?

why 10.0.0.0 IP address from let’s say 10.0.0.0/24 subnet is not used?

I of course know about explanation - “host zero isn’t used because it is the network number”,  but why does it mean that we cannot use it?

so according to RFC1812 section 4.2.3.1:

```
(2) SHOULD silently discard on receipt (i.e., do not even deliver to
    applications in the router) any packet addressed to 0.0.0.0 or {
    <Network-prefix>, 0 }.  If these packets are not silently
    discarded, they MUST be treated as IP broadcasts (see Section
    [5.3.5]).  There MAY be a configuration option to allow receipt
    of these packets.  This option SHOULD default to discarding
    them.
```

So 10.0.0.0 IP address from 10.0.0.0/24 subnet cannot be used because it will be discarded by the router :smile:

10.0.0.0 is just for example here.

However, with RFC 3021, there was a change about /31s subnets for P2P links, that allow to use .0 addresses for P2P purposes:

```
(h)  { , , 0 }

         Subnetwork number.  SHOULD NOT be used as a source address,
         except when the originator is one of the endpoints of a point-
         to-point link with a 31-bit mask.  For other types of links, a
         packet with such a destination SHOULD be silently discarded.
         If these packets are not silently discarded, they MUST be treated
         as IP broadcasts
```

## References

* What is the network address (x.x.x.0) used for? https://serverfault.com/questions/135267/what-is-the-network-address-x-x-x-0-used-for
