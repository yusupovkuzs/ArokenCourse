Exstensions:
  CSS Peek
  eCSStractor for VSCode
  Gist
  HTML to CSS autocompletion
  IntelliSense for CSS class names in HTML
  Live Server

settings.json
{
    "workbench.startupEditor": "none",
    "workbench.colorTheme": "One Monokai 80s",
    "editor.guides.bracketPairs": true,
    "workbench.iconTheme": "vscode-icons",
    "htmltagwrap.tag": "div",
    "editor.smoothScrolling": true,
    "editor.fontSize": 15,
    "editor.minimap.enabled": false,
    "breadcrumbs.enabled": false,
    "editor.tabSize": 2,
    "explorer.confirmDelete": false,
    "editor.detectIndentation": false,
    "editor.glyphMargin": false,
    "editor.parameterHints.enabled": false,
    "editor.hover.enabled": false,
    "terminal.integrated.fontSize": 15,
    "editor.renderWhitespace": "boundary",
    "editor.lineHeight": 23,
    "security.workspace.trust.enabled": false,
    "editor.linkedEditing": true,
    "ecsstractor_port.add_comment": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
    "emmet.extensionsPath": [ "~/AppData/Roaming/Code/User/emmet" ],
}

keyboards.json
[
  {
    "key": "ctrl+alt+c",
    "command": "extension.ecsstractor_port_run"
  }
]

snippets.json
{
	"html": {
		"snippets": {
			"d": "<div class=\"${1}\">${2}</div>",
			"i": "<img class=\"${1}\" src=\"${2}\" alt=\"${3}\">"
		}
	}
}
