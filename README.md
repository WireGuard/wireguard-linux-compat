# WireGuard for Linux 3.10 - 5.5

> **This is a fork** of the upstream [wireguard-linux-compat](https://git.zx2c4.com/wireguard-linux-compat/) tree (base: `5de064d`). On top of upstream it adds support for binding a single device to multiple listening ports and a peer to multiple endpoints (commas-separated / CSV values). See [`src/README`](src/README) for a full changelog and usage. It also carries the `allowedips: Increase stack size` fix. This was written during a 2021 internship as an experiment; it is not used in production and is published for archival/reference purposes only.

WireGuard was merged into the Linux kernel for 5.6. This repository contains a backport of WireGuard for kernels 3.10 to 5.5, as an out of tree module.

**More information may be found at [WireGuard.com](https://www.wireguard.com/).**

## License

This project is released under the [GPLv2](COPYING).
