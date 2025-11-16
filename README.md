# Issyx Imaging Platform - Releases

Official release packages for the Issyx Imaging Platform.

## Quick Install

Run these commands on your Ubuntu 22.04+ or Debian 12+ server:

```bash
# Download latest release
wget https://github.com/jdmays13/issyx-releases/releases/download/v2.5.1/issyx-v2.5.1.tar.gz

# Extract
tar -xzf issyx-v2.5.1.tar.gz
cd issyx-imaging-platform

# Install
sudo ./install-standalone.sh
```

## Requirements

- Ubuntu 22.04+ or Debian 12+
- 4GB RAM minimum (8GB recommended)
- 100GB disk space (500GB+ recommended for OS images)
- Static IP address (critical for PXE boot)
- Root/sudo privileges

## What Gets Installed

- FastAPI backend (Python 3.10+)
- React frontend
- PostgreSQL database
- Redis cache
- Nginx reverse proxy
- TFTP server for PXE boot

## After Installation

1. Open web interface: `http://YOUR_SERVER_IP`
2. Complete setup wizard
3. Configure your DHCP server with PXE options

See the full documentation in the release package for detailed instructions.

## Releases

| Version | Date | Notes |
|---------|------|-------|
| [v2.5.1](https://github.com/jdmays13/issyx-releases/releases/tag/v2.5.1) | November 2025 | Simplified setup wizard, DHCP configuration, browser caching fixes |
| [v2.5.0](https://github.com/jdmays13/issyx-releases/releases/tag/v2.5.0) | November 2025 | Standalone installer, auto-configuration |

## Support

For issues and feature requests, visit the main repository.

---

**Issyx Imaging Platform** - Enterprise Network Imaging Solution
