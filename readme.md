# Creating New Incident on Service Now w/ PowerShell Script

## Project Overview

This lab documents the use of a PowerShell script to automate the creation of an incident on Service Now.

The purpose of this project was to:

- Create a PowerShell Script.
- Create a incident ticket on Service Now with a script.

## Environment Details

| Component              | Configuration                         |
|------------------------|---------------------------------------|
| Cloud Provider         | AWS                                   |
| Compute Service        | Amazon EC2                            |
| Operating System       | Windows Server Base 2025              |
| Ticketing Service      | Service Now Developer                 |
| Terminal               | PowerShell                            |

## Steps

### 1. Create PowerShell Script

- Navigate to the developer instance of Service Now.
- Copy API, username, and password.
- Open File Explorer, go to C: drive and create a Scripts folder.
- Select New > Text Document to create a .txt file.
- Paste the script into the .txt file, select save as and add the ".ps1" extension to save as a PowerShell file.

### 2. Run Script

- Open PowerShell as Administrator.
- Paste the Script and run it.
- Verify that the user has been added in the Active Directory Users and Computers app.

## Outcome

Successfully automated the creation of an incident on Service Now using PowerShell.