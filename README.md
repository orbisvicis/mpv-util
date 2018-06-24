Utilities for working with `mpv`:

 *  `mpv_smb_sub`

    An 'mpv' wrapper that, for each Samba file URI, appends all matching subtitle files from the corresponding directory to the list of external subtitles by supplementing the command-line arguments using '--sub-files-add'. Avoids adding duplicate files and minimizes server queries.

Example:

    mpv_smb_sub -s fuzzy -- "smb://server/share/path/to/media.mkv"


License: GPL-3.0-or-later
