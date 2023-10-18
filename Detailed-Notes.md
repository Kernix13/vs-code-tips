# Notes

## Intro

- Directly above line 1 of your code is the breadcrumb list. You can click into the final part of the breadcrumbs to select a function or other code element and jump to that section of the file.
- Mini-map: sux IMO, I turned it off
- Terminal: either `CTRL` + `Tilde` or `CTRL` + `J`

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
1. [Shortcuts](#shortcuts)
1. [](#)

## Command Palette

- `CTRL` + `SHIFT` + `P` - anything you can do in VS Code shows up there
- It is mainly used so you only use the kyeboard
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
code {
  font-family: 'Courier New', Courier, 'Lucida Console', Consolas, Monaco,
    'Lucida Sans Typewriter', monospace;
}
```

## Settings

- When you change a default setting, in the UI in the Settings view it shows a thin orange left-border to indicate that you changed it
- Rulers - try `80`, good to make the code more readable

```json
{
  "editor.rulers": [80]
}
```

- Editor: word wrap - I have mine sett to `on`
- Cursor Blinking: I chose `phase`

## Base Features

- Explorer sidebar - right most top icon collapses all open folders!!!
- Right-click options when in explorer sidebar
- Outline - like breadcrumbs - can see the structure of the active file and click on an element to go to that element
- Extension: `Advanced New File` > by patbenetar - NO

## Code editor

- _Side by side editing_: 1) drag a tab to the side opposite the navigator - drag it back over to remove that, 2) click the open book icon, 3) `ALT` + `click`
- _Top to bottom editing_ - drag a tab to the bottom or `ALT` + `hover` over open book icon to have it change shape
- _Editor Groups_ - not for me
- _Enable Preview_: the italic name in the tab when you click a file - dbl-click or edit to keep it open
- _Start Up State_:
- Text Editor vs IDE (Integrated Development Environment): notepad vs vs code

## Intellisense

- Intellisense: code completion, parameter info, quick info, member lists, and more
- Learn more at: https://code.visualstudio.com/docs/editor/intellisense
- Intellisense trigger keys: on keywords, the start of your var or fx names, parens, etc but only at the start of typing them
- To trigger them use `CTRL` + `SPACEBAR`
- You can also `right-click` > `Go to Definition`
- `JSDoc` 3 is an API documentation generator for JavaScript
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

## Find and Replace

1. CTRL + F in editor

- Option #1: `CTRL` + `W` - to close an open file/tab - for the replace field the last icon is to "Replace All" - only searches in current file
- Option #2: Search icon in sidebar - also has a replace box - searches your entire codebase - also files to include or exclude, e.g. `components/**` which means do not search below that folder
  - Go into Settings > search exclude > to see what VS Code excludes
- Option #3: sidebar > hover over a folder > right-click > Find in Folder
- Option #4: an icon above when you do #3 - ?
- Multi-cursor editing - `ctrl` + `F` > then `ALT` + `ENTER` to select all occurences - quicker than `CTRL` + `D`
- `right-click` > `Rename Symbol` to rename the Fx or any object and all references to it
- `right-click` > `Peek` > `Peek Definition` - you can edit it in that peek - ehh

### Refactoring

Looks like another Find and Replace

- `right-click` > `Find all references` but only for usable code - will not match in comments
- `right-click` > `Find all occurences` but only for the file you are in - for find and replace everywhere but I prefer the sidebar

## Extensions

- `CTRL` + `SHIFT` + `X`
- The more exttensions you have, the slower VS Code becomes
- You can turn off extensions in a project folder if you don't need them!!!
  - Open extensions sidebar > click the gear icon > click `Disable (Workspace)`
- For collaborators have them all have the same extensions - you can tell VS Code to recommend the same extensions for people contributing:
  - `CTRL` + `SHIFT` + `P` > type `recommended extensions`
  - That createes a `.vscode` folder and inside `extensions.json`
  - Add to the `recommendations` array - search for an extension, click on it

> He wants to use `esbenp.prettier-vscode` next to the name but I only have `v10.1.0` next to the name - same for every other extension - only a version # - it might require the recommendations cmd

## Settings Sync

- Great for multiple computers you own
- Click the Accounts icon in the sidebar > select `Sign into sync settings`
- Sign in with GitHub > Continue > Allow > now settings and extensions are synced on all your computers

## Snippets

- Start typing > arrow to what you want > `TAB` or `ENTER` to autocomplete

> NOTE: you will see code that may be better than yours

- Or CTRL+SHIFT+P to open cmd palette > inserrt snippet
- Extensions can add to the snippets in vs code - NICE

### Build custom snippets

- `CTRL`+`SHIFT`+`P` > snippet > Preferences: Configure User Snippets
- Then you can choose Global or other choices - `SKIP`

## Emmet

- Emmet cheatsheet: https://docs.emmet.io/cheat-sheet/
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

## HTML CSS Workflow

Built-in features in vs code:

1. Emmet
2. Code folding

- Click the down arrows to fold a code block

3. Color picker

- Cnter a color value and a color box appears
- Hover over it and the color picker opens
- If you click the top bar of the color picker, you can cycle though various color types like Hex, HSL, etc
- that works for inline styles, style tags, and in a CSS file

4. CSS class definition hovers

- Hover over the selector and you can see the specificity

Settings:

1. Auto closing tags

- He doesn't like them - huh?

2. Auto Updating tags - ?
3. Linked editing

- Go into Settings > Link Editing > click the checkbox to turn it on!!!

4. Wrap attribuutes

- Settings > Wrap Attributes

## HTML and CSS Extensions

1. Color Highlight:

- It highlights where you have your color codes - No!
- `Option` (Alt?) + `Click` on the link tag path to open that file - but CTRL+Click does it for me anyway

2. CSS Peek:

- Right-click > go to Definition for a class name in the HTML
- Right-click Peek Definition - ehh

3. HTML End Tag Labels: Tells yyou ttags end - NO!
4. Code Spell Check: spell checks your content text in HTML pages - NO

5. `HTML CSS Support`:

- Intellisense - `CTRL` + `spacebar` and it will suggest clases you already have - that could be useful
- `CTRL` + `spacebar` deoesn't do anything for me - yes it does, you need the class in a CSS file
- You have to add an array to `settings.json` for things like the CDN for Tailwind or Bootstrap - EXCELLENT
- `CTRL` + `,` - then type `css style sheets` - click edit in settings.json
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

## Node and NPM

Extensions

1. npm - use it from the cmd palette - WHY?
2. gitignore - maybe but not for me
3. npm Intellisense - auto-complete require() / inport
4. `Version Lens` - adds a "V" top right and it will add the latest version for all your dependencies in `package.json`
5. `Import Cost` - it will calculate the size of each dependency - great to see what you are shipping to your users - YES!

## JavaScript Workflow

1. Intellisense - already covered
2. JSDoc - a comment above a JS Fx that shows what the Fx does -
3. Auto Imports - ok
4. Code Navigation + Renaming - ?
5. Code Actions on Save - search for "code actions on dave" in Settings -
6. Update Imports on Move - already happens for me

## JavaScript Extensions

1. ESLint

- To catch errors or things that could be confusing when you write your code - and before running code
- But you need to do `npm i eslint` or `npm i -g eslint` or `npm i -D eslint`
- Also create `.eslintrc` file

## Shortcuts

- `right-click` on a tab of a file > "Close to the right" to close all tabs/files to the right of that file
- `CTRL` + `T` to search for Fxs in your project - "Go to symbol"
