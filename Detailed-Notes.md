# Notes

Notes from the video by freeCodeCamp ~ 6hrs long

## Best Of

- ✅ `CTRL` + `SPACEBAR` to activate Intellisense
- ✅ `CTRL` + `SHIFT` + `F` show sidebar search
- ✅ `CTRL` + `SHIFT` + `H` show sidebar search and replace
- ✅ All Multi Cursor techniques
- ✅ Open command palette with `>` - bakspace to remove that and use `@` to find symbols (breadcrumbs) in the file, or `:` for "Go To line number" and `>` is for commands and nothing lists the files in the project folder
- ✅ `CTRL` + `SHIFT` + `\` while on a bracket/brace/paren and it will go to its matching bracket/brace/paren
- ✅ Directly above line 1 of your code, click the final part of the breadcrumbs
- ✅ Command Palette: `CTRL` + `SHIFT` + `P`
- ✅ You can turn off extensions in a project folder if you don't need them - Open extensions sidebar > click the gear icon > click `Disable (Workspace)`
- ✅ Editor: word wrap - I have mine set to `on`
- ✅ _Side by side editing_: 1) drag a tab to the side opposite the navigator - drag it back over to remove that, 2) click the open book icon, 3) `ALT` + `click`
- ✅ `JSDoc` 3 is an API documentation generator for JavaScript
- ✅ You can turn off extensions in a project folder if you don't need them!!!
  - ✅ Open extensions sidebar > click the gear icon > click `Disable (Workspace)`
- ✅ For collaborators have them all have the same extensions - you can tell VS Code to recommend the same extensions for people contributing:
  - ✅ `CTRL` + `SHIFT` + `P` > type `recommended extensions`
  - ✅ That createes a `.vscode` folder and inside `extensions.json`
  - ✅ Add to the `recommendations` array - search for an extension, click on it
- ✅ Start typing > arrow to what you want > `TAB` or `ENTER` to autocomplete
- ✅ Emmet cheatsheet: https://docs.emmet.io/cheat-sheet/
- ✅ CSS class definition hovers - Hover over the selector and you can see the specificity
- ✅ Linked editing - Go into Settings > Link Editing > click the checkbox to turn it on
- ✅ You have to add an array to `settings.json` for things like the CDN for Tailwind or Bootstrap
- ✅ `Import Cost` - it will calculate the size of each dependency - great to see what you are shipping to your users
- ✅ ESLint, Run `npm init -y` then `npm i -D eslint`, Also create `.eslintrc` file
- ✅ **Tailwind CSS Intellisense**: you need to have a file tailwind.config.js
- ✅ To open a folder within the folder you are in, `-r` is for reload
- ✅ `CTRL`+ `R` for online VS Code keyboard shortcuts list
- ✅ `CTRL` + `W` to close the tab you are in
- ✅ `CTRL` + `SHIFT` + `T` to reopen a closed tab
- ✅ `Right-click` on a tab of a file > "Close to the right" to close all tabs/files to the right of that file
- ✅ `SHIFT` + `CTRL` + `ENTER` to add a blank line above the line you are one and you do not need to be at the end of the line
- ✅ `CTRL` + `]` to tab entire line
- ✅ `CTRL` + `[` to tab entire line backwards
- ✅ `CTRL` + `P` to open a file
- ✅ `CTRL` + `K`, release CTRL then `V` to open markdown preview to the side
- ✅ `CTRL` + `SHIFT` + `V` to open markdown preview full view
- ✅ `F12` on a function call to "Go To Definition"
- ✅ Hover over a Fx call and hold `CTRL` which makes it a link to the definition - `CTRL` + `click` again to close a TypeScript definition
- ✅ `Tabnine Ai Code Completion` extension: by tabnine.com
- ✅ When you change a default setting, in the UI in the Settings view it shows a thin orange left-border to indicate that you changed it
- ✅ `// TODO:` - add to code in JS but make sure to do is all caps
- ✅ Rulers - try `80`, good to make the code more readable

```json
{
  "editor.rulers": [80]
}
```

## Intro and miscellaneous

- Directly above line 1 of your code is the breadcrumb list. You can click into the final part of the breadcrumbs to select a function or other code element and jump to that section of the file.
- Mini-map: sux IMO, I turned it off
- Terminal: either `CTRL` + `Tilde` or `CTRL` + `J`
- ✅ `// TODO:` - add to code in JS but make sure to do is all caps

<div id="back-to-top"></div>

## Table Of Contents

1. [Command Palette](#command-palette)
1. [Themes and Extensions](#themes-and-extensions)
1. [Fonts](#fonts)
1. [Settings](#settings)
1. [Base Features](#base-features)
1. [Code editor](#code-editor)
1. [Intellisense](#intellisense)
1. [Find and Replace](#find-and-replace)
1. [Refactoring](#refactoring)
1. [Extensions](#extensions)
1. [Settings Sync](#settings-sync)
1. [Snippets](#snippets)
1. [Build custom snippets](#build-custom-snippets)
1. [Emmet](#Emmet)
1. [Command Line Tools](#command-line-tools)
1. [HTML CSS Workflow](#html-css-workflow)
1. [HTML and CSS Extensions](#html-and-css-xtensions)
1. [Node and NPM](#node-and-npm)
1. [JavaScript Workflow](#javascript-workflow)
1. [JavaScript Extensions](#javascript-extensions)
1. [React Workflow](#react-workflow)
1. [Vue Workflow](#vue-workflow)
1. [Tailwind Workflow](#tailwind-workflow)
1. [Markdown Workflow](#markdown-workflow)
1. [Laravel Workflow](#laravel-workflow)
1. [Visual Upgrades](#visual-upgrades)
1. [Settings json file](#settings-json-file)
1. [Minimalist Workflow](#minimalist-workflow)
1. [VS Code Terminal](#vs-code-terminal)
1. [Git and GitHub](#git-and-github)
1. [Multiple Projects Workflow](#multiple-projects-workflow)
1. [Autosave and Autoformat](#autosave-and-autoformat)
1. [Preview Your Work](#preview-your-work)
1. [Keyboard Shortcuts](#keyboard-shortcuts)
   1. [Miscellaneous](#miscellaneous)
   1. [Tabs](#tabs)
   1. [Lines](#lines)
   1. [Navigation](#navigation)
   1. [Multi Cursor](#multi-cursor)
   1. [Display](#display)
1. [Calling APIs in VS Code](#calling-apis-in-vs-code)
1. [Vim in VS Code](#vim-in-vs-code)
1. [AI Coding Helpers](#ai-coding-helpers)

## Command Palette

- `CTRL` + `SHIFT` + `P` - anything you can do in VS Code shows up there
- It is mainly used so you only use the keyboard
- Use `toggle`: `toggle terminal` (?)

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Themes and Extensions

- Open cmd pallette > color theme > `Preferences: color themes` - you can preview each one installed
- Icon Theme > go to Extensions and type in "icon theme"
- Io cycle thru the options, open command palette and type "icon theme"

## Fonts

- Cascadia Code, FiraCode,
- Ligatures - not for me
- My CSS monspace font stack most commonly installed on people's systems:

```css
pre,
code,
kbd,
var {
  font-family: 'Courier New', Courier, 'Lucida Console', Consolas, Monaco,
    'Lucida Sans Typewriter', monospace;
}
```

## Settings

- ✅ When you change a default setting, in the UI in the Settings view it shows a thin orange left-border to indicate that you changed it
- ✅ Rulers - try `80`, good to make the code more readable

```json
{
  "editor.rulers": [80]
}
```

- ✅ Editor: word wrap - I have mine set to `on`
- ✅ Cursor Blinking: I chose `phase`

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Base Features

- Explorer sidebar - right most top icon collapses all open folders!!!
- Right-click options when in explorer sidebar
- Outline - like breadcrumbs - can see the structure of the active file and click on an element to go to that element
- Extension: `Advanced New File` > by patbenetar - NO

## Code editor

- ✅ _Side by side editing_: 1) drag a tab to the side opposite the navigator - drag it back over to remove that, 2) click the open book icon, 3) `ALT` + `click`
- _Top to bottom editing_ - drag a tab to the bottom or `ALT` + `hover` over open book icon to have it change shape
- _Editor Groups_ - not for me
- _Enable Preview_: the italic name in the tab when you click a file - dbl-click or edit to keep it open
- _Start Up State_:
- Text Editor vs IDE (Integrated Development Environment): notepad vs vs code

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Intellisense

- Intellisense: code completion, parameter info, quick info, member lists, and more
- Learn more at: https://code.visualstudio.com/docs/editor/intellisense
- Intellisense trigger keys: on keywords, the start of your var or fx names, parens, etc but only at the start of typing them
- To trigger them use `CTRL` + `SPACEBAR`
- You can also `right-click` > `Go to Definition`
- ✅ `JSDoc` 3 is an API documentation generator for JavaScript
- Extra info with `JSDoc`: type `/**` and `*/` gets added and you get things like `@param` if you do it over a function with a parameter:

```js
/**
 * Add 2 numbers together
 * @param {number} x The first number to add
 * @param {number} y The second number to add
 * @returns number
 */
function add(x, y) {
  return x + y;
}
add(2, 2);
```

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Find and Replace

1. CTRL + F in editor

- Option #1: `CTRL` + `W` - to close an open file/tab - for the replace field the last icon is to "Replace All" - only searches in current file
- Option #2: Search icon in sidebar - also has a replace box - searches your entire codebase - also files to include or exclude, e.g. `components/**` which means do not search below that folder
  - Go into Settings > search exclude > to see what VS Code excludes
- Option #3: sidebar > hover over a folder > right-click > Find in Folder
- Option #4: an icon above when you do #3 - ?
- Multi-cursor editing - `Ctrl` + `F` > then `ALT` + `ENTER` to select all occurences - quicker than `CTRL` + `D`
- `right-click` > `Rename Symbol` to rename the Fx or any object and all references to it
- `right-click` > `Peek` > `Peek Definition` - you can edit it in that peek - ehh

### Refactoring

Looks like another Find and Replace

- `right-click` > `Find all references` but only for usable code - will not match in comments
- `right-click` > `Find all occurences` but only for the file you are in - for find and replace everywhere but I prefer the sidebar

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Extensions

- `CTRL` + `SHIFT` + `X`
- The more extensions you have, the slower VS Code becomes
- ✅ You can turn off extensions in a project folder if you don't need them!!!
  - ✅ Open extensions sidebar > click the gear icon > click `Disable (Workspace)`
- ✅ For collaborators have them all have the same extensions - you can tell VS Code to recommend the same extensions for people contributing:
  - ✅ `CTRL` + `SHIFT` + `P` > type `recommended extensions`
  - ✅ That createes a `.vscode` folder and inside `extensions.json`
  - ✅ Add to the `recommendations` array - search for an extension, click on it

> He wants to use `esbenp.prettier-vscode` next to the name but I only have `v10.1.0` next to the name - same for every other extension - only a version # - it might require the recommendations cmd

## Settings Sync

- Great for multiple computers you own
- Click the Accounts icon in the sidebar > select `Sign into sync settings`
- Sign in with GitHub > Continue > Allow > now settings and extensions are synced on all your computers

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Snippets

- ✅ Start typing > arrow to what you want > `TAB` or `ENTER` to autocomplete

> NOTE: you will see code that may be better than yours

- Or CTRL+SHIFT+P to open cmd palette > insert snippet
- Extensions can add to the snippets in vs code - NICE

### Build custom snippets

- `CTRL`+`SHIFT`+`P` > snippet > Preferences: Configure User Snippets
- Then you can choose Global or other choices - `SKIP`

## Emmet

- ✅ Emmet cheatsheet: https://docs.emmet.io/cheat-sheet/
- Can use Emmet in CodePen also
- `html:5` + `TAB` does the same thing as `!` + `TAB`
- `CTRL`+`SHIFT`+`P`and "Emmet Wrap with abbreviation" - use it all the time!
- Balance Outward - ?

## Command Line Tools

- He is talking about the system terminal (command prompt, PowerShell)
- `code .` to open the current directory in VS Code
- `code folder_name` to open a folder

Install CLI tools

- `CTRL`+`SHIFT`+`P` > type `install code command in PATH`
- Once that is installed close powershell, reopen and type `code --help`

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## HTML CSS Workflow

Built-in features in vs code:

1. Emmet
2. Code folding

- Click the down arrows to fold a code block

3. Color picker

- Enter a color value and a color box appears
- Hover over it and the color picker opens
- If you click the top bar of the color picker, you can cycle though various color types like Hex, HSL, RGB, etc
- that works for inline styles, style tags, and in a CSS file

4. ✅ CSS class definition hovers - Hover over the selector and you can see the specificity

Settings:

1. Auto closing tags

- He doesn't like them - huh?

2. Auto Updating tags - ?
3. ✅ Linked editing - Go into Settings > Link Editing > click the checkbox to turn it on!!!
4. Wrap attribuutes

- Settings > Wrap Attributes

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## HTML and CSS Extensions

1. Color Highlight:

- It highlights where you have your color codes - No!
- `Option` (Alt?) + `Click` on the link tag path to open that file - but `CTRL` + `Click` does it for me anyway

2. CSS Peek:

- Right-click > go to Definition for a class name in the HTML
- Right-click Peek Definition - ehh

3. HTML End Tag Labels: Tells you tags end - NO!
4. Code Spell Check: spell checks your content text in HTML pages - NO

5. `HTML CSS Support`:

- Intellisense - `CTRL` + `spacebar` and it will suggest clases you already have - that could be useful
- `CTRL` + `spacebar` deoesn't do anything for me - yes it does, you need the class in a CSS file
- ✅ You have to add an array to `settings.json` for things like the CDN for Tailwind or Bootstrap - EXCELLENT
- `CTRL` + `,` - then type `css style sheets` - click edit in `settings.json`
- But you still have to do `CTRL` + `Spacebar` and it may take a while to load
- From the extension docs in VS Code:

> If it is not possible to specify local or remote styles in HTML or via template inheritance, they can be specified in VS Code settings per workspace folder in `.vscode/settings.json` and will suggest for all HTML files within that workspace folder

```json
{
  "css.styleSheets": [
    "https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css",
    "https://cdn.jsdelivr.net/npm/tailwindcss@0.7.4/dist/tailwind.min.css" /* this one */,
    "https://unpkg.com/browse/tailwindcss@2.0.1/dist/tailwind.min.css" /* or this one */,
    "https://unpkg.com/browse/tailwindcss@^2/dist/tailwind.min.css" /* or this one - I used this one */,
    "/style.css",
    "style.css",
    "${fileBasenameNoExtension}.css" /* what does this do? */
  ]
}
```

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Node and NPM

Extensions

1. npm - use it from the cmd palette - WHY?
2. gitignore - maybe but not for me
3. npm Intellisense - auto-complete require() / import
4. `Version Lens` - adds a "V" top right and it will add the latest version for all your dependencies in `package.json`
5. ✅ `Import Cost` - it will calculate the size of each dependency - great to see what you are shipping to your users - YES!

## JavaScript Workflow

1. Intellisense - already covered
2. JSDoc - a comment above a JS Fx that shows what the Fx does -
3. Auto Imports - ok
4. Code Navigation + Renaming - ?
5. Right-click > Source-action > Organize imports - organizes your imports and removes any unused imports - may need `editor.codeActionOnSave` in `settings.json`
6. Code Actions on Save - search for "code actions on save" in Settings -
7. Update Imports on Move - already happens for me

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## JavaScript Extensions

1. ✅ ESLint

- To catch errors or things that could be confusing when you write your code - and before running code
- ✅ Run `npm init -y` then `npm i -D eslint`
- We need `package.json`
- ✅ Also create `.eslintrc` file - to do that:
  - `CTRL`+`SHIFT`+`P` to open the cmd palette > type "eslint" and
  - Choose "Create ESLint Configuration": that opens prompts in the terminal
  - That actually runs in t he terminal `node_modules\.bin\eslint.cmd`
  - You can also run this command directly using `npm init @eslint/config`
  - `y` to proceed > choose "To check syntax and find problems"
  - Choose JS Modules > Choose "None of these" for frameworks
  - Choose "No" for Typescript and "Browser" for where the code runs
  - Choose to format it as a JS file
- You will see errors for variables tthat are declared but never used, const vars that have been reassigned.
- The file that is created as a result of all of that has a value of `eslint:recommended` - rules for how our code should be formatted
- Go to eslint.org > then to https://eslint.org/docs/latest/rules/:
- If you have `eslint:recommended`it shows you what it does here - everything with a check mark - a GOOD READ!
- If you see a light bulb click and you can select things like Remove unreachable code
- If you have a lot of problems you can open up Problems with `CTRL` + `SHIFT` + `M` - you get the lightbulb in the Problems tab which you should check for a possible solution

2. `JavaScript (ES6) code snippets` - HAVE IT - `imp` for imports, `fre` for a forEach block,

- For `imp` the cursor is first at the package name, if you hit TAB it goes back to what you want to name it
- `imd` is for import destructure
- `clg` for console.log

3. Path Intellisense - for importing files as soon as you start typing a path -
4. Turbo Console Log - Not for me
5. `JavaScript Booster` - helpers - to refactor code - Maybe

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## React Workflow

- Extension: Simple React Snippets - props and types - SKIP

Emmet and JSX:

- need to edit settings.json

## Vue Workflow

Extensions: Vetur, Vue VSCode Snippets, VS Code Extension Pack

> I haven't worked with Vue that much so I'm not going to take a lot of notes

- Vetur: Seems to be the best one for Vue
- Vue VSCode Snippets:
- VS Code Extension Pack

## Tailwind Workflow

Extensions: Tailwind Docs, Tailwind CSS Intellisense, Headwind

- Tailwind Docs: extends the Cmd Paleete (CTRL+SHIFT+P) - select something and it opens it in the browser
- ✅ **Tailwind CSS Intellisense**: you need to have a file tailwind.config.js
- Headwind: sorts the classes in your class or className attribute - would be good if working on a team

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Markdown Workflow

Extension: Markdown Preview GitHub Styling, Markdown All In One, markdownlint

- Markdown Preview GitHub Styling: totally unnecessary
- Markdown All In One: ehhh, markdown is not that hardd that I need TAB shortcuts
- markdownlint: to find errors or recos for better writing

## Laravel Workflow

> Make sure you have PHP installed

Extension: PHP Intellephense, phpfmt, Laravel Extra Intellisense, Laravel Blade Snippets, Laravel Blade Spacer, PHP Namespace Resolver

- PHP Intellephense: better than PHP Intelisense,
- phpfmt: formatter for PHP
- Laravel Extra Intellisense:
- Laravel Blade Snippets:
- Laravel Blade Spacer:

## Visual Upgrades

Settings:

1. renderIndentGuides: leave then on - I prefer them
2. lineHeight: leave at 0
3. breadcrumbs: I prefer them though I do not use them much

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Settings json file

- If you hover over a setting that is a boolean or has set choices, a pencil icon appears to the left and you can change it

## Minimalist Workflow

- Absolutely stupid - why?
- Maybe try Zen mode

## VS Code Terminal

- ✅ To open a folder within the folder you are in, `-r` is for reload

```sh
# -r is for reload
code folder-name -r
```

- If you have a lot of problems you can open up Problems with `CTRL` + `SHIFT` + `M` - you get the lightbulb in the Problems tab which you should check for a possible solution
- You can have multiple terminals including groups
- The up and down angle icons are for expanding and reducing the size of the terminal
- You can go into settings and search for "terminal" to change things like line height and font size
- Right-click > panel position > left or right

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Git and GitHub

> Only use the terminal, do not use the controls in VS Code

5 extensions

- Git History: install it > CTRL+SHIFT+P and type "history" > choose View File History or Line History or just View History (git log)
- Git Blame: NO!
- gitlink: MAYBE
- Git Indicators: NO!
- `GitLens`: includes Git Blame and Git History - the links at top top right are good - this is a good one

> Look into adding tags: _...Typically, people use this functionality to mark release points_

- `git tag` (with optional `-l` or `--list`) or `git tag -l "v1.8.5*"`

## Multiple Projects Workflow

- Multiple folders / GitHub repos -
- VS Code has "Workspaces"
- A Workspace is just multiple folders in a project
- Common for root files, front-end folder, back-end folder
- You can save your Workspaces

Extensions for working with multiple projects:

- Project Manager: used to switch between ddifferent projects - NO
- Peacock: NO

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Autosave and Autoformat

- Auto Save setting - NO
- Prettier: sets a standard for the team
- The problem is not formatting your code before pushing to GitHub
- Format on Save and Format on Paste
- _default format_?

## Preview Your Work

- `Live Server`: YES
- `Browser Preview`: puts a browser on the right side of VS Code! Think you need to use the Cmd Palette for that

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Keyboard Shortcuts

**Key Bindings**

You work faster when you don't use your mouse

`CTRL+SHIFT+P` > search for "keyborad shortcuts" > choose "Help: Keyboard Shortcuts Reference" or

### Miscellaneous

1. ✅ `CTRL`+ `R` to go to [VS Code Windows Keyboard Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
1. `CTRL` + `T` to search for Fxs in your project - "Go to symbol" - ???
1. `CTRL` + `arrow right` or `arrow left`: jumpt to next whitespace or symbol vs Cursor Smooth setting
1. `CTRL` + `SPACEBAR` to activate Intellisense
1. Command Palette: `CTRL` + `SHIFT` + `P`
1. Balanace outward for emmet???

### Tabs

1. `F11` toggle full-screen
1. ✅ `CTRL` + `W` to close the tab you are in
1. ✅ `CTRL` + `SHIFT` + `T` to reopen a closed tab
1. ✅ `Right-click` on a tab of a file > "Close to the right" to close all tabs/files to the right of that file

### Lines

1. `ALT` + `down arrow` or `up arrow` to move lines
1. `SHIFT` + `ALT` + `down arrow` or `up arrow` to copy a line up/down
1. `SHIFT` + `CTRL` + `down arrow` or `up arrow` to select multiple lines
1. ✅ `SHIFT` + `CTRL` + `ENTER` to add a blank line above the line you are one and you do not need to be at the end of the line
1. ✅ `CTRL` + `]` to tab entire line
1. ✅ `CTRL` + `[` to tab entire line backwards

### Navigation

1. ✅ `CTRL` + `P` to open a file
1. ✅ `CTRL` + `K`, release CTRL then `V` to open markdown preview to the side
1. ✅ `CTRL` + `SHIFT` + `V` to open markdown preview full view
1. `CTRL` + `SHIFT` + `P` to open command palette
1. `CTRL` + `HOME` to do to beginning of file
1. `CTRL` + `END` to go to end of file
1. `CTRL` + `G` then type a line # to go to that line
1. `CTRL` + `SHIFT` + `O` to show all "symbols" in the file
1. ✅ `F12` on a function call to "Go To Definition"
1. ✅ Hover over a Fx call and hold `CTRL` which makes it a link to the definition - `CTRL` + `click` again to close a TypeScript definition
1. Clicking the breadcrumbs does a lot of that as well
1. `CTRL` + `SHIFT` + `\` while on a bracket/brace/paren and it will go to its matching bracket/brace/paren

> `CTRL` + `SHIFT` + `P` opens the command palette with `>` - bakspace to remove that and use `@` to find symbols (breadcrumbs) in the file, or `:` for "Go To line number" and `>` is for commands and nothing lists the files in the project folder

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Multi Cursor

1. `ALT` + `click` or
1. Select text then `CTRL` + `D` to select next instance for another cursor
1. Click anywhere > `SHIFT` + `ALT` + `Drag` to create multiple line cursors
1. `CTRL` + `ALT` + `down arrow` or `up arrow`
1. Select text > `CTRL` + `F` > `ALT` + `ENTER`
1. `ESC` to exit out of multi-cursor
1. `CTRL` + `SHIFT` + `arrow left` or `arrow right` to select next word - CTRL + C to copy!!!

### Display

1. `CTRL` + `J` or `CTRL` + `tilde` to toggle terminal
1. `CTRL` + `,` to open settings tab
1. `CTRL` + `B` to toggle sidebar/explorer
1. `CTRL` + `SHIFT` + `E` show explorer, toggle focus
1. `CTRL` + `SHIFT` + `F` show sidebar search
1. `CTRL` + `SHIFT` + `H` show sidebar search and replace
1. `CTRL` + `SHIFT` + `X` show extensions

> You can change a keyboard shortcut but why? `key bindings`

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## GitHub PRs

- **Extension**: GitHub Pull Requests and Issues - just friggin do it on GitHub
- adding comments for different lines for a changed file
- **Extension**: Remote Repositories - NO

## Calling APIs in VS Code

- Postman or Insomnia
- you go back and forth from one of the above programs to your code

2 Extensions to do that:

- REST Client: not as good as ->
- Thunder Client: nice but I'll just use Postman or Insomnia

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Vim in VS Code

- [Vim home page](https://www.vim.org/)
- A text editor with a very high learning curve
- it has 2 modes: 1) Navigation mode, 2) Insert/Edit mode
- There are Vim extensions for VS Code: Vim or `amVim` or Learn Vim
  - You can use down and up arrows to move around or better:
  - `j` to move down a line, `k` to go up
  - `h` to go left , `L` to go right
  - To edit press `i` to insertthen start typing
  - `ESC` to get back to navigation mode
  - `5j` to go down 5 lines
  - `b` goes to the beginning of a word to your left
  - `w` goes to the beginning of a word to your right
  - `e` to go to the end of a word
  - `v` to highlight/select a char
  - `ci'` = change inside quote

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## AI Coding Helpers

Extensions:

- Kite:
- ✅ `Tabnine Ai Code Completion`: by tabnine.com
  - https://app.tabnine.com/profile/subscription
  - https://app.tabnine.com/profile/teams
  - Pro is $12/Month
- Anything with a hexagon is a tabnine feature
- `GitHub Copilot`: is $100/year though they have a free tier:
  - https://github.com/pricing
  - look for icon at far right of status bar
  - Not working - error:

```
[INFO] [auth] [2023-11-05T17:58:02.367Z] Invalid copilot token: missing token: 403

[ERROR] [default] [2023-11-05T17:58:02.369Z] Extension activation failed: "No access to GitHub Copilot found. You are currently logged in as xxxxxx."

CHECK: https://github.com/orgs/community/discussions/40019
```

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>
