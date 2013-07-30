# JS to Coffee plugin for Sublime Text 3

Converts files, selection and clipboard content from Javascript to Coffee using js2coffee

## Installation

### [Sublime Package Control](http://wbond.net/sublime_packages/package_control)

In the command Pallette choose **Package Control: Install Repository** and select **JS2Coffee for 2 && 3**

### Git installation

Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/anderson916/sublime-js-to-coffee.git "Js2Coffee"

The "Packages" directory is located at:

* OS X:

        ~/Library/Application Support/Sublime Text 3/Packages/

* Linux:

        ~/.config/sublime-text-3/Packages/

* Windows:

        %APPDATA%/Sublime Text 3/Packages/

## Usage

* **Convert whole javascript file** `Shift+Alt+F` - creates new file in the same folder using the same name as the source ending with '.js'.
* **Convert selection** `Shift+Alt+S` - replaces selection of javascript with JADECoffee content.
* **Convert clipboard content** `Shift+Alt+V` - inserts Coffee of converted clipboard javascript content.

### In Command Palette:

* **JS2Coffee: Convert file**
* **JS2Coffee: Convert selection**
* **JS2Coffee: Convert clipboard content**

## Sublime Text 2

Follow the instruction from [Sublime Text 2 branch](https://github.com/anderson916/sublime-js-to-coffee/tree/SublimeText2)
