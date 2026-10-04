# Z BIM Viewer

Windows portable BIM viewing, coordination and quantity reports.

**[Download the portable viewer](https://github.com/Kwaybadu/z-bim-viewer-downloads/releases)**

This repository contains public download instructions and release notes. Application development source is maintained separately. A valid device license is required to use the viewer; downloading the ZIP does not grant activation.

## Install

1. Open **Releases** above and download `Z-BIM-Viewer-0.4.1-Windows-x64-Portable.zip` and its `.sha256` checksum.
2. Extract the complete ZIP into a writable folder. Keep all files and the ThirdParty folder together.
3. Run **Start Z BIM Viewer.cmd**. Keep its console open while using the viewer.
4. Your browser opens the local viewer. On a new PC, request a device license from the person supplying the software, then import the supplied `.zlicense` file.
5. Choose **Select project** to open your project folder, or **New project** to create one.

Choose the named **Windows-x64-Portable.zip** asset. GitHub's automatic **Source code** archives contain only this download repository's documentation and are not the application.

## What it includes

- Coordinated IFC/prepared-NWC viewing, properties, sections, measurements and visibility tools.
- Saved comments and annotations, aligned floor PDFs and split views.
- Tile quantities, tile layouts and Excel reports.
- Construction-joint areas, casting stages and concrete-volume schedules.

The current release is a **preview** for testing. Quantities with review warnings need checking before use. Large-model speed and detail depend on the PC and model geometry.

## Requirements

- Windows 10/11 x64 and a current Edge or Chrome browser with WebGL2.
- Node.js, pnpm and Codex are not required for the portable copy.
- New NWC conversion requires a separately installed, licensed **Navisworks Manage 2024**. Autodesk software is not included.
- Already prepared projects and standard IFC imports do not require Autodesk software. Some IFC files need optional preparation on an equipped workstation.
- This is a local application. Hosted accounts, assignment emails and synchronized multiuser editing are not enabled.

## Update

Save and close the old viewer. Extract the new release into a new application folder and select your existing project folder. Keep a project backup and the old application until you have checked the update. Compatible releases reuse a valid device license on the same Windows user/PC.

Project data is separate from this download. Keep the whole project folder, including its hidden `.z-bim` and `.model-cache` folders, together.

## Verify the ZIP

In PowerShell, compare this result with the downloaded `.sha256` file:

```powershell
Get-FileHash -Algorithm SHA256 '.\Z-BIM-Viewer-0.4.1-Windows-x64-Portable.zip'
```

The executable is not yet Authenticode-signed. A checksum verifies the downloaded bytes; it is not a publisher signature. Do not disable antivirus to install it.

## License and support

Contact the person supplying the viewer for activation or renewal. Do not post license requests, license files or project data in public issues. Public downloads do not make the application source open source. Bundled third-party components retain their own licenses and notices in the complete ZIP.

Report reproducible software bugs through Issues without including confidential project information. Include the app version, Windows version, steps and the error text.
