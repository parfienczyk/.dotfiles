File `.vscode/settings.json` in VSC

```
{
  "window.zoomLevel": 0,
  "window.title": "${dirty} ${activeEditorMedium}${separator}${rootName}",
  "editor.fontFamily": "FiraCode-Retina",
  "editor.fontLigatures": true,
  "editor.rulers": [80, 120],
  "editor.fontSize": 14,
  "editor.lineHeight": 25,
  "editor.letterSpacing": 0.5,
  "workbench.editor.tabSizing": "shrink",
  "workbench.fontAliasing": "default",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "[javascript]": {
    "editor.fontLigatures": "'ss02', 'ss19'"
  },
  "editor.snippetSuggestions": "top",
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "typescript",
      "autoFix": true
    },
    {
      "language": "typescriptreact",
      "autoFix": true
    }
  ]
}
```
