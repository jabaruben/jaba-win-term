# jaba-win-term
Custom Windows Terminal with Panes

- Create a shorcut in Desktop with this command inside:
```
wt.exe wsl.exe; split-pane cmd.exe; split-pane -H C:/"Program Files"/Git/bin/bash.exe; mf left
```
- Next, right click on shortcut and click on "add task bar" option


When you click on this aplication in your taskbar, open 3 terminals in panes at the same time.
