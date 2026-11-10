
# vscode

1. Install the Vim extension (vscodevim.vim) (https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).
2. Open the Command Palette and run Preferences: Open User Settings (JSON). Copy all "vim.*" settings from your current settings.json (Library/Application Support/Code/User/settings.json) into it, including their complete arrays and objects.
3. Run Preferences: Open Keyboard Shortcuts (JSON). Merge the shortcuts from your current keybindings.json (Library/Application Support/Code/User/keybindings.json) into it.

This transfers things like your Space leader, jj to Escape, and Ctrl+H/J/K/L pane navigation. If the machine runs Windows or Linux, review shortcuts containing cmd and choose appropriate replacements.
