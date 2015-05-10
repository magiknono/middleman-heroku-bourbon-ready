#MIDDLEMAN-TEST
Testing middleman with custom basic features for futures dev

## Goals

 - (optionnal : Slim templating) ERB by default
 - Sass support with Bourbon / Neat / bitters
 - A basic page layout & index page based on Normalize.css
 - Livereload
 - Jquery > 2 (not for ie 6/7/8)
 - Google analytics Ready snippet in Layout
 - Heroku ready with puma

## Links

 - start here : https://middlemanapp.com/basics/install/

## Usage
*Start as as always*
```
cd mynew-middleman-repo/
git init
git commit -m "init the middleman repo"
git remote add origin git@github.com:magiknono/middleman-test.git
git clone ssh://git@github.com:magiknono/middleman-test.git
```
*Install middleman-test*
```
bundle
middleman version
```
current version is : Middleman 3.3.12 and it is auto fixed in gemlist with the install :

*Start middleman
```
middleman server

*Commit and deploy to heroku
git add .
git commit -m "deploy custom middleman starter kit"

heroku create
heroku push origin master
heroku open

BUG : google fonts are only loaded in http,not https 
Release: v0.1
