Bootstrap 4 Big Grid
==================
A set of larger grid options for Bootstrap 4.0.

Documentation and Tests
=======================
http://benwhitehead.github.io/bootstrap-big-grid/
forked from thedutchess/bootstrap-big-grid

Motivation
==========
Bootstraps Grid only provides a grid up to 1200px wide, this project provides more grids for common higher resolutions all the way up to 8K.

Changelog
=========
30/03/2018 Updated container with class to enlarge fitting screen size proportionally
28/03/2018 Changed name of project

09/10/2017 Updated grid class names and sizes for a more even spread of breakpoints at higher resolutions and to ensure future class compatibility with Bootstrap 4.
- ```col-xlg-*``` => ```col-hd-*```
- ```col-uhd-*``` => ```col-4k-*```, breakpoint at 3840px
- ```col-4k-*``` => ```col-5k-*```, changed breakpoint from 4096px to 5120px
- ```col-8k-*``` changed from 8192px to 7680px

28/07/2017 Updated for Bootstrap 3.3.7

Usage
=====
The easiest way to use Bootstrap Big Grid is with Bower
```bash
bower install --save bootstrap4-big-grid
```

Alternatively download a [release](https://github.com/Rombecchi/bootstrap4-big-grid/releases) and use the css files in the dist directory.

Then link it into your page after the main bootstrap css

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<link rel="stylesheet" href="bower_components/bootstrap4-big-grid/dist/css/bootstrap4-big-grid.min.css"/>
```

New Classes
===========

### New Grid Classes
`.col-hd-`   : 1366 x 768  
`.col-fhd-`  : 1920 x 1080  
`.col-rt-`   : 2560 x 1600  
`.col-rt15-` : 2880 x 1800  
`.col-4k-`   : 3840 × 2160  
`.col-5k-`   : 5120 x 2880  
`.col-8k-`   : 7680 x 4320  

### New Responsive Utilities Classes
`.visible-hd`  
`.visible-fhd`  
`.visible-rt`  
`.visible-rt15`  
`.visible-4k`  
`.visible-5k`  
`.visible-8k`  
  
`.hidden-hd`  
`.hidden-fhd`  
`.hidden-rt`  
`.hidden-rt15`  
`.hidden-4k`  
`.hidden-5k`  
`.hidden-8k`  

Project Status
==============

I'll continue to update this project until it will be outdated from technology. Please report any inconvenience. Thanks.
If you want feel free to fork the repo and start making improvments.


Copyright and License
=====================
Copyright 2013-2014 Ben Whitehead under the Apache 2.0 license.

Forked from Marjolein Flinders (thedutchess) on  Jul 28, 2017
