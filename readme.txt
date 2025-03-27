GODOT DOCS: https://docs.godotengine.org/en/stable/


NAMING CONVENTIONS:
	Most things should be snake_case like files, variables, and function names.
	Other things like classes and Node names should be PascalCase.

TODO:
	1) Make mushroom_boy move. Use mushroom_boy.gd (the script file) to manipulate the mushroom boy scene in
		mushroom_boy.tscn. 
	2) Once he can move, put him in maple_tree.tscn and try to make the portal functional to move him to 
		next_bg.tscn. I already added portal.tscn to both scenes.
		You'll likely use signals to do this so look that up in the docs
	3) Play around more if you want

TL;DR

Everything in Godot is nodes and scenes. For example Henny in Maple is a scene. But a player is also a scene that
handles input, nested in the henny scene which handles the background stuff.
