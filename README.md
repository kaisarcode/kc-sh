# kc-sh

Lightweight shell tools built with the same KaisarCode mindset: small pieces, direct behavior, and readable implementation.

This repository is the shell-side counterpart to the broader `kc-*` ecosystem. The goal is not to hide complexity behind a large framework, but to keep each tool inspectable, editable, and easy to compose from the terminal.

## Philosophy

`kc-sh` favors:

- simple shell scripts over unnecessary abstraction
- explicit input/output behavior
- tools that can be read quickly and modified locally
- composition through pipes and small contracts

The scripts are meant to stay understandable at a glance. If you want to know what exists here, inspect the repository directly and read the files.

## Usage

Run a script directly:

```bash
./kc-xxx ...
```

Or use the dispatcher:

```bash
./kc-run xxx ...
```

Most tools provide:

```bash
./kc-xxx -h
```

## Development

This repository is intentionally minimal. The preferred workflow is:

1. Read the script.
2. Run it locally.
3. Adjust behavior directly.
4. Validate with `kcs`.

## Validation

KaisarCode shell scripts in this repository should be checked with:

```bash
kcs ./kc-*
```

---

**Author:** KaisarCode

**Email:** <kaisar@kaisarcode.com>

**Website:** [https://kaisarcode.com](https://kaisarcode.com)

**License:** [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html)

© 2026 KaisarCode
