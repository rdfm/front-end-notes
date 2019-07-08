# Sass NOTES










## MISC NOTES

### SASS (on Mac via Homebrew)
$ brew install sass

*Please note the path to the Dart SDK:
  /usr/local/opt/dart/libexec

$ sass - -version

---

### Dart SASS  (via npm)
-install Dart SASS (https://sass-lang.com/install)

*Node.js (using npm)
$npm install -g sass

*Mac
$brew install sass/sass/sass

NOTE: Check installation

```vim
$ sass --version
```

COMPILE FILES (Terminal Command):

```vim
$ sass source/stylesheets/index.scss build/stylesheets/index.css
```

Syntax: (sass command) (source scss file-location) (output css file-location)

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


