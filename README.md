<p align="left">
    <!-- Discord Badge -->
    <a href="https://discord.gg/https://discord.com/invite/E2Bp7GtcaA"><img src="https://img.shields.io/discord/1060607505186684978?logo=Discord&colorA=1e1e2e&colorB=a6e3a1&style=for-the-badge"></a>
    <!-- Version Badge -->
    <a href="https://github.com/Justus0405/rofi-gpu-screen-recorder/blob/main/rofi-gpu-screen-recorder.sh"><img src="https://img.shields.io/badge/Version-1.0-blue?colorA=1e1e2e&colorB=cdd6f4&style=for-the-badge"></a>
</p>

<p align="left">
    <!-- Stars Badge -->
	<a href="https://github.com/Justus0405/rofi-gpu-screen-recorder/stargazers"><img src="https://img.shields.io/github/stars/Justus0405/rofi-gpu-screen-recorder?colorA=1e1e2e&colorB=b7bdf8&style=for-the-badge"></a>
    <!-- Issues Badge -->
	<a href="https://github.com/Justus0405/rofi-gpu-screen-recorder/issues"><img src="https://img.shields.io/github/issues/Justus0405/rofi-gpu-screen-recorder?colorA=1e1e2e&colorB=f5a97f&style=for-the-badge"></a>
    <!-- Contributors Badge -->
	<a href="https://github.com/Justus0405/rofi-gpu-screen-recorder/contributors"><img src="https://img.shields.io/github/contributors/Justus0405/rofi-gpu-screen-recorder?colorA=1e1e2e&colorB=a6da95&style=for-the-badge"></a>
</p>

# Rofi gpu-screen-recorder Controls

This script lets you start, stop, pause, and save screen recordings or replays using a simple menu in Rofi. It uses `gpu-screen-recorder` for fast GPU-based screen recording. You can run it with a keybind and control everything from one menu.

## Preview

![rofi-gpu-screen-recorder-preview](https://github.com/user-attachments/assets/44b1e73a-19f6-4ff4-979a-f32109096712)

## Dependencies

> [!INFO]
> This script needs some kind of `nerdfont`
> in order to display the icons properly!

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/Justus0405/rofi-gpu-screen-recorder.git
   ```

2. Navigate to the directory:

   ```shell
   cd rofi-gpu-screen-recorder
   ```

3. Make the file an executable:

   ```shell
   chmod +x rofi-gpu-screen-recorder.sh
   ```

4. Move the file:

   ```plaintext
   Put the file somewhere you will remember (for eg: ~/.config/rofi/scripts)
   ```

## Usage

Set a keybind to run the script. For i3 it would be:

```plaintext
bindsym Mod1+z exec "bash $HOME/.config/rofi/scripts/gpu-screen-recorder.sh"
```

Which will run the script when pressing ALT + Z

#

<p align="center">
	Copyright &copy; 2025-present <a href="https://github.com/Justus0405" target="_blank">Justus0405</a>
</p>

<p align="center">
	<a href="https://github.com/Justus0405/rofi-gpu-screen-recorder/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Justus0405/rofi-gpu-screen-recorder?logo=Github&colorA=1e1e2e&colorB=cba6f7&style=for-the-badge"></a>
</p>
