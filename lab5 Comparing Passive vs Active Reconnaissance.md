## Comparing Passive vs Active Reconnaissance

| **Aspect** | **Passive Reconnaissance** | **Active Reconnaissance** |
|------------|----------------------------|---------------------------|
| **Tool Examples** | `whois`, `theHarvester`, Google Dorking, Shodan, `nslookup`, Maltego, crt.sh, Archive.org, public GitHub searches | `ping`, `netdiscover`, `nmap`, `traceroute`, `tcpdump` (with permission) |
| **Risk Level** | Low | High |
| **Detection Possibility** | Minimal | High |

### Summary

Start with **passive reconnaissance** (tools listed above) to gather public, non-intrusive intelligence — low risk and unlikely to trigger alerts. Move to **active reconnaissance** only after you have explicit authorization; active tools give accurate, real-time technical detail but are detectable and carry higher operational risk.
