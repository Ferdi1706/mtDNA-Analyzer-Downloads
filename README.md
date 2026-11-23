# mtDNA Analyzer — application updates

This repository is reserved for signed Windows application releases. It contains no laboratory projects, genetic data, application source code or licensing secrets.

The repository is private during setup. No public production release is available yet.

Releases will contain `mtDNA_Analyzer_Desktop.exe`, `update.json`, and `update.json.sig`. The application verifies the Ed25519 manifest signature and executable SHA-256 before installing an update. A valid device-bound license is required for analysis. Analysis data are processed locally.

Licensing is handled separately through Keygen; no Keygen release objects are created by this update process.
