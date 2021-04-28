# Dotfiles
This repository is a collection of my dotfiles for development work.

Currently it only contains my zsh configuration but will be updated to include more things in the future.

## zsh
My zsh config is a modular set of configuration files that are loaded in alphabetical order from the `.zshrc.d` folder. The main `.zshrc` file is just responsible for loading all the files in the folder.

`100.base.zshrc` loads `oh-my-zsh`, my prompt and plugins. Each other file is pretty self-explanatory by the name of the file.