# atom
這邊整理了一些我自己有在使用的 packages

## 目錄

- [Syntax](#syntax)
- [Lint](#lint)
- [Themes](#themes)
- [AutoComplete](#autocomplete)
    - [autocomplete-modules](#autocomplete-modules)
    - [autocomplete-paths](#autocomplete-paths)
    - [autocomplete-php](#autocomplete-php)
    - [autocomplete-sass](#autocomplete-sass)
- [Uncategorized](#uncategorized)
    - [atom-beautify](#atom-beautify)
    - [atom-import-sort](#atom-import-sort)
    - [atom-update-packages](#atom-update-packages)
    - [autoclose-html](#autoclose-html)
    - [cht-menu](#cht-menu)
    - [color-picker](#color-picker)
    - [docblockr](#docblockr)
    - [editorconfig](#editorconfig)
    - [Emmet](#emmet)

## Syntax

- [atom-jinja2](https://atom.io/packages/atom-jinja2)
- [atom-json-color](https://atom.io/packages/atom-json-color)


#### [atom-json-color](https://atom.io/packages/atom-json-color)
> 必須說，在 atom 裡面編輯 json 真的是很折磨人的事情，因為他的 color scheme 真的有等於沒有，這個解救了我 XD

Color a JSON in Atom Editor with a color per level
(If you are using a light theme, you can go to the package setting and check "LightTheme" then restart Atom or Ctrl-Alt-R to reload the window.)

With the plugin :)

![atom-json-color-with](https://cloud.githubusercontent.com/assets/8104134/13286515/3763bc2a-db02-11e5-8f24-060648002bd6.png)

Without the plugin :(

![atom-json-color-without](https://cloud.githubusercontent.com/assets/8104134/13286516/37671a78-db02-11e5-9c0a-6e0a96130d14.png)

## Lint

## Themes

## AutoComplete
#### [autocomplete-modules](https://atom.io/packages/autocomplete-modules)
> 也會讀取你的 webpack 設定，很方便喔。

Autocomplete for require/import statements.

![Preview](https://cloud.githubusercontent.com/assets/3505878/7442538/9c1892cc-f11e-11e4-8070-3fa8b79beefc.gif)

#### [autocomplete-paths](https://atom.io/packages/autocomplete-paths)
> 自動補完路徑

Adds path autocompletion to autocomplete+

![autocomplete-paths](http://s1.directupload.net/images/140411/p5kvife6.gif)

#### [autocomplete-php](https://atom.io/packages/autocomplete-php)
An Atom PHP autocompleter for `autocomplete-plus`

**Now it is mandatory to have PHP in the environment PATH**

Beta version.

![Demo](https://raw.github.com/Azakur4/autocomplete-php/master/assets/img/demo.gif)

#### [autocomplete-sass](https://atom.io/packages/autocomplete-sass)
CSS property name and value autocompletions for SASS in Atom. Install
[autocomplete-plus](https://github.com/atom/autocomplete-plus) before
installing this package.

This is powered by the list of CSS property and values [here](https://github.com/adobe/brackets/blob/master/src/extensions/default/CSSCodeHints/CSSProperties.json)

![autocomplete-sass](http://i.imgur.com/1vB8Bdu.gif)

You can update the prebuilt list of property names and values by running
the `update.coffee` file at the root of the repository and then checking in
the changed `properties.json` file.

## Uncategorized

#### [atom-beautify](https://atom.io/packages/atom-beautify)
> Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom

| Before | After |
| --- | ---- |
| Original HTML | Beautified HTML |
| ![image](https://cloud.githubusercontent.com/assets/1885333/16542727/db52adc6-408a-11e6-824e-04aed06bd2f7.png) | ![image](https://cloud.githubusercontent.com/assets/1885333/16542728/dcac3700-408a-11e6-8e35-9c8fc4432edc.png) |

#### [atom-import-sort](https://atom.io/packages/atom-import-sort)
> 寫 ES6 時很喜歡這個 package，但會把 comment 當成獨立的去 sort 比較困擾一點，另外就是 `import * as XXX from 'packages'` 這個也會被錯誤排序。

Sort ES6 imports. Manually – or automatically when you save your Javascript files.

![Screencast](https://github.com/renke/atom-import-sort/blob/master/media/atom-import-sort.gif?raw=true)

This package does **not** sort `require` calls. Only ES6-style imports are supported as of now. Support for `require` may be added later, but it's generally harder to do this compared to imports.

#### [atom-update-packages](#atom-update-packages)
> 自動幫你升級 packages 不用每次 apm update 或者到設定去升級

Keep your Atom packages up to date.

![Screenshot](https://f.cloud.github.com/assets/83656/2521579/c30d4b2a-b4ac-11e3-898a-5c763e9a1c5a.png)

#### [autoclose-html](#autoclose-html)
> 自動關閉 html tag

#### [cht-menu](https://atom.io/packages/cht-menu)
> 對於介面感覺看英文有痛苦的，可以裝。
![](https://raw.githubusercontent.com/Sheng-Bo/atom-cht-menu/master/screenshot/02.jpg)

#### [color-picker](https://atom.io/packages/color-picker)
![Color Picker in action](https://github.com/thomaslindstrom/color-picker/raw/master/preview.gif)

#### [docblockr](https://atom.io/packages/docblockr)
> 幫你產生 doc block 很方便的工具

#### [editorconfig](https://atom.io/packages/editorconfig)
[EditorConfig](http://editorconfig.org) helps developers maintain consistent coding styles between different editors

![](https://f.cloud.github.com/assets/170270/2327994/dfe40cb4-a3f6-11e3-862f-894999973373.png)

#### [Emmet](https://atom.io/packages/emmet)
[Emmet](http://emmet.io) support for [Atom](http://atom.io).
