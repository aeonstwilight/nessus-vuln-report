# Nessus Vuln Report

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A lightweight Windows desktop application for analyzing and normalizing Nessus CSV exports.

Designed for vulnerability management and SOC workflows, this tool provides SLA tracking, exploit visibility, risk scoring, and visual analytics — all in a native executable with no Python or browser required.

---

## Features

### 📊 Metrics Dashboard
- Total vulnerability count  
- Severity breakdown (Critical, High, Medium, Low)  
- Exploitable findings count  
- CVSS ≥ 9 findings  
- Oldest vulnerability detected  
- Automated Risk Score & Risk Rating  

---

### ⏳ SLA & Remediation Tracking

**Remediation Windows**
- Critical / High → 30 days  
- Medium → 90 days  
- Low → 180 days  

Automatically calculates:
- Age (Days)  
- Days Remaining  
- Expired Status (⚠ indicator)  
- “Expired Only” filtering  

---

### 🔍 Interactive Vulnerability Table

Displays:
- Plugin ID  
- Plugin Name  
- Severity  
- Host  
- CVSS Score  
- Exploit Availability  
- Age (Days)  
- Days Remaining  
- Expired Status  
- Solution (truncated for readability)  

Includes severity filtering and duplicate cleanup.

---

### 📈 Visualizations
- Severity Pie Chart  
- Top 5 Hosts by Critical Vulnerabilities  
- Aging Buckets (0–30, 31–60, 61–90, 90+ days)  

---

### 📤 Export & Portability
- Download cleaned/normalized CSV  
- Native Windows executable  
- Fully offline operation  
- No external data transmission  

---


## Use Cases
- Vulnerability management operations  
- SLA compliance validation  
- SOC triage support  
- Audit preparation  
- Pre-SIEM data normalization  

## Installation

### Running the Executable (Windows)

1. Download `NessusVulnReport.zip` from the [Releases](https://github.com/aeonstwilight/nessus-vuln-report/releases) page.  
2. Extract the folder anywhere.  
3. Run `app.exe` from the extracted folder.



## Usage

###

Upload your Nessus CSV file.

Click Analyze to see metrics and risk score.

Use the buttons to view Severity Pie Chart, Top 5 Hosts, and Aging Buckets.

Click Download Cleaned CSV to save the processed report.
