My personal VS Code keybindings for C, js, python, julia, C++, go.
See actual keybindings for hotkeys.

Windows 10 location: %appdata%/Roaming/Code/User/

Also including settings.json(open and apppend it, don't replace) for extension Save and Run (wk-j.save-and-run) that allows c to be compiled and ran on save, making it act like nodemon.
alternative for wk-j.save-and-run is to make a batch called 0_run_nodemon.bat:
nodemon %1
then drag and drop script onto bat file. allows VS code to be used with a full monitor of terminal output
