# Github theme for Twitter Bootstrap 3.0.0

No more ugly huge elements. No more big fonts. No more candy-style buttons.
Only strict and perfect beauty.
Demo: http://slider23.github.io/bootstrap-theme-github/

## Installation

Replace original `bootstrap.css` or `bootstrap.min.css` by `dist/css/bootstrap.css` or `dist/css/bootstrap.min.css`

## Built by Themestrap

**Themestrap** is a simple starter kit for constructing Twitter Bootstrap 3+ themes. It provides the skeleton
for a simple, maintainable theme that always uses code directly from Bootstrap with as little replacement as
possible.

### Themestrap's Philosophy

1. A theme should be built *on top* of the framework, with as little intrusive change as possible.
2. As the framework evolves, a theme should be easily updated to the latest version.

To this end, Themestrap provides you with two simple files to modify: **variables.less**
and **theme.less** (both in the `less` directory). You can tweak any and all of the Bootstrap variables 
in **variables.less** and support any additional code or classes you'd like in **theme.less**. The compiled
theme CSS includes the Bootstrap library and will automatically pick up any overrides from variables.

### Creating a Theme with Themestrap

To create a theme, first start by cloning the Themestrap repository into a directory named for
your theme. We recommend a `bootstrap-theme-THEME_NAME` naming scheme:

    git clone https://github.com/divshot/themestrap.git bootstrap-theme-THEME_NAME
    
Next, you should open `bower.json` and change the package name from `bootstrap-theme-themestrap`
to match what you want your theme to be named. Now you're ready to install dependencies using
[Grunt](http://gruntjs.com) and [Bower](https://github.com/bower/bower) (you must have these
installed).

    npm install
    bower install
    
Now you're ready to go! Simply edit `less/variables.less` and `less/theme.less` to your liking.
When you're ready, just run `grunt` and it will compile and minify the distribution for you.
You can also run `grunt watch` to automatically compile as you work.