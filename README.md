![](https://img.shields.io/github/v/release/VQH-cmd/Sync.encrypted)
![](https://tokei.rs/b1/github/VQH-cmd/Sync.encrypted?category=code)
![](https://tokei.rs/b1/github/VQH-cmd/Sync.encrypted?category=files)
![](https://img.shields.io/github/languages/code-size/VQH-cmd/Sync.encrypted)
![](https://img.shields.io/github/repo-size/VQH-cmd/Sync.encrypted)
![](https://img.shields.io/github/downloads/VQH-cmd/Sync.encrypted/total)

# VQHcmd-Sync.encrypted

- 📦 *Project Name:* **VQHcmd-Sync**
- 👨‍💻 *Author:* **Võ Quốc Huy**
- 🌐 *Author URL:* **https://VQH-cmd.GQ**

________________________________________________________________

## Description

A synchronization project for my website template.

Use this project to save ton of coding time if you have my template.

> *This is the encrypted version.*

________________________________________________________________

## Installation

🗳 *Name*	| 🔗 *Link*
--------	| --------
**Node.js**	| https://nodejs.org
**gulp.js**	| https://gulpjs.com

> 👉 **Note**: *Use the lastest version !*

+ node_modules:
	- Click the file **`-install.bat`**.
	- or Run command **`npm install`** in the **Terminal**.

________________________________________________________________

## Config

> The information in **`config.json`** file.

> Edit this file at first to suit with your computer and project.

*Parameter*		|  *Type*		| *Description*
--------		| --------		| --------
`project`		| **string**	| Project Directory.
`minify_html`	| **boolean**	| Minify all **".html"** files.
`do_pug`		| **boolean**	| Generate **".html"** files with **".pug"** files.
`do_php`		| **boolean**	| Watch PHP.
`wp_admin`		| **boolean**	| WordPress admin pages.
`obfuscator`	| **boolean**	| Protect JavaScript files.
`php_loc`		| **string**	| PHP location.
`domain`		| **string**	| Your local domain.

________________________________________________________________

## Functions

Auto convert from	| to
--------			| --------
.pug				| `.html`
.html				| `.min.html* (minify files)`
.sass				| `.css`
all ".css" files	| `1 ".css" file`
"style.css"			| `Purge file (remove unused css tags)`
all ".js" files		| `1 ".js" file`

> Support: `HTML`, `CSS`, `JavaScript`, `Pug`, `SASS`, `PHP`, `WordPress`, `localhost`.

> Support older browser versions by auto editing **`.css`** files without writing every single browser’s support codes.

> Synchronize browsers: Dynamic **`Code → View`** without reloading the site, synchronize all browsers.

________________________________________________________________

## Commands & Description

> Use the **`Terminal`** to execute the commands.

📟 Commands			| 📝 Description
--------			| --------
`gulp`				| Start synchronizing. Synchronize the project when edit inner files.
`gulp img_min`		| Optimize all image files.
`gulp css_purge`	| Remove unnecessary css style.
`gulp clean`		| Delete all unnecessary files created by Gulp *(VQH-Sync)*.
`gulp clean_all`	| Delete all the generated files.
`npm install -g npm-check-updates`	| Install check update.
`ncu`				| Check Update.

________________________________________________________________

## Repository tree

+ **`Project_Name/`** *(also the root folder)*
	- **`assets`** *(assets folder)*
		- **`css`** *(css folder)*
			- **`build`** *(debug folder)*
				- **`admin`** *(admin debug folder)*
		- **`fa`** *(Font Awesome folder)*
		- **`fonts`** *(Font folder)*
		- **`html_preprocessor`** *(.html build folder)*
			- *Many files...*
		- **`img`** *(Image folder)*
		- **`js`** *(JavaScript folder)*
			- **`build`** *(debug folder)*
				- **`admin`** *(admin debug folder)*
				- **`script`** *(page script debug folder)*
		- **`sass`** *(.css build folder)*
			- *Many files...*
	- **`data`** *(database)*
	- **`docs`** *(information about the Project)*
	- **`inc`** *(include php folder)*
	- **`locale`** *(Languages folder)*
	- **`.htaccess`**
	- **`robots.txt`**

________________________________________________________________

## License

[GNU General Public License v3.0](https://github.com/VQH-cmd/Sync.encrypted/blob/master/LICENSE)

________________________________________________________________

Copyright © 2018 - 2020, [Võ Quốc Huy](https://VQH-cmd.GQ).