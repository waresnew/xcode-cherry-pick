# Xcode Cherry Pick

Uses Github's (arm64) macOS environment to extract specific files that are bundled in Xcode without needing to download the full Xcode package (~15 GB) every time. This is useful if you don't need/use Xcode but do need certain files in Xcode that are unavailable elsewhere.

You can modify `files.txt` to change which files are extracted: on each line, enter the path to the file relative to Xcode.app, followed by a space, followed by the desired file name when uploaded. By default the following files are included:

- gamepolicyctl, for programatically querying and setting Game Mode
