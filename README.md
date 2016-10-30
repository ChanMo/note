# My Linux Note

My linux is Arch.

## Git
安装:

	sudo pacman -S git

服务器:

    mkdir project.git
    cd project.git
    git init --bare


## Vim
[my .vimrc file](http://github.com/ChanMo/vimrc.git)

	sudo pacman -S vim

## Emacs

	sudo pacman -S emacs

## Python

    sudo pacman -S python-pip
    sudo pacman -S python-virtualenv

### Pypi

    python setup.py register
    python setup.py sdist bdist_wheel upload


### Django

    mkdir demo
    virtual env
    source env/bin/activate
    pip install django

django的一些常用模块:
* django-flat-theme
* django-ckedior
* django-mptt
* sorl-thumbnail
* django-import-export
* mysql-python
    

## NodeJS

    sudo npm cache clean -f
    sudo npm install -g n
    sudo n stable
    sudo ln -s /usr/bin/nodejs /usr/bin/node

[mygulp](http://github.com/ChanMo/mygulp.git)

## Graphics
gimp, inkscape, blender, opencad

## Shell

1. lscpu
2. tightvncserver

## OpenCV

    sudo pacman -S opencv python-numpy

## Others
1. scrot 截屏工具
    `scrot -s`

2. scp 文件传输工具
3. shutdown 系统关闭工具
4. shell 执行shell文件
5. pandoc test.md --toc --smart --latex-engine=xelatex --template=pandoc.tex -o test.pdf
6. youtube-dl
7. tar
8. xclip 剪贴板
9. xset dpms force off
