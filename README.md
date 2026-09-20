# Siteinfo

VB6 DCD PC Info tool (`SiteInfo.exe`): picks a site code from ADO `tblSites`, reads WMI hardware (serial/manufacturer/model/memory/speed), upserts `tblPCInfo`, and writes a KiXtart-style template (`$SITENAME` / `$SERIALNUMBER`) for site naming. Open `Siteinfo.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Siteinfo.vbp`) | VB6 | WinForms exe | Capture PC info per site and emit naming template |
