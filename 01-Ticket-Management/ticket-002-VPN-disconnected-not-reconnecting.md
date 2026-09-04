# Ticket #002: Network/ Remote Issues

## Ticket Information

| Field               | Details                              |
| ------------------- | -------------------------------------|
| Ticket ID           | INC-002                              |
| Date                | 2026-09-03                           |
| Priority            | High                                 |
| Category            | Network / Remote Access              |
| Status              | Resolved                             |
| User                | Jevaun Bynoe                         |
| Assigned Technician | IT Support                           |
| Issue               | VPN disconnected and won't reconnect |

## Problem Description

The user reported that the VPN disconnected and won't reconnect.

## Troubleshooting Performed

1. Noted the user is working remotely.
2. verified the device had an active internet connection.
3. Opened the command terminal on the remote device.
4. Ran "ipconfig /flushdns" command to clear the local/DNS resolver cache.
5. Restarted the device to confirm changes.
6. after logging back in, opened the VPN client.
7. Attempted to reconnect to VPN client
8. Verified that the VPN client was successfully connected.
9. confirmed the user could access network resources.
   

## Root Cause

A local network/DNS resolution issue was suspected to have contributed to the VPN connection failure. Clearing the DNS cache and restarting the device resolved the connectivity issue.

## Resolution

The local DNS cache was cleared and the device was restarted. The user was subsequently able to reconnect to the VPN and regain access to the required network resources.

## Final Status

**Resolved**

