# Ticket #003: Software installation issue 

## Ticket Information

| Field               | Details                              |
| ------------------- | -------------------------------------|
| Ticket ID           | INC-003                              |
| Date                | 2026-09-04                           |
| Priority            | Medium                               |
| Category            | Software                             |
| Status              | Open                                 |
| User                | Sarah Williams                       |
| Device              | Windows 11 Workstation               |
| Assigned Technician | IT Support                           |
| Issue               | Unable to install required software  |
 
## Initial Investigation

- The user attempted to install 7-Zip.
- User reported the installation started as normal then abruptly stops.
- A popup with an error message saying "Installation failed. Unable to write to the installation directory".
- This is the user's first time installing this software.
- Confirmed other applications are installing as normal.
- Confirmed the user has an internet connection and is able to browse websites and work related systems as normal.
- The user is using Windows 11 pro, version 24H2.

## Troubleshooting

### Step 1: Run the installer as administrator
- Right clicked 7-Zip installer.
- Selected "run as administrator.
- Attempted download again.
- **Result**: installation completed successfully.

## Root Cause
The installation failed because the installer did not have the permissions to write to the installation directory.

Running the installer as administrator gave it the required permissions to complete the installation.

## Verification
- Opened 7-Zip. 
- Confirmed the application launched without errors.
- Tested zip file extraction.
- Confirmed zip files can be extracted successfully
- **Result**: Software fully works as intended.

## Resolution
The user was unable to install 7-Zip because the installer did not have the sufficient permissions to write to the installer directory.

The 7-Zip installer was then used with "run as administrator privileges, allowing the installer to write to the installer directory and complete the installation successfully.

The 7-Zip application was then tested and confirmed to be working correctly without errors.

## Ticket Status
**Solved**
