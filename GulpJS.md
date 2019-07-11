# [GulpJS](https://gulpjs.com/)

**Resources**:
- [Getting Started / Quick Start](https://gulpjs.com/docs/en/getting-started/quick-start)

## Quick Start

```vim
$ node --version
$ npm --version
$ npm --version
$ npm install --global gulp-cli

$ npx mkdirp my-project
$ cd my-project
$ npm init

$ npm install --save-dev gulp
$ gulp --version


// FILE (in root): gulpfile.js, add:
function defaultTask(cb) {
  // place code for your default task here
  cb();
}

exports.default = defaultTask

$ gulp
```

## References

- [GitHub: gulpjs](https://github.com/gulpjs/gulp)
- [Article: Using Gulp 4 in your workflow for Sass and JS files](https://coder-coder.com/gulp-4-walk-through/)
- [thecodercoder/frontend-boilerplate](https://github.com/thecodercoder/frontend-boilerplate)