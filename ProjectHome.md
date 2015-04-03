A couple plugins I wrote for Notepad++

Python Indent: An auto-indenter for Python. It looks for one of the appropriate keywords at the start of the line and indents one level in on the next line.

Tab Indent, Space Align: A plugin to provide support for using tabs for indent and spaces for alignment. It does a couple things. First, when you insert a new line it will exactly copy the preceding indent, instead of turning tabs to spaces or vice-versa. Second, if you insert a tab anywhere in the indentation part of a line (which is considered to be from the beginning of the line to the first non-tab) it will insert a tab, otherwise it will insert spaces. (For multiple lines, tab is always inserted)