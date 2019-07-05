# VSCode context menu options for Nemo

Nemo, Cinnamon DE file manager, supports adding actions and scripts to it's context menu.

Just save the following files inside  `~/.local/share/nemo/actions/` to add "Open with VSCode" options to Nemo's context menu:
* **vscode_open_folder.nemo_action**: Open current folder in VSCode;
* **vscode_open_selected_folder.nemo_action**: Open selected folder in VSCode;
* **vscode_open_file.nemo_action**: Open selected file in VSCode (single file);
* **vscode_open_multiple_files.nemo_action**: Open selected files in VSCode (multiple file).

Take this as inspiration and create your own scripts and actions.
