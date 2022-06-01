NewtonScript Module for BBEdit
====

A [BBEdit](http://www.barebones.com/products/bbedit/) [Codeless Language Module](http://www.barebones.com/support/develop/clm.html) for the NewtonScript language.
Keywords & functions sourced from [The NewtonScript Programming Language](https://www.newted.org/download/manuals/NewtonScriptProgramLanguage.pdf) 1996, Apple Computer, Inc.

SUPPORTS
----

* Single & multi-line comments
* Strings
* Numbers
* Keywords
* Code folding
* Function popup

Nested begin/end blocks do not fold -- this is also the behaviour of BareBones’ sample Pascal codeless language module (CLM).
Frames/arrays do not fold.
But functions in frame slots or assigned to a variable do appear in the editor’s function popup menu.

INSTALLATION
----

Copy the NewtonScript.plist file to ~Library/Application Support/BBEdit/Language Modules/. Quit and relaunch BBEdit for the module to take effect.
