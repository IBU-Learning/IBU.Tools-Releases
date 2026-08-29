# IBU.Tools User Guide

## Preview status

IBU.Tools v0.9.0 Preview is undergoing validation and is not yet available for download. When published, it will provide no-cost Preview access through **30 November 2026 (UTC)**. Use copied models for evaluation and independently verify changes, exports, and output before using results in production.

The supported hosts are Revit 2024, Revit 2025, Revit 2026.5 or later, and Revit 2027. Revit 2026 versions earlier than 2026.5 are not supported.

## Install

These steps apply after the installer is published on the [Releases page](https://github.com/IBU-Learning/IBU.Tools-Releases/releases).

1. Close all supported Revit versions.
2. Download the installer from this repository's Releases page. The Preview download is not yet available.
3. Verify the published filename and SHA-256 checksum before running it.
4. Run the installer with administrator approval.
5. Select one or more detected supported Revit versions. Revit 2026 must be version 2026.5 or later.
6. Start Revit and open the **IBU Tools** ribbon tab.

The installer deploys the add-in for the selected Revit versions. It does not install or update Revit.

## Upgrade

1. Close Revit.
2. Download and verify the newer installer when one is published.
3. Run it and review the selected Revit components; previous selections may be restored.
4. Complete setup, then start each selected Revit version and verify the IBU Tools ribbon.

Do not distribute or reuse an older validation installer after a replacement is published.

## Uninstall or change installed versions

- To change Revit components, rerun the current installer and select the versions that should remain installed.
- To remove IBU.Tools, use Windows **Installed apps** / **Apps & features**, select IBU.Tools, and choose **Uninstall**.
- Close Revit before changing or removing the add-in.
- Afterward, start each affected Revit version and confirm the IBU Tools ribbon is present or absent as intended.

## Getting started

Open the **IBU Tools** ribbon tab. **About** is the only action in the General panel. About shows the installed version, Preview status, and user-initiated links to this guide and the Releases page. The Help action in the About header opens this guide.

The add-in performs no automatic network requests. Help, Documentation, and Update open GitHub only after you click them. See [Privacy](PRIVACY.md).

## Module workflows

### Schedule Export

Open a model containing the schedule, choose **Export Schedule**, select the supported schedule and options, and review the destination and generated workbook.

### Schedule Import

Work from a copied model, choose **Import Schedule**, select the supported workbook, review its preview and validation messages, then verify affected data after applying.

### Print Center

Choose **Print Center**, select and review sheets and output settings, confirm the destination, run the output, and inspect the result.

### Sheet Manager

Choose **Sheet Manager**, search or filter the available sheets, apply supported edits deliberately, and verify affected sheets, title blocks, and parameters.

### Parameter Manager

Choose **Parameter Manager** and use the Explorer, Shared Parameters, Standards, and Review/Preview & Apply stages as applicable. Review scope, binding, categories, values, and warnings before applying to a copied model.

### Health Check

Choose **Health Check**, run the supported checks, review findings in context, and optionally export a local report. Validate findings before modifying the model.

## Troubleshooting

- **Ribbon is missing:** confirm the selected Revit version is supported, restart Revit, and rerun the installer to verify that component is selected.
- **Revit 2026 is rejected:** update Revit to 2026.5 or later. The installer does not update Revit.
- **Help or Update does not open:** confirm you initiated the action and that Windows can open HTTPS links. IBU.Tools does not make a background request.
- **A workflow is unavailable after 30 November 2026 UTC:** the Preview period has ended. About, Help, Documentation, and Update remain available.
- **Unexpected result:** stop, preserve a copy of the model, capture reproducible steps, and report a sanitized issue.

For assistance, follow the safe reporting instructions in [Support](SUPPORT.md).

## PDF guide status

A checked PDF User Guide remains a final-release deliverable. It is not yet complete; this Markdown guide is the current public reference.
