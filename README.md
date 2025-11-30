Best way to install is just to clone the repo into your ~/.vscode/extensions folder.

1. Clone repo:
```
git clone git@github.com:jrohlandt/vscode-rainyday-color-theme.git rainyday-color-theme-0.0.1
```

2. Open VSCode and use Preferences: Color Theme command to see if theme is available.

3. If not available check if it is listed in ~/.vscode/extensions/.obsolete.
4. If marked as obsolete. Edit .obsolete to remove rainyday from the file.
5. Next manually add entry into ~/.vscode/extensions/extensions.json
```
  {
    "identifier": {
      "id": "jrohlandt.rainyday"
    },
    "version": "0.0.1",
    "location": {
      "$mid": 1,
      "path": "/Users/youruser/.vscode/extensions/rainyday-color-theme-0.0.1",
      "scheme": "file"
    },
    "relativeLocation": "rainyday-color-theme-0.0.1"
  },
```

## Old instructions
1. To use download and unzip (or clone repo).

2. Check package.json for version number and then append version number to folder name.
E.g. vscode-rainyday-color-theme-0.0.1

3.
Copy folder to:
on Windows %USERPROFILE%\.vscode\extensions
OR 
on Mac/Linux $HOME/.vscode/extensions

4. 
Then in VScode look for rainyday color-theme