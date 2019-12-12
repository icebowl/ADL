# Custom Directory Views

# ENABLE DIRECTORY
Options +Indexes

# SET INDEX OPTIONS 
IndexOptions IgnoreCase FancyIndexing FoldersFirst SuppressHTMLPreamble

# IGNORE THESE FILES
IndexIgnore .git .htaccess .ftpquota favicon.ico img _head.html _foot.html _css.css cgi-bin README.md

# SET DISPLAY ORDER
IndexOrderDefault Ascending Name

# SPECIFY HEADER FILE
HeaderName _head.html

# SPECIFY FOOTER FILE
ReadmeName _foot.html

# FOLDER DESCRIPTIONS
AddDescription "<span class='description'>Directory Listing</span>" transfer

# SPECIFY CUSTOM ICONS
AddIcon img/_md.gif .md
AddIcon img/_file.gif .txt .pdf .zip .jpg .jpeg .jpe .JPG .png .gif .mp3 .rar .mpg .indd .psd .tar .tif .html .htm .css .doc .log .js .ico, .eml
AddIcon img/_directory.png ^^DIRECTORY^^
AddIcon img/_parent.gif *.
AddIcon img/_svg.png *.svg

