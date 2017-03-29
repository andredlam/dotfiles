### Installation (customized for myself)

#### For MAC
```
1. Go to "http://brew.sh/" and install Brew on Mac
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Go to https://github.com/rupa/z and clone z
$ git clone https://github.com/rupa/z.git

3. Create folder ~/code/z and move z.sh

4.
$ git clone https://github.com/andredlam/dotfiles.git && cd dotfiles && ./sync.sh
```

### For Ubuntu
```
1. Prerequisite:
$ sudo apt install linuxbrew-wrapper
$ sudo add-apt-repository "deb http://archive.ubuntu.com/ubuntu $(lsb_release -sc) main universe"
$ sudo apt-get remove vim-common 
$ sudo apt-get clean && sudo apt-get purge 
$ sudo apt-get update && sudo apt-get install vim

2. Go to https://github.com/rupa/z and clone z
$ git clone https://github.com/rupa/z.git


3. Create folder ~/code/z and move z.sh

4.
$ git clone https://github.com/andredlam/dotfiles.git && cd dotfiles && ./sync.sh
```


### To update later on, just run the sync again.
