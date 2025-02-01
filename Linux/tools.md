# Helpful CLI/TUI tools for investigations:
ncdu - Interactive disk usage TUI
chntpw - Windows registry editor (for Linux)
sqlitebrowser - SQLite explorer written in Qt
rg - Ripgrep, a significantly faster version of grep

# Discovery and recovery
- testdisk - Great at analyzing hard drives and images. Will preserve metadata, filenames and directory paths.
- photorec - A companion tool to testdisk. Can recover files at the cost of losing all metadata and other information.
- foremost - A file carving tool that recovers files using headers, footers, and data structures. Again, does not keep metadata.
- scalpel - Another file carving tool. Was part of the Sleuth Kit, but was abandoned. May still be useful?

# Usenet: .dbx
Has largely fallen out of popularity, but some people still use it, and it may be present on old hard drives too.
- uudeview - Decode UUencoded files.
- `strings <file> | grep -iE "JFIF|Exif|PNG|GIF89a"` - Check if there's any image files.

## Usenet group classifications
- Exmaple: alt.binaries.pictures.trainspotting
- alt = One of the biggest hierarchy on Usenet, named as an "alternative" to the "big 8" at the time. Alt is largely unregulated, and may content illegal content.
- alt.binaries = The most infamous of all on Usenet. These groups content binary data, such as images, videos or software, and can be quite big in size. These groups likely contain explicit and/or illegal content. 
- alt.binaries.pictures = Signifying that pictures were the primary focus of that group.
- alt.binaries.pictures.trainspotting = Topics are typically by the end of the file name, which signify their main topic. Trainpotting, games, music, and other unsavoury content. 
