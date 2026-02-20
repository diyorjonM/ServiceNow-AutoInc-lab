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
    
    <img width="1363" height="724" alt="Screenshot 2026-02-19 at 10 35 49 PM" src="https://github.com/user-attachments/assets/9d5e5a51-ffca-4dc0-b559-d9ef9ba5aece" />

  - Open File Explorer, go to C: drive and create a Scripts folder.

    <img width="773" height="724" alt="Screenshot 2026-02-19 at 10 02 18 PM" src="https://github.com/user-attachments/assets/55678e49-2062-4f37-b56e-7f72ff772721" />

    <img width="1125" height="591" alt="Screenshot 2026-02-19 at 10 02 33 PM" src="https://github.com/user-attachments/assets/3f435e8d-a057-413d-99cf-03bf9639158e" />

    <img width="1123" height="592" alt="Screenshot 2026-02-19 at 10 02 43 PM" src="https://github.com/user-attachments/assets/60004423-3ec8-4a29-84f3-ed8bccd62fdf" />

  - Select New > Text Document to create a .txt file.
  - Paste the script into the .txt file, select save as and add the ".ps1" extension to save as a PowerShell file.

    <img width="707" height="473" alt="Screenshot 2026-02-19 at 10 42 05 PM" src="https://github.com/user-attachments/assets/235c9751-eabc-4c75-ab4d-5f326b50c720" />

### 2. Run Script

  - Open PowerShell as Administrator.

    <img width="772" height="723" alt="Screenshot 2026-02-19 at 10 07 29 PM" src="https://github.com/user-attachments/assets/5bd33f6e-f8c2-4c3a-a04a-ccb14b42acbc" />

  - Paste the Script and execute it.

    <img width="1113" height="625" alt="Screenshot 2026-02-19 at 10 43 32 PM" src="https://github.com/user-attachments/assets/a0c2a686-bb34-4d9a-9218-5f8523b41747" />

  - Verify that the script ran successfully.
  
    <img width="1111" height="699" alt="Screenshot 2026-02-19 at 10 44 19 PM" src="https://github.com/user-attachments/assets/de1cfdec-fc67-4f4c-98a5-427b4103b003" />

  - Navigate back to Service Now and select start building.

    <img width="274" height="147" alt="Screenshot 2026-02-19 at 10 37 50 PM" src="https://github.com/user-attachments/assets/9d7f1436-524b-44eb-b6e7-0f224e4d56dd" />

  - Select All, scroll down and select Incidents.

    <img width="520" height="582" alt="Screenshot 2026-02-19 at 10 38 17 PM" src="https://github.com/user-attachments/assets/d2c9e300-1f56-4998-bac8-0ba52894be43" />

  - Verify that the incident has been created.

    <img width="1365" height="724" alt="Screenshot 2026-02-19 at 10 47 53 PM" src="https://github.com/user-attachments/assets/c9184051-d315-431b-97db-99f5ab98aae7" />

## Outcome

Successfully automated the creation of an incident on Service Now using PowerShell.
