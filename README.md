# soc-analyst-homelab-splunk
SOC Analyst Home Lab using Kali Linux, Metasploitable 2 and Splunk Enterprise
# SOC Analyst Home Lab using Kali Linux, Metasploitable 2 and Splunk

## Project Overview

This project demonstrates a SOC Analyst home lab built using Kali Linux, Metasploitable 2, and Splunk Enterprise.

The objective was to simulate attacks, collect logs, ingest them into Splunk, create dashboards, and configure alerts for security monitoring.

## Tools Used

* Kali Linux
* Metasploitable 2
* Splunk Enterprise
* VirtualBox
* Nmap
* SSH
* FTP

## Lab Architecture

Kali Linux (Attacker)

↓

Metasploitable 2 (Target)

↓

Log Collection

↓

Splunk Enterprise

↓

Dashboards & Alerts

## Network Configuration

Kali Linux: 192.168.56.101

Metasploitable 2: 192.168.56.102

## Activities Performed

### 1. Network Scanning

Performed Nmap scans from Kali Linux to discover open services on Metasploitable 2.

### 2. SSH Authentication

Generated successful SSH login events.

### 3. FTP Authentication Failures

Generated failed FTP login attempts to create security events.

### 4. Log Analysis

Analyzed:

* /var/log/auth.log
* /var/log/syslog
* /var/log/apache2/access.log

### 5. Splunk Log Ingestion

Uploaded logs into Splunk index:

portscan_lab

### 6. Dashboard Creation

Created security monitoring dashboards including:

* Events by Log Source
* Failed Login Attempts
* Attacker IP Activity
* Successful SSH Logins

### 7. Alert Configuration

Configured alerts for:

* Failed Login Detection
* Successful SSH Login Detection

## Skills Demonstrated

* SIEM Monitoring
* Log Analysis
* Security Event Investigation
* Splunk Dashboard Development
* Alert Creation
* Linux Administration
* Network Security Monitoring

## Screenshots

Screenshots are available in the screenshots folder.

## Author

Abinesh R
