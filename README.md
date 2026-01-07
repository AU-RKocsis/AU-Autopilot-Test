# Aunalytics Autopilot Registration Script

This repository contains the automated Autopilot device registration script for Aunalytics.

## Script: AU-Autopilot.ps1

Installs required modules and launches the AutopilotOOBE module with pre-configured parameters for Aunalytics device enrollment.

### Features
- Bypasses WAM (Web Account Manager) using Device Code authentication
- Pre-configured for Aunalytics tenant and security groups
- Supports Enterprise, Kiosk, and Shared device enrollment
- Automated naming convention (WAU####)

### Usage

Quick launch via URL:
```powershell
irm https://tinyurl.com/AU-Autopilot | iex
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
