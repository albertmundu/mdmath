# ![mdmath](img/icon.png) mdmath

**mdmath** allows to use *Visual Studio Code* as a markdown editor capable of typesetting and rendering TeX math.
In fact it functions and renders identically to the build in markdown viewer. Additionally KaTeX works as fast math renderer.

![mdmath editing](img/edit.gif)

## Features
Simplify the process of authoring and live previewing markdown documents containing math formulas.
This extension is a comfortable tool for scientists, engineers and students with markdown as their first choice 
document format.

* Inline math by `$ ... $`
* Display math by `$$ ... $$`
* Inline math with tables
* Embedded HTML
* Syntax highlighting with code sections
* Export resulting HTML code for web usage

## Installation ...

### ... from inside of VSCode

Press <kbd>F1</kbd> key inside of *Visual Studio Code* and type `extension`. Choose `Extensions: Install Extension` 
and then select the `Markdown+Math` extension from the list.

### ... from Mac & Linux Command Line
```
cd $HOME/.vscode/extensions
git clone https://github.com/goessner/mdmath.git
cd mdmath
npm install
```

### ... from Windows Command Line
```
cd  %USERPROFILE%\.vscode\extensions
git clone https://github.com/goessner/mdmath.git
cd mdmath
npm install
```

## Usage

* Launch *VS Code*, create or open a markdown file (`.md`).
* Press <kbd>Ctrl+Shift+.</kbd> to open a preview window side by side, or ...
* .. alternatively press <kbd>Ctrl+Shift+P</kbd> and run the command `Markdown+Math` to achive the same.
* Typeset in your markdown source window and see the preview window live updating.
* Press <kbd>Ctrl+Shift+P</kbd> and run the command `Markdown+Math as HTML` to open an output window for 
  viewing and possibly copying the corresponding HTML source.

![mdmath html export](img/htmlExport.png)

>**Note**: Attempt to show HTML output with *Preview Window* as *Active Window* results in a warning `Cannot show source of that document!`. Make your your markdown source window *active* first.


## Dependencies

* [markdown-it](https://github.com/markdown-it/markdown-it)
* [markdown-it-katex](https://github.com/waylonflinn/markdown-it-katex)
* [highlight.js](https://github.com/isagalaev/highlight.js)

## Issues, Hints and Wishes

* VS Code is a great piece of software from Microsoft. It is based on [Electron](http://electron.atom.io/). Maybe someday TeX math within Markdown is supported without extensions.
* In order to create `*.pdf` output from your Markdown you should consider using [Pandoc](http://pandoc.org/).
* Opening multiple preview windows is not possible at current. Even changing the active markdown source window doesn't update the
preview window properly. Close the preview window first as a workaround here.

## Contributing

See [contributing.md](contributing.md)

## ChangeLog

* November 25, 2016
  * First Release 0.8.0

## License

*Markdown+Math* for VS Code is licensed under the [MIT License](http://opensource.org/licenses/MIT)

 © [Stefan Gössner](https://github.com/goessner)
