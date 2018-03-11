# atom_package_list

To print the list of your current packages run:

apm list --installed --bare > packages.list

This will create a fiel called packages.list that includes all your existing packages.

To restore it us this line:

apm install `cat packages.list`

This works only to backup your packages and not your settings.
The ~/.atom folder will include .json, .cson .coffee and a .less fiel that represent your config files.

