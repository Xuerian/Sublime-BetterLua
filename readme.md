Better Lua
====

New scopes for themes
----
Provides new scopes for themes to support:
* variable.object - [Primary] Table being accessed
* variable.object.nested - Interim tables being accessed
* variable.language.self
* meta.call.method
* meta.call.function

Scope names may change if I find they should be something else. 


Included theme
----
Includes a variant of Obsidian supporting some of these scopes. Any theme you wish to use must support these scopes for you to see any of the new highlighting. tmLanguage files are fairly simple to edit.

Installation
----
* Clone or unzip into Data/Packages/BetterLua
* (Optionally) select Color Scheme -> BetterLua -> Obsidian III

Building BetterLua.tmLanguage
----
* Install [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev)
* Make changes to BetterLua.YAML-tmLanguage
* Build plist (.tmLanguage) with Ctrl-B

See also
----
* https://github.com/rorydriscoll/LuaSublime
* https://github.com/minism/SublimeLove
* https://github.com/jfromaniello/Grandson-of-Obsidian
