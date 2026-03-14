# VSCode Extension

- Install TexLive
- VSCode Extension:
  - Paste Image - mushan
  - LaTex Workshop - James Yu
- Since I have `exiftool` installed by chocolatey. This will conflict with the pearl.exe path. I will need to uninstall exiftool by chocolatey,
  and remove the pearl.exe from `C:\ProgramData\chocolatey\bin`. Otherwise it will cause the error "The system cannot find the file specified" when running the command "pdflatex -synctex=1 -interaction=nonstopmode %.tex" in the terminal.
- Remove keybinding for `ctrl+alt+v` in VSCode, otherwise it will conflict with the Paste Image extension. You can do this by going to File > Preferences > Keyboard Shortcuts and searching for `ctrl+alt+v` and removing the keybinding.
