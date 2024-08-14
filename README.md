# Notes

> [!CAUTION]
> This script is intended for personal use, Use it at your own risk.

This script helps you create and organize your Markdown notes with ease.

## Dependencies

Make sure you have the following dependency installed:

```go
go install github.com/charmbracelet/gum@latest
```

## Installation

To install the script, add it your shell configuration

```bash
echo "source /path/to/notes.sh" >> $HOME/.bashrc
```

## Usage

Creating a new note is straightforward. Just use the `nt` command:

```bash
# This will open a prompt for you to input the folder and filename
# Example: projects/project1/notes.md
nt create
```

> [!NOTE]
> By default, the script opens Neovim as your editor. If you'd prefer to use a
different editor, you can easily change this by setting the `$EDITOR` variable

## Additional Commands

To explore more commands and options, use:

```bash
nt help
```

## Contributing

If you encounter any issues or have suggestions for improvements, feel free to
contribute by submitting a pull request or opening an issue.
