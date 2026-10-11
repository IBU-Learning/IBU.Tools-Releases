# IBU.Tools Release Notes

## v0.9.1 Preview — 11 October 2026

[Download v0.9.1 Preview](https://github.com/IBU-Learning/IBU.Tools-Releases/releases/tag/v0.9.1)

Installer: `IBU.Tools-v0.9.1-Setup.exe`

SHA-256: `4DE8E343E9E4128D528F8DFADE6641E1E70F2B3D9BEA13AC04E989A5697F9B2D`

### What's included

- Per-user installation for Revit 2024, 2025, 2026.5+ and 2027. Normal installation does not require administrator permission.
- Print Center export and result-message refinements, individual Health Cleanup selection, Parameter Manager duplicate-parameter review, and the restored single-parameter Excel Import with an optional Equals filter.
- Free offline Preview access through 30 November 2026 UTC. No account or licence key is required. Tool access ends at `2026-12-01T00:00:00Z`; About, Preview Details, Help, Documentation and Update remain available.

### Moving from machine-wide v0.9.0

Close Revit and have an administrator or IT uninstall the machine-wide v0.9.0 edition before installing v0.9.1 in the intended Windows account. The new installer refuses mixed installations and does not perform a seamless migration. Back up personal settings first. Check for one IBU.Tools ribbon and verify settings after installation. See the [getting-started guide](USER_GUIDE.md#upgrade-or-change-installed-versions).

### Access conditions and limitations

- The exact v0.9.1 package has not received live Revit acceptance. Earlier per-user installer candidates passed owner-observed Revit 2027 loading and tool-opening checks.
- Same-user upgrade, downgrade refusal, controlled failed-upgrade rollback and settings preservation were not fully tested.
- Windows SmartScreen and Revit unsigned-publisher warnings may appear. Current modal tool windows are expected and accepted.
- Excel multi-parameter import remains deferred. Evaluate with copied models and verify changes and exports before relying on results in production.

The [v0.9.0 Preview](https://github.com/IBU-Learning/IBU.Tools-Releases/releases/tag/v0.9.0) remains available separately.

## v0.9.0 Preview — 30 August 2026

[Download v0.9.0 Preview](https://github.com/IBU-Learning/IBU.Tools-Releases/releases/tag/v0.9.0)

Installer: `IBU.Tools-v0.9.0-Setup.exe`

SHA-256: `5455E1E802280E7B7E16CCF80C2DE62242EF25D4DBCB7C151F22A4E369889DE0`

### Included tools

Excel Export / Import, Print Center with Naming Profile Builder, Sheet Manager, Parameter Manager and Health Check. See the [overview](../README.md#supported-revit-versions) for supported Revit versions.

### Access conditions and limitations

- Preview access is time-limited. Check **About > Preview Details** for the installed build's validity; reminders appear near expiry.
- When access ends, tool operations become unavailable. About, Help, Documentation and Update remain accessible. An extension or replacement build is not guaranteed.
- Use copied models for evaluation and verify changes and exported files before relying on them in production. Health Check findings support review; they do not certify model correctness.
- Update opens the Releases page when clicked; it does not automatically download or install software.
- Pristine-machine validation, runtime network tracing and live expiry UX testing remain unverified.

[Getting started](USER_GUIDE.md) · [Downloads](https://github.com/IBU-Learning/IBU.Tools-Releases/releases) · [Support](SUPPORT.md)
