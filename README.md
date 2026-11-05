# RedactPlus downloads

Official Windows installers for RedactPlus. This public repository hosts installer binaries and release metadata only; product source code is maintained separately.

- [Download the latest Windows installer](https://github.com/Safe-Redact/redactplus-downloads/releases/latest/download/RedactPlus-Setup.exe)
- [All versions and release notes](https://github.com/Safe-Redact/redactplus-downloads/releases)
- [Latest SHA-256 checksums](https://github.com/Safe-Redact/redactplus-downloads/releases/latest/download/SHA256SUMS.txt)
- [Latest release metadata](https://github.com/Safe-Redact/redactplus-downloads/releases/latest/download/release.json)

Each release keeps its original installer and source commit identity. Preview builds do not replace the stable download. Version 0.3.8 is the initial manual release; the new team release pipeline starts at 0.4.1.

After downloading, run the installer and sign in with your work account to activate your licence. The Lite installer downloads optional local processing components when needed. Windows may show a SmartScreen prompt because this build is not code-signed.

To check a downloaded installer in PowerShell:

```powershell
Get-FileHash .\RedactPlus-Setup.exe -Algorithm SHA256
```

Compare the result with the matching version's `SHA256SUMS.txt`.
