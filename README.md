#MIDDLEMAN-TEST
Testing middleman with minimum basic features for futures dev

## Goals

 - (optionnal : Slim templating) ERB by default
 - Sass support with Bourbon / Neat / bitters
 - A basic page layout & 404 page based on Normalize.css
 - Livereload

## Links

 - start here : https://middlemanapp.com/basics/install/

## Usage
*Start as as always*
```
cd mymiddlemanrepo/
git init
touch README.md
nano README.md
git add README.md
git commit -m "init the middleman repo"
git remote add origin git@github.com:magiknono/mymiddlemanrepo.git
git push -u origin master
```
*Install middleman*
```
gem install middleman
middleman version
```
current version is : Middleman 3.3.12 and it is auto fixed in gemlist with the install :
```
middleman init --rack
```

