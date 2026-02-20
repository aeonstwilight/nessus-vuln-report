# Nessus Vuln Report

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Nessus Vuln Report is a **lightweight desktop tool** for analyzing Nessus CSV vulnerability reports. It provides metrics, risk scoring, and visualizations for quick vulnerability triage — all in a **native desktop GUI** using PySimpleGUI.

---

## Features

🚀 Features
📊 Metrics Summary Dashboard

Total vulnerability count

Severity breakdown: Critical, High, Medium, Low

Exploitable findings count

CVSS ≥ 9 findings

Oldest vulnerability discovered

Automatically calculated Risk Score & Risk Rating

⏳ SLA & Remediation Tracking

Automatic remediation windows:

Critical / High → 30 days

Medium → 90 days

Low → 180 days

Calculates:

Age (Days)

Days Remaining

Expired Status

⚠️ Visual indicator for expired vulnerabilities

Filter to show Expired Only

🔍 Interactive Vulnerability Table

Displays:

Plugin ID

Plugin Name

Severity

Host

CVSS Score

Exploit Availability

Age (Days)

Days Remaining

Expired Status

Solution (truncated for readability)

Severity-based filtering

Designed to mimic SOC/Splunk-style review workflow

📈 Visualizations

Severity Pie Chart

Top 5 Hosts by Critical Vulnerabilities

Aging Buckets View

0–30 days

31–60 days

61–90 days

90+ days

🛡 Intelligent Data Handling

Automatically handles missing Nessus CSV columns

Normalizes inconsistent severity formatting

Cleans duplicate host/plugin combinations

Prevents crashes from unexpected report variations

📤 Export & Portability

Download cleaned/normalized CSV for:

Splunk ingestion

Reporting

Audit evidence

Further analysis

Native Windows executable

No Python required for end users

No browser required

💻 Native Desktop Application

Lightweight Windows executable

No installation required

Runs fully offline

No data leaves your machine

---

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
