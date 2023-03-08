# thunar-fastprint
The custom printing action for Thunar.
It's a quick way to print multiple files from Thunar. You can print some grafical and text files from contex menu in Thunar.
Just like in Windows.

## Installation
1. Move thunar-print.sh to your $PATH folder
2. Check that libreoffice and imagemagick is already installed
3. Add custom actions in Thunar with command `thunar-print.sh %F` for next file extensions (list below)
```
*.doc;*.docx;*.xls;*.xlsx;*.odt;*.ods;*.jpg;*.jpeg;*.png;*.tiff;*.tif;*.gif;*.pdf;*.ps;*.txt
```
