# Better Comments

The Better Comments extension will help you create more human-friendly comments in your code.  
With this extension, you will be able to categorize your annotations into:
* Alerts
* Queries
* TODOs
* Highlights
* Commented out code can also be styled to make it clear the code shouldn't be there
* Any other comment styles you'd like can be specified in the settings

![Annotated code](images/better-comments.PNG)

## Configuration

This extension can be configured in User Settings or Workspace settings.

`"better-comments.multilineComments": true`  
 This setting will control whether multiline comments are styled using the annotation tags.
 When false, multiline comments will be presented without decoration.

`"better-comments.highlightPlainText": false`  
This setting will control whether comments in a plain text file are styled using the annotation tags.
When true, the tags (defaults: `! * ? //`) will be detected if they're the first character on a line.

`better-comments.tags`  
The tags are the characters or sequences used to mark a comment for decoration.
The default 5 can be modified to change the colors, and more can be added.

```json
"better-comments.tags": [
  {
    "tag": "!",
    "color": "#FF2D00",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "?",
    "color": "#3498DB",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "//",
    "color": "#474747",
    "strikethrough": true,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "todo",
    "color": "#FF8C00",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "*",
    "color": "#98C379",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  }
]
```

## Supported Languages

* Ada
* Auto Hot Key
* AL
* Alloy
* Apex
* AsciiDoc
* BrightScript
* C
* C#
* C++
* ColdFusion
* Clojure
* COBOL
* CoffeeScript
* CSON
* CSS
* Dafny
* Dart
* Dockerfile
* Elixir
* Elm
* Erlang
* F#
* Fortran
* GAS x86/x86_64/AMD64 assembly _(at&t/GNU syntax)_
* gdscript
* GenStat
* git config
* gitignore
* Go
* GraphQL
* Groovy
* Haskell
* Haxe
* HiveQL
* HTML
* Java
* JavaScript
* JavaScript React
* JSON with comments
* Julia
* Kotlin
* LaTeX (inlc. BibTeX/BibLaTeX & plain TeX)
* Less
* Lisp
* Lua
* Makefile
* Markdown
* MATLAB
* NASM/YASM x86/x86_64/AMD64 assembly _(intel syntax) [asm]_
* Nim
* Objective-C
* Objective-C++
* Pascal
* Perl
* Perl 6
* PHP
* Pig
* PlantUML
* PL/SQL
* PowerShell
* Promela
* Puppet
* Python
* R
* Racket
* Rainmeter _(win10 desktop widget config file [modified ini])_
* Ruby
* Rust
* SAS
* Sass
* Scala
* SCSS
* ShaderLab
* ShellScript
* SQL
* STATA
* Stylus
* Swift
* Tcl
* Terraform
* TOML
* Twig
* TypeScript
* TypeScript React
* Verilog
* Visual Basic
* Vue.js
* XML
* YAML
