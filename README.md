RAID Performance Calculator
An open source interactive web-based tool to estimate read/write performance, usable storage capacity, and fault tolerance for common RAID and ZFS configurations.

License: MIT — free to use, share, and modify. See the LICENSE file for details.

🚀 Live Demo
View the Calculator

💽 Supported RAID Types
RAID 0, 1, 5, 6, 10

RAIDZ1, RAIDZ2, RAIDZ3 (ZFS)

✨ Features
Performance Estimation — Calculates read & write speed multipliers based on drive count and RAID type

Capacity Calculation — Estimates usable capacity after parity/reserve space

Fault Tolerance Overview — Shows how many drives can fail without data loss

Visual Comparison — Generates charts for quick analysis

Drive Type Presets — Supports HDD, SSD, and NVMe workloads (sequential vs. random)

Beginner Friendly — Simple UI, no installation required

MIT Licensed — 100% open source, contributions welcome

📸 Preview

📖 How It Works
Enter:

Number of drives

Drive size

Workload type (Sequential or Random)

The calculator outputs:

Read speed multiplier

Write speed multiplier

Total usable storage

Fault tolerance rating

⚡ Installation (Local Copy)
bash
Copy
Edit
git clone https://github.com/bradgarrison/raid-performance-calculator.git
cd raid-performance-calculator
open index.html
🤝 Contributing
Contributions, bug reports, and feature requests are welcome!

Fork the repo

Create a feature branch

Submit a pull request

📜 License
MIT License — see the LICENSE file for details.

