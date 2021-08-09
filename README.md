# gallery-dl-fetch
gallery-dl-fetch gathers your archive and uses simple gallery-dl commands to fetch new uploads automatically.

## Outline
NOTE: This is my first python project and my first script in years. There may be bugs and development may be messy and slow.

1. Ask user for gallery-dl download directory. An empty response assumes default settings for gallery-dl. Path is saved to <directory> table.

2. Gather folder/subfolder names in "*/gallery-dl/", save to <site><username> table. JSON? Assuming default folder structure.

3. For each separate <site>, ask the user for preferred gallery-dl command. Provide a simple example command for the site in the user-prompt, default to a basic command if an empty response from the user. gallery-dl-fetch assumes default settings, and defaults to "$ gallery-dl -d "<directory>" "<site><username>""
