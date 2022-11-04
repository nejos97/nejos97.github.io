The source of the personal joanthan Nenba person website accesible here: https:nenbajonathan.com

## ℹ Installation

And then execute:

    $ bundle install

and run the local server:

    $ bundle exec jekyll serve

#### Pro tip:
Use color icons with the same hue as the menu items. Icons will be black and on hover the color will be shown.

### ✒ Creating posts
Posts are created in the `_posts` directory. Following front matter attributes are supported:
```
---
layout: post #Do not change.
category: [programming, testing] #One, more categories or no at all.
title: "Lorem ipsum" #Article title.
author: andy #Author's nick.
og_image: assets/example.png #Open Graph preview image.
og_description: "Example description." #Open Graph description.
---
Your markdown content here.
```

Markdown attribute can be omitted if you don't use markdown inside the block (e.g. by using the lightbox syntax).

### ℹ Notes
[1] Hue can be either one of the predefined colors or any of the CSS `color` attribute supported values (hex, rgb...).

[2] Submenus are generated recursively, so any menu (and submenu) can have its own submenu.

#### Predefined colors
You can use following predefined colors:
```scss
--c-themePrimaryLight: #EFEFEF;
--c-themePrimaryDark:  #101010;
--c-themeSecondaryLight: #DADADA;
--c-themeSecondaryDark: #252525;
--c-themeTerniaryLight: #AEAEAE;
--c-themeTerniaryDark: #515151;
--c-themeQuaternaryLight: #919191;
--c-themeQuaternaryDark: #888888;

--c-themeHueRed: #C02717;
--c-themeHueGreen: #8EA604;
--c-themeHueBlue: #2E86AB;
--c-themeHueOrange: #E59500;
--c-themeHuePurple: #9F00CE;
--c-themeHueBrown: #230007;
```
These colors are CSS variables, usage: `var(--var-name)`

## 🤝 Contributing
 
Bug reports and pull requests are welcome on [GitHub](https://github.com/nejos97/nejos97.github.io/issues).

## Credits
Thansk to [Valery Melou](https://valerymelou.com/) for the template.

## ⚖ License
© Nenba Jonathan. The website is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

