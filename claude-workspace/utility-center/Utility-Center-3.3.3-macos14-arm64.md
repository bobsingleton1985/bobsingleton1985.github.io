# Utility Center 3.3.3

- Fix: Chuwi exit-node toggle failed with "Не удалось прочитать tailscale status --json" when the app was launched from Finder. The Tailscale.app binary ignored the command and printed a GUI notice instead of running as a CLI; the app now forces CLI mode (`TAILSCALE_BE_CLI=1`).
- Non-JSON output from Tailscale is now shown in the error instead of being hidden.
