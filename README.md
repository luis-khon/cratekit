# Cratekit
## PStd Manager

A simple command-line tool to **open** and **close** `.PStd` project files in a reversible way.

It handles these tasks:
- **Open** a `.PStd` file into an extracted **project folder**
- Automatically create a **backup** of the original `.PStd` as a `.bak`
- **Close** the project folder back into the original `.PStd` format
- Clean up after closing so the folder returns to its original state (and removes the `.bak`)

---

## Requirements

- Python 3
- Linux (Ubuntu tested)

---

## How to Install

1. Clone (or download) the repo
2. Make sure you have Python 3 available:

```bash
python3 --version
