# Cisco CLI Hub

*[Türkçe](README.md)*

Cisco IOS / IOS-XE / NX-OS command reference — routing, switching, VPN, QoS.

**→ [Live: altanmelihhh-web.github.io/cisco-ios-cli-hub/](https://altanmelihhh-web.github.io/cisco-ios-cli-hub/)**

A searchable single-page reference for the commands that come up repeatedly in
the field. Each entry carries the command, what it does and when to reach for
it, so it hands you something runnable instead of a page to skim.

| | |
|---|---|
| Entries | 925 |
| Categories | 34 |
| Dependencies | none — single page, entirely client-side |
| Network calls | none |

## Coverage

- ACL
- BFD
- BGP
- DAI
- DHCP
- DHCP Snooping
- Debug
- Device Mgmt
- EEM
- EIGRP
- EtherChannel
- HSRP
- IP SLA
- IPsec VPN
- Interface
- MPLS
- Monitoring
- Multicast
- NAT
- NX-OS
- OSPF
- Ping/Trace
- Port Security
- QoS
- Route-Map
- SNMP/Syslog/NTP
- SPAN
- STP
- Security
- Static Route
- Storm Control
- Track
- VLAN
- VRF

## Usage

Open the page and search. Filtering is instant, and the category headings work
as navigation. Commands copy with one click.

Running it locally needs nothing extra:

```bash
git clone https://github.com/altanmelihhh-web/cisco-ios-cli-hub.git
cd cisco-ios-cli-hub
python3 -m http.server 8000    # or just open index.html
```

No build step, no package manager, no backend — `index.html`, `app.js`,
`style.css`.

## Note

Every address in the examples is documentation-range (RFC 5737 / RFC 1918) and
fictional. Consider the effect before running any of these against your own
environment; some change configuration or affect traffic.

## License

MIT — see [LICENSE](LICENSE).
