{
  "workbench.colorTheme": "Ayu Dark",
  "editor.minimap.enabled": false,
  "explorer.openEditors.visible": 0,
  "breadcrumbs.icons": false,
  "workbench.editor.enablePreview": false,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.editor.showIcons": false,
  "breadcrumbs.enabled": false,
  "files.autoSave": "onFocusChange",
  "editor.renderLineHighlight": "none",
  "javascript.suggest.enabled": false,
  "javascript.suggest.includeAutomaticOptionalChainCompletions": false,
  "typescript.suggest.enabled": false,
  "typescript.suggest.includeAutomaticOptionalChainCompletions": false,
  "python.autoComplete.showAdvancedMembers": false,
  "editor.quickSuggestions": {
    "other": false,
    "comments": false,
    "strings": false
  },
  "editor.parameterHints.enabled": false,
  "typescript.suggest.completeJSDocs": false,
  "typescript.suggest.paths": false,
  "editor.hover.enabled": false,
  "workbench.iconTheme": "file-icons-colourless",
  "explorer.decorations.badges": false,
  "outline.icons": false,
  "workbench.activityBar.visible": true,
  "problems.decorations.enabled": false,
  "problems.autoReveal": false,
  "workbench.colorCustomizations": {
    "editorError.foreground": "#00000000",
    "editorWarning.foreground": "#00000000",
    "editorInfo.foreground": "#00000000"
  },
  "[python]": {
    "editor.defaultFormatter": "ms-python.python"
  },
  "editor.formatOnSave": true,
  // "diffEditor.renderSideBySide": false, //dont' know what this does
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "editor.snippetSuggestions": "none",
  "editor.suggestOnTriggerCharacters": false,
  "javascript.validate.enable": false,
  "editor.lightbulb.enabled": false,
  "diffEditor.ignoreTrimWhitespace": true,
  "editor.renderWhitespace": "none",
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
