# Ticket #005: Computer Running Extremely Slow

## Ticket Information

| Field               | Details                              |
| ------------------- | -------------------------------------|
| Ticket ID           | INC-005                              |
| Date                | 2026-09-09                           |
| Priority            | Medium                               |
| Category            | Hardware / Performance               |
| Status              | Resolved                             |
| User                | Kevin Zhang                          |
| Device              | Windows 11 Workstation               |
| Assigned Technician | IT Support                           |
| Issue               | Computer running slow                |

## Issue Description

The user reported that their computer started to run extremely slowly over the last few days.

Applications would take 5 minutes or more to open and the computer would occasionally freeze.

The Issue was affecting the user from completing work.

## Initial Troubleshooting

The user had already attempted the following to resolve the issue:

- Restarted the computer
- Closed any extra programs

These action did not resolve the issue.

## Troubleshooting Performed

**1.** Checked for malware and security threats
Ran Windows Defender scanner to check whether malware or other security threats could be contributing to the system's poor performance.

**Result**: Windows defender found 1 threat on the device and deleted it.

**2.** Freed disk space
Used the built-in Windows Disk Cleanup to remove unnecessary temporary files and other files that were consuming storage space.

**Result**: Additional disk space was recovered.

**3.** Checked for system updates
Checked Windows update settings for any available system updates and installed all updates that were listed. 

**4.** Restarted the computer
Performed a fresh restart after completing the maintenance tasks to ensure system updates and changes were properly applied.

## Resolution

The computer was restarted after the troubleshooting and maintenance steps.

## Root cause
**Contributing factors**:
- Insufficient available disk space
- Virus/threat found by windows defender
- Outdated software

## Technical Notes

The issue was addressed using standard endpoint troubleshooting procedures:
- Security scan
- Disk cleanup
- System updates
- System restart

If the issue returns, additional troubleshooting should be performed, including checking Task Manager for high CPU/RAM/disk utilization, reviewing startup applications, checking disk health, and examining Windows Event Viewer for recurring errors.

## Skills Demonstrated\

- Windows endpoint troubleshooting
- Malware/security scanning
- Disk cleanup and storage management
- Windows Update management
- Basic system performance troubleshooting
- Incident documentation
- User impact assessment
- Root cause analysis
- Troubleshooting escalation procedures
