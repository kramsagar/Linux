Editors
1.	Implement some playbooks
2.	Terraform manifest files
3.	Edit existing configuration files
Editors for editing files.
Some examples editors ->
1.	Vscode
2.	Nano  - Debian OS
3.	Vieditor, vim editor – redhat default editors
Vi having 3 types of modes:
1.	Command line mode
2.	Insert mode / edit mode
3.	Exit mode

VIM having 4 types of modes:
1.	Command line:
a.	To open the file -> vim file.txt
b.	Copy the line
i.	yy
ii.	5yy – 5 lines to copy
c.	Copy the word
i.	yw
d.	Delete the line
i.	dd
ii.	5dd – 5 lines
e.	Delete the word
i.	dw – delete a word 
f.	Paste copied content
i.	p
ii.	5p – paste 5 times copied content
g.	Save changes
i.	Shift + zz – to save changes
h.	Find a string inside a file
i.	/<string>
i.	Undo changes
i.	u – undo changes
2.	Insert mode
a.	I – to move to insert mode
b.	I (capital I) – to move to beginning of the line and also into insert mode
c.	A – come into inert and go to end of the line
d.	Esc to exit from insert mode
3.	Advance command line mode
a.	Set line numbers
i.	:set nu
b.	Remove lines numbers
i.	:set nonu
c.	Copy the lines
i.	:1,5co20 – copy 1 to 5the lines and copy at 20th line
d.	Move the line + more lines
i.	One to 5 files to move 15th line
:1,5m15
e.	Save changes
i.	:w - save
f.	Quit from file
i.	:q
g.	Save and exit from the file
i.	:wq
h.	Override the file
i.	:wq! Override the file
4.	Visual mode
Inside config file I have 100 lines.
I want to 50 lines to comment them, then ?
To comment multiple lines in a file:
a.	Ctls + v -> to end into visua mode
b.	Shift + up and down  shift + I   add # to comment -> press esc 

