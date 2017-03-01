# laravel
This is my cheatsheet for laravel operations on Mac Terminal

## Initiate Laravel
If opening or restarting Mac Terminal, put in following to include Laravel
$ `export PATH=$PATH:$HOME/.composer/vendor/bin`

There is also a way to automatically set Laravel, so you don't have to do the above command line everytime restarting Mac Terminal. See: http://stackoverflow.com/questions/25373188/laravel-installation-how-to-place-the-composer-vendor-bin-directory-in-your

## Use sublime in Mac Terminal CLI
if $ `subl` did not work, uninstall sublime first.
Then, install sublime via homebrew using $ `brew cask install sublime-text`
And Voila! You can open the directory (incl. folders and files in it) using $ `subl .`
Whereas, `subl` would only open up sublime text with an untitled sublime tab.
