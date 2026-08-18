<div align="center">

# Jetpooh
Yet another simple proxy client, developed for network debugging and enhancement
</div>

## Features

- Lightweight desktop network proxy built with C++20 and wxWidgets.
- HTTP and SOCKS5 inbounds.
- Rule, Global, and Direct routing modes.
- Direct, Reject, Shadowsocks, VMess, Trojan, and SOCKS5 outbounds.
- TOML configuration with one-time import for supported Clash / Mihomo YAML files.
- Native wxWidgets interface with optional local REST / IPC control APIs.
- Localhost-only listeners by default and configuration validation before startup.

## Usage

Windows Technical Preview:

```text
1. Extract the release archive to a writable directory.
2. Run JetPoohClassic.exe.
3. Select a proxy and routing mode in the desktop app.
4. Connect through the configured HTTP or SOCKS5 inbound.
5. Exit JetPooh from the window or system tray.