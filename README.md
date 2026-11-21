# MYCYPHER releases

Installers for [MYCYPHER](https://mycypher.tech), the end-to-end encrypted team workspace. This repository holds no source code.

## Mac

macOS 12 or later, Apple silicon and Intel. Download **`Cypher-mac-universal.dmg`** from the
[latest release](https://github.com/easybandz777/cypher-releases/releases/latest), open it and drag MYCYPHER to Applications.

The app is signed with a Developer ID and notarized by Apple, so it opens without warnings. It does not update itself yet:
download new versions here. Versions before 1.1.7 were called Cypher: after installing MYCYPHER, delete the old `Cypher.app`
from Applications. Both use the same data on your Mac, so nothing is lost.

## Windows (test build)

Windows 10 or 11, 64-bit (Windows on Arm runs it through emulation). Download **`Cypher-Setup-x64.exe`** from the
[latest release](https://github.com/easybandz777/cypher-releases/releases/latest) and run it. It installs MYCYPHER for your
user account, without administrator rights, and adds desktop and Start menu shortcuts. It does not update itself yet.

The Windows installer is not signed yet, so Windows warns before it runs: if your browser says the file isn't commonly
downloaded, choose **Keep**; when Windows says "Windows protected your PC", click **More info**, then **Run anyway**.

## Checksums

Every release lists the SHA-256 checksum of its files in `SHA256SUMS.txt`. Compare it with `shasum -a 256 Cypher-mac-universal.dmg`
on a Mac, or `Get-FileHash .\Cypher-Setup-x64.exe` in PowerShell on Windows (PowerShell prints it in capital letters).

## Everywhere else

MYCYPHER also runs in the browser at [mycypher.tech](https://mycypher.tech).
