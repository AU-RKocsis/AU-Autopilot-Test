# Aunalytics Autopilot Registration Script

This repository contains the automated Autopilot device registration script for Aunalytics.

## Script: AU-Autopilot.ps1

Installs required modules and launches the AutopilotOOBE module with pre-configured parameters for Aunalytics device enrollment.

### Features
- Bypasses WAM (Web Account Manager) via registry disable during authentication
- Interactive browser-based login (no device code needed)
- Pre-configured for Aunalytics security groups
- Supports Enterprise, Kiosk, and Shared device enrollment
- Automated naming convention (WAU####)
- Automatic WAM restoration after enrollment

### Usage

Quick launch via URL:
```powershell
irm https://raw.githubusercontent.com/AU-RKocsis/AU-Autopilot-Test/main/AU-Autopilot.ps1 | iex
```

Or run directly:
```powershell
.\AU-Autopilot.ps1
```

### Requirements
- PowerShell 5.1 or later
- Internet connection
- Admin privileges

### Author
Mark Newton (Updated by Robert Kocsis - 2025)
