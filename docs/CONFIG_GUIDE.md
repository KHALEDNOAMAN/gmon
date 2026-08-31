# gmon Configuration Guide

## Supported Game Servers
| Game | Protocol | Default Port |
|------|----------|-------------|
| CS2 | A2S Query | 27015 |
| Minecraft | Query | 25565 |
| Rust | A2S Query | 28015 |
| Valheim | A2S Query | 2457 |
| ARK | A2S Query | 27015 |

## Quick Start
```bash
cargo install gmon
gmon --ip 192.168.1.100 --port 27015
```

## Configuration
```toml
[server]
ip = "192.168.1.100"
port = 27015
protocol = "a2s"

[display]
refresh_rate = 2  # seconds
show_players = true
show_vars = true
latency_history = 60  # seconds
```

## Terminal Shortcuts
| Key | Action |
|-----|--------|
| q | Quit |
| Tab | Switch panels |
| ↑/↓ | Scroll player list |
| r | Force refresh |
| g | Toggle latency graph |
