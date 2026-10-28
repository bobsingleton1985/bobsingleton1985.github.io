# Utility Center 3.4.0

- New: **Monitoring** — a card at the top of the main window and a separate «Мониторинг» window. Shows agents, the Claude route and systems with plain statuses (ОК / ВНИМ. / РИСК / СБОЙ / НЕТ ДАННЫХ), the time of the last check, and a log of state changes. Click a row for details.
- Read-only: the window only reads the status page of the collector on Mac mini; it never restarts or changes anything.
- Data older than 3 minutes is marked as stale instead of being shown as healthy.
- The address is not built into the app: optional `monitorURL` in `site.json`, otherwise the Mac mini address from `site.json`.
