A simple command-line application for managing multiple clipboard entries using Python. This project allows users to save, load, and list clipboard data using custom keys.

Features :
Save clipboard content associated with a key.
Load clipboard content using a specific key.
List all saved clipboard keys and their corresponding contents.


Example :: 

python multiclipboard.py save
# Enter a key: my_note
# Output: DATA SAVED!!!

python multiclipboard.py load
# Enter a key: my_note
# Output: Data copied to clipboard

python multiclipboard.py list
# Output: {'my_note': 'content of the clipboard'}


