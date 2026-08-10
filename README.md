# Engineering Surface – CATIA V5 Automation Toolkit

A Windows desktop application for inspecting and managing CATIA V5 assemblies, editing component metadata, generating bills of materials, and creating structured drawing sheets.

> This is an independent engineering utility and is not affiliated with or endorsed by Dassault Systèmes. CATIA is a trademark of Dassault Systèmes.

## Features

- Connects to the active CATIA V5 session and CATProduct
- Displays the complete CATIA product structure
- Shows CATPart and CATProduct thumbnails
- Searches and filters BOM items
- Edits part number, nomenclature, description, revision, and material
- Shows or hides selected components in CATIA
- Duplicates assembly components
- Exports a professional Microsoft Excel BOM
  - Optional component thumbnails
  - Grouped quantities and totals
  - Assembly summary worksheet
  - Material summary
  - Missing-property quality checks
  - CATPart/CATProduct color coding
- Retains CSV export support
- Creates CATDrawing sheets with an engineering frame, title block, and assembly parts list
- Includes integrated support and contact links

## Requirements

- Windows 10 or Windows 11
- CATIA V5 with an active automation session
- Microsoft Excel for `.xlsx` export
- A 64-bit build is recommended when using 64-bit CATIA

## Installation

1. Download the latest release from the **Releases** page.
2. Extract the complete ZIP package; do not copy only the executable if the release contains supporting files.
3. Start CATIA V5 and open a CATProduct.
4. Run `EngineeringSurface.CATIAV5Toolkit.exe`.
5. If Windows displays a SmartScreen warning for an unsigned build, verify the release checksum before continuing.

## Basic usage

1. Start CATIA and open the assembly you want to inspect.
2. Launch the Engineering Surface toolkit.
3. Press **F5** or use the Refresh icon to reload the active CATIA structure.
4. Select components from the tree or BOM grid.
5. Use the toolbar commands to show, hide, duplicate, save, or export.
6. Use the spreadsheet icon to create the professional Excel BOM.


## Known limitations

- Windows only
- CATIA-specific commands require CATIA V5 to be running
- Excel export requires a locally installed Microsoft Excel application
- Access to component properties can depend on CATIA cache/design mode and document permissions
- Drawing generation can vary according to the CATIA drafting standard and printer configuration

## Privacy and engineering data

The application works with the active local CATIA session. Do not publish customer CATPart, CATProduct, CATDrawing, Excel BOM, or proprietary screenshots in this repository.

## Support

For a specific project or custom request:

- Email: [ennadisto@gmail.com](mailto:ennadisto@gmail.com)
- YouTube: [Engineering Surface](https://www.youtube.com/@Eng.Surface)

The application is free to use. Custom support and additional development requests may be paid services, with pricing based on complexity.


