# ProxyPal v0.4.40

**Released:** 2026-06-06

## Sidecar Upgrade: CLIProxyAPI v7.1.44 → v7.1.47

This release upgrades the bundled CLIProxyAPI sidecar from **v7.1.44** (June 3) to **v7.1.47** (June 6), picking up 3 upstream releases with pluginhost capabilities, safemode example server, and file-backed request/response logging.

### What changed (v7.1.45 → v7.1.47)

**Plugin system (v7.1.47):**

- **pluginhost capabilities** — command-line flag handling and plugin execution for the plugin host subsystem

**Safemode (v7.1.46):**

- **Example API key warning server** — reference implementation for surfacing compromised-key warnings in safemode deployments

**Logging (v7.1.45):**

- **File-backed request/response sources** — enhanced API logging with persistent request/response capture

**Fixes (v7.1.45):**

- **xai orphaned tool_choice** — drops orphaned `tool_choice` when the Claude tools array is empty, preventing replay errors

---

## Notes

This is a sidecar-only bump — no ProxyPal UI or API surface changes.
