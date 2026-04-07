# kc-sh

> **KaisarCode Shell Utilities** - A collection of lightweight, architecture-agnostic, and XDG-compliant shell tools for modern Unix environments.

[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
[![Website](https://img.shields.io/badge/website-kaisarcode.com-orange.svg)](https://kaisarcode.com)

## Overview

`kc-sh` is a suite of high-performance shell scripts designed to streamline development, automation, and system management. Every tool follows the philosophy of being "small, sharp, and focused," adhering strictly to **XDG Base Directory** specifications and supporting multiple CPU architectures.

## Included Tools

| Tool | Description |
| :--- | :--- |
| **`kc-sh`** | The central dispatcher. Run any tool using `kc-sh <tool>`. |
| **`kc-venv`** | Virtual Environment manager. Activates a root directory with full XDG isolation. |
| **`kc-shm`** | Shared memory key-value store powered by `/dev/shm`. |
| **`kc-dmn`** | Unix socket manager for daemonized command interactions. |
| **`kc-wch`** | File and directory watcher. Emits `add`, `upd`, and `del` events. |
| **`kc-fifo`** | Intelligent named pipe (FIFO) manager. |
| **`kc-chat`** | Interactive chat loop delegator for CLI sub-processes. |
| **`kc-inp`** | Standard input delegator for payload handling. |
| **`kc-kcs`** | KaisarCode Standards Validator for workspace compliance. |
| **`kc-ngr`** | N-Gram generator for text analysis using sliding windows. |
| **`kc-tpm`** | Text Profile Matcher (0 to 1 similarity matching). |

## Installation

To use these tools anywhere in your system, add the `kc-sh` directory to your `PATH` or symlink the dispatcher:

```bash
# Add to your .bashrc or .zshrc
export PATH="$PATH:/home/kaisar/Work/kc-sh"

# Or use the dispatcher directly
./kc-sh --help
```

## Usage Examples

### Virtual Environments
```bash
# Create and enter an isolated environment
kc-sh venv ./my-project-env
```

### Shared Memory store
```bash
# Set a value in /dev/shm
kc-sh shm set user_id 1234

# Retrieve it
kc-sh shm get user_id
```

### File Watching
```bash
# Watch for changes in the current directory
kc-sh wch .
```

## License

Distributed under the [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

---

**Author:** KaisarCode

**Email:** <kaisar@kaisarcode.com>

**Website:** [https://kaisarcode.com](https://kaisarcode.com)

**License:** [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html)

© 2026 KaisarCode
