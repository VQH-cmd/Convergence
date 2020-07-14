![](https://img.shields.io/github/v/release/VQH-cmd/Convergence.encrypted)
![](https://tokei.rs/b1/github/VQH-cmd/Convergence.encrypted?category=code)
![](https://tokei.rs/b1/github/VQH-cmd/Convergence.encrypted?category=files)
![](https://img.shields.io/github/languages/code-size/VQH-cmd/Convergence.encrypted)
![](https://img.shields.io/github/repo-size/VQH-cmd/Convergence.encrypted)
![](https://img.shields.io/github/downloads/VQH-cmd/Convergence.encrypted/total)

![Convergence](logo.jpg)

# **Convergence**_.encrypted_

- 📦 *Project Name:* **`Convergence`**
- 🏗️ *Project Version:* **`5.4.0`**
- 👨‍💻 *Author:* [**VQH-cmd**](https://VQH-cmd.github.io)

________________________________________________________________

## **`[01]:` Description**

- A synchronization project for **[Monolith](https://github.com/VQH-cmd/Monolith.lite)** template.
- Use this project to save ton of coding time.

________________________________________________________________

## **`[02]:` Installation**

🗳 *Name*	| 🔗 *Link*
--------	| --------
**Node.js**	| https://nodejs.org
**gulp.js**	| https://gulpjs.com

> 👉 **`NOTE:`** *Use the lastest version !*

+ node_modules:
	- Click the file **`-install.bat`**.
	- or Run command **`npm install`** in the **Terminal**.

> Use the command `set-executionpolicy remotesigned` in the **Windows Powershell** if you see
> ```
> gulp.ps1 cannot be loaded because running scripts is disabled on this system
> ```
> in the Terminal.

________________________________________________________________

## **`[03]:` Config**

> The information in **`config.json`** file.

> Edit this file at first to suit with your computer and project.

> `0` = _false_<br />
> `1` = _true_

```json
{
  "server": {

      "💡NOTE💡": "Project Directory",
      "project": "D:/Projects/name",

      "💡NOTE💡": "Your local domain",
      "domain": "project.local",

      "💡NOTE💡": "Your PHP source location",
      "php_loc": "D:/php/7.4.4",
  },

  "preprocessor": {

      "💡NOTE💡": "Minify all '.html' files",
      "minify_html": 0,

      "💡NOTE💡": "Generate '.html' files with '.pug' files",
      "pug": 0,

      "💡NOTE💡": "Is PHP project ?",
      "php": 1,

      "💡NOTE💡": "Apply WordPress admin ?",
      "wp_admin": 0,

      "💡NOTE💡": "Is Django project ?",
      "django" : 0,

      "💡NOTE💡": "0 = /static",
      "💡NOTE💡": "'app_name' = /app_name",
      "django_static" : 0 or "app_name"
  },

  "css": {

      "💡NOTE💡": "Auto remove unused CSS styles",
      "purge": 1
  },

  "js": {

      "💡NOTE💡": "Protect JavaScript files",
      "💡NOTE💡": "⚠️File size will be increased",
      "encrypt": 0,

      "💡NOTE💡": "0 = Basic protect",
      "💡NOTE💡": "1 = Extreme protect",
      "encrypt_level": 0
  },

  "img": {

      "💡NOTE💡": "Auto minify all image files",
      "minify": 0
  }
}
```

________________________________________________________________

## **`[04]:` Functions**

Auto convert from		| to
--------				| --------
.pug					| `.html`
.sass					| `.css`
all ".css" files		| `1 ".css" file`
all ".js", ".ts" files	| `1 ".js" file`

> Support: `HTML`, `Pug`, `CSS`, `SASS`, `JavaScript`, `TypeScript`, `PHP`, `WordPress`, `Django`, `Wagtail`, `localhost`.

> Support older browser versions by auto editing **`.css`** files without writing every single browser’s support codes.

> Synchronize browsers: Dynamic **`Code → View`** without reloading the site, synchronize all browsers.

________________________________________________________________

## **`[05]:` Commands & Description**

> Use the **`Terminal`** to execute the commands.

📟 Commands			| 📝 Description
--------			| --------
`gulp`				| Start synchronizing. Synchronize the project when edit inner files.
`gulp clean`		| Delete all temporary files.
`gulp clean_all`	| Delete all the generated files.
`npm install -g npm-check-updates`	| Install check update.
`ncu`				| Check Update.

________________________________________________________________

## **`[06]:` Repository tree**

> All files in **`/build`** folder will be converted into **`/assets`** folder.

### **`[06.00]`: Assets & Build**

+ **`.../`**
	- **`/assets`** *(assets)*
		- `/css` *(css)*
		- `/fa` *(Font Awesome)*
		- `/fonts` *(Font)*
		- `/img` *(Image)*
		- `/js` *(JavaScript)*
	- **`/build`** *(build)*
		- `/css` *(css)*
			- `/admin` *(will export '\*.admin.css' files)*
			- `/libs` *(CSS Library)*
		- `/js` *(JavaScript + TypeScript)*
			- `/admin` *(will export '\*.admin.js' files)*
			- `/backend` *(Example: Vue, React, Angular,...)*
			- `/functions` *(Short Call)*
			- `/ie` *(will export 'ie.js' file)*
			- `/libs` *(JavaScript Library)*
			- `/script` *(will export individual files)*
			- `custom.js` *(Custom file for whom have not known how to control this template)*
			- `tsconfig.json` ([TypeScript](https://www.typescriptlang.org) Config)
		- `/pug` *(Pug)*
		- `/sass` *(SASS)*
			- `/admin` *(will export '\*.admin.css' files)*
			- `custom.sass` *(Custom file for whom have not known how to control this template)*
		- `/img` *(Image)*
		- `libs.json` ([Convergence](#)'s Libraries Config)

----------------------------------------------------------------

### **`[06.01]`: Front-End, [PHP](https://www.php.net), [WordPress](https://wordpress.org)**

+ **`Project_Name/`** *(also the root)*
	- **`/assets`** *(assets)*
	- **`/build`** *(build)*
	- `/data` *(database)*
	- `/docs` *(information about the Project)*
	- `/inc` *(include PHP files)*
	- `/locale` *(internationalization)*
	- `.htaccess`
	- `robots.txt`

----------------------------------------------------------------

### **`[06.02]`: [Django](https://www.djangoproject.com) + [Wagtail](https://wagtail.io)**
+ **`Project_Name/`** *(Also the root)*
	- `/account`
	- `/app_name`
		- `/templates`
		- **`/build`** *(Build)*
		- `/static`
	- `/docs` *(Information about the Project)*
	- `/global`
		- `/templates`
		- **`/build`** *(Build)*
		- `/static`
	- `/media`
	- `/static`
	- `manage.py`

________________________________________________________________

## **`[07]:` License**

[GNU General Public License v3.0](https://github.com/VQH-cmd/Convergence.encrypted/blob/master/LICENSE)

________________________________________________________________

Copyright © 2018 - 2020, [VQH-cmd](https://VQH-cmd.github.io).