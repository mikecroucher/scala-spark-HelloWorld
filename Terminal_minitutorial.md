# Basic use of the command line

Learning to use the command line is essential for advanced programming, but it can also
improve your day to day tasks.
You can access your entire computer via the command line and do everything you can normally do
using the Graphical User Interface... and more.

This (mini)tutorial will guide you through the very basics of using
the command line.

When you launch a terminal, the default path/location is your home directory, however
if at any point you are unsure which folder you are "in" (which is your working
directory) you only need to type the command `pwd`.

## Understanding the syntax
When you open the terminal you might see something similar to: **username@computer ~ $**

## Listing the Directory contents
If within a directory you want to see its content you can use the `ls` command.

If you need more detailed information on the contents (e.g. access permissions,
date the file was last modified, etc.) you can use the command `ls -l`.

## Moving across directories
To change your working directory you need to use the `cd` command, followed by the *pathname* of the directory you want to move into e.g
`cd /HelloWorld/src/`

If you do not specify a pathname and just type `cd`, ut will take you back to your home directory.
