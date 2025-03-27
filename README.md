# Dotfiles
My linux dotfiles
## Tools
- **Sway:** Window manager
- **Waybar:** Top bar that displays some information like workspaces, battery, date..
- **Wofi:** Applications launcher
- **Foot:** Terminal emulator
- **Dunst:** Notification manager
- **Neovim:** Text editor
- **Zathura:** A simple PDF viewer with vim keybindings
- **Ranger:** A terminal file manager with vim keybindings
## Screenshots
![Screenshot6](https://github.com/user-attachments/assets/1017859a-dbba-4fee-b88d-bc9dc396b8d6)
![Screenshot1](https://github.com/user-attachments/assets/044d7421-ade2-4050-9380-f53c160168cd)
![Screenshot5](https://github.com/user-attachments/assets/a1289b59-bf50-42fb-a320-9b1ee2217dbf)
![Screenshot3](https://github.com/user-attachments/assets/642b7ae0-c8da-4dc5-981b-8f08ae0d560d)
![Screenshot2](https://github.com/user-attachments/assets/e45477d8-f05a-47e5-a90c-6532c5546347)
![Screenshot4](https://github.com/user-attachments/assets/e67e0a92-b501-487f-bf64-632408d050c8)
## Setup
1. Clone the repository
```sh
git clone https://github.com/danielrouco/dotfiles.git
```
2. Move .bashrc to the default path
```sh
mv dotfiles/.bashrc ~/.bashrc
```
3. Move all the other config files to ~/.config
```sh
mv dotfiles/* ~/.config
```
4. Install all the packages
- With apt:
```sh
sudo apt install sway waybar wofi foot dunst neovim zathura ranger
```
- The proccess with another package manager will be similar
> [!WARNING]
> These configuration files were not made to be a good starting point for customization. Instead, they were created for personal use, so be aware that there are some settings that may not fit your needs well
