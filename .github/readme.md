
<h1 align="center">

 <br>

  <div align="center">

  <div align="center">
   <p>Deadly Dotfiles ~/</p>


 
   <br>
</div>
</h1>

<p align="center"> 
  <img src="https://cdn.discordapp.com/attachments/1058051418369568768/1330168081921740872/FD2D1CC8-0B01-4608-94A0-F6773738EBBE.png?ex=678cff10&is=678bad90&hm=6061f21a192ae24a2116997a63a89cf6c476db325487b00530a53f30f0aa3ff9&?width=867&height=488">
</p> 



<br>

<table align="right">
  <tr>
    <td align="center">
      <sup>
            <samp>
                  These Dotfiles are still WIP.<br>
                  Use it at your own risk!
            </samp>
      </sup>
    </td>
  </tr>



<table>

Hi there, thanks for dropping by 💙, 

these are my Kali Linux and AwesomeWM configuration files.

This rice uses my own colorscheme [Articblush](https://github.com/articblush/).

Special thanks to [alpha](https://github.com/alphatechnolog) and [saimoomedits](https://github.com/saimoomedits).

</table>

<br>

<br>

<img src="https://awesomewm.org/doc/api/images/AUTOGEN_wibox_logo_logo_and_name.svg" width=250 align="right">



| task              | name                   |
| ----------------- | ---------------------- |
| wm                | [awesome-git](https://github.com/awesomeWM/awesome)                                      |
| terminal          | [wezterm](https://wezfurlong.org/wezterm/)                                      |
| gtk theme         | [articblush](https://github.com/articblush/gtk)
| bar               | [wibar](https://awesomewm.org/apidoc/popups_and_bars/awful.wibar.html)                   |
| compositor        | [picom-arian8j2](https://github.com/Arian8j2/picom)                                  | 

<br>




<details close>
    <summary><samp><b>Installation</b></samp></summary>


<br>

## ‎ <samp>Setup</samp>

### Clone the repository

First clone the repository

```sh
git clone -b awesomewm https://github.com/drakenox/deadlydots
cd deadlydots
```

<br>



<details close>
    <summary><samp><b>Requirements</b></samp></summary>


<br>

### Requirements

Then make sure you have the next requirements installed

#### Fonts

| **font** | **utility** |
|----------|-------------|
|[Product Sans (Google Sans)](https://www.cufonfonts.com/font/google-sans)|Main UI Font|
|[Iosevka Nerd Font](https://nerdfonts.com/font-downloads)|Some icons, others are rendered using svg|
|[CaskaydiaCove Nerd Font](https://nerdfonts.com/font-downloads)|Terminal font|

#### Dependencies

| **dependency** | **utility** |
|----------------|-------------|
|awesomeWM|The window manager (Use the GIT version)|
|picom|The compositor, i'm using the [Arian8j's picom fork](https://github.com/Arian8j2/picom)|
|zsh|The shell|
|bat|Enhanced cat|
|rofi|Apps launcher|
|playerctl|Remotely music management (needs to use dbus, use dbus-run-session if your session isn't started with dbus)|
|light|Manage the brightness using the cli|
|pulseaudio|Well, just the audio manager|
|pactl|Manage pulseaudio using the cli|
|starship|Prompt|
|wezterm|Terminal|


### Copy the configs

**WARNING**: Configuration files may be overrided.

```sh
cp -r ./.config/* ~/.config
cp -r ./.etc/* ~/.local/bin
```

