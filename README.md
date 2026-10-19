# SQLTreeo Restore downloads

This repository only hosts the release files of **SQLTreeo Restore**, the tool by
[SQLTreeo](https://www.sqltreeo.com/sqlrestore) that opens SQL Server backup files (.bak) without a SQL Server,
shows what is inside and restores only the tables you need: exported to CSV or copied into a SQL Server database.
The installed application reads the releases here to offer automatic updates.

- **Download:** the `SqlRestore-win-Setup.exe` asset of the [latest release](../../releases/latest)
  (Windows 10/11, 64-bit, no .NET installation needed). `SqlRestore-win-Portable.zip` runs without installing,
  and `SqlRestore.exe` is the whole application in one file, for computers where nothing may be installed; neither
  updates itself.
- **Product page:** https://www.sqltreeo.com/sqlrestore
- **Support:** https://www.sqltreeo.com

SQLTreeo Restore is commercial software. It is licensed, not sold: see [LICENSE.txt](LICENSE.txt) (end-user
license agreement). Third-party open-source components are listed in the application (Settings › About ›
Third-party notices) and in `THIRD-PARTY-NOTICES.txt` inside the installer and the zip.

The `.nupkg` and `releases.*.json` files are used by the updater and are not meant to be downloaded manually.
