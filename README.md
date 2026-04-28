# FFlags Dumper

![Python](https://img.shields.io/badge/python-3.10%2B-blue?style=flat-square&logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey?style=flat-square)
![Open Source](https://img.shields.io/badge/open%20source-yes-brightgreen?style=flat-square)

An FFlags dumper built in Python. It's open source and the code is intentionally kept short and readable so you can follow along easily. It attaches to the Roblox process, scans memory for the FFlags container, and resolves all flag offsets automatically.

---

## How it works

1. Attaches to the running Roblox process
2. Scans memory for the FFlags container
3. Automatically resolves all flag offsets
4. Exports results in your chosen format

---

## Output formats

Supports 4 export formats:

| Format | Output file | Description |
|--------|-------------|-------------|
| C++ | `.hpp` | Header file |
| C# | `.cs` | Class file |
| Python | `.py` | Offsets file |
| JSON | `.json` | Structured data file |

---

## Usage

```bash
python fflag_dumper.py
```

Just run it while Roblox is open and it'll dump everything automatically.

---

## Requirements

- Python 3.10+
- Windows
- Roblox open and running

---

> For educational and research purposes only.
