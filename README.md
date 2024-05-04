<div align="center">

## Puppy's Hyprland Dot Files

![GitHub Repo stars](https://img.shields.io/github/stars/PuppyAnimations/Hyprland-Dots?style=for-the-badge&color=cba6f7) ![GitHub last commit](https://img.shields.io/github/last-commit/PuppyAnimations/Hyprland-Dots?style=for-the-badge&color=b4befe) ![GitHub repo size](https://img.shields.io/github/repo-size/PuppyAnimations/Hyprland-Dots?style=for-the-badge&color=cba6f7)

<br/>
</div>

#### Preview
https://github.com/JaKooLit/Hyprland-Dots/assets/85185940/4bebe592-ca43-4962-9b5c-38f16d63a9fa

## My Hyprland install Scripts
- You can install Hyprland using Scripts below:
- [Arch-Linux](https://github.com/PuppyAnimations/Arch-Hyprland)
- Refer to install scripts what packages needed to install... but atleast, Hyprland packages are needed.

### 👀 Screenshots
- All screenshots are collected [here](https://github.com/PuppyAnimations/Hyprland-Dots-Showcase).

#### 📦 Whats new?
- To easily track changes, I will be updating the changelogs. [CHANGELOGS](https://github.com/PuppyAnimations/Hyprland-Dots/wiki/Changelogs)  Screenshots will be included if worth it!

### 💥 Copying / Installation / Update instructions 💥
- [`MORE INFO HERE`](https://github.com/PuppyAnimations/Hyprland-Dots/wiki/Install_&_Update) 
> [!Note] 
> The auto copy script will create backups of intended folders to be copied. However, still a good idea to manually backup just incase script failed to backup!
- ~/.config (btop cava hypr kitty rofi swappy swaync waybar wlogout) - These are folders to be copied.
- ~/Pictures/wallpapers - Will be backed up
- Clone this repo by using git. Change directory, make executable and run the script:
```bash
git clone --depth=1 https://github.com/PuppyAnimations/Hyprland-Dots.git
cd Hyprland-Dots
```
- to copy/install from upstream (possible bugs):
```bash
chmod +x copy.sh
./copy.sh
```
- to copy/install from releases (more "stable"):
```bash
chmod +x release.sh
./release.sh
```

- UPGRADE.sh (Experimental):
> [!IMPORTANT]
> You should atleast v1.0.0 in your hyprland dots (ls ~/.config/hypr) to check version
> You need rsync for it to work

> [!CAUTION]
> You should have already up and running Hyprland before using this function
```bash
chmod +x upgrade.sh
./upgrade.sh
```

#### 🛎️ A small note on wallpapers
- by default, only few wallpapers will be copied (1 each dark and light plus 2 more). You will be offered to download more wallpapers. You can preview/check the additional wallpapers on [THIS](https://github.com/PuppyAnimations/Wallpaper-Bank/tree/main/wallpapers) Link

#### ⚠️⚠️⚠️ A MUST! after copying / Installing these dots

+ By default I have not set a wallpaper. Press SUPER W and set a wallpaper. This is also to initiate pywal for waybar, kitty (tty) and rofi themes. If you use the copy.sh script, you wont need to do this.
+ Nvidia Owners. Make sure to edit your `~/.config/hypr/UserConfigs/ENVariables.conf` (recommended). Below env's will be activated if automatic copy is used
> WLR_NO_CURSORS,1 , LIBVA_DRIVER_NAME,nvidia ,  __GLX_VENDOR_LIBRARY_NAME,nvidia 
- NVIDIA users / owners, after installation, check [THIS](https://github.com/JaKooLit/Hyprland-Dots/wiki/Notes_to_remember#--for-nvidia-gpu-users).
+ If you have already set your own keybinds, monitors, etc.... Just copy over from backup created before log-out or reboot. (recommended)

#### 📖 Known issues and possible solutions
- check out [FAQ](https://github.com/JaKooLit/Hyprland-Dots/wiki/FAQ) and [UNSOLVED ISSUES](https://github.com/JaKooLit/Hyprland-Dots/wiki/Known_Issues).


#### 🙋 QUESTIONS
- FAQ! Yes you can use these dotfiles to other distro! Just ensure to install proper packages first!
- QUICK HINT! Click the HINT! Waybar module (note only available in Waybar default and Simple-L [TOP] layout). Can be launched by Keybind SUPER H
- More question? [click here](https://github.com/JaKooLit/Hyprland-Dots/wiki/).

#### 🙏 Special request
- If you have improvements on the dotfiles or configuration, feel free to submit a PR for improvement. I always welcome improvements as I am also just learning just like you guys!

#### 🤷‍♂️ TO DO
- [ ] Tweak dots - 🚧 in constant progress 

#### 🔮 Discord Server
- Join JaKooLit's [Discord server](https://discord.gg/V2SJ92vbEN).

### 💖 Support
- A Star on my Github repos would be nice.
- Subscribe to JaKooLit's [Youtube Channel](https://www.youtube.com/@Ja.KooLit).
- You can also buy JaKooLit Coffee Through ko-fi.com or Coffee.com.

<a href='https://ko-fi.com/jakoolit' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy JaKooLit a Coffee at ko-fi.com' />

[!["Buy Jakoolit A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/JaKooLit)
