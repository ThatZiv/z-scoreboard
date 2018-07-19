# Clean Scoreboard *Fully Configurable*
**z-scoreboard** is a resource by *Zua* that allows users to __easily__ configure the playerlist or scoreboard

![alt-text](https://github.com/ThatZiv/z-scoreboard/blob/master/screenshots/ss1.png?raw=true)

## __Installation__
1. Download [Here](https://github.com/ThatZiv/z-scoreboard).
2. Put the **z-scoreboard** folder into your **resources** folder 
3. Add `start z-scoreboard` into your **server.cfg**

## __Configuration__
| Value | Type | Description|
|-----|-----|--- |
| `--main-bg-color` | `rgba` | Main Background Color |
|`--main-heading-bg-color` | `rgba` | Header Background Color |
| `--main-font` | `font-family` | Master Font |
| `--main-text-color` | `rgba`  | Master Font Color |
| `--main-font-size` | `px` | Master Font Size |
| `--main-window-width` | `px` | Playerlist Window Width |
| `-main-window-height` | `px` | Playerlist Window Height|
| `--main-text-align` | `direction` | Master Text Align |
| `--main-heading-height` | `px` | Header hight |
| `--main-padding` | `px` | Master Padding - *Try not to mess w/ this  (forgot what I made it assigned to)*|
| `--main-font-weight` | `100-900` | Master 'Bolding' in Text |
---
`config.css`
```css
:root /* Edit this for config */ {
--main-bg-color: rgba(44, 70, 112, 0.329);
--main-heading-bg-color: rgba(0, 0, 0, 0.568);
--main-font: 'Roboto Condensed', sans-serif; /* If you are using a font api, pls import it. in the index or here */
--main-text-color: rgba(255, 255, 255, 0.9);
--main-font-size: 39px;
--main-window-width: 370px;
--main-window-height: 185px;
--main-text-align: left;
--main-heading-height: 23px;
--main-padding: 7px;
--main-font-weight: 500;
}
```
To change keypress value to open scoreboard -> go to `client.lua` | Default Key: **Z**

## __Support__
If you need any help/support, join my [discord](https://discordapp.com/invite/yWddFpQ) and ask in **#support**

## __Screenshots__
![alt-text](https://raw.githubusercontent.com/ThatZiv/z-scoreboard/master/screenshots/ss1.png)
![alt-text](https://raw.githubusercontent.com/ThatZiv/z-scoreboard/master/screenshots/ss2.png)
![alt-text](https://raw.githubusercontent.com/ThatZiv/z-scoreboard/master/screenshots/ss3.png)
![alt-text](https://raw.githubusercontent.com/ThatZiv/z-scoreboard/master/screenshots/ss4.png)

-------
