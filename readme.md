# Simple Bash Bookmarking

  Written By ["getmizanur"](http://stackoverflow.com/questions/7374534/directory-bookmarking-for-bash) and improved by Taylor Otwell

## Install:
```
cp zap.bash ~/zap.bash
```
Add this line to your .bashrc
```
# zap bookmark manager
if [ -f ~/.zap.bash ]; then
    source ~/zap.bash
fi
```
## Usage:
```
$ cd ~/test && zap remember test # save bookmark
$ zap to test # go to bookmark
$ zap locations # show all bookmarks
$ zap forget test # delete bookmark
```

