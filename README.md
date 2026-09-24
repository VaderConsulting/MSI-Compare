# MSI Compare

VB6 MSI Compare (`MSI Compare.exe`, VBP title MSI Compare; UI caption "MSI Explorer"). Side-by-side Windows Installer browser for two `.msi`/`.msm` databases via `msi.dll`, with dual TreeViews of Files/Registry/Components, optional MST transform apply under `c:\temp\msi_compare_temp\`, and Load MSI 1 / MSI 2 menus.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`MSI Compare.vbp`) | VB6 | WinForms exe | Dual-pane MSI/MSM compare browser |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `MSI Compare.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`
  - `MSCOMCTL.OCX`
- Windows Installer Object Library (`msi.dll`)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/MSI Compare`.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
