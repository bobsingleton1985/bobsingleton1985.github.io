# Utility Center 3.3.2

- Household network addresses are no longer built into the app. They are read from a local settings file (`~/Library/Application Support/UtilityCenter/site.json`); without it, network features stay disabled and change nothing.
- Turning the Chuwi exit node on no longer forces LAN access off.
- Exit-node availability trusts the selected node's own status and reports UNKNOWN instead of a false "offline".
- Signed in-app updates via Sparkle 2.10.1 (Ed25519); automatic checks and installs remain off.
