# syshealth

**System Health Check Utility**

`syshealth` is a utility that calculates a system health score based on various system metrics such as CPU usage, memory usage, disk space, and load average. It generates a Markdown report highlighting areas for improvement.
This script is mostly just made for learning. Doesn't really tell you much if we're being completely honest. The markdown report is severely lacking in details too.

## 📥 Installation

### Using the Debian Package

```bash
wget -O syshealth.deb https://github.com/VictorBjorke/syshealth/releases/download/v1.0/syshealth_1.0_all.deb
sudo dpkg -i syshealth.deb
sudo apt-get install -f

