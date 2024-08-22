<h1 align="center"> Windows dotfiles </h1>
<p align="center"> Windows dotfiles, this isn't a joke and without wsl lol. </p>

## Install
The installation depends on each program, I will leave you the most important.

### PoweShell
First you need to install some tools:

- [z](https://github.com/JannesMeyer/z.ps) better than cd command
- [fzf](https://github.com/junegunn/fzf) list directories and files
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) neofetch its dead and this work better in windows
- [onefetch](https://github.com/o2sh/onefetch) neofetch but for projects
- [lazygit](https://github.com/jesseduffield/lazygit) i don't prepare dot for this but i recommend this tool (it's git but with tui ((install [git](https://git-scm.com) before it's obvious)))

And you need install a some nerdfonts, I recommend:
- [FiraCode](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/FiraCode.zip)
- [JetBrainsMono](https://www.jetbrains.com/es-es/lp/mono/)
- [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Hack.zip)
- [Meslo Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Meslo.zip)

But you can use any nerdfonts, only you need to change the font in the alacritty toml file or in the terminal settings.json. You can check the [nerdfonts](https://www.nerdfonts.com) page.

In ur poweshell use this commands:
``` bash
New-Item -Path $PROFILE -Type File -Force
notepad $PROFILE
```

Copy the content from profile.ps1 and paste in the notepad, it's all.

In addition, copy the content from fastfetch folder to this path:
``` path
%USERPROFILE%/.config/fastfetch
```

![fzf](./assets/fzf.png)
### Alacritty
I prefer [kitty](https://sw.kovidgoyal.net/kitty/) but it is not available on windows, [alacritty](https://github.com/alacritty/alacritty) is an excellent alternative.

Only copy paste the toml file to your alacritty path, maybe is this:
``` Path
%APPDATA%/alacritty
```

![alacritty](./assets/alacritty.png)
### Terminal
If you prefer to use windows terminal you only go to preferences > open json file.

Copy the content from terminal/settings.json.

![terminal](./assets/terminal.png)

### VS code
- Go to preferences (open json)
- Copy the content from vscode/settings.json
- Install the [apc](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension) extension

![vscode](./assets/vscode.png)

### Cider
I use apple music and the apple music client in windows it's horrible. I recommend buy [cider](https://cider.sh) for $3.99 usd you got this. I use the [catppuccin](https://github.com/catppuccin/cider) theme.

![cider](./assets/cider.png)

If you use spotify i recommend [spicetify](https://spicetify.app).

### NEOVIM
I prefer [neovim](https://neovim.io) than vscode so if you want to try neovim [checkthis](https://github.com/AngelYahir/foxy.nvim)!. I am working on a new version of this neovim configuration with many more things, I will update it in these days.

![neovim](./assets/nvim.png)

## Scheme color
I really love [catppuccin](https://catppuccin.com) scheme color. So check their page, they have ports for many tools.

![catppuccin](./assets/catppuccin.png)

## Extras
This is a list of programs that I use and that I recommend.
- [DataGrip](https://www.jetbrains.com/datagrip/) It's good for database management.
- [httpie](https://httpie.io) It's good for testing APIs in personal projects (I recommend [postman](https://www.postman.com) or [Insomnia](https://insomnia.rest/products/insomnia) for professional projects or if you have a team).
- [DBeaver](https://dbeaver.io) It's good for database management if you don't want to pay for DataGrip.
- [Obsidian](https://obsidian.md) The best note-taking app better than [notion](https://www.notion.so).
- [BetterBird](https://www.betterbird.eu/downloads/index.php) Email client, i use outlook but this is good if you wanna try something new or if you want separate your personal email from your work email.
- [LibreWolf](https://librewolf.net) Firefox but with more privacy the best web browser.
- [Brave](https://brave.com) If you want a chronium based browser.
- [Windows PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) It's good for customizing your windows and if you miss [rofi](https://github.com/davatorium/rofi) in windows.
- [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) It's good for customizing your desktop.
- [Birwarden](https://www.bitwarden.com) Password manager (don't forget your master pass).
- [LLVM](https://llvm.org) C++ Compiler.
- [GitKraken](https://www.gitkraken.com) Git GUI/TUI.
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) VS Code extension or if you use neovim [todo-comments](https://github.com/folke/todo-comments.nvim?tab=readme-ov-file).
