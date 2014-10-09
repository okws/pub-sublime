##Installation

Clone this git repo in Sublime Text's `Packages` directory.

### Mac OS X

```
~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
```

### Windows

```
%APPDATA%/Sublime Text 2/Packages/
```


##Editing `.tmLanguage` files

Don't ever edit the `.tmLanguage` files directly. Instead, edit the `.json`
files and convert them to `.tmLanguage.`

To convert files, use <a href="https://sublime.wbond.net/">Package Control</a>
to install `AAAPackageDev`. When you've edited the `.json` file and are ready
to test your changes, run the `AAAPackageDev: Convert (YAML, JSON, Plist to...`
which will validate your `.json` file and overwite the old `.tmLanguage.`

##Screenshots

Autocomplete and commenting:

<img src="https://dl.dropbox.com/u/22817005/Resources/sublime/Github/features.png" />

Function navigation:

<img src="https://dl.dropbox.com/u/22817005/Resources/sublime/Github/functionnav.png" />

Pub and html:

<img src="https://dl.dropbox.com/u/22817005/Resources/sublime/Github/pubhtml.png" />

If you want the colorscheme, you can grab that here: <a href="http://github.com/andrewfiorillo/Cupid">http://github.com/andrewfiorillo/Cupid</a>
