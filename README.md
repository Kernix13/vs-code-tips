# VSCode Tips and Tricks

This is a list of common and less well known tips, not a comprehensive list.

## Common Shortcuts

**Note**: The shortcuts involving a letter are Uppercase to make them easier to read but they can be lowercase as well (and usually are).

1. `CTRL+S` to open Keyboards Shortcuts
1. `ALT+#` to switch between open tabs (not numpad numbers)
1. `CTRL+P` to search for file and open
1. `CTRL+TAB` to cycle thru open tabs
1. `CTRL+,` to open Setings page
1. `CTRL+J` or ` CTRL+``` to toggle terminal/command line
1. `CTRL+B` to toggle sidebar
1. `CTRL+L` to select multiple lines
1. `F1` to open command palette
1. `F1` + type 'format' for format a selection or a document
1. `F1` + start typing _emmet_ and select "Emmet: Wrap with Abbreviation". Best for wrapping a block of HTML with a tag
1. Double-click 'item' then `CTRL+D` to select other occurrences
1. `ALT+Click` for multiple cursors
1. `CTRL+F` to open search box, then `ALT+R` to toggle RegEx option
1. `CTRL+SHIFT+O` to open the command palette and show the names of the variables and functions in a long file
1. `CTRL+SHIFT+Arrow-down` to copy cursor focus line or selected line(s) down, Arrow-Up to copy it up
1. `ALT+Arrow-Up` or Down to move a line up or down
1. `F1` to open command palette - try out ~Emmet: Wrap with abbreviation`
1. `F2` while on a var or function name to rename throught out your project 
1. `SHIFT+ALT+F` to format the entire document, or `CTRL+K CTRL+F` for current selection

## HTML Tab Triggers

1.

## CSS Tab Triggers

1. `tdn` for `text-decoration: none`
1. `tac` for `text-align: center`

## JavaScript Tab Triggers

1.

## Top bar icons

1.

## Bottom bar icons

1.

Here is a GitHub repo that has a lot of VS Code tips (redundant?):

https://github.com/microsoft/vscode-tips-and-tricks

However, it's really comprehensive. I think a more scaled-down version would be useful for beginners, as opposed to advanced users.

## Debugging

1. You need an HTML and JS file
2. Click the left sidebar debug icon
3. Clik the gear icon at the top to select the browser - BRAVE is not an option!
4. Check out Stackoverflow: [How to attach the VSCode debugger to the Brave browser?](https://stackoverflow.com/questions/53380075/how-to-attach-the-vscode-debugger-to-the-brave-browser)

Video: The New Way To Debug JavaScript in VS Code - No Extension Required by James Q Quick

- need to have your JS app running locally so open with live server
- I need to switch to Chrome - after clicking the gear icon select chrome and then you get a JSON config file called launch.json
- live server runs on port 5500 so change the config file from 8000 to 5500 
- then click the play button top left to trigger the debugging instance 
- your app will then relaunch in chrome 

Actual debugging
- you need to create a breakpoint inside of vs code to do the debugging
- you create a brakpoint by clicking the red dot to the line of the line numbers - start at the top of your code
- then click the run button again 

## Miscellaneous

Change terminal from Powershell on Windows to Git Bash:
- in settings search for `terminal`
- scroll way down to `Terminal > Integrated > Default Profile: Windows`
- Change the default setting of `null` to `Git Bash`


### Sync settings

Token: `vscode://vscode.github-authentication/did-authenticate?windowid=1&code=ENTER_CODE_HERE`

1. Copy the token.
2. Switch back to VS code.
3. Click Signing in to github.com... in the status bar.
4. Paste the token and hit enter.
