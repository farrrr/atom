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
    - [ex-mode](#ex-mode)
    - [expose](#expose)
    - [file-icons](#file-icons)
    - [tool-bar](#tool-bar)

## Syntax

- [atom-jinja2](https://atom.io/packages/atom-jinja2)
- [atom-json-color](https://atom.io/packages/atom-json-color)
- [language-babel](https://atom.io/packages/language-babel)
- [language-blade](https://atom.io/packages/language-blade)
- 


#### [atom-json-color](https://atom.io/packages/atom-json-color)
> 必須說，在 atom 裡面編輯 json 真的是很折磨人的事情，因為他的 color scheme 真的有等於沒有，這個解救了我 XD

Color a JSON in Atom Editor with a color per level
(If you are using a light theme, you can go to the package setting and check "LightTheme" then restart Atom or Ctrl-Alt-R to reload the window.)

With the plugin :)

![atom-json-color-with](https://cloud.githubusercontent.com/assets/8104134/13286515/3763bc2a-db02-11e5-8f24-060648002bd6.png)

Without the plugin :(

![atom-json-color-without](https://cloud.githubusercontent.com/assets/8104134/13286516/37671a78-db02-11e5-9c0a-6e0a96130d14.png)

## Lint
- [linter](https://atom.io/packages/linter)
- [linter-eslint](https://atom.io/packages/linter-eslint)

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

#### [ex-mode](https://atom.io/packages/ex-mode)
> Atom 的 vim-mode 的增強版

#### [expose](https://atom.io/packages/expose)
> 將你所有的 Tab 類似 OSX 的 Exposé 一樣展開

Quick tab overview of open files. Similar to Mac OSX Exposé / Mission Control, Firefox Tab Group, Safari and Chrome Tab Overview, etc.

* Shows active tab, panes and previews.
* The text editor preview is taken from [Minimap](https://github.com/atom-minimap/minimap) if present, else a suitable file icon is used.
* Shows file icons in tabs if the [file-icon package](https://github.com/DanBrooker/file-icons) is installed.

![expose-package](https://raw.githubusercontent.com/mrodalgaard/atom-expose/master/screenshots/preview.png)

#### [file-icons](https://atom.io/packages/file-icons)
> 依照檔案的種類，給予精美的 icon，必裝

Adds file specific icons to atom for improved visual grepping. Works with Tree View and Fuzzy Finder and Tabs.

![Screenshot](https://raw.githubusercontent.com/DanBrooker/file-icons/master/preview.png)

A number of icons and colours are provided by default for a range of common file types.
If you have file that you would like custom icons for you can easily add this yourself.

Icons are now specified via CSS (Less) only.

#### [fold-functions](https://atom.io/packages/fold-functions)
Folds functions within your code. Currently comes with a toggle, fold, and unfold option that will look for functions marked with 'meta.function'. Handy because it won't fold things like comments associated with functions.

![screenshot](http://robballou.com/i/fold.gif)

*Note: this currently folds only those functions it finds at a single indentation (e.g. it will fold the top level functions)*

Heavily inspired/influnced by [Fold Comments](https://atom.io/packages/fold-comments).

#### [atom-git-control](https://atom.io/packages/git-control)
Provides a GUI interface to manage all commonly-used git commands.

This is a first-release, while tested as part of creating this package, it has not been extensively used on much larger projects. In short: there are possibly still some issues remaining. At the same time, wanted to get the package out there and used.

![Git](https://raw.githubusercontent.com/jacogr/atom-git-control/master/screenshots/git-01.png)

#### [gitignore-snippets](https://github.com/github/gitignore)
Quickly create .gitignore files with templates from [GitHub](https://github.com/github/gitignore).

![demo](https://dl.dropboxusercontent.com/u/268400/gitignore-snippets.gif)

#### [imdone-atom](https://atom.io/packages/imdone-atom)
> 超華麗的 todo，支援拖拉喔

A hackable task-board in your code.

![gifrecord_2015-11-12_085528](https://cloud.githubusercontent.com/assets/233505/11121461/9899fb14-891b-11e5-8aba-a4646f8b1428.gif)

#### [merge-conflicts](https://atom.io/packages/merge-conflicts)
> merge conflicts 時最好用的工具。

Resolve your git merge conflicts in Atom!

![conflict-resolution](https://raw.github.com/smashwilson/merge-conflicts/master/docs/conflict-resolution.gif)

This package detects the conflict markers left by `git merge` and overlays a set of controls for resolving each and navigating among them. Additionally, it displays your progress through a merge.

#### [minimap](https://atom.io/packages/minimap)
A preview of the full source code.

![Minimap Screenshot](https://github.com/atom-minimap/minimap/blob/master/resources/screenshot.png?raw=true)
<small>In the screenshot above the minimap-git-diff and minimap-highlight-selected plugins are activated.</small>

> 以下是 minimap 的 plugins
##### [minimap-autohide](https://atom.io/packages/minimap-autohide)
This package automatically hides the minimap until you need it.

When editing normally, you have the entire window for your editor. As soon as you begin to scroll, the minimap appears and you can interact with it normally.

Written by @JayKuri - If you like it, say Hi!

![Minimap autohide animated image](https://raw.githubusercontent.com/jayk/minimap-autohide/master/screenshot.gif)

##### [minimap-cursorline](https://atom.io/packages/minimap-cursorline)
Displays Atom cursorline in the minimap.

![Minimap cursorline Screenshot](https://github.com/atom-minimap/minimap-cursorline/blob/master/screenshot.gif?raw=true)

##### [minimap-linter](https://atom.io/packages/minimap-linter)
Atom package to display linter markers on minimap.

![minimap-linter](https://raw.githubusercontent.com/nesukun/atom-minimap-linter/master/minimap-linter.gif)

#### [tool-bar](#tool-bar)
> 可以客製化 tool-bar，我是自己參考其他的 plugin 做出自己的 toolbar
> 下面是基於 tool-bar 開發的預製 toolbar plugin

##### [atom-toolbar-almighty](https://atom.io/packages/tool-bar-almighty)
![screenshot](https://rawgit.com/varemenos/atom-toolbar-almighty/master/screenshot.png)

##### [flex-toolbar](https://atom.io/packages/flex-tool-bar)

##### [tool-bar-besser](https://atom.io/packages/flex-tool-bar)
![screenshot](https://cdn.rawgit.com/besser/atom-toolbar-besser/a988ed6/screenshot.png "tool-bar-besser")
