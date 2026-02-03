# HetrixTools macOS Server Monitoring Agent

Documentation available here: https://docs.hetrixtools.com/category/server-monitor/

### Changelog

#### Version 2.0.0:
- Initial macOS release (agent type 3)
- CPU usage, user/system breakdown, load averages, clock speed (Apple Silicon + Intel)
- RAM and swap usage via `vm_stat`
- Disk usage per mount point with inode tracking
- Per-interface network RX/TX bandwidth
- Per-physical-disk IO read/write metrics via `ioreg`
- Port connection auto-detection and tracking
- Service/process status monitoring
- CPU temperature via `powermetrics` (Apple Silicon)
- Drive health via `smartmontools` (optional)
- Outgoing ping support (latency and packet loss)
- Running processes snapshot
- macOS `launchd` scheduling (replaces `cron`/`systemd`)
- Pure Bash 3.2 compatible (no dependencies beyond macOS defaults)
