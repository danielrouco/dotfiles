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
![Screenshot 1](https://github.com/user-attachments/assets/1d18a6c5-918e-4e35-978f-adc43c2f6805)

![Screenshot 2](https://github.com/user-attachments/assets/8fcec4f9-9da1-46c7-902f-14e9ac79a417)

![Screenshot 3](https://github.com/user-attachments/assets/8ac58a45-3cda-4cf2-b745-a2891d111137)

### Waybar
![Screenshot 4](https://github.com/user-attachments/assets/07256739-ea6b-4b28-96ff-046a8a7b389c)

![Screenshot 5](https://github.com/user-attachments/assets/e310f683-40c4-4584-a897-5e984ec194ca)

![Screenshot 6](https://github.com/user-attachments/assets/3cda32f9-8948-48a4-8f7f-9279e1586d34)

![Screenshot 7](https://github.com/user-attachments/assets/1f987c81-8470-40aa-9c60-4622c733904e)

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
