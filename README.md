# kc-sh

KaisarCode shell utilities.

## Overview

`kc-sh` is a collection of standalone shell tools.

## Included Tools

| Tool | Description |
| :--- | :--- |
| **`kc-sh`** | Dispatcher. Runs tools as `kc-sh <tool>`. |
| **`kc-shm`** | Key-value store backed by `/dev/shm`. |
| **`kc-dmn`** | Unix socket interface for daemon processes. |
| **`kc-wch`** | File watcher emitting `add`, `upd`, `del`. |
| **`kc-fifo`** | Named pipe (FIFO) manager. |
| **`kc-chat`** | Interactive loop delegator for subprocesses. |
| **`kc-chml`** |  Wraps standard input in a single ChatML message. |
| **`kc-inp`** | Standard input handler. |
| **`kc-kcs`** | Workspace validation tool. |
| **`kc-ngr`** | N-gram generator. |
| **`kc-tsm`** | Token similarity matcher for candidate generation. |
| **`kc-tfr`** | Token frequency matcher for candidate generation. |
| **`kc-tpm`** | Text profile similarity matcher between files. |
| **`kc-env`** | Activates a directory as a virtual environment. |

## Installation

Add the directory to `PATH`:

```bash
export PATH="$PATH:/path/to/kc-sh"
```

Or run directly:

```bash
./kc-sh --help
```

---

**Author:** KaisarCode

**Email:** <kaisar@kaisarcode.com>

**Website:** [https://kaisarcode.com](https://kaisarcode.com)

**License:** [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html)

© 2026 KaisarCode
