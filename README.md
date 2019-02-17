# PLEASE don't forget!!!
On any new pc this is brought to, create a symbolic link so that **~/.vimrc** will point to the **~/.vim/vimrc** file!!

You can do this by simply typing:
```
ln -s ~/.vim/vimrc ~/.vimrc
```
Which is called a soft link, I think. Check out the [linux documentation for ln -s](https://help.github.com/articles/basic-writing-and-formatting-syntax/) or some other resource if you're more curious than I am about this.
