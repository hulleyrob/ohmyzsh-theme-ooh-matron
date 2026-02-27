# ohmyzsh-theme-ooh-matron

## Introduction

An oh-my-zsh theme

### Feature

* real time prompt
* command running time cost prompt
* command running error hint

## Usage

### Basic Zsh Theme

#### Install

1. clone repo
   ```
   git clone https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron
   ```
2. copy theme
   ```
   cp ./ohmyzsh-theme-ooh-matron/ooh-matron.zsh-theme ~/.oh-my-zsh/themes/ooh-matron.zsh-theme
   ```
3. edit .zshrc change ZSH_THEME to 
    ```
   ZSH_THEME="ooh-matron"
    ```
    you can run
   ```
   sed -i 's/ZSH_THEME="robbyrussell"/ZSH_THEME="ooh-matron"/g' ~/.zshrc
    ```
11. execute zshrc
    ```
    source ~/.zshrc
    ```

* see also: [Overriding and adding themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Customization#overriding-and-adding-themes);

#### Recommended Zsh Plugins

1. [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
2. [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
3. [command-line fuzzy finder](https://github.com/junegunn/fzf)

* plugins/zsh-interactive-cd is already sourced in the .zshrc file

#### iTerm2 Preferences

##### Color

<!-- cspell:disable-next-line -->
* iTerm2: settings -> Profiles -> Colors -> Color Presets -> import ```./ooh-matron.itermcolors```
* alternate terminal: try [Alternate terminal installation and configuration](https://iterm2colorschemes.com/)

#### Why newline on the prompt?

<img width="713" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron/assets/17217514/cbfd35b4-e9a4-4be1-95f7-7372713d104b">

Useful if using smaller terminal windows

#### What do the red and green dot mean?

<img width="429" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron/assets/17217514/123b3772-2c46-42f5-94ab-8ab40842658b">

Red Dot   = Last command returned unsuccesful completion status

Green Dot = Last command returned succesful completion status
