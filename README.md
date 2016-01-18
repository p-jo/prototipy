# prototipy
Web prototype with Jekyll and Bootstrap Sass

## Jekyll
http://jekyllrb.com

Setup
```
gem install jekyll
jekyll new prototipy
```

Run
```
jekyll serve -w
```

### Docs
http://jekyllrb.com/docs/  
https://github.com/shopify/liquid/wiki/Liquid-for-Designers  
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

## Bootstrap
http://getbootstrap.com

Setup  
```
bower install bootstrap-sass
```

## Plugins and CSS
Download plugins with Bower: http://bower.io  
Move files to `assets` folder  
Sass files are compiled by Jekyll if they are in the `_sass` folder with a file to include them in `css` 
Minor changes to css in `_sass/custom.scss`

## Misc
Script for LiveReload included: http://livereload.com/
