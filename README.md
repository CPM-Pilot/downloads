# CPMPilot downloads

CPMPilot is CPM scheduling software for construction project controls teams, made by PROMAC Consulting (Project Management and Controls Consulting LLC). This repository holds the official Windows installers; the application's source code is not published.

Website: https://cpmpilot.com

## Download

The newest release is always available at:

https://github.com/CPM-Pilot/downloads/releases/latest/download/CPMPilot-Setup.exe

Earlier versions are listed under Releases, each with its release notes and the SHA-256 checksum of its installer. A free 30-day trial starts from the installer; see https://cpmpilot.com/free-trial/ for the sign-up and the system requirements.

## Verify the download

Every installer is code-signed by Project Management and Controls Consulting LLC with Microsoft Artifact Signing and timestamped. Before running it:

1. Right-click the downloaded file, choose Properties, then Digital Signatures. The signer must read "Project Management and Controls Consulting LLC".
2. Optionally compare the file's SHA-256 with the value in the release notes. In PowerShell: `Get-FileHash .\CPMPilot-Setup.exe -Algorithm SHA256`

If Windows SmartScreen shows "Windows protected your PC" on a brand-new release, that is reputation lag for a freshly signed file: click More info, check that the publisher is Project Management and Controls Consulting LLC, then Run anyway.

## Support

info@cpmpilot.com
