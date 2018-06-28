# UploadDemo

Indentify the MIME type of a given file.

Technologies used: HTML, JavaScript

Tool: Sublime Text Editor

Approach: 
- Identify the first bytes of the file which are read using FileReader 
- Once the reading is completed, these bytes are converted to hexadecimal number.
- This hexadecimal numbers used are file signature for each MIME type.
- The loadMime function return the MIME type

