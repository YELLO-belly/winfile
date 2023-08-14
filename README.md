# ![icon](winfile.png) Windows File Manager (WinFile)

## Changes in this fork:
- Added handling of read-only attribute for files copied from CD-ROM drives. A new option can be toggled on or off in winmm.ini **CopyCdromReadOnlyAttrib=0/1** (Default is 1). This is to either simulate the original Winfile behaviour of retaining the read-only attribute or the File Explorer one where read-only attributes are removed from files copied from CD-ROM drives.

- Added preliminary html help documentation and changed the help menu to load them instead of the obsolete and non-working .hlp files.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) License.
