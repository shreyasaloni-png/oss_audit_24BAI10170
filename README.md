# OSS Audit: Inkscape
**Student Name:** Shreya Saloni  
**Registration Number:** 24BAI10170  
**Course:** Open Source Software (NGMC)

## Project Description
This repository contains a comprehensive technical audit and suite of shell scripts for **Inkscape**, the premier open-source vector graphics editor. This project explores FOSS licensing (GPL v2+), system integration, and the ethical philosophy of open-source development.

## Repository Structure
* `/scripts/system_identity.sh`: Reports system kernel, user, and distro license info.
* `/scripts/package_inspector.sh`: Validates Inkscape installation using a `case` statement.
* `/scripts/disk_auditor.sh`: Audits system directory permissions using a `for` loop.
* `/scripts/log_analyzer.sh`: Processes system logs using a `while-read` loop.
* `/scripts/manifesto_gen.sh`: An interactive script for generating a FOSS manifesto.

## Technical Requirements
* **OS**: Linux (Ubuntu/Debian preferred)
* **Shell**: Bash
* **Permissions**: Run `chmod +x scripts/*.sh` before execution.

## License
This project is part of an academic audit. The software being audited (Inkscape) is licensed under the **GNU GPL v2+**.
