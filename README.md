# Simurg PTP CSS Themes

Two standalone external stylesheets adapt PTP's Retro and Dark appearances to Simurg while preserving Simurg content and branding. Their desktop utility header uses two static rows, retains the native Simurg links, and does not depend on hover menus. The first forum topic-status column remains hidden, so PTP-style read/unread topic identifiers are not shown.

## Use

Use either stable external stylesheet address.

### Dark

This matches the compact charcoal PTP style with gray panels and controls:

```text
https://raw.githack.com/erkcet/simurg-ptp-dark-css-test/refs/heads/main/simurg-ptp-dark.css
```

### Retro

This keeps the separate burgundy PTP Retro style:

```text
https://raw.githack.com/erkcet/simurg-ptp-dark-css-test/refs/heads/main/simurg-ptp-dark-local-test.css
```

Load it with Simurg's External stylesheet URL setting, a browser user-style
extension, or Safari's stylesheet tool, and apply it only to the Simurg
domain. The address follows the repository's `main` branch, uses a short CDN
cache lifetime, and stays the same when the stylesheet is updated.

## Safety

This repository is an isolated visual test. It does not modify the Simurg application, database, server, or user account.
