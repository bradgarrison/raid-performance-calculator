# RAID Performance Calculator

An interactive web-based tool to estimate **read/write performance, usable storage capacity, and fault tolerance** for common RAID and ZFS configurations.

Supports:
- RAID 0, 1, 5, 6, 10
- RAIDZ1, RAIDZ2, RAIDZ3 (ZFS)

## 🚀 Live Demo
[**View the Calculator**](https://bradgarrison.github.io/raid-performance-calculator/)

---

## ✨ Features
- Calculates **read & write speed multipliers** based on drive count and RAID type
- Estimates **usable capacity** after parity/reserve space
- Fault tolerance overview for each configuration
- Comparison chart for quick visual analysis
- Supports HDD, SSD, and NVMe workloads (sequential vs. random)
- MIT Licensed — free to use, share, and modify

---

## 📸 Preview
![RAID Performance Calculator Screenshot](og-image.png)

---

## 📖 How It Works
Enter:
1. Number of drives
2. Drive size
3. Drive type (HDD/SSD/NVMe)
4. Workload type (Sequential or Random)

The calculator then estimates:
- **Read speed multiplier**
- **Write speed multiplier**
- **Total usable storage**
- **Fault tolerance** (drives that can fail without data loss)

---

## ⚡ Installation (Local Copy)
Clone the repository:
```bash
git clone https://github.com/bradgarrison/raid-performance-calculator.git
