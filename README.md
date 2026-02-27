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
   sed -i 's/ZSH_THEME=".*"/ZSH_THEME="ooh-matron"/g' ~/.zshrc
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

<img width="1426" height="144" alt="image" src="https://github.com/user-attachments/assets/9e5859ac-9f90-443e-a12a-352167e22bed" />

Useful if using smaller terminal windows

#### What do the red and green dot mean?

<img width="858" height="646" alt="image" src="https://github.com/user-attachments/assets/850a3844-b5e8-4283-aa80-34ee46928494" />


Red Dot   = Last command returned unsuccesful completion status

Green Dot = Last command returned succesful completion status
