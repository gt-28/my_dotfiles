# my_dotfiles
My ~/.dotfile configurations for better productivity

**_Warning:_** If you want to try these dotfiles, please fork this repository, review the code, and remove things that aren't necessary for your environment. _Not responsible for any environmental damanges with these settings_. Please be mindful while configuring your environment.

## Usage:

``` 
git clone https://github.com/gt-28/my_dotfiles.git 
```

To update, cd into your local `my_dotfiles` repository and then:

### For vim config

*Pre-requisite:*

`vim` package is already installed.

If not please install `vim` based on your `linux` distro.

```
Example: 
  centos:
    sudo yum install -y vim
   
   ubuntu:
    sudo apt install -u vim
```

*vim-config:*

```
cd my_dotfiles

cp -r .vim/*  ~/.vim/

cd ~

ln -s .vim/.vimrc .vimrc
```

### For git

you can update the existing `.gitconfig` from your home dir or you can copy from the repository you cloned.

*Pre-requisite:*

`git` package is already installed.

If not please install `git` based on your `linux` distro.

```
Example: 
  centos:
    sudo yum install -y git
   
   ubuntu:
    sudo apt install -u git
```

*git-config:*

```
cd my_dotfiles

cp -r .gitconfig  ~/.gitconfig

```
