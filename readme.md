#Better Lua

## Highlighting Example

![Table nesting example (Obsidian III)](https://raw.githubusercontent.com/Xuerian/Sublime-BetterLua/master/obsidian_table_examples.png)

## New scopes for theme usage

* variable.object - [Primary] Table being accessed
* variable.object.nested - Interim tables being accessed
* variable.language.self
* meta.call.method
* meta.call.function

Scope names may change if I find they should be something else. 


## Included theme

Includes a variant of Obsidian supporting some of these scopes. Any theme you wish to use must support these scopes for you to see any of the new highlighting. tmLanguage files are fairly simple to edit.

## Installation

1. Clone or unzip into Data/Packages/BetterLua
* (Optionally) select Color Scheme -> BetterLua -> Obsidian III

## Building BetterLua.tmLanguage yourself

1. Install [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev)
* Make changes to BetterLua.YAML-tmLanguage
* Build plist (.tmLanguage) with Ctrl-B

## See also

* https://github.com/rorydriscoll/LuaSublime
* https://github.com/minism/SublimeLove
* https://github.com/jfromaniello/Grandson-of-Obsidian
