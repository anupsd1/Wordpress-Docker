This file can be get wordpress on localhost:8000. And the content will be saved on the local drive at wp-content.
If the container created is deleted, the contents of the wordpress file will still be saved on the local drive wp-content.
When you recreate the container, the saved content can still be used.

POSSIBLE ERROR CHANCES

Error:
ERROR: yaml.scanner.ScannerError: while scanning for the next token
found character '\t' that cannot start any token

Solution
There are multiple reasons for the above error, for me it was that I had not used the tab properly on the next line after volumes
