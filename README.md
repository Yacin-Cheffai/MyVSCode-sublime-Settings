{
    "workbench.colorCustomizations": { 
        "statusBar.background" : "#1A1A1A", 
        "statusBar.noFolderBackground" : "#212121", 
        "statusBar.debuggingBackground": "#263238"
    },
    "files.autoSave": "onFocusChange",
    "breadcrumbs.enabled": true,
    "window.menuBarVisibility": "default",
    "editor.minimap.enabled": false,
    "editor.quickSuggestions": {
        "other": false,
        "comments": false,
        "strings": false
    },
    "workbench.statusBar.feedback.visible": false,
    "python.pythonPath": "/usr/bin/python3",
    "terminal.integrated.rendererType": "dom",
    "python.linting.pep8Enabled": true,
    "explorer.decorations.badges": false,
    "explorer.decorations.colors": false,
    "editor.snippetSuggestions": "none",
    "editor.suggestOnTriggerCharacters": false,
    "editor.wordBasedSuggestions": false,
    "workbench.editor.enablePreview": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "window.titleBarStyle": "custom",
    "editor.parameterHints.enabled": false
}


____________________________________________________________________________
sublime keybinding

[
	{"keys": ["ctrl+alt+m"], "command": "toggle_menu"},
    { "keys": ["ctrl+:"], "command": "toggle_comment", "args": { "block": false } },

]


settings

{
	"auto_complete": false,
	"color_scheme": "Packages/ayu/ayu-dark.sublime-color-scheme",
	"ignored_packages":
	[
		"Vintage"
	],
	"save_on_focus_lost": true,
	"show_definitions": false,
	"theme": "ayu-dark.sublime-theme",
	"translate_tabs_to_spaces": true,
	"tab_completion": true,
	"shift_tab_unindent": true,
}


_______________________________________________________________________
i3


focus_follows_mouse no
for_window [class="^.*"] border pixel 3
