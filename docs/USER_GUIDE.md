# IBU.Tools Help & Getting Started

For product availability, supported Revit versions and downloads, see the [overview](../README.md). Read the [access conditions and limitations](RELEASE_NOTES.md#access-conditions-and-limitations) before use.

## Install

To install the v0.9.1 Preview:

1. Close Revit. Download the installer from the [v0.9.1 Preview release](https://github.com/IBU-Learning/IBU.Tools-Releases/releases/tag/v0.9.1) and verify its published SHA-256 checksum.
2. Run setup in the Windows account that will use IBU.Tools and select the required supported Revit versions. A normal per-user installation does not require administrator permission.
3. Complete setup, start Revit and open the **IBU Tools** ribbon.

The installer does not install or update Revit. Revit 2026 requires update 2026.5 or later.

## Open Help

Choose **About** on the ribbon to check the installed version and product status. **Help** and **Documentation** open this page; **Update** opens Releases. These links open in your browser only when clicked.

## Upgrade or change installed versions

If you have a machine-wide v0.9.0 installation, close Revit and ask an administrator or IT to uninstall it before installing v0.9.1. The per-user installer will not remove or migrate the machine-wide edition. Do not run both editions together. Back up personal settings and confirm the old IBU.Tools add-in registration has been removed before proceeding; contact support if an unowned or duplicate registration remains.

For an existing per-user installation, close Revit before running a replacement installer. Verify the selected Revit versions, a single IBU.Tools ribbon and your settings afterward. Upgrade, downgrade refusal, failed-upgrade rollback and settings preservation have not been fully tested; keep a backup before changing installations.

## Uninstall

Close Revit. In Windows **Installed apps** / **Apps & features**, select **IBU.Tools > Uninstall**. Restart the affected Revit versions to confirm removal.

## Troubleshooting

- **Ribbon missing:** check compatibility and the installed Revit component, then restart Revit.
- **Apply unavailable:** review the validation message before proceeding.
- **Browser link not opening:** check internet access and the default browser.
- **Unexpected result:** stop, preserve a model copy and contact support with sanitised steps.

[Contact support](SUPPORT.md) · [Privacy](PRIVACY.md)
