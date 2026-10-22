## Impedance Table v0.1.0

First Windows build for generating impedance-table DXFs for Altium fabrication drawings.

### Included
- Board catalog indexed by PCB part number; reopen and edit saved tables.
- Single-ended and differential requirements with grouped layer names.
- Separate differential pair-gap and coplanar ground-clearance columns.
- Automatic dashes, mil/mm conversion, live preview, and DXF export.
- 10 mil table lines and nominal 45 mil text with 5 mil strokes.
- Light, Dark, and System themes; save backups and unsaved-change prompts.

### Install
Download **ImpedanceTable-Windows.zip**, extract it, and run **ImpedanceTable.exe**.
Requires Windows 10/11 with .NET Framework 4.8.
The ZIP contains the app, usage guide, and sample output. It does not contain the private development source.

### Validation and first-use check
The EXE compiled successfully; 14 core checks passed. The sample DXF passed an independent structural audit with no errors or repairs. Native Windows UI operation and Altium import still require hands-on verification.

Import DXFs at **1:1 in millimeters**, regardless of the units shown in the table cells.
Text is exported as stroke geometry. Edit your saved board in the app to revise it.
