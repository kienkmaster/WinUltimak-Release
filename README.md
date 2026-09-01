# WinUltimak Releases

Public binary releases for WinUltimak, a Windows x64 desktop utility collection.

The source code is maintained separately in a private repository. Release packages in this repository are distributed under the [MIT License](LICENSE).

## Download

Download the latest ZIP and its matching `.sha256` file from [GitHub Releases](https://github.com/kienkmaster/WinUltimak-Release/releases/latest).

Each ZIP contains:

- `WinUltimak.exe`
- `LICENSE`

The `Releases/v<version>` folders mirror the verified assets attached to GitHub Releases. Use the GitHub Releases page for normal downloads.

## Verify SHA-256

Run the following command in PowerShell from the directory containing the downloaded ZIP:

```powershell
$zip = Get-ChildItem -LiteralPath . -Filter 'WinUltimak_v*.zip' | Select-Object -First 1
Get-FileHash -Algorithm SHA256 -LiteralPath $zip.FullName
```

Compare the displayed hash with the value in the matching `.zip.sha256` file.

## Trademark notice

WinUltimak is an independent project and is not affiliated with, authorized, sponsored, or endorsed by Microsoft Corporation. Microsoft and Windows are trademarks of the Microsoft group of companies. All other trademarks are the property of their respective owners.
