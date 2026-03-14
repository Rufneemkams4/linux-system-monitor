# linux-system-monitor
Bash script for Linux system monitoring

# Linux System Monitoring Script

## Overview

This project demonstrates basic Linux system monitoring automation using Bash scripting. The script checks CPU usage, memory usage, disk usage, and uptime.

## Technologies

Linux
Bash scripting
System monitoring utilities

## Script Purpose

System administrators monitor system health to detect performance problems early. This script demonstrates basic automation of system monitoring tasks.

## Script

#!/bin/bash

echo "System Health Report"
echo "-------------------"

echo "Hostname:"
hostname

echo "Uptime:"
uptime

echo "CPU Load:"
top -bn1 | grep load

echo "Memory Usage:"
free -h

echo "Disk Usage:"
df -h

echo "Logged Users:"
who

## Skills Demonstrated

- Bash scripting
- Linux monitoring tools
- System health analysis
- Basic automation

## Lessons Learned

This project helped me understand how Linux administrators monitor system performance and automate routine checks.

## Career Relevance

Demonstrates skills used in:

- Systems Administration
- IT Operations
- Infrastructure monitoring
- DevOps support roles
