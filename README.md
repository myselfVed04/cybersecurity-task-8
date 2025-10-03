# Task 8 – Identify and Remove Suspicious Browser Extensions (Brave)

## Objective
Identify and remove suspicious Brave browser extensions and test VPN setup for privacy.

### Steps performed
1. Opened Brave extensions page: `brave://extensions/`.
2. Captured extensions list (before removal) — `screenshots/extensions-before.png`.
3. Inspected each extension and removed suspicious ones.
4. Captured extensions list (after removal) — `screenshots/extensions-after.png`.
5. Captured public IP (before VPN) — `screenshots/ip-before.png`.
6. Installed ProtonVPN (Free) and connected to a server.
7. Captured public IP (after VPN) — `screenshots/ip-after.png`.
8. (Optional) Performed speed tests before/after VPN.

### Files / Screenshots
- `screenshots/extensions-before.png`
- `screenshots/extensions-after.png`
- `screenshots/ip-before.png`
- `screenshots/ip-after.png`
- (optional) `screenshots/speed-before.png`, `screenshots/speed-after.png`

### Findings / Notes
- Extensions removed.
- VPN used: ProtonVPN Free — connected to `<Netherland>` server.
- Observations: IP changed from `<103.127.35.2>` to `<185.100.234.253>`; browsing speed changed from `<1 Mbps>` to `<58 Mbps>`.

### Conclusion
Removing suspicious extensions reduces risk of tracking and data leakage. VPN encrypts traffic and hides public IP but may slow down speed and may not guarantee full anonymity.

