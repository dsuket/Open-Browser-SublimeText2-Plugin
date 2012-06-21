#Search anywear for the currently selected text.

This package adds the ability to open any doc using text selection for [Sublime Text 2][1].

##Install

If your using the [Sublime Package Manger][2] hold down Ctrl+shift+p and type
`Package Control: Install Package`. Then search for `open browser` and hit return.

If your not using the package manager  you can download the package as a zip file [https://bitbucket.org/nwjlyons/google-search/get/tip.zip][3] then copy it into your Sublime packages directory.

##Usage

First thing you have to do is to set up some key binding in your user key binging file, for instance : 
	
	{ "keys": ["ctrl+alt+g"], "command": "open_browser", "args" : {"url" : "http://google.fr/?q=%s"}},
	{ "keys": ["ctrl+alt+w"], "command": "open_browser", "args" : {"url" : "http://codex.wordpress.org/Function_Reference/%s"}},
	{ "keys": ["ctrl+alt+c"], "command": "open_browser", "args" : {"url" : "http://api20.cakephp.org/search/%s"}},
	{ "keys": ["ctrl+alt+h"], "command": "open_browser", "args" : {"url" : "http://fr.php.net/manual-lookup.php?pattern=%s"}},

###Other Examples

You can also open cheat sheet.

	{ "keys": ["super+shift+/"], "command": "open_browser",
	 "args" : {"url" : "http://docs.sublimetext.info/en/latest/reference/keyboard_shortcuts_win.html"}},

To use the command select some text, use your key binding and have fun !