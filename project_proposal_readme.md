# Project 1 Proposal: Network Health Checker (CLI)

## Problem Statement
Network administrators and system operators frequently need a lightweight and immediate method to check the availability of multiple local network devices. Manually pinging devices one by one is time-consuming and inefficient, especially when trying to pinpoint network outages or unresponsive hardware in real-time.

## Why It Matters
A fast, automated CLI tool reduces diagnostic time from minutes to seconds. By scanning up to 20 IP addresses in parallel and flagging unreachable hosts within 5 seconds, administrators can rapidly detect connection drops, maintain network reliability, and perform routine health checks without needing heavy graphical network management tools.

## Team Members and Roles
- **Team Lead / Developer:** Responsible for core CLI implementation, ping request logic, and input validation.
- **Documentation & QA:** Responsible for maintaining project specs (`SPEC.md`), logging AI usage (`AI_USE.md`), and writing acceptance tests.

## Tools Plan
- **Programming Language:** Python 3.12 (using standard libraries such as `subprocess`, `sys`, and `ipaddress`).
- **Version Control:** Git & GitHub CLI (`gh`).
- **Development Environment:** Visual Studio Code on Windows 11.