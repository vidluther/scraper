# Steps to get the Scraper Working

## Prep 

First get your mac capable of running some command line tools. You can use the Terminal App that comes with MacOS, or you can get iTerm2 at https://iterm2.com

#### MacOS Command Line Utils 

```
xcode-select --install
```

#### Homebrew 
For more information go to https://brew.sh

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


#### Python 
```
brew install python
```

Close Terminal/iTerm and Re-open it. 

```
 pip3 install wayback-machine-scraper
````

Restart Terminal once again.

```
mkdir wayback
cd wayback
wayback-machine-scraper -f 20120101 -t 20181231 'www.lorr.com'
```

Open Finder and then do your thang.

When you try to open a .snapshot file, your computer will ask you how you want to open it, just tell it to use your favorite browser. 
If it doesn't give you the option of selecting your browswer, you'll see a dropdown that says "Recommended Applications".. click on that and choose "All Applications"

