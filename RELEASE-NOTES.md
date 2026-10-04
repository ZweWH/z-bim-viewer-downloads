# Z BIM Viewer 0.4.1 — Windows portable preview

Released 4 October 2026.

Download **Z-BIM-Viewer-0.4.1-Windows-x64-Portable.zip**, extract the entire ZIP and run **Start Z BIM Viewer.cmd**. A valid device license is required. GitHub's automatic Source code archives contain only this download repository's documentation, not the application.

## Changes

- Remove CJ directly from the concrete schedule, including its casting stages, saved calculations and outline on the 2D plan.
- A confirmation lets you cancel. Undo or Ctrl+Z restores the removed CJ during the current session, including its saved result. Other CJs remain unchanged.
- Includes the existing 0.4.0 viewing, drawing, comments, tile and concrete tools.

## Updating from 0.4.0

Save and close the old viewer. Extract this ZIP into a new application folder and select the existing complete project folder. Valid device licenses remain compatible on the same PC/Windows user. Keep your project backup and previous app until the update is checked.

## Validation and limits

- 1,147 automated tests and the frontend build passed.
- 26 isolated portable checks passed, covering activation, restart, local API protection, synthetic IFC preparation and cache reuse.
- The packaged CJ removal/cancel/undo workflow was checked with a synthetic model and plan.
- 338 package files were audited and verified against the ZIP; third-party notices and required source bundles are retained.
- This is a preview: no physical second-PC or new raw-NWC conversion test was performed for this release. The executable is not Authenticode-signed.
- Windows 10/11 x64 with current Edge or Chrome is required. New NWC conversion additionally needs separately installed, licensed Navisworks Manage 2024. Prepared projects and standard IFC imports do not require it.
- Quantity review warnings still require checking. Hosted collaboration, email notifications and automatic software updates are not enabled.

## SHA-256

`960a8331e126e93d9fc3145446f07b2a2a6ec1287ccc02c387373544e6ac1461`

This checksum applies to `Z-BIM-Viewer-0.4.1-Windows-x64-Portable.zip`.
