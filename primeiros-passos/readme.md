# JAVASCRIPT COMPLETO ES6+

## VSCode, Node e Git

# AMBIENTE

## Instalar o Node.js

https://nodejs.org/en/

## Instalar o Git

https://git-scm.com/downloads

## Instalar o Visual Studio Code

https://code.visualstudio.com/

## VISUAL STUDIO CODE (EXTENSÕES E PLUGGINS)

Copie essa lista de uma vez e cole em seu terminal no visual studio com ctrl+V + enter. Essa extensão é a que eu uso.
code --install-extension adpyke.codesnap &&
code --install-extension CoenraadS.bracket-pair-colorizer &&
code --install-extension dbaeumer.vscode-eslint &&
code --install-extension EditorConfig.EditorConfig &&
code --install-extension esbenp.prettier-vscode &&
code --install-extension johnpapa.vscode-peacock &&
code --install-extension jpoissonnier.vscode-styled-components &&
code --install-extension kamikillerto.vscode-colorize &&
code --install-extension mikestead.dotenv &&
code --install-extension ms-vsliveshare.vsliveshare &&
code --install-extension Perkovec.emoji &&
code --install-extension PKief.material-icon-theme &&
code --install-extension ricardo-emerson.create-react-tsx-component &&
code --install-extension ritwickdey.LiveServer &&
code --install-extension rocketseat.rocketseatreactjs &&
code --install-extension rocketseat.rocketseatreactnative &&
code --install-extension rocketseat.theme-omni &&
code --install-extension tht13.html-preview-vscode &&
code --install-extension dracula-theme.theme-dracula &&
code --install-extension formulahendry.code-runner

## Configurando o Visual Studio Code

# Settings.json mude as configurações para :

{
"workbench.startupEditor": "none",
"workbench.colorTheme": "Omni",
"workbench.iconTheme": "material-icon-theme",
// Good for Recording
"editor.quickSuggestions": false,
"editor.mouseWheelZoom": true,
"editor.renderLineHighlight": "gutter",
"breadcrumbs.enabled": true,
"explorer.compactFolders": false,
// Window settings
"window.zoomLevel": 1,
"window.titleBarStyle": "native", // "native" on Linux, "custom" on Windows
"window.menuBarVisibility": "toggle",
// Disable JS auto-import behavior
"javascript.updateImportsOnFileMove.enabled": "never",
// Editor Behavior
"editor.selectionClipboard": false, // Only for Linux
"javascript.suggest.autoImports": false,
"editor.formatOnSave": true,
"editor.suggestSelection": "first",
"editor.codeActionsOnSave": {
"source.fixAll.eslint": true
},
// Explorer Behavior
"explorer.confirmDragAndDrop": false,
"explorer.confirmDelete": false,
// Sets the Font size and family
"editor.fontFamily": "JetBrains Mono",
"editor.fontWeight": "400",
"editor.fontSize": 15,
"editor.lineHeight": 24,
"editor.fontLigatures": true,
// Editor indentation settings
"editor.tabSize": 2,
"editor.insertSpaces": true,
"editor.detectIndentation": true,
// Auto applies editor rules for long lines of code
"editor.rulers": [80, 120],
// Increases terminal font size
"terminal.integrated.fontSize": 14,
// ESLint configuration
"eslint.packageManager": "yarn",
"eslint.codeActionsOnSave.mode": "all",
"prettier.singleQuote": true,
"prettier.trailingComma": "es5",
"eslint.validate": [
"javascript",
"javascriptreact",
"typescript",
"typescriptreact"
],
// Emmet
"emmet.syntaxProfiles": {
"javascript": "jsx" // Defines auto closing tags in JSX
},
"emmet.includeLanguages": {
"javascript": "javascriptreact"
},
// Git settings
"git.enableSmartCommit": true,
"git.autofetch": true,
"git.confirmSync": false,
// Extensions
"extensions.ignoreRecommendations": false, // Do not ignore recommendations
// Colorize settings
"colorize.languages": ["javascript", "typescript", "json", "html", "css"],
// Peacock colors (customizable)
"peacock.favoriteColors": [
{
"name": "Rocketseat Purple",
"value": "#7159C1"
},
{
"name": "Dracula Dark",
"value": "#0B0A10"
}
],
// Pretier settings
"[json]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[javascript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[html]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[yaml]": {
"editor.defaultFormatter": "dbaeumer.vscode-eslint"
},
"[typescriptreact]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[typescript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
}
}
