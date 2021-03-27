# linux-kernel-tuning
Linux-Kernel-Tuning-and-Hardening
Bash script for optimizing performance and hardening Linux kernel by adjusting the kernel parameters. It is self-explained and not supposed to be a one-thing-fit-all script. You should see the script for yourself and adjust the values for your need. Use it with caution.

Usage
1. Download the script to a folder on your Linux machine (eg.: /root/scripts/), then execute it
chmod +x kernel_hardening_tuning.sh
./kernel_hardening_tuning.sh
2. Allow the script to run everytime the system starts
vim /etc/rc.local

# Add the following line:
/root/scripts/kernel_hardening_tuning.sh
