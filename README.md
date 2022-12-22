# README


## Table of contents

- [Motivations](#motivations)
- [Project description](#description)
- [Visuals](#visuals)
- [Instructions](#instructions)
- [Files](#files)
- [Credits](#credits)
- [License](#license)
- [Status](#status)


## Motivations <a name="motivations"></a>

This idea of a theme came to me because I'm a Ravenclaw and wanted a new VSCode theme using the Ravenclaw palette.


## Project description <a name="description"></a>

This project contains the necessary files to create a VSCode Extension called "Ravenclaw" that is rewamping the VSCode colours.

## Visuals <a name="visuals"></a>

![image](https://user-images.githubusercontent.com/29840762/209167148-35b54add-676b-408d-8a68-3f23de89c6fa.png)


## Instructions <a name="instructions"></a>

### Install using Command Palette

1. Go to View -> Command Palette or press Ctrl+Shift+P
2. Then enter Install Extension
3. Write *Ravenclaw*
4. Select it or press Enter to install

### Install using Git
If you are a git user, you can install the theme and keep up to date by cloning the repo:

```console
git clone https:/https://github.com/jmballard/ravenclaw-theme.git ~/.vscode/extensions/ravenclaw
cd ~/.vscode/extensions/ravenclaw
npm install
npm run build
```

### Activating theme
Run Visual Studio Code. The Ravenclaw Theme will be available from File -> Preferences -> Color Theme dropdown menu.

## Files <a name="files"></a>

Here is the content of this repo:

```text
- .vscode
|- launch.json

- themes
|- Ravenclaw-color-theme.json

- .gitattributes
- .gitignore
- .vscodeignore
- CHANGELOG.md
- LICENSE
- package.json
- README.md

```


## Credits <a name="credits"></a>

To update the colours, please use

- [color-hex website](https://www.color-hex.com/) for the colours you want to use. The Ravenclaw palette used was from there.
- [VSCode refs](https://code.visualstudio.com/api/references/theme-color) for the list of references to use to update VSCode's themes
 

## License <a name="license"></a>

MIT License

Copyright (c) [2022] [Julie Ballard]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Project status  <a name="status"></a>

This theme is at its first version. Happy to get any feedback on any upgrade that could be added to it.
