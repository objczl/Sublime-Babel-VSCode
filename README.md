# Sublime Babel
When using your favorite theme, Visual Studio Code doesn't always display syntax highlight colors as expected. This extension tries to mimic Sublime's [babel-sublime](https://packagecontrol.io/packages/Babel) package as much as possible to address poor coloring.

**Note**: VS Code may interpret scopes slightly differently than Sublime so it won't always be 100% the same between the two editors unless you tweak your theme a bit. Hopefully it is close though.

## Installation

1. Uninstall any preexisting JavaScript grammar extensions (e.g. [Latest TypeScript and JavaScript Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.typescript-javascript-grammar), [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring)) to prevent conflicts
2. Install Sublime Babel via `ext install vscode-eslint` in Command Palette
3. When opening a `.js` or `.jsx` file, ensure the language mode is set to `JavaScript (Babel)`

![statusbar](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/statusbar.png)

For best results, please consider using my [Charcoal Oceanic Next](https://marketplace.visualstudio.com/items?itemName=joshpeng.theme-charcoal-oceanicnext) theme.



## Comparisons

Here is a quick example of the improved grammar compared against the popular [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring) extension on the marketplace. Notice how [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring) handles comments and strings incorrectly.

![Babel ES6/ES7](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/babel-es6.png)

![Sublime Babel](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/sublime-babel.png)

![React](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/react.png)