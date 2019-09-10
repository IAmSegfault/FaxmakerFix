# FaxmakerFix
 A permissions fix for shared folders that get faxes from GFI Faxmaker

---
How to use:
---

Edit fax_permissions.ps1 by changing J:\fax to your shared folder location.
Change everyone:F to a user or group that will access your shared drive, for instance faxuser:F

Run the script as a scheduled task once every few minutes to handle incoming faxes.