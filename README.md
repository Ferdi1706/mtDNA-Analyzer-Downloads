# MitoConcord — Windows downloads

**Version 0.13.3:** Definite effective conflicts from segments without open indel boundaries can establish incompatibility even when another segment has an unresolved boundary. The interface reports the guaranteed lower bound and marks unresolved indel alignments explicitly. Original variant notation remains accessible, and evaluable regions follow circular control-region order. CSV and Excel distinguish diagnostic totals from the guaranteed lower bound. Reconstruction and edit distance remain string-v1; the revised assessment rule is string-boundary-decision-v2. Confirmed string projects saved by this version require reader 0.13.3. Technical regression and native Windows checks passed; independent scientific validation remains pending.

**Version 0.13.1:** New projects select string-based single-profile comparison. Confirm complete rCRS difference lists within coverage once in project settings; the saved confirmation is reused for mixture checks and directed graph relationships. Existing projects retain their saved method. Includes compact sequence alignment, reconstructed-sequence/FASTA export, mixtures shown by default with a single option to exclude them, and high-contrast graph cursors. String projects require a current MitoConcord version. Technical regression has passed; independent scientific validation of the new string method remains pending.

Previously named **mtDNA Analyzer**.

[Download MitoConcord for Windows](https://github.com/Ferdi1706/mtDNA-Analyzer-Downloads/releases/latest/download/MitoConcord.exe)

MitoConcord provides local mtDNA profile comparison, compatibility networks, control-region views and qualitative mixture screening.

All views remain visible without a license. Three bundled synthetic demo projects can be analysed to explore the application. You can also select your own Sequencher reports or GeneMarkerHTS result files and inspect recognition metadata: the original PDF, detected sample names, variant counts and coverage. Extracted variant lists, diagnostic call details and source-text access for your own reports require a license and are withheld by the API when unlicensed. Adding profiles to a project, analysing your own data, editing settings and exporting results require a valid device-bound license. Project and sequence data are processed locally.

The application checks for new versions in the background at startup and on request in **License & updates**. Available updates include release notes loaded from the signed GitHub manifest. Installation requires confirmation. The previous EXE is retained for rollback; the application restarts automatically and confirms successful installation. Latest-version status is shown only after a verified release check.

Updating an existing installation changes the visible name and application icon to MitoConcord. Existing projects, saved activations, preferences and recent-project lists remain available. The updater keeps the executable at its existing path, so its filename may remain `mtDNA_Analyzer_Desktop.exe`. New downloads use `MitoConcord.exe`.

This repository distributes application binaries and signed update metadata. It contains no laboratory projects, genetic data, application source repository, license keys or private signing keys. GitHub's automatically generated source archives contain this download repository's documentation, not the application source.

Release assets: `MitoConcord.exe`, the identical compatibility asset `mtDNA_Analyzer_Desktop.exe`, `update.json` and `update.json.sig`. The signed manifest continues to reference the compatibility asset so previous versions can update. The application verifies the Ed25519 signature and executable SHA-256 before installation. Save active work before updating.

Licensing is handled separately through Keygen, including periodic checks and time-limited signed offline access. This update process does not create Keygen release objects.

For automatic replacement, run the portable EXE from a short local folder that you can write to. Very long Windows paths can prevent creation of the rollback filename.
