# we-first-project
First Weekend Website

### Reference

![alt](assets/img/reference.jpg)

### Features

#### LESS / CSS Stuff

- Watches for Less changes on save
- Checks for Less errors and outputs them without you having to rerun Gulp
- Autoprefixes for legacy browsers
- Combines all CSS into one big and sexy minified file
- Includes Less Bootstrap

#### Javascript Stuff

- Automatically compiles all jQuery libraries into one big file JS file
- Lints custom scripts for errors
- Combines all custom scripts into one file

### Build

```
git clone git@github.com:frontend-dev-init/we-first-project.git
cd we-first-project
npm install
gulp
```

### Quick Tips
- Any changes in `assets/less/*` will trigger the Less to compile on save
- All files in `assets/js/libs/*`  will be compressed to `build/jquery.plugins.min.js`
- All files in `assets/js/*` (except for `libs`) will be compressed to `build/scripts.min.js`

These commands build [Less](http://lesscss.org/) code into CSS code. Open [index.html](index.html) file in order to see the webpage.

### Authors
[Kapil Gupta](https://github.com/daemonslayer)
<br>[Uğur Kurt](https://github.com/UgurKurt)

### Template

The base code is from a template called [gulp-and-less-starter-kit](https://github.com/scotch-io/gulp-and-less-starter-kit.git) by [scotch-io](https://scotch.io/). Please check out their other works too. They are awesome.
