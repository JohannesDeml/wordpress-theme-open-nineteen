# Introduction

The wordpress twentynineteen theme is a beautiful fully functional theme with gutenberg support. This repository is a standaolone fork of the theme with some design changes. This theme is ment for personal websites that should be light and elegant. [Example Website](https://deml.io)

### Implementation Decisions

* Create a standalone repository to enable easy maintanance and forkability for the theme
* Keep an extra branch vanilla-twentynineteen to merge changes from the parent theme
* Use npm with build scripts as the [wordpress main repo](https://github.com/WordPress/wordpress-develop), to support easy access and scss.

### Design Decisions

* Use only one font: [Inter](https://rsms.me/inter/)
* Remove elements like previous and next entry
* Remove author information
* Get rid of oversized headings
* Add of some additional css classes for easy styling


## Build Project

```
npm install
npm run-script build
```

## Todo

* Create a fitting preview screenshot
* Improve Category entry style
* Use variable inter font when supported
* Add theme to [official wordpress themes](https://make.wordpress.org/themes/handbook/review/)

## Additional Licences

* Twenty Nineteen WordPress Theme, © 2018 WordPress.org, GNU GPL
* Inter Fonz, © 2016-2019 The Inter Project Authors (me@rsms.me), SIL OPEN FONT LICENSE Version 1.1
* normalize.css, © 2012-2018 Nicolas Gallagher and Jonathan Neal, MIT
* Underscores, © 2012-2018 Automattic, Inc., GNU GPL v2 or later
