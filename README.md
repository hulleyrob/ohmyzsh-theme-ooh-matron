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

[<img width="713" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron/assets/17217514/cbfd35b4-e9a4-4be1-95f7-7372713d104b">](https://private-user-images.githubusercontent.com/17217514/344128918-cbfd35b4-e9a4-4be1-95f7-7372713d104b.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzIyMTE3MjgsIm5iZiI6MTc3MjIxMTQyOCwicGF0aCI6Ii8xNzIxNzUxNC8zNDQxMjg5MTgtY2JmZDM1YjQtZTlhNC00YmUxLTk1ZjctNzM3MjcxM2QxMDRiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAyMjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMjI3VDE2NTcwOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE4MDUyYzMwNGVhMjM3ZjVhNTczZjBhYzM2NTk3ZDM4MDk1YjQ4MDdkNzgzOWE2MGM3OGQzYzViOTExNGQxOGUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.GvQFTeMzsfd8rzvC474I5GXHhElsrxec4ufQ73ENnC4)<img width="1426" height="144" alt="image" src="https://github.com/user-attachments/assets/134c71e6-fa03-45eb-9bea-a95e27c986f2" />


Useful if using smaller terminal windows

#### What do the red and green dot mean?

[<img width="429" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron/assets/17217514/123b3772-2c46-42f5-94ab-8ab40842658b">](https://private-user-images.githubusercontent.com/17217514/344129272-123b3772-2c46-42f5-94ab-8ab40842658b.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzIyMTE3MjgsIm5iZiI6MTc3MjIxMTQyOCwicGF0aCI6Ii8xNzIxNzUxNC8zNDQxMjkyNzItMTIzYjM3NzItMmM0Ni00MmY1LTk0YWItOGFiNDA4NDI2NThiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAyMjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMjI3VDE2NTcwOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTkzMzY3ZDI0Zjk5ZTEzMjVlYTY5MzA2ZDBmNjVhYjBhY2M5YjE1OTMzN2Q2Y2JkOGNkMWIzZGVhY2JlZDM0YTUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.2UmSiqrkDeGxsWgEzP0j1VyPkrtfYPjomCEil6YCYho)<img width="858" height="646" alt="image" src="https://github.com/user-attachments/assets/965cf238-5cfd-4866-bbd7-4d9728113b00" />


Red Dot   = Last command returned unsuccesful completion status

Green Dot = Last command returned succesful completion status
