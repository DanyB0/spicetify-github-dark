# spicetify-github-dark
A theme for spicetify inspired by the Discord and GitHub dark themes.

I used [this theme](https://github.com/morpheusthewhite/spicetify-themes/tree/master/BurntSienna) as a basis.

## Screenshots
![screenshot1](https://github.com/DanyB0/spicetify-github-dark/blob/main/screenshots/preview1.png)

![screenshot2](https://github.com/DanyB0/spicetify-github-dark/blob/main/screenshots/preview4.png)

![screenshot3](https://github.com/DanyB0/spicetify-github-dark/blob/main/screenshots/preview3.png)
## Installation and usage

1.  Repository download
  
    **Using Git**

    If you are a git user, you can install the theme and keep up to date by cloning the repo:
    ```
    git clone https://github.com/DanyB0/spicetify-github-dark
    ```
    **Manual download**
    
    Download using the [GitHub .zip download](https://github.com/DanyB0/spicetify-github-dark/releases) option and unzip it.

2.  Copy the files into the [Spicetify Themes folder](https://github.com/khanhas/spicetify-cli/wiki/Customization#themes). Run:

    **Linux**

    ```bash
    cd spicetify-github-dark
    cp -r * ~/.config/spicetify/Themes
    ```

    **MacOS**

    ```bash
    cd spicetify-github-dark
    cp -r * ~/.config/spicetify/Themes
    ```

    **Windows**

    ```powershell
    cd spicetify-github-dark
    cp * "$(spicetify -c | Split-Path)\Themes\" -Recurse
    ```

3.  Apply the theme just by running:
    ```bash
    spicetify config current_theme spicetify-github-dark
    spicetify apply
    ```
## Team
This project is maintained by me.
[![DanyB0](https://avatars.githubusercontent.com/u/66164380?s=100)](https://github.com/DanyB0) |
--- |
[DanyB0](https://github.com/DanyB0) |
## License
[MIT](./LICENSE)
