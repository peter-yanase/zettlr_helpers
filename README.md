# Zettlr Helpers

## What are these?

Some Python scripts to augment Zettlr functionality.

## What is included?

### new_note.py

Creates a new note based on a template.

### convert_vivaldi.py

Converts the exported Vivaldi notes to markdown.

### batch_rename.py

This script renames all the markdown files in a folder to lower case and with underscores instead of spaces, i.e. it turns `My random note.md` into `my_random_note.md`.

## batch_replace.py

This script replaces a string in all the markdown files in a folder. Useful when to alter the naming conventions in your metadata.

*Be careful with what you replace! This script replaces strings not words!* (Also note that it is case-sensitive.) In other words, replacing "other" with "utter" will change "Mother" to "Mutter."

# How do I use these?

`$ python xxxx.py`
