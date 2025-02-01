# Installation and Usage

## Overview
This repository provides an `install.ps1` script to automate the installation of Windows Store packages and other software. It uses the PowerShell command line and requires package names from either the [Microsoft Store](https://www.microsoft.com/en-us/store/apps) or [winstall.app](https://winstall.app).

## Prerequisites
- Windows 10 or later
- PowerShell
- Administrative privileges (if required by certain packages)

## How to Use
1. Clone or download this repository.  
2. Open PowerShell in the repository's folder.  
3. Run the script:  
    ```powershell
    ./install.ps1
    ```
4. Follow any on-screen prompts or enter package names as necessary.  

## Finding Package Names
### Using the Microsoft Store
1. Browse the [Microsoft Store website](https://www.microsoft.com/en-us/store/apps).  
2. Search for the desired app.  
3. Copy the package identifier (often found in the URL or product page). eg `9nbdxk71nk08` for whatsapp in the URL `https://apps.microsoft.com/detail/9nbdxk71nk08?hl=en-US&gl=US`. 

### Using winstall.app
1. Go to [winstall.app](https://winstall.app).  
2. Search for the application.  
3. Copy the package name or ID listed on the app details page.  

## Notes
- Ensure your script is updated to include new apps as needed.  
- Package names may vary: always double-check spelling and spacing to avoid installation failures.  

For more in-depth usage or troubleshooting, consult PowerShell documentation or official sources for each application.