# LightQ

**A lightweight, command-line operating system built on the Debian kernel.**

LightQOS boots straight to a fast command line. Graphical applications open in their own windows only when you ask for them, so the system stays light while still being useful for everyday work.

## Features

- **CLI-first design**: starts in the command line, with a graphical interface on demand
- **One command for everything**: install, open, update and remove software through `lightq`
- **Smart-chat (Q-Unit)**: describe a task in plain language, such as storage, network, users or backups, and Q-Unit guides you through it and performs it
- **System snapshots**: save and restore the system, and a snapshot is taken before security changes
- **Built-in security**: `lightq secure scan` runs real checks and gives a score out of 100, with a dry-run mode before any change
- **Windowed apps**: open any installed app or terminal application in its own window
- **Customisable**: font colour themes, 12/24-hour clock, and screen resolution to fit your device

## Quick Start

```bash
lightq help                  # list all commands
lightq download <name>       # install an app or service
lightq open <app>            # open it in a window
lightq start smart-chat      # guided task assistant
lightq snapshot create       # save a restore point
lightq secure scan           # check system security
```

## Installation

1. Download the LightQOS ISO and boot it on a virtual machine or USB stick. It starts in live mode.
2. To install permanently, run:

```bash
sudo lightq-install
```

3. Remove the ISO and boot from the disk.

## Documentation

After installation, the user manual is available in your home directory:

```bash
less ~/README
```

---

**LightQOS - By Me**
