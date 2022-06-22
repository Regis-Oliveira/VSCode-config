# VSCode-config
My personal config

#Keybindings.json

[
  { "key": "shift+alt+down",   "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus" },
  { "key": "shift+alt+up",     "command": "editor.action.copyLinesUpAction",
    "when": "editorTextFocus" },
]

#Settings.json

{    
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.lineHeight": 26,
    "editor.semanticHighlighting.enabled": false,
    "editor.tabSize" : 2,

    "workbench.colorTheme": "Dracula Pro",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",

    "explorer.compactFolders": false,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,

    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",

    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,

    "editor.rulers": [80, 120],
        
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },

    "[prisma]" : {
        "editor.formatOnSave" : true
    },
    
    "material-icon-theme.activeIconPack" : "nest",

    "emmet.syntaxProfiles": { "javascript": "jsx" },
    "emmet.includeLanguages": { "javascript": "javascriptreact" },

    "javascript.suggest.autoImports": true,
    "typescript.suggest.autoImports": true,
}
