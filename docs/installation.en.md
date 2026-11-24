# Install Organization AI

Open the [published releases](https://github.com/NeoliaTeams/organization-ia-downloads/releases). Download your platform’s package and `SHA256SUMS.txt` from the same release. Compare the output to the checksum beside the exact filename. If they differ, leave the file unopened and contact [support](https://getneolia.com/support/contact/?app=organization-ia&need=technical).

## macOS on Apple silicon

1. Verify the DMG in Terminal with `shasum -a 256 "Organisation-AI-0.5.20-macos-arm64.dmg"`.
2. Open the DMG, drag the app to **Applications**, then launch it from that folder.
3. The 0.5.20 DMG is signed and notarized. If macOS blocks it, send the warning text to support. If the app displays a startup error, use the log link provided in the dialog.

## Windows x64

1. Verify the ZIP in PowerShell with `Get-FileHash ".\Organisation-AI-0.5.20-windows-x64.zip" -Algorithm SHA256`.
2. In File Explorer, select **Extract All**. Open `Organization IA.exe` from the extracted folder. Keep the supplied files alongside it.
3. The 0.5.20 executable ships without an Authenticode signature. SmartScreen may display **Unknown publisher**. See the [GetNeolia Windows download guide](https://getneolia.com/apps/organization-ia/docs/en/telechargements.html) for installation alerts. For an antivirus warning or an organization policy block, contact support or your administrator.

You can also use the [web app](https://organisation-ai.getneolia.com/) without installation.
