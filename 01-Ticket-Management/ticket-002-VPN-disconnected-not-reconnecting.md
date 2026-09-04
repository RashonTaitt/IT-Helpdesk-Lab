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
2. Opened the command terminal on the remote device.
3. Ran "ipconfig /flushdns" command to clear stale DNS entries.
4. Restarted the device to apply changes.
5. Once logged back in, attempted to reconnect to VPN client.
6. Verified that the VPN client was successfully connected.

## Root Cause

Stale DNS entries blocking access

## Resolution

The client was cleared of old entries and the user was able to reconnect after a system restart

## Final Status

**Resolved**

