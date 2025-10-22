[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu BEGIN)

> [!CAUTION]
> This project is an **independent fork of VyOS®**.
> It is **not affiliated with, endorsed by, or sponsored by VyOS Networks Corporation** by any means.
> VyOS® is a registered trademark of VyOS Networks Corporation.

[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu END)

# vyos-utils

This repository contains utility binaries used by the VyOS CLI,
written in OCaml for speed and memory safety.

Currently, they are:

* `validate_value` — the top-level validation utility that checks regexes and executes external validators.
* `validators` — validator executables:
  * `file_path` — checks directory and file paths.
  * `numeric` — checks numbers and number ranges.
  * `url` — checks URLs/URIs.
* `completion` — completion helpers:
  * `list_interfaces` — produces lists of network interfaces.
