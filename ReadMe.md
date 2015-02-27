NewtonScript Module for TextWrangler
====

by Simon Bell <simon@newtonresearch.org>

A [TextWrangler](http://http://www.barebones.com/products/textwrangler/) [Codeless Language Module](http://www.barebones.com/support/develop/clm.html) for the NewtonScript language.
Keywords & functions sourced from [The NewtonScript Programming Language](http://manuals.info.apple.com/en_US/NewtonScriptProgramLanguage.PDF) 1996, Apple Computer, Inc.

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

Copy the NewtonScript.plist file to ~Library/Application Support/TextWrangler/Language Modules/. Quit and relaunch TextWrangler for the module to take effect.
