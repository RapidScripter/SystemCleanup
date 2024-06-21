# SystemCleanup PowerShell Script

## Overview
The `System-Cleanup.ps1` script automates the process of cleaning up the C: drive on Windows machines with low disk space. It removes temporary files, Windows SoftwareDistribution folder contents, user temp files, IIS logs (if applicable), and empties the recycling bin. The script logs all deleted files in a transcript located in the `$env:TEMP` directory.

## Features
- Cleans Windows temporary files
- Cleans Windows SoftwareDistribution folder
- Cleans user temporary files
- Cleans IIS logs (if applicable)
- Empties the recycling bin
- Logs all deletions in a transcript file

## Requirements
- PowerShell v3 or higher
- Administrative privileges

## Usage
1. **Download the Script**
   Save the script to your hard drive with a `.ps1` extension, for example, `System-Cleanup.ps1`.

2. **Run the Script**
   Open an elevated PowerShell prompt (Run as Administrator) and execute the script:
   ```powershell
   PS C:\> .\System-Cleanup.ps1
