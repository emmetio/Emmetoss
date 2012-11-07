     /$$$$$$$$                                         /$$
    | $$_____/                                        | $$
    | $$       /$$$$$$/$$$$  /$$$$$$/$$$$   /$$$$$$  /$$$$$$    /$$$$$$   /$$$$$$$ /$$$$$$$
    | $$$$$   | $$_  $$_  $$| $$_  $$_  $$ /$$__  $$|_  $$_/   /$$__  $$ /$$_____//$$_____/
    | $$__/   | $$ \ $$ \ $$| $$ \ $$ \ $$| $$$$$$$$  | $$    | $$  \ $$|  $$$$$$|  $$$$$$
    | $$      | $$ | $$ | $$| $$ | $$ | $$| $$_____/  | $$ /$$| $$  | $$ \____  $$\____  $$
    | $$$$$$$$| $$ | $$ | $$| $$ | $$ | $$|  $$$$$$$  |  $$$$/|  $$$$$$/ /$$$$$$$//$$$$$$$/
    |________/|__/ |__/ |__/|__/ |__/ |__/ \_______/   \___/   \______/ |_______/|_______/

Emmetoss is an extended HTML and CSS snippets collection for the [Emmet toolkit](http://github.com/sergeche/zen-coding/).

## Features

Multiple edit points are supported for most of the snippets.

* Shorter abbreviations (fallback to original syntax is provided)

```css
o-v => overflow: visible; /* CSS, instead of 'ov-v' */
ls-n => list-style: none; /* 'lis-n' */
br10 => border-radius: 10px; /* 'bdrs10' */

i => <img src="" alt=""> /* HTML, instead of 'img' */
ta => <textarea name="" id=""></textarea> /* 'textarea' */
f-g => <form action="#" method="get"></form> /* 'form:get' */
```

* Extended values

```css
f => font: italic bold px/px Helvetica, Arial, sans-serif; /* CSS, instead of 'font:;' */
bdt => border-top: px solid #000; /* 'border-top:;' */
bg => background: #fff url() 0 0 no-repeat; /* 'background:;' */

btn => <button type="submit"></button> /* HTML, instead of '<button></button>' */
```

* Default values

```css
ov => overflow: hidden; /* CSS, instead of 'overflow:;' */
fw => font-weight: bold; /* 'font-weight:;' */
ws => white-space: nowrap; /* 'white-space:;' */
```

* Extra snippets for existing properties
* CSS3 power (animations, transforms, transitions, etc)
* Multiple abbreviations for the same snippets (less chance to miss)
* Extended font stacks
* Hex, RGB, RGBA, HSL and HSLA colors support
* Cross-browser linear-gradients
* Conditional comments
* Additional `<header>` elements
* And much more.

See the [Reference](https://github.com/damirberg/Emmetoss/wiki) for more info.

## Usage

### Sublime Text 2

* Install [Emmet plugin](https://github.com/sergeche/emmet-sublime)
* Open menu item "Preferences", click on "Browse packages"
* Copy `Emmet.sublime-settings` into `/User/` folder

### Other editors

You should copy `snippets.json` to the Extensions Path directory. This path may be different for every editor. For example, for ST2 it’s ~/emmet, but you can override it in preferences, for Coda/Espresso/TextMate this path can be defined in plugin Preferences dialog ([described by Sergey Chikuyonok](https://github.com/sergeche/emmet-sublime/issues/47)).