# Provision

This is just a GitHub repo for me to keep track of files I use to provision my computers, like aliases I like to use to make my time in the console more productive.

The files in this repo are locally just symbolic links to the real files:

```
ln -sf ~/.bashrc .bashrc
ln -sf ~/.vimrc .vimrc
ln -sf ~/.zshrc .zshrc
ln -sf ~/[PATH]/[TO]/.gitconfig .gitconfig
```

* To find the correct `.gitconfig` file, execute `git config --list --show-origin`.
