# Z BIM Viewer 0.4.2 — Windows portable preview

6 October 2026.

Download **Z-BIM-Viewer-0.4.2-Windows-x64-Portable.zip**, extract the complete ZIP and run **Start Z BIM Viewer.cmd**. A valid device license is required. GitHub's Source code archives contain only the public repository's documentation.

## Changes

- Shared concrete volume counts once within a casting stage: 10 + 5 with 1 shared totals 14 cubic metres.
- Object review lists unmeasurable items with 3D inspection, exclusion and restore. Recalculate after changing exclusions.
- Draw CJ outlines with rectangles or polylines and expand the plan workspace.
- Compact edge dimensions, arrow handles, hide-category and isolate controls improve CJ 3D editing.
- Bounded NWC seam repair reduces false open-geometry errors; genuinely incomplete solids still require review.
- Existing tile, drawing, comments and model-coordination tools remain available.

## Update

Save and close the old viewer. Extract this release into a new application folder, then select your existing complete project folder. Keep your backup and previous app. Valid licenses remain compatible on the same PC/Windows user.

**Recalculate previous concrete results after updating.** The new method deducts shared volume and retains calculation review checks. Different overlapping casting stages still need correction.

## Validation and limits

- 1,227 automated tests passed, zero failures or skips; production build passed.
- 389 focused concrete/CJ/licensing checks and 4 packaging-notice checks passed.
- 26 isolated portable runtime checks passed: activation gates, activation/restart, protected APIs, synthetic IFC preparation and cache reuse. These were agent-run on the development PC, not owner acceptance on another PC.
- Packaged-browser synthetic smoke: 14 cubic metre union, malformed-object review, restore/exclude/recalculate, cancelling a 3D height edit, expanded-plan rectangle creation and schedule removal. No captured browser warnings/errors in those workflows.
- 377 package files audited and checked byte-for-byte in the ZIP; third-party notices and required source bundles retained.
- Preview: second-PC acceptance and fresh raw-NWC conversion remain unverified. Executable is not Authenticode-signed. Existing licensing policy is unchanged.
- Final workbook rendering in desktop Excel was not rechecked for this release; workbook regressions pass in the source suite. The browser download automation timed out and did not verify the downloaded file.
- New NWC conversion needs a separately installed licensed Navisworks Manage 2024. Prepared projects and standard IFC imports do not require it.
- Hosted collaboration, email notifications and automatic updates are not enabled. No new large-project performance benchmark claim.

## SHA-256

4c761b89772ca321eb2913060e3da17d92e45ab0eebdac493649d5511fb63e87

Applies to Z-BIM-Viewer-0.4.2-Windows-x64-Portable.zip (60258178 bytes).
