#MIDDLEMAN-TEST
Testing middleman with custom basic features for futures dev

## Goals

 - (optionnal : Slim templating) ERB by default
 - Sass support with Bourbon / Neat / bitters
 - A basic layout page & index page based on Normalize.css
 - Livereload
 - Jquery > 2 (not for ie 6/7/8)
 - Google Fonts with Open-sans
 - Google analytics Ready snippet in Layout
 - Heroku ready with puma

## Installation
*Setup*
```
mkdir your-folder
git clone git@github.com:magiknono/middleman-test.git your-folder
cd your-folder
git remote rm origin
git remote add origin your-git-url
```
*Install gems*
```
bundle install
middleman version (check if it works)
```
current version is : Middleman 3.3.12 and it is auto fixed in gemlist with the install :

##Start middleman
```
middleman server
```
###Deploy to heroku
*First Commit*
```
git init
git add .
git commit -m "initialise custom middleman starter kit"
```
*Deploy to heroku and test in browser*
```
heroku create
heroku push origin master
heroku open
```

*BUG* : google fonts are only loaded in http,not https 

### Link for more info on middleman

 - start here : https://middlemanapp.com/

