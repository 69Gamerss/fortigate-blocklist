# FortiGate SSL VPN brute-force sources

IP addresses that tried to log in to FortiGate SSL VPN portals with dictionary usernames (password spraying).
`fortigate-sslvpn-bruteforce.txt` has one address per line, ready for FortiGate `config system external-resource` (type address).

- Source: failed SSL VPN logins on FortiGates we manage. Addresses whose attempts look like a real user's typo are
  left out.
- Every entry expires 30 days after it was last seen: hosting and VPN addresses change hands.
- Updated automatically.

False positive? Open an issue with the address.
