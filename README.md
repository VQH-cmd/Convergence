![Convergence](logo.jpg)

# **Convergence**

- 📦 *Toolkit:* **`Convergence`**
- 🏗️ *Version:* **`7.0.6`**
- 👨‍💻 *Author:* [**VQH-cmd**](https://VQH-cmd.github.io)

<br>

________________________________________________________________

<br>

## **`[01]:` Description**

- A toolkit for **[Monolith](https://github.com/VQH-cmd/Monolith.lite)** template.
- Inspired by: **[Captain Panic! & Systek - [Monolith]: Convergence)](https://captainpanicmonolith.bandcamp.com/track/convergence)**

<br>

________________________________________________________________

<br>

## **`[02]:` Installation**

💼 *Base*	| 🔗 *Link*
--------	| --------
**Node.js**	| https://nodejs.org (16.x.x)
**gulp.js**	| https://gulpjs.com

<br>

### **Install Commands** (Terminal):
```
npm install
```
```
yarn install
```

<br>

> Use the command `set-executionpolicy remotesigned` in the **Windows Powershell** if you see
> ```
> gulp.ps1 cannot be loaded because running scripts is disabled on this system
> ```
> in the Terminal.

<br>

________________________________________________________________

<br>

## **`[03]:` Functions**

Auto convert from		| to
--------				| --------
.pug					| `.html`
.sass					| `.css`
all ".css" files		| `1 ".css" file`
all ".js", ".ts" files	| `1 ".js" file`

> Support:
`HTML`,
`Pug`,
`CSS`,
`SASS/SCSS`,
`TypeScript`,
`PHP`,
`localhost`,
`ftp`,
[WordPress](https://wordpress.org),
[Shopify](https://www.shopify.com),
[TheBASE](https://thebase.in).

<br>

________________________________________________________________

<br>

## **`[04]:` Commands & Description**

> Use the **`Terminal`** to execute the commands.

📟 Commands			| 📝 Description
--------			| --------
`gulp --p <DEST>`				| Start the Toolkit.
`gulp --p <DEST> --env <in shopify.yml>`	| Start the Toolkit for [Shopify](https://www.shopify.com) project, default env: `dev`.
`gulp clean --p <DEST>`		| Delete all temporary files.
`gulp clean_all --p <DEST>`	| Delete all the generated files.
`ncu`				| Check Update.

`<DEST>` = Destination. Example:
<br>
`gulp --p D:/Project/example_x`
<br>
`gulp --p D:/Shopify/example_x --env prod`

<br>

________________________________________________________________

<br>

## **`[05]:` Repository tree**

> All files in **`/build`** folder shall be converted into **`/assets`** folder.

<br>

### **`📦` [Root]: Assets & Build**

+ **`.../`**
	- **`/assets`** *(assets)*
	- **`/build`** *(build)*
		- `/config` *(Config Folder)*
			- `breakpoint.json` (CSS Breakpoint Responsive)
			- `config.json` ([Convergence](#)'s Config)
			- `ftp.json` (FTP Config)
			- `misc.json` (SASS Config)
			- `theme.json` (Themes/Colors Config)
			- `whitelist.json` (PurgeCSS config)
		- `/js` *(JavaScript + TypeScript)*
			- `/components`
			- `/libs` *(JavaScript Library, support {.js, .ts})*
			- `/script` *(shall export individual files)*
			- `script.ts`
		- `/pug` *(Pug)*
		- `/sass` *(SASS)*
			- `/style` *(shall export '\*.style.css' files)*
			- `style.sass`
		- `/img` *(Image [Optional])*
	- **`/docs`** *(identify)*
	- **`.editorconfig`**

<br>

----------------------------------------------------------------

<br>

### **`default`: Front-End, [PHP](https://www.php.net), [WordPress](https://wordpress.org)**

+ **`Project_Name/`** *(also the root)*
	- **`📦[Root]`**
	- `/data` *(database)*
	- `/docs` *(information about the Project)*
	- `/inc` *(include PHP files)*
	- `/locale` *(internationalization)*
	- `.htaccess`
	- `robots.txt`
	- `...`

<br>

----------------------------------------------------------------

<br>

### **[Shopify](https://www.shopify.com)**

+ **`Project_Name/`** *(also the root)*
	- **`📦[Root]`**
	- `/config` *(Shopify)*
	- `/layout` *(Shopify)*
	- `/locales` *(Shopify)*
	- `/sections` *(Shopify)*
	- `/snippets` *(Shopify)*
	- `/templates` *(Shopify)*
	- `shopify.yml` *(Shopify config)*

<br>

----------------------------------------------------------------

<br>

### **[TheBASE](https://thebase.in)**

+ **`Project_Name/`** *(also the root)*
	- **`📦[Root]`**
	- `theme.html` *(result)*

<br>

________________________________________________________________

<br>

## **`[06]:` Download**

Download link in any **Monolith** project via this location:
+ **`Project_Name/`** *(also the root)*
	- **`/build`**
		- `convergence.yml`

<br>

________________________________________________________________

Copyright © 2018 - 2021, [VQH-cmd](https://VQH-cmd.github.io).
