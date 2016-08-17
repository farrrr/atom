# atom
這邊整理了一些我自己有在使用的 packages

## 目錄

- [Syntax](#syntax)
- [Lint](#lint)
- [Themes](#themes)
- [Uncategorized](#uncategorized)
    - [atom-beautify](#atom-beautify)
    - [atom-import-sort](#atom-import-sort)
    - [atom-update-packages](#atom-update-packages)
    - [autoclose-html](#autoclose-html)
    - [autocomplete-modules](#autocomplete-modules)

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

#### [autocomplete-modules](https://atom.io/packages/autocomplete-modules)
> 會自動補完 packages，也會讀取你的 webpack 設定，很方便。

Autocomplete for require/import statements.

![Preview](https://cloud.githubusercontent.com/assets/3505878/7442538/9c1892cc-f11e-11e4-8070-3fa8b79beefc.gif)



