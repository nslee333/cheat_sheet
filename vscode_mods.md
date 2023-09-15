This setting allows me to highlight a word, with alt + right or left arrow, move horizontally with other words on the line.
	- similar to alt + up or down to move line up or down.
	Keybindings.json [
	[
	    {
	        "key": "alt+left",
	        "command": "editor.action.moveCarretLeftAction",
	        "when": "editorFocus && editorHasSelection || editorHasMultipleSelections "
	    },
	    {
	        "key": "alt+right",
	        "command": "editor.action.moveCarretRightAction",
	        "when": "editorFocus && editorHasSelection || editorHasMultipleSelections"
	    }
	]
	]


Editor: Suggest On Trigger Characters: FALSE
	- Set because I was tired of accepting suggestions on '.' key press.


"editor.acceptSuggestionOnCommitCharacter": false,
    "editor.acceptSuggestionOnEnter": "off",

