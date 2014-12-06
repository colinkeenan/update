update
======

This simplistic package is meant to be used as a way to launch, with a mouse-click, a system-wide update of Arch Linux in a terminal.

To use it as intended, after installation, you should add it to a launcher. For example, in Xfce, you could

1. right-click on a panel and choose 'Panel -> Add New Items'
1. click 'Launcher', then 'Add'
1. click 'Close'
1. right-click the question-mark now showing on the panel, and choose 'Properties'
1. click '+'
1. type 'update' into the search box
1. choose 'Update System'
1. click 'Close'

Now, instead of a question mark, you will see an icon for updating system packages. When clicked, it will open the terminal, ask for your sudo password, and update the system using 'yaourt -Syua'. If there are any pacnew files, it will prompt for what to do with them using 'yaourt -C'.
