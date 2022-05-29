This script continuously checks if selected (highlighted) text fits the shape of either epoch seconds or milliseconds. If it does the script tries to parse.

For simplicity the script only covers dates that are represented by either 10 digit seconds or 13 digit milliseconds.

# Dependencies

- https://github.com/cdown/clipnotify To detect selection of text. Executable is included in this project for convenience. Alternatively, build form source.
- `xsel` to read the selected text from clipboard (https://wiki.ubuntuusers.de/xsel/)
- `notify-send` provided by the `libnotify-bin` package

# Usage

Just run it in some terminal.
