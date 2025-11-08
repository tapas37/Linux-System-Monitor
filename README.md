# 🖥️ Linux System Monitor Tool (C++)

## 📌 Overview
A console-based system monitor built in **C++** for **Linux**, displaying real-time system information such as CPU usage, memory usage, uptime, running processes, disk usage, and temperature. Similar to the Linux `top` command.

---

## ⚙️ Features
- Displays CPU usage and memory usage
- Shows system uptime
- Displays the total number of running processes
- Lists top 5 CPU-consuming processes:
  - Firefox
  - Chrome
  - VS Code
  - gnome-shell
  - systemd
- Shows disk usage stats (`df -h`)
- Displays system temperature (if supported)
- Saves system report to `log.txt` every 10 seconds
  ## 🧑‍💻 How to Run
1. Open your Linux terminal in the project folder.
2. Compile the C++ file:
```bash
g++ system_monitor.cpp -o system_monitor

