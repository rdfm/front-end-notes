# Sass NOTES

[https://sass-lang.com/](https://sass-lang.com/)

**Sass** =  

**Definition**:

- a stylesheet language that’s compiled to CSS
- use variables, nested rules, mixins, functions, and more
- compile **.sass** and **.scss** files into **.css** files
- compiles into fully CSS-compatible syntax

**Resources**:

- [Install](https://sass-lang.com/install) 
- [Documentation](https://sass-lang.com/documentation)
- [Tutorial: Sass Basics](https://sass-lang.com/guide)
- [Built-In Functions](https://sass-lang.com/documentation/functions)
- [node-sass](https://github.com/sass/node-sass#usage)
- [Dart Sass](https://pub.dev/documentation/sass/latest/sass/sass-library.html)

## Install Sass

### Install Anywhere (Standalone)

- [Download package from GitHub](https://github.com/sass/dart-sass/releases/tag/1.22.3)
- [Adding it to your PATH](https://katiek2.github.io/path-doc/)

### Install Anywhere (npm / Node.js)

```vim
$ npm install -g sass
```

**NOTE**: Pure JS implementation of Sass, runs slower. But, same interface.

### Install on Mac OSX (Homebrew)

```vim
$ brew install sass/sass/sass
```

**NOTE**: Path to the Dart SDK: /usr/local/opt/dart/libexec

### Check if Sass installed

```vim
$ sass --version
```

## Compile Files (via Terminal / Command Line)

```vim
$ sass source/stylesheets/index.scss build/stylesheets/index.css
```

Syntax: (sass command) (source scss file-location) (output css file-location)

### One-to-One Mode

### Many-to-many Mode

###



============================================================
## MISC NOTES





EXAMPLE PROJECT WORKFLOW:

```vim
$ mkdir project_folder
$ cd project_folder
$ mkdir scss
$ cd scss
$ touch styles.scss
$ cd ..
$ sass --watch scss:css
```

---

### Plugin: gulp-sass (preprocessor)
$ npm install gulp-sass --save-dev
$cd ..
$subl  gulpfile.js
- add to  gulpfile.js: 
	var sass = require('gulp-sass');
	- add gulp tasks (i.e. $gulp sass)

- create scss file (style.scss) in scss folder 
$ gulp sass 
	- command will then create a css file in the css folder

---

### COURSE: Sass Essential Training

GitHub Repo: https://github.com/planetoftheweb/sassEssentials

Clone a specific branch:
$ cd  Desktop
$ git clone -b 03_01b https://github.com/planetoftheweb/sassEssentials.git

$ sudo npm install


CSS Extension
Pre-processed
Extensible
Written in Ruby

* Features: Variables

$main_color: #9E2932

.navbar {
	background: $main_color
}

* Features: Nesting

.pixgrid {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
    li {
      padding: 0 5px 5px 0;
    }
  }
}

* Features: Partials

// Core Partial
@import  "variables";
@import "mixins";
@import "base";
@import "layout";

// Import Modules
@import "modules/intro";
@import "modules/nav";
@import "modules/welcome";
@import "modules/events";

* Features: Extend

.btn {
	... 
}

.btn-reverse {
	@extend .btn;
	...
}

* Features: Operators

* Features: Mixins

@mixin rounded ( $radius: 10px ) {
	...
}

ul {
	@include rounded(20px);
}

* Syntax: .sass (Older)

* Syntax: .scss (Newer, and able to write regular css) 


Install sass: https://sass-lang.com/

sourcemap: true;

@mixin break($args...) {
	@media (min-width: nth($args, 1)){
		@content;
	}
}


