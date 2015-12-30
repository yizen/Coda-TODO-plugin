# Coda-TODO-plugin
A sidebar plugin for the [Coda](https://panic.com/coda/) text editor from Panic that scans TODO and FIXME in the active document and display a clickable list on a new sidebar panel.

![](http://i.imgur.com/yvTlkIu.png)

# Installation

* Automatic install
Download the “TODOFIXME.codawebscriptsidebar” file, and double-click to let Coda install the plugin for you.

![](http://i.imgur.com/BDjIfTg.png)

* Manual install
Download the “TODOFIXME.codawebscriptsidebar” file, and move it to the Coda plugin folder, which is located at 
```/Users/{your user}/Library/Application Support/Coda 2/Plug-ins```

* Enabling the sidebar
Open the first tab of the sidebar, locate the TODO icon, right-click and choose “Add to sidebar dock”.

![](http://i.imgur.com/qSJdrb9.png) 

This will pin the icon as a new tab on the right.

![](http://i.imgur.com/fTobSke.png)

# How to use

The panel will scan each text document once you load it, select it on the file liste and thumbnail.

The plugin will parse NOTE, OPTIMIZE, TODO, HACK, XXX, FIXME, and BUG comments and display them in a list.

The icon will display F for FIXME, T for TODO etc., along with the source line number, and the actual comment.

![](http://i.imgur.com/yvTlkIu.png)

# Uninstalling 

Open the Coda Preferences panel, and click on the Plug-in tab. locate the TODO Sidebar panel, and click “Uninstall”

![](http://i.imgur.com/9u5DuYp.png)

# Thank you

A lot of code and inspiration has been borrowed from [John Postlethwait](https://github.com/JohnPostlethwait/fixme) FixMe node module.

